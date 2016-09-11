## Puertos Lógicos  
  
  Un *Puerto Lógico* es una zona, o localización, de la memoria de un ordenador que se asocia con un puerto físico o con un canal de comunicación, y que proporciona un espacio para el almacenamiento temporal de la información que se va a transferir entre la localización de memoria y el canal de comunicación.

Un puerto lógico es una salida de bits, que pueden ser 1 o 0, o sea, un puerto es el valor que se usa en el modelo de la capa de transporte para distinguir entre las múltiples aplicaciones que se pueden conectar al mismo host, o puesto. Entonces un puerto lógico de Internet es una interface de software que permitirá el ingreso y salida de data por aplicaciones que usan Internet.

Los puertos se identifican por números desde 1 hasta más de 65.000.

Los principales puertos lógicos, son los siguientes:

* *20 - __FTP Data__* - Utilizado por servidores FTP (File Transfer Protocol) para la transmicion de datos en modo pasivo.  
* *21 - __FTP__* - Tambien utilizado por servidores FTP. Su mala configuracion puede resultar en ataques (troyanos, hacking, etc..).  
* *22 - __SSH__* - Puerto utilizado por Secure Shell (SSH), el cual es un protocolo y un programa que lo utiliza para acceder a maquinas remotas a travez de una red. Ademas funciona como una herramientra de transmicion de datos, desde ficheros sueltos hasta una sesion de FTP cifrado.  
* *23 - __Telnet__* - Telnet es una herramienta que proporcionauna ventana de comandos, los cuales permiten controlar una pc de forma remota. Es una de las formas mas faciles de entrar ilicitamente en una pc ajena.  
* *25 - __SMTP__* - Puerto utilizado por SMTP (Simple Mail Transfer Protocol), o en español Protocolo de transferencia simple de correo electronico. Como deben suponer, es el protocolo, basado en texto, que permite transferir correo electronico entre diferentes computadoras, PDA's, celulares, etc.  
* *53 - __DNS__* - Este puerto lo utiliza el DNS (Domain Name System), esta base de datos distribuida o jerarquica, se encarga de traducir nombres de dominios a IP's.  
* *59 - __DCC__* - Utilizado principalmente en programas de comunicacion para transferir ficheros.  
* *79 - __Finger__* - En este puerto se corre el servicio Finger, el cual a sido uno de los mayores problemas de seguridad en Unix, ya que este proporciona informacion, muy detallada, de los usuarios de una maquina, esten o no logueados.  
* *80 - __HTTP__* - Puerto que transmite el protocolo HTTP (Hypertext Transfer Protocol) que es el utilizado en cada transaccion web (WWW).  
* *110 - __POP3__* - Puerto que utiliza el servicio POP3 (Post Office Protocol 3), que es el correo electronico, offline.  
* *113 - __IDENT__* - Servicio de identificacion/autorizacion. Los servidores de internet, como POP, IMAP, SMTP, IRC consultan este puerto en respuesta a conexiones de clientes.  
* *135 - __RPC__* - Remote Procedure Cell. Este servicio, es el encargado de administrar la comunicacion con otra pc cuando un programa solicita ejectuar codigo en esa otra pc. De esta forma, el programador no tiene que procuparse por esta conexion.  
* *139 - __NetBIOS__* - Por este puerto funciona el servicio NetBIOS que es el encargado de compartir ficheros de tu pc, por tu red interna. Con este puerto abierto peligras de que gente de todo el mundo, pueda ver y usar estos ficheros a travez de internet.  
* *143 - __IMAP__* - Por aca, se ejecuta el IMAP (Internet Message Access Protocol). Este es un servicio nuevo, por lo cual los servidores de internet que lo utilizan, no han tenido suficiente tiempo para madurar. Lo cual implica, que este sea una muy buena via de acceso para los intrusos.  
* *443 - __HTTPS__* - El Hypertext Transfer Protocol Secure, no es mas que una versión segura, del ya mencionado HTTP.  
* *445 - __MSFT DS__* - Server Message Block. A partir de Windows 2000, microsoft añadió la posibilidad de ejecutar SMB directamente sobre TCP/IP sin la capa extra de NBT.  
* *1080 - __Socks__* - Aqui funciona el servicio Socks, el cual es un protocolo que permite a las aplicaciones cliente-servidor usar de manera transparente los servicios de un firewall de red.  
* *5000 - __UPnP__* - El universal plug n' play define protocolos y procedimientos comunes para garantizar la interoperatividad sobre PC's permitidos por red, aplicaciones y dispositivos inalambricos.  
* *8080 - __WebProxy__* - Este puerto lo pueden utilizar terceros para ocultar su verdadero IP a los servidores web.  

*Fuente:* [Puertos lógicos](https://sites.google.com/site/gestionderedesdedatossmt/puertos-y-servicios/puertos-fisicos/puertos-fisicos)
