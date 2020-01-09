# munin_velop

## Conf examples :
### In /etc/munin/munin.conf :
[velop.mydomain.com]
    address 127.0.0.1
    use_node_name no

### In /etc/munin/plugin-conf.d/velop.mydomain.com :
 [velop_velop.mydomain.com_*]
 env.velop_password myveloppassword
 env.velop_master_host 192.168.1.241

### In /etc/munin/plugins :
velop_velop.rosello.eu_192.168.1.241_wifi0 -> /usr/share/munin/plugins/velop_fqdnhost_nodeip_interface
velop_velop.rosello.eu_192.168.1.241_wifi1 -> /usr/share/munin/plugins/velop_fqdnhost_nodeip_interface
velop_velop.rosello.eu_192.168.1.241_wifi2 -> /usr/share/munin/plugins/velop_fqdnhost_nodeip_interface
velop_velop.rosello.eu_192.168.1.242_wifi0 -> /usr/share/munin/plugins/velop_fqdnhost_nodeip_interface
velop_velop.rosello.eu_192.168.1.242_wifi1 -> /usr/share/munin/plugins/velop_fqdnhost_nodeip_interface
velop_velop.rosello.eu_192.168.1.242_wifi2 -> /usr/share/munin/plugins/velop_fqdnhost_nodeip_interface
velop_velop.rosello.eu_hosts -> /usr/share/munin/plugins/velop_fqdnhost_hosts
