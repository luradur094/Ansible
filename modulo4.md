# Configurar un playbook en Ansible
Los playbooks lo que hacen es permitirnos gestionar la configuracion de despliegue

Su configuracion se realiza de la siguiente manera.
- Los parametros se introducen en un fichero .yml
- Su estructura seria la siguiente:

![Local](https://github.com/luradur094/Ansible/blob/main/Imagen/pagina%20ansible.png)

- Ansible tiene diferentes modulos que realizan determinadas acciones por ejemplo:
1- File: Este moculo lo que haces es manejar los ficheros y sus propiedades

2- Git: Este modulo lo que hace es realizar gestiones del git contra los repositorios para la implementacion de archivos o software

3- Archive: Este modulo crea un archivo comprimido de uno o mas archivos 

4- Command: Este modulo es uno de los mas basicos toma el nombre del comando seguido de una lista de argumentos

-5 Copy: Este modulo copia un archivo desde la maquina local o remota a una direccion de la maquina remota 