# openshift-g2
### Base is CentOS 7 minimal installation  
```shell:
sudo yum -y install git
git clone https://github.com/pjos/openshift-g2.git
sudo openshift-g2/bin/install-oc-env
```

### start local OpenShift cluster

`sudo oc cluster up`
