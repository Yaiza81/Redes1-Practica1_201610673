# Práctica 1

Se solicita configurar y administrar los dispositivos de una infraestructura de red para una compañía siguiendo la siguiente topología de red

### Topología de red 
![T](C:/Users/usuario/Pictures/Screenshots/topo.png)

## Configuraciones para la topología de Red 
  A continuación se detalla cada uno de los comandos necesarios para realizar la configuración de cada uno de los dispositivos que conforman la topología de red 

### Router 
  Comando para acceder a la configuración de la terminal 
  - configure terminal 
  
  Comando para acceder a la interfaz fastEthernet 0/0
  - int f0/0
  
  Comando para configurar la ip del router 
  - ip address 192.168.13.254 255.255.255.0
  
  Comando para activar la interfaz
  - no shutdown
  
  Salir de la interfaz fastEthernet 0/0
  - Exit 
  
  Comando para acceder al fastEthernet 0/1
  - int f0/1
  
  Comando para configurar la ip del router 
  - ip address 192.168.17.254 255.255.255.0
  
  Comando para activar la interfaz
  - no shutdown
  
  Salir de fastEthernet 0/1
  - Exit 
  
  Salir de las configuraciones
  - exit 
  
  Guardar los cambios 
  - wr 
  
  Para mostrar la información de las interfaces
  - show ip interface brief
  

### VPC2
  Comando para configurar la ip 
  - ip 192.168.13.15/24 192.168.10.254
  
  Para mostrar la configuración de ip y máscara de red 
  - sh ip 
  
  Para guardar los cambios 
  - save 

### VPC3
 Comando para configurar la ip 
  - ip 192.168.17.15/24 192.168.10.254
  
  Para mostrar la configuración de ip y máscara de red 
  - sh ip 
  
  Para guardar los cambios 
  - save

### VPC4
 Comando para configurar la ip 
  - ip 192.168.17.30/24 192.168.10.254
  
  Para mostrar la configuración de ip y máscara de red 
  - sh ip 
  
  Para guardar los cambios 
  - save

### linux-1
  Entrar al panel de control 
  
  Seleccionar Network 
  
  Ingresar la siguiente ip
  
  
  Al darle enter los espacios se llenan automaticamente 
  
  Aplicar y Salir 
  
  
  Abrir la terminal 
   Comando para mostrar la configuración 
   - ifconfig 
   
   
    


## Glosario


