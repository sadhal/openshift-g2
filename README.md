# openshift-g2
### The base is a CentOS 7 minimal installation  
```shell:
sudo yum -y install git
git clone https://github.com/pjos/openshift-g2.git
sudo openshift-g2/bin/install-oc-env
```

### Start local OpenShift cluster

```shell:
sudo oc cluster up
```
