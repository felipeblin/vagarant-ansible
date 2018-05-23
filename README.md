# vagrant-ansible
La idea de este proyecto es probar vagrant con ansible
Se crean tres máquinas dos con Centos/7 y una con ubuntu/trusty64
Un servidor es Apache que tiene una página en demo en "192.168.33.12/11"
Otro servidor es mysql
El server apache se puede chequear con:
 1.- vagrant ssh server
 2.- sudo systemctl status httpd
 3.- exit
 También con ip addr se puede ver la ip de la máquina
 Después en un browser en máquina local se puede ver la página
 de ejemplo index.html
