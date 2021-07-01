OpenCluster  --   Python Distributed Computing API
===========
### 1,Install
```bash
	$ git clone https://github.com/astroitlab/opencluster.git ${OPENCLUSTER_HOME}
```
### 2,Configuration:
```bash
    $ mkdir -p /work/opencluster/logs
    $ cp ${OPENCLUSTER_HOME}/opencluster/config.ini ${OPENCLUSTER_HOME}/opencluster/logging.conf /work/opencluster
```    
### 3,Start Cluster

modify config.ini and sbin/nodes according to your cluster, then run:
```bash
	$ sbin/start-all.sh
```    
### 4,Run tests
```bash
    $ cd ${OPENCLUSTER_HOME}
    $ python example/helloManager.py -h
```    