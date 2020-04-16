FROM ubuntu:18.04
RUN apt update && apt install -y git maven && rm -rf /var/lib/apt/lists/*
WORKDIR /var
RUN git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello boxfuse
WORKDIR /var/boxfuse
RUN mvn package
