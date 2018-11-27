# Purpose:
Program goes through files in a directory, run through each file, pull data (show command) and add to one file.

# How to run python script (version 1.08)<br/>
python3.7 parse_files_in_dir_ver_1_08.py
Starting string: COMMAND: show lldp neigh
Enter full directory path: /home/rdiaz/config_backups/site_a/backups/SITEA_backup_20181124/

cat parse_output.txt | more

SITEA-I001-B1F2R1_10.235.239.10
===============
show lldp neigh
Capability codes:
    (R) Router, (B) Bridge, (T) Telephone, (C) DOCSIS Cable Device
    (W) WLAN Access Point, (P) Repeater, (S) Station, (O) Other

Device ID           Local Intf     Hold-time  Capability      Port ID
CNSD-A173           Gi1/0/30       120        W               0
CNSD-A174           Gi1/0/35       120        W               0
CNSD-A171           Gi1/0/36       120        W               0
CNSD-A178           Gi1/0/37       120        W               0
CNSD-A177           Gi1/0/31       120        W               0

Total entries displayed: 5


SITEA-I002-B1F2R1_10.135.2.132
===============
show lldp neigh
Capability codes:
    (R) Router, (B) Bridge, (T) Telephone, (C) DOCSIS Cable Device
    (W) WLAN Access Point, (P) Repeater, (S) Station, (O) Other

Device ID           Local Intf     Hold-time  Capability      Port ID
CNSD-A139           Fa1/0/1        120        W               0
CNSD-A140           Fa1/0/5        120        W               0
CNSD-A141           Fa2/0/47       120        W               0
CNSD-A142           Fa2/0/48       120        W               0


Total entries displayed: 4

