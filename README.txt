This project deploy 2 instances in yandex.cloud - builder and prod. To deploy is used terrafom with ansible 
In the main server use Ubuntu 20.04
Config ansible.cfg - timeout and inventory directory (need if you don't use root)
Check app - ip_addr_prod:8080/LoginWebApp