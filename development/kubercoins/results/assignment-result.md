# INSTALACIÍN DE KUBERCOINS

Participantes
- Victor Eduardo Zavaleta rangel
- Daniel Eduardo Aguuilar Zuñiga
- Eleu López López
- Arce muñoz Ocampo

Actividades
- Instalar la aplicación en un namespace dedicado en el nodo 1.
- Verificar el estado de los nodos del cluster Kubernetes.
- Clonar el repositorio [kubercoins](https://github.com/jpetazzo/kubercoins).
- Iniciar la aplicación en kubernetes.
- Verificar los logs de los pods aplicativos.
- Navegar al webui.

Comandos
- `kubectl get nodes`
- `cd ~`
- `git clone https://github.com/jpetazzo/container.training`
- `kubectl apply -f ~/container.training/k8s/dockercoins.yaml`
- `kubectl logs deploy/worker` 
- `kubectl logs deploy/hasher` 
- `kubectl get svc webui` 
- `curl 10.96.112.44/index.html` 
