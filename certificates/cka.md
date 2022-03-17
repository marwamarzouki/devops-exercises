## Certified Kubernetes Administrator (CKA)

### Pods contient un ou plusieurs conteneur (plus petite unité dans kubernetes)

<details>
<summary>Deploy a pod called web-1985 using the nginx:alpine image</code></summary><br><b>

`kubectl run web-1985 --image=nginx:alpine --restart=Never`
</b></details>

<details>
<summary>How to find out on which node a certain pod is running?</summary><br><b>

`kubectl get po -o wide`
</b></details>
