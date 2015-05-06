hdfs-namenode Cookbook
======================
COnfigures a node to run hdfs-namenode service

Requirements
------------

Attributes
----------

Usage
-----
#### hdfs-namenode::default
knife bootstrap IP -j '{"masterip": "x.x.x.x"}' -x vagrant -P vagrant -r 'recipe[hdfs-namenode]' --sudo

A hadoop name node will be started on IP and will listen to the value specified for "masterip" at port 9000.

Contributing
------------

License and Authors
-------------------
