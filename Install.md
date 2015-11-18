# install nutch_solr on ubuntu 12.04

#### install Solr 3.6.0 on ubuntu 12.04
```
sudo apt-get install openjdk-7-jdk
sudo mkdir solr
cd solr
wget http://archive.apache.org/dist/lucene/solr/3.6.0/apache-solr-3.6.0.tgz
tar -xzvf apache-solr-3.6.0.tgz
cd /example
java -jar start.jar*
```
#### install Nutch 1.5 on ubuntu 12.04
```
sudo mkdir nutch
cd nutch
wget https://archive.apache.org/dist/nutch/1.5/apache-nutch-1.5-bin.tar.gz
tar -xzvf apache-nutch-1.5-bin.tar.gz
```


