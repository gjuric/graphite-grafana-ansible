Ansible role for Graphite & Grafana
===================================

Tested on Debian 8 (Jessie).

The setup
---------

* Graphite web is run with uWSGI
* Graphite web is available through nginx (port 8080)
* Granafa is available on default HTTP port (80)
in front of Graphite web and Graphana