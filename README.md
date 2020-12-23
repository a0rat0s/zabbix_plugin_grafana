# zabbix_plugin_grafana
**Alexander Zobnin**'s [Zabbix plugin for Grafana](https://grafana.com/grafana/plugins/alexanderzobnin-zabbix-app) compiled for **FreeBSD**.

I uploaded this compiled version of [alexanderzobnin-zabbix-app](https://github.com/alexanderzobnin/grafana-zabbix-app) for Grafana from my own need to compile it for FreeBSD since i love FreeBSD and i use grafana and zabbix in a FreeBSD server and although linux and windows binary versions of the plugin are available for the latest release, for FreeBSD there is none until today **(December 21, 2020)**.
[Reference here](https://github.com/alexanderzobnin/grafana-zabbix/issues/1022), [and here](https://github.com/alexanderzobnin/grafana-zabbix/issues/1054#issuecomment-706676252)

So i uploaded my compiled binary file [zabbix-plugin_freebsd_amd64](https://github.com/a0rat0s/zabbix_plugin_grafana/releases/latest) in case there is someone who wants to use it because it may be difficult for some to prepare the proper build environment e.g. being behind proxies with self-signed certs, difficulty to set up proper os and programs, etc.

Compiled as Alexander Zobnin [recommends here](https://github.com/alexanderzobnin/grafana-zabbix/issues/1022#issuecomment-682366412)

**Details:**<br>
**Author of Zabbix plugin for Grafana:** Alexander Zobnin

**Compilation Details**
**OS:** <FreeBSD 12.1-RELEASE>
**Node.js** version: <node-14.13.0>
**go** version: <go-1.15.6,1>

How to install:
Just copy **zabbix-plugin_freebsd_amd64** to **/var/db/grafana/plugins/alexanderzobnin-zabbix-app/** and start/restart Grafana service.
