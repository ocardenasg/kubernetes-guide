# Kubernetes (k8s)

## GENERALES

```
kubectl api-resources
```

## PODS

#### Listar pods:

```
kubectl get pods
```

#### Crear un pod básico:

```
kubectl run --generator=run-pod/v1 --image=IMAGE POD_NAME
```

#### Eliminar un pod:

```
kubectl delete pod POD_NAME ANOTHER_POD_NAME ...
```

#### Detalles de un pod:

```
kubectl describe pod POD_NAME
```

#### Obtener el manifiesto de los pods:

```
kubectl get pod POD_NAME -o yaml
```
