# ansible-docker-fgb-sbpp
Ansible playbook to deploy sourcebans and stuff for friendgroupb.com


Uses venv stuff fyi. Target host is Debian 13 currently

FYI:
Need to change vars at bottom in group_vars/all.yml
templates/Caddyfile.j2 has some hardcoded FQDNs on the Caddyfile
db-init.sql.j2 references an IP references in all.yml to allow external DB access (your gmod server most likely!)
Update invntory.yml with your target IPa
Copy site files task in playbook.yml took forever last time, might not be working correctly?
