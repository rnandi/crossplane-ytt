# crossplane-ytt
Deploys [Crossplane](https://github.com/crossplaneio/crossplane) using [ytt](https://get-ytt.io/) and [kapp](https://get-kapp.io/).

## Install
```
$ ytt -f . | kapp deploy -a crossplane -f- -c -y
$ kapp inspect -a crossplane
