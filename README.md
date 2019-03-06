# apache-metron
Apache Metron powered by Docker
Based on the official repo [Apache Metron](https://github.com/apache/metron)

## How to use

### Build the docker
```bash
docker build -t metron-docker:latest
```

### Run the Docker
```bash
docker run -itd --privileged --name=metron metron-docker
```

### Go inside the docker
```bash
docker exec -it --privileged metron bash
```

### Build Metron
```bash
cd metron.git
mvn clean package -DskipTests [-e -X]
```

###### Work still in progress...
