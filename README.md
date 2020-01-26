# Kubernetes Desktop Client

Kubernetes desktop client which allows to open terminal into a pod with a click of a button.

NOTE: This software is still work in progress

## Known Issues

* If token used by `kubectl` is expired, application will refresh it, but not save into `~/.kube/config`. This will cause `kubectl` break with error `Refresh token is invalid or has already been claimed by another client.`. The solution for now is to list some resources using `kubectl` in a corresponding context first, e.g.: `kubectl get pods`. After that everything will work fine, untill token expires again.

## Screenshots

<img src="images/screen-1.png">
<img src="images/screen-2.png">
<img src="images/screen-3.png">
<img src="images/screen-4.png">

## Downloads

All versions are available in [releases](https://github.com/inikolaev/get-kubernetes-desktop-client/releases).
