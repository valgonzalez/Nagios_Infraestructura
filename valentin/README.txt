# El archivo nagios.cfg.conf, es una copia del archivo de configuración de nagios, el 
# nagios.cfg.  Este es un respaldo de este archivo.
#
# El archivo htpasswd.users, es el archivo donde se guarda el password de acceso del
# usuario de la interfas web nagiosadmin
#
# El archivo commands.cfg tiene una contraseña definida en el comando NSClient++ que
# hace match con el archivo de config de los clientes windows monitoreados por Nagios.
# Se adicionaron comando adicionales para monitorear los san switches nuevos.
#
# Se modifica el archivo timeperiods, se define un nuevo periodo de tiempo de monitoreo
# llamado workhours-digicel para asignarlo a equipo no productivos. 
#
# Se modifica archivo cgi.cfg, se agrega usuario de solo lectura para el noc
# tambien se copia nuevamente el archivo htpasswd.users 09/02/2022 AT.
#
# Se agrega definicion de comando "check_esxi_hardware" en file command.cfg para monitorear el HW
# de nodos ESXi 09/14/2023 AT.
