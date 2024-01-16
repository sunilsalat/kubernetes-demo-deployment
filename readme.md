## To encode string to base64

echo -n "This is a string to be encoded." | base64

## kubectl useful commands

-   kubectl get all / pods / deployment
-   kubectl get configmap
-   kubectl get secret
-   kubectl delete deployment <deployment-name>
-   kubectl rollout restart deployment <deployment-name>
-   kubectl describe pds/ service/ deployment <name-of-component>
-   kubectl logs <pod-name> -f
-   kubectl get node -o wide - to get ip of node
-   kubectl port-forward <pod-name | service-name | etc> <localhost-port>:<pod-port>
