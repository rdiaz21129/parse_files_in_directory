# Purpose:
Program goes through files in a directory, run through each file, pull data (show command) and add to one file.

# How to run python script (version 1.08)<br/>
python3.7 parse_files_in_dir_ver_1_08.py<br/>
Starting string: COMMAND: show lldp neigh<br/>
Enter full directory path: /home/rdiaz/config_backups/site_a/backups/SITEA_backup_20181124/<br/>

cat parse_output.txt | more<br/>

SITEA-I001-B1F2R1_10.235.239.10<br/>
===============<br/>
show lldp neigh<br/>
Capability codes:<br/>
    (R) Router, (B) Bridge, (T) Telephone, (C) DOCSIS Cable Device<br/>
    (W) WLAN Access Point, (P) Repeater, (S) Station, (O) Other<br/>

Device ID           Local Intf     Hold-time  Capability      Port ID<br/>
CNSD-A173           Gi1/0/30       120        W               0<br/>
CNSD-A174           Gi1/0/35       120        W               0<br/>
CNSD-A171           Gi1/0/36       120        W               0<br/>
CNSD-A178           Gi1/0/37       120        W               0<br/>
CNSD-A177           Gi1/0/31       120        W               0<br/>

Total entries displayed: 5<br/>


SITEA-I002-B1F2R1_10.135.2.132<br/>
===============<br/>
show lldp neigh<br/>
Capability codes:<br/>
    (R) Router, (B) Bridge, (T) Telephone, (C) DOCSIS Cable Device<br/>
    (W) WLAN Access Point, (P) Repeater, (S) Station, (O) Other<br/>

Device ID           Local Intf     Hold-time  Capability      Port ID<br/>
CNSD-A139           Fa1/0/1        120        W               0<br/>
CNSD-A140           Fa1/0/5        120        W               0<br/>
CNSD-A141           Fa2/0/47       120        W               0<br/>
CNSD-A142           Fa2/0/48       120        W               0<br/>


Total entries displayed: 4<br/>


