# Proyecto_software
Proyecto Integrador
El diseño de la red:

![Anotación 2020-03-06 195730](https://user-images.githubusercontent.com/60333022/76133688-5f596680-5fe7-11ea-93f4-51aa80cff26c.jpg)


Solo tiene una puerta de enlace para toda la red, se usaron varias configuraciones para poder tener la red bien configurada.

La red consta de 4 Switch la cual todos tienen configurado el puerto troncal en el f0/1 con diferentes vlans:
 
 las vlans asignadas fueron:
 
  Switch 1: vlan40
  
  Switch 2: vlan 50
  
  Switch 3: vlan 60
  
  Switch 4: vlan 70
  
  
Asi como el router consta con entrada y salida de datos para todas las maquinas, todas las maquinas estan conectadas
y hacen ping asi esten en diferentes vlans.

las vlans nativas con las ip de los switch son las siguientes:

Switch 1: vlan nativa 40 con ip 172.16.4.2

Switch 2: vlan nativa 50 con ip 172.16.4.17

Switch 3: vlan nativa 60 con ip 172.16.3.33

Switch 4: vlan nativa 71 con ip 172.16.4.49


Se uso  clase B en todas las redes con 16 hosts totales y 14 usados







