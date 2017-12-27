HOW TO USE
==========

Uses **net-snmp-5.7.3** to build your custom snmp agent. 

```
docker run -it truthadjustr/net-snmp-builder bash
cd /net-snmp/
./configure 
make
```

To manually build image in your machine:

```
git clone https://github.com/truthadjustr/net-snmp-builder.git
cd net-snmp-builder/
docker build -t mybuilder .
```
And then you can use your new image **mybuilder**.

```
docker run -it mybuilder bash
cd /net-snmp
```

