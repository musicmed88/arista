# arista
Early attempts at Arista scripts
1. pull_interface_status - logs in and pulls interface, description, status, and vlan ID for access port
-- Note that this breaks if it hits an interface that is part of a trunk or Port-channel
2. pull_inventory - logs in and pulls hostname, IP, Firmware, and model
