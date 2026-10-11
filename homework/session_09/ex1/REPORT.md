## 1. Lệnh `docker version`

```text
$ docker version
Client:
 Version:           <Docker client version>
 API version:       <API version>
 OS/Arch:           <OS/architecture>
 Context:            <Docker context>

Server: Docker Engine
 Engine:
  Version:          <Docker Engine version>
  API version:      <API version>
  OS/Arch:          <OS/architecture>
```

## 2. Lệnh `docker info`

```text
$ docker info
Client:
 Version:    <Docker client version>
 Context:    <Docker context>
 Debug Mode: false

Server:
 Containers: <container count>
  Running:   <running count>
  Paused:    <paused count>
  Stopped:   <stopped count>
 Images:     <image count>
 Server Version: <Docker Engine version>
 Storage Driver: <storage driver>
 Operating System: <Docker host operating system>
 Architecture: <architecture>
 CPUs: <CPU count>
 Total Memory: <memory>
```

## 3. Lệnh `docker run hello-world`

```text
$ docker run hello-world

Hello from Docker!
```
