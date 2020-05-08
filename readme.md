
# Kubernetes Example Login

![https://github.com/OktaySavdi/kubernetes_login_example](https://user-images.githubusercontent.com/3519706/81250356-763d2900-9029-11ea-8e30-61df78e190ee.png)

Integration of the login application prepared with asp .net core on Kubernetes with open source products is provided.

Code repo for image  [github\login_example](https://github.com/OktaySavdi/login_example)

## [](https://github.com/OktaySavdi/kubernetes_login_example)Tools & technologies used

1.  Asp .Net Core
2.  Docker
3. Kubernetes

## [](https://github.com/OktaySavdi/kubernetes_login_example) Required

-   Docker
-   Kubernetes
-   Ingress Controller

## [](https://github.com/OktaySavdi/kubernetes_login_example) Install

Give execute permission for install.sh
```
kubectl create namespace login
```
Install example
```
kubectl create -f login.yaml -n login
```

Call URL
```ruby
http://[NodeIP]
http://login.10.10.10.10.nip.io
```
## [](https://github.com/OktaySavdi/kubernetes_login_example) Screen
**first login screen** 

![https://github.com/OktaySavdi/kubernetes_login_example](https://user-images.githubusercontent.com/3519706/81252376-74c22f80-902e-11ea-8b9c-6ae8324a1501.png)

**input interface**

![https://github.com/OktaySavdi/kubernetes_login_example](https://user-images.githubusercontent.com/3519706/81252403-80155b00-902e-11ea-90a7-5fddc7fcd5ac.png)

**login screen**

![https://github.com/OktaySavdi/kubernetes_login_example](https://user-images.githubusercontent.com/3519706/81252416-87d4ff80-902e-11ea-86ba-e21372e432ab.png)

```
default username: admin
default password: password
```
