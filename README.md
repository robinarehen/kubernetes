# kubernetes
Proyecto en el cual se aprender a utilizar **Kubernetes**.

# Minikube
En este apartado se muestra la inicialización, partiendo que ya se ha instalado previamente `minikube`, lo ideal es trabajar con `Docker`, pero en este caso se trabajar con `Hyper V` por permisos en el equipo a trabajar. 
[Documetación Oficial](https://minikube.sigs.k8s.io/docs/start/?arch=%2Fwindows%2Fx86-64%2Fstable%2F.exe+download)

* Configurar `minikube` para que `Hyper V` sea la base de ejecución.

```ps
minikube config set driver hyperv
```

* Iniciar `minikube` con `Hyper V`.

```ps
minikube start --driver hyperv --hyperv-virtual-switch="Default Switch"
```

* Detener `minikube`

```ps
minikube stop
```

* Ver los perfiles, las maquinas y el estado en `minikube`.

```ps
minikube profile list
```

* Ver el dashboard de `kubernetes`

```ps
minikube dashboard
```