# TA-onionImport
This add-on is to be used on a Security Onion Import node to ingest Zeek logs located at /nsm/import/.../zeek/logs/\*.log and Suricata logs located at /nsm/import/.../suricata/eve\*.log

This add-on contains 64 unique inputs, one for Suricata's EVE log while also accounting for all of Zeek's default log types found here: https://docs.zeek.org/en/current/script-reference/log-files.html

This add-on also creates 46 unique indexes ((1) Suricata & (45) Zeek)

Use this add-on with [TA-Zeek](https://github.com/InfinityWatch/TA-Zeek) and [TA for Suricata](https://splunkbase.splunk.com/app/4242/) to parse your imported Zeek and Suricata data!
