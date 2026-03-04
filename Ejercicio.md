Primero hago npm install.
![alt text](image.png)  

Activo depensantbot y espero a que lea el fichero para que pueda detectar las alertas.  

![alt text](image-2.png)  

![alt text](image-1.png)  

Ya aparecen los mensajes:  

![alt text](image-3.png)  

### Comenta brevemente las vulnerabilidades que consideres que tienen más importancia.
- qs (versión 0.6.6 y 6.2.0): Presenta varias alertas de severidad Alta. Este paquete se encarga de parsear consultas URL. Podría permitir a un atacante inyectar propiedades en objetos globales de JavaScript y ejecutar código.
- hoek (versión 2.16.3): Su vulnerabilidad de nivel Alto generalmente se refiere a denegación de servicio (DoS) por un uso ineficiente de memoria
- path-to-regexp: Esta vulnerabilidad suele estar ligada a ReDoS (Regular Expression Denial of Service). Un atacante puede enviar una URL  que haga que la expresión regular tarde un tiempo indefinido en procesarse, dejando la web colgada.