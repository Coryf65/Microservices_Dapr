# Microservices And Dapr

- Learning about Microservices and using Dapr.
- Content from [Microservices with Dapr book](https://github.com/PacktPublishing/Practical-Microservices-with-Dapr-and-.NET)

| Tools Used | Docs |
| -- | -- |
| Docker | [Getting Started](https://docs.docker.com/get-started/) |
| .Net 5 | [.NET 5](https://docs.microsoft.com/en-us/dotnet/core/whats-new/dotnet-5) |
| Dapr 1.1 or > | [Docs](https://docs.dapr.io/) |
| VS Code | [Installer](https://code.visualstudio.com/) |
| Python 3.8 | [Docs](https://www.python.org/) |
| Azure CLI - 2.15.1 or > | [Docs](https://docs.microsoft.com/en-us/cli/azure/) |
| Locust 1.3.1 or > | [Docs](https://locust.io/ "Load testing tool") |
| WSL2 (Windows Subsytem for Linux) | [Docs](https://docs.microsoft.com/en-us/windows/wsl/about) |

## Commands

- see running dockers
```bash
$ docker ps --format "{{.ID}}: {{.Image}} - {{.Ports}} - {{.Names}}"
```

- 
```bash
$ kubectl get pods --namespace dapr-system
```

- Create a basic web api
```bash
$ dotnet new webapi -o dapr.microservice.webapi
```