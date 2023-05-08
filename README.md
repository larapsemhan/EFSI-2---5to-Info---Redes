# EFSI 2
## Clasroom 5° a:
En proceso :construction_worker:
## Clasroom 5° b:
En proceso :construction_worker:

___
# TP1

(Template)

 ## Consigna:
 * El trabajo es por grupos de proyecto
 * Tienen que trabajar todos utilizando la metodologia del workflow de github
 * Organizar que parte del glosario/tabla hace cada uno por medio de la seccion de Issues
 * Cada alumno:
    * trabaja en su propia Branch
    * tiene que resolver por lo menos 1 issue del profesor
    * tiene que efectuar un pull request y resolver conflictos


# Tabla "Guia" =\> "Cheat-Sheet":

<table class="tg">
<thead>
  <tr>
    <th class="tg-9wq8" colspan="6">MODELO DE CAPAS (Layers)</th>
    <th class="tg-9wq8" rowspan="2">Protocolos de red </th>
    <th class="tg-9wq8" rowspan="2">Dispositivo de conexion de red</th>
  </tr>
  <tr>
    <th class="tg-9wq8">"Tipos" de Capas</th>
    <th class="tg-9wq8" colspan="2"> MODELO OSI</th>
    <th class="tg-9wq8" colspan="2">MODELO TCP/IP </th>
    <th class="tg-9wq8">Unidad de datos de protocolo (PDU)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-9wq8" rowspan="4">Capas del anfitrion/host "Software"</td>
    <td class="tg-9wq8">7</td>
    <td class="tg-9wq8">Aplication</td>
    <td class="tg-9wq8" rowspan="3">4</td>
    <td class="tg-9wq8" rowspan="3">Process</td>
    <td class="tg-9wq8" rowspan="3"></td>
    <td class="tg-9wq8" rowspan="3"></td>
    <td class="tg-9wq8" rowspan="4"></td>
  </tr>
  <tr>
    <td class="tg-9wq8">6</td>
    <td class="tg-9wq8">Presentation</td>
  </tr>
  <tr>
    <td class="tg-9wq8">5</td>
    <td class="tg-9wq8">Session</td>
  </tr>
  <tr>
    <td class="tg-9wq8">4</td>
    <td class="tg-9wq8">Transport</td>
    <td class="tg-9wq8">3</td>
    <td class="tg-9wq8">Transport</td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
  </tr>
  <tr>
    <td class="tg-9wq8" rowspan="4">Capas de red  "Firmware" "Hardware"</td>
    <td class="tg-9wq8">3</td>
    <td class="tg-9wq8">Network</td>
    <td class="tg-9wq8">2</td>
    <td class="tg-9wq8">Network / Internet</td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
  </tr>
  <tr>
    <td class="tg-9wq8">2</td>
    <td class="tg-9wq8">Data link</td>
    <td class="tg-9wq8" rowspan="3">1</td>
    <td class="tg-9wq8" rowspan="3">Media</td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
  </tr>
  <tr>
    <td class="tg-9wq8">1</td>
    <td class="tg-9wq8">Physical</td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
  </tr>
  <tr>
    <td class="tg-9wq8">0*</td>
    <td class="tg-9wq8">Media</td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
  </tr>
</tbody>
</table>

*La capa de Medio (Media) no forma parte oficial del Modelo OSI, pero esquematicamente la estudiamos ahi

# Glosario

## Contenido del Glosario:
* Definicion y/o explicacion
* En que capa TCP/IP \<=\> OSI trabajan
### Definiciones Generales
  * Server: 
  Un server, en el lenguaje informático, es un ordenador y sus programas, que están al servicio de otros ordenadores. 
El servidor atiende y responde a las peticiones que le hacen los otros ordenadores. Los otros ordenadores, que le hacen peticiones, serán los "clientes" del servidor.
  * Host: Un Host es un ordenador, que ofrece servicios y datos  al resto de ordenadores conectados a la red, sea esta local o global como internet
  * Telefono IP: Un teléfono IP permite la comunicación por voz mediante la red de datos y servidores de telefonía, donde se autentica mediante credenciales y direcciones IP. 
### Elementos de una red
#### y en que capa de los modelos TCP/IP \<=\> OSI trabajan ==>> se completa en la tabla
  *  Router: Un router es un dispositivo de hardware que permite la interconexión de ordenadores en red. 
  *  Switch
   *  Switch Capa 2 (=): Un switch 2 tiene como función de enrutamiento sólo dirección mac, donde transmite la información a través de cables en una red y permite una comunicación física estable y segura entre dispositivos.
   *  Switch Capa 3:  Un switch 3 admite varios tipos de enrutamiento, como enrutamiento estático y enrutamiento dinámico, donde permite la conmutación de paquetes inspeccionando sus direcciones IP y sus direcciones MAC
  *  Hub: Un HUB sirve para conectar varios dispositivos simultáneamente a uno solo.
  *  Wireless Access-point: Un Wireless Access-point establece una conexión inalámbrica entre equipos donde  forma una red inalámbrica externa) con la que interconectar dispositivos móviles o tarjetas de red inalámbricas
  *  Wireless Router: Un Wireless Router nos provee acceso a la red local y a internet de forma inalámbrica a cualquier dispositivo
  *  WAN: WAN se define como métodos de entrega de capa física y de capa de enlace de datos, entre los que se incluye el direccionamiento, el control de flujo y la encapsulación.
  *  LAN: Un LAN permite a sus usuarios el intercambio de datos y la compartición de recursos.
  *  VLAN: Una VLAN, es un método para crear redes lógicas independientes dentro de una misma red física.​
  *  WLAN: WLAN (Wireless Local Area Network),  es una red de tipo local cuyos equipos no necesitan estar vinculados a través de cables para conectarse.
  *  Media (Medio de Transporte)
* ### Protocolos
  *  VOIP: El término VoIP significa Voz sobre Protocolo de Internet, y se trata de un método con el que puedes hacer llamadas de voz a través de la red. Para eso, se toman el audio de lo que estás diciendo por el micrófono y se convierte en datos digitales, que se transmiten por la red a otro dispositivo donde se interpretan para que se escuche de nuevo la voz.
Esto quiere decir que es una alternativa a las llamadas telefónicas convencionales. Con la VoIP no se depende de la señal de las antenas o del cable del teléfono, sino que se depende de la cobertura de Internet que tengas para poder transmitir las llamadas. Esto tiene una parte negativa, y es que si hay una mala cobertura la llamada también perderá calidad.
  *  DNS: DNS son las iniciales de Domain Name System (sistema de nombres de dominio) y es una tecnología basada en una base de datos que sirve para resolver nombres en las redes, es decir, para conocer la dirección IP de la máquina donde está alojado el dominio al que queremos acceder.
  *  FTP: 
  *  SSH
  *  SMTP
  *  POP
  *  SNMP
  *  DHCP
  *  HTTP/S
  *  TCP / UDP: Un UDP  es un protocolo del nivel de transporte (encapsulado entre la capa de red y la capa de aplicación del modelo OSI) basado en la transmisión sin conexión de datagramas 
  *  IPv4: Un IPv4 tiene la responsabilidad de identificar hosts basados en sus direcciones lógicas donde dirige los datos entre ellos a través de la red subyacente.
  *  IPv6: Un IPv6 incluye diversas opciones de seguridad en sus especificaciones, como la encriptación de la información y la autentificación del remitente de dicha información.
  *  ARP: ARP (Address Resolution Protocol ó protocolo de resolución de direcciones). Es un protocolo de nivel de red responsable de encontrar la dirección hardware (MAC Address) que corresponde a una determinada dirección IP. Para ello se envía un paquete (ARP request) a la dirección de difusión de la red (broadcast - MAC ff ff ff ff ff ff) que contiene la dirección IP por la que se pregunta, y se espera a que esa máquina (u otra) responda (ARP reply) con la dirección Ethernet que le corresponde. 
  *  MAC: La dirección MAC o MAC Address de un dispositivo es la dirección física de la tarjeta de red. Se trata de un identificador único que es asignado por el fabricante a cada equipo de hardware de red. MAC es el acrónimo o abreviatura de Media Access Control y se refiere al conjunto de protocolos comunicacionales por medio del cual, varios equipos o dispositivos conectados a la red acuerdan usar conjuntamente un determinado medio de transmisión. 
  *  IEEE 802.11 (WIFI): El grupo de estándares IEEE 802.11 describe la capa física y MAC de redes inalámbricas WLAN locales (en Polonia comúnmente conocidas como Wi-Fi). Incluye cuatro protocolos independientes (a, b, g, n).
En el mundo de la tecnología inalámbrica, el término Wi-Fi es sinónimo de acceso inalámbrico en general, a pesar de que es una marca comercial específica propiedad de Wi-Fi Alliance, un grupo dedicado a certificar que los productos de Wi-Fi cumplen con el conjunto de IEEE de estándares inalámbricos 802.11.
  *  IEEE 802.3 (ETHERNET): Ethernet describe una tecnología para redes de datos cableadas que conectan software y/o hardware entre sí. Esto se lleva a cabo principalmente a través de cables LAN, razón por la cual a veces también se hace referencia a Ethernet como tecnología LAN. De esta forma, Ethernet permite el intercambio de datos entre dispositivos finales. Estos pueden ser computadoras, impresoras, servidores, enrutadores u otros. Cuando se combinan en una red local, estos dispositivos establecen conexiones a través del protocolo Ethernet y pueden intercambiar paquetes de datos entre sí. El protocolo actual y más ampliamente distribuido es IEEE 802.3.
  *  Fibra OPTICA: La fibra óptica es un medio físico de transmisión de información, usual en redes de datos y telecomunicaciones, que consiste en un filamento delgado de vidrio o de plástico, a través del cual viajan pulsos de luz láser o led, en la cual se contienen los datos a transmitir.
  *  "Firewall": Un firewall, también conocido como cortafuegos, es un elemento informático que trata de bloquear el acceso, a una red privada conectada a Internet, a usuarios no autorizados.

   

* ###   Unidad de Datos de protocolo (PDU)(Encapsulamiento)
  * Datos: término general para la PDU que se utiliza en la capa de aplicación.
  * Segmento: PDU de la capa de transporte.
  * Paquete: PDU de la capa de red
  * Trama: PDU de la capa de enlace de datos
  * Bits: PDU de la capa física que se utiliza cuando se transmiten datos físicamente por el medio
  * Señal (dbm): es el índice de potencia en decibeles (dB) de la potencia medida en referencia a un milivatio.Mientras más cercano sea el valor a 0, más fuerte será la señal. 

* ###   Medios
  * #### Conectores
    * (con foto) Conector RJ45 Hembra (Jack RJ45)
    * ![Image Conector RJ45 Hembra](https://http2.mlstatic.com/D_NQ_NP_934201-MLA31063664935_062019-O.jpg) 
    * (con foto) Conector RJ45 Macho (ficha RJ45)
    * ![Image Conector RJ45 Macho](https://www.thekingoftechnology.com/thumb/1634108299156_800x800.jpg) 
    * (con foto) Norma T568A y T568B (ficha RJ45 y JackRJ45)
    * ![Image Norma T568A y T568B (ficha RJ45 y JackRJ45)](https://media.fs.com/images/community/upload/kindEditor/202105/07/rj45-colores-1620368705-Z84UyZ6rZ2.webp) 
    * Cable Cruzado vs Cable Derecho
    * ![Image Cable Cruzado vs Cable Derecho](https://wiki.elhacker.net/_/rsrc/1608728549080/redes/zona-fisica/codigo-de-colores-para-cables-de-red-con-conectores-rj45/7.gif) 
  * #### CABLE UTP (CAT5 CAT5e y CAT6)
    * Colores de los pares del cable UTP
    * ![Image Colores de los pares del cable UTP](https://qingcaisite.files.wordpress.com/2016/12/inner-structure-of-cat5-cat5e-and-cat6.jpg) 
    * Diferencias Constructivas
      La principal diferencia entre los cables CAT5e y CAT6 reside en el ancho de banda que puede admitir el cable para las transferencias de datos. Los cables CAT6 han sido diseñados para trabajar con frecuencias de hasta 250 MHz, en comparación con los 100 MHz de los cables CAT5e. Esto significa que un cable CAT6 puede procesar más datos al mismo tiempo. Es similar a la diferencia entre una autovía de 2 y otra de 4 carriles. En ambas podrá circular a la misma velocidad, pero una autovía de 4 carriles soporta mayor tráfico al mismo tiempo.
    * Velocidades Maximas
      Los cables CAT6 funcionan a una frecuencia de hasta 250 MHz, que es más del doble de la de los cables CAT5e (100MHz), ofrecen velocidades de hasta 10GBASE-T o 10 Gigabits Ethernet, mientras que los cables CAT5e admiten hasta 1 GBASE-T o 1 Gigabit Ethernet
    * Distancias Maximas
      Longitud máxima de cable CAT5e vs. CAT6. Tanto CAT5e como CAT6 ofrecen longitudes de hasta 100 m por segmento de red
  * #### IEEE 802.3 (ETHERNET)
    * 10BASE-T (802.3i)
        1. cantidad de pares en uso
        2. Velocidad Maxima
        3. Tipo de cable
    * 100BASE-TX (802.3u)
     1. cantidad de pares en uso
     2. Velocidad Maxima
     3. Tipo de cable
    * 1000BASE-T (802.3ab)
     1. cantidad de pares en uso
     2. Velocidad Maxima
     3. Tipo de cable
    * Full Duplex (802.3x)
    * Auto-negociación
    * Velocidad
      En los inicios de Ethernet se adopta el modo semi dúplex o half-duplex de 10 Mbit/s; por lo tanto, se requieren mecanismos como CSMA / CD para garantizar la   estabilidad del sistema. Con el desarrollo de tecnologías, emergen el modo full-duplex y 100M Ethernet, que mejoran en gran medida el rendimiento de Ethernet. 
    * Full Duplex vs Half Duplex\
      Por un lado podemos empezar a explicar qué significa Full Dúplex. Este término describe la transmisión y recepción de datos simultáneas a través de un canal. Un dispositivo que sea Full Dúplex es capaz de realizar transmisiones de datos de red bidireccionales al mismo tiempo.
      En Dúplex Completo, como se traduce en español, tiene un mejor rendimiento al duplicar el uso del ancho de banda. Un ejemplo en la utilización del Full Dúplex es en un teléfono. Aquí la comunicación es simultánea y de forma bidireccional. También está presente en los switches de red.
      Podemos poner como ejemplo una carretera de dos vías. Por allí pueden pasar coches en ambos sentidos. Lo mismo ocurre con la comunicación en el Full Dúplex. Es por ello que este modo de transmisión ofrece un mejor rendimiento.
      Respecto a las conexiones de Internet hay un punto muy a tener en cuenta y es que las conexiones alámbricas, las que conectan cables Ethernet, son Full Dúplex.
      Esto permite obtener así mejores velocidades.
    * POE (802.3af): 
     El IEEE 802.3af detalla una tecnología PoE diseñada para proporcionar hasta 15.4 W de corriente continua (mínimo 44 VCC y 350 mA) a cada dispositivo. (Debido a las pérdidas en el cable, se garantiza que solo 12.95 W están disponibles en el equipo que se va a alimentar).
La tecnología utiliza un solo conector RJ45 estándar y un cable Cat5 (o incluso Cat3) y puede manejar decenas de vatios. Una vez que la red Ethernet se instala para la comunicación, también se puede utilizar para la energía, ahorrando en materiales, mano de obra, tiempo de instalación y costos de mantenimiento continuo.

