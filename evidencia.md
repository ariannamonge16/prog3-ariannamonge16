\# Evidencia de entorno · Arianna Chaves



\## java -version



```text

java version "25.0.4.1" 2026-08-18 LTS

Java(TM) SE Runtime Environment (build 25.0.4.1+1-LTS-5)

Java HotSpot(TM) 64-Bit Server VM (build 25.0.4.1+1-LTS-5, mixed mode, sharing)

```



\## mvn -v



```text

Apache Maven 3.9.16 (2bdd9fddda4b155ebf8000e807eb73fd829a51d5)

Maven home: C:\\Users\\Arianna\\OneDrive\\Escritorio\\UNIVERSIDAD\\UAM\\2026\\III CUATRIMESTRE\\PROGRAMACIÓN III\\MAVEN\\apache-maven-3.9.16

Java version: 25.0.4.1, vendor: Oracle Corporation, runtime: C:\\Program Files\\Java\\jdk-25.0.4.1

Default locale: es\_CR, platform encoding: UTF-8

OS name: "windows 11", version: "10.0", arch: "amd64", family: "windows"

```



\## git --version



```text

git version 2.55.0.windows.5

```



\## docker run hello-world



```text

Unable to find image 'hello-world:latest' locally

latest: Pulling from library/hello-world

4f5508667dd0: Pull complete

d5e71e642bf5: Download complete

Digest: sha256:5e23090353324d887c48ad5e5c56d294eab81588df9605b07d1afe895f9cc8f8

Status: Downloaded newer image for hello-world:latest



Hello from Docker!

This message shows that your installation appears to be working correctly.



To generate this message, Docker took the following steps:

&#x20;1. The Docker client contacted the Docker daemon.

&#x20;2. The Docker daemon pulled the "hello-world" image from the Docker Hub.

&#x20;   (amd64)

&#x20;3. The Docker daemon created a new container from that image which runs the

&#x20;   executable that produces the output you are currently reading.

&#x20;4. The Docker daemon streamed that output to the Docker client, which sent it

&#x20;   to your terminal.



To try something more ambitious, you can run an Ubuntu container with:

&#x20;$ docker run -it ubuntu bash



Share images, automate workflows, and more with a free Docker ID:

&#x20;https://hub.docker.com/



For more examples and ideas, visit:

&#x20;https://docs.docker.com/get-started/

```



\## mvn clean package \&\& java -cp target/classes uam.prog3.App



```text

PEGA AQUÍ TODA LA SALIDA COMPLETA DE:



mvn clean package



Debe terminar con:

\[INFO] BUILD SUCCESS



Y después agrega al final:



Hello World!

```



