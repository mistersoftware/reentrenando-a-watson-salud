05/08/2020 @
7:24
PM
5
Intents
19:24
 
<div class="msgj">Buena noche.</div>
 
<div class="msgj">En Watson salud nos complace poder asistirte.</div>
 
<div class="msgj">Puedes llamarme Mister chatbot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
me llamo jose
 
 
¿Te llamaré José vale?
ok
 
¿Qué puedo hacer por ti el día de hoy José?
deseo agendar una cita medica
 
¿La cita médica es para ti o es para alguien más?
es para alguien mas
 
Por favor indicame el número de documento del paciente que requiere la cita médica
cc 987349563
 
</br>En este momento estamos enviando tus datos al servicio SAP.</br></br> Pulsa cualquier tecla para continuar.
.
 
José tenemos estas opciones disponibles para la cita médica:</br></br>
 
[Multi-option response]
Title: 1. 15 de julio de 2018 a las 10:20 am en CM SUBA
Description (optional): Descripcion opcional

 
[Multi-option response]
Title: 2. 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR
Description (optional): segunda descripcion

 
3. 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE</br>
 
Elije una o dime otra fecha por favor
la primera
#decisión
la = @pronombres:la
la primera = @opción:primera
 
Has elegido la primera opción:
 
José tu cita médica quedará reservada para el día 15 de julio de 2018 a las 10:20 am en el centro médico CM SUBA, con el documento CC 987349563. </br></br>Recuerda que debes llegar 30 minutos antes y pasar por el punto ágil para facturar tu cuota moderadora.</br></br>Si no puedes ir a tu cita, cancela con 3 horas de anticipación y permite que alguien la tome por ti.</br></br>
 
¿Esta bien?
ok
#aceptar
ok = @decisión:sí
 
</br>En este momento estamos enviando tus datos al servicio SAP.</br></br> Pulsa cualquier tecla para continuar.
.
#corregir
 
Agendada con exito
 
¿Podemos hacer algo más por ti?
no
#decisión
no = @decisión:no
 
chao, ¡cuidate!
19:26

---

06/08/2020 @
6:44
PM
4
Intents
18:44
 
Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio MinTic ICETEX IA y Platzi. </br> </br> Por favor oprime cualquier tecla para comenzar...
.
#corregir
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13D.jpg" title="source: imgur.com" /></a>
 
<div class="msgj">Buena noche.</div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
erasmo
#cambiar_usuario
e = @pronombres:me
erasmo = @extractor:me llamo
asmo = @verbo:llamar
asmo = @persona:yo
asmo = @modo_tiempo:indicativo presente
 
Antes de comenzar permiteme confirmar si he entendio bien tu nombre </br></br>Te llamas erasmo, ¿es correcto?
si
#aceptar
si = @decisión:sí
 
¿Cuál es el motivo de tú visita el día de hoy erasmo?
deseo agendar una cita medica
#agendar_cita
deseo = @verbo:desear
deseo = @persona:yo
deseo = @modo_tiempo:indicativo presente
una = @sys-number:1
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
cita medica = @opción:médica
cita medica = @tramite:Salud
medica = @dato:tipo_de_cita
medica = @especialidad:médica
 
¿La cita médica es para ti o es para alguien más?
es para mi tia
#cambiar_usuario
es = @persona:él
es = @persona:ella
es = @verbo:ser
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
mi tia = @temática:tio
tia = @genero:femenino
 
Procediendo a buscar disponibilidad utilizando tus preferencias guardadas. </br>En este momento estamos enviando tus datos al servicio SAP.</br></br> Pulsa cualquier tecla para continuar.
.
#corregir
 
erasmo tenemos estas opciones disponibles para la cita médica:</br></br>
 
[Multi-option response]
Title: 1. 15 de julio de 2018 a las 10:20 am en CM SUBA
Description (optional): Descripcion opcional

 
[Multi-option response]
Title: 2. 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR
Description (optional): segunda descripcion

 
3. 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE</br>
 
Elije una o dime otra fecha por favor
18:46

---

06/08/2020 @
8:26
PM
2
Intents
20:26
 
Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio MinTic ICETEX IA y Platzi. </br> </br> Por favor oprime cualquier tecla para comenzar...
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13D.jpg" title="source: imgur.com" /></a>
 
<div class="msgj">Buenas noches.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
me llamo pepe
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
pepe = @nombre:José
 
 
Cuéntame José, ¿qué se te ofrece?
deseo agendar una cita medica
#agendar_cita
deseo = @verbo:desear
deseo = @persona:yo
deseo = @modo_tiempo:indicativo presente
una = @sys-number:1
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
cita medica = @opción:médica
cita medica = @tramite:Salud
medica = @dato:tipo_de_cita
medica = @especialidad:médica
 
¿La cita médica es para ti o es para alguien más?
para mi papa
#cambiar_usuario
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
papa = @genero:masculino
papa = @temática:padre
papa = @otra_persona:padre
 
Por favor indicame el número de documento de tu "papa" "papa"
20:28

---

06/08/2020 @
8:44
PM
3
Intents
20:44
 
Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio MinTic ICETEX IA y Platzi. </br> </br> Por favor oprime cualquier tecla para comenzar...
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13D.jpg" title="source: imgur.com" /></a>
 
<div class="msgj">Hola, Buena noche.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
pee
#cambiar_usuario
p = @pronombres:me
= @extractor:me llamo
= @verbo:llamar
= @persona:yo
= @modo_tiempo:indicativo presente
 
Antes de comenzar permiteme confirmar si he entendio bien tu nombre </br></br>Te llamas pee, ¿es correcto?
si
#aceptar
si = @decisión:sí
 
¿Como podemos ayudarte pee?
deseo agendar una cita medica
#agendar_cita
deseo = @verbo:desear
deseo = @persona:yo
deseo = @modo_tiempo:indicativo presente
una = @sys-number:1
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
cita medica = @opción:médica
cita medica = @tramite:Salud
medica = @dato:tipo_de_cita
medica = @especialidad:médica
 
¿La cita médica es para ti o es para alguien más?
es para mi amigo claudio
#cambiar_usuario
es = @persona:él
es = @persona:ella
es = @verbo:ser
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
amigo = @otra_persona:amiga
20:45

---

06/08/2020 @
9:03
PM
3
Intents
21:03
 
Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio MinTic ICETEX IA y Platzi. </br> </br> Por favor oprime cualquier tecla para comenzar...
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13D.jpg" title="source: imgur.com" /></a>
 
<div class="msgj">Hola, Buena noche.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
me llamo jose
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
jose = @nombre:José
 
 
¿Como podemos ayudarte José?
deseo agendar una cita medica
#agendar_cita
deseo = @verbo:desear
deseo = @persona:yo
deseo = @modo_tiempo:indicativo presente
una = @sys-number:1
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
cita medica = @opción:médica
cita medica = @tramite:Salud
medica = @dato:tipo_de_cita
medica = @especialidad:médica
 
¿La cita médica es para ti o es para alguien más?
es para mi tia claudia
#cambiar_usuario
es = @persona:él
es = @persona:ella
es = @verbo:ser
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
mi tia = @temática:tio
tia = @otra_persona:tío
tia = @genero:femenino
claudia = @nombre:Claudia
 
Vamos a necesitar algunos datos de claudia, comencemos por el numero de identificación
pep 21343
#corregir
pep = @tipo_documento:PEP
21343 = @sys-number:21343
 
</br>En este momento estamos enviando tus datos al servicio SAP.</br></br> Pulsa cualquier tecla para continuar.
.
#corregir
 
José tenemos estas opciones disponibles para la cita médica:</br></br>
 
[Multi-option response]
Title: 1. 15 de julio de 2018 a las 10:20 am en CM SUBA
Description (optional): Descripcion opcional

 
[Multi-option response]
Title: 2. 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR
Description (optional): segunda descripcion

 
3. 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE</br>
 
¿Cuál es tu elección?
21:05

---

06/08/2020 @
9:28
PM
4
Intents
21:28
 
Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio MinTic ICETEX IA y Platzi. </br> </br> Por favor oprime cualquier tecla para comenzar...
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13D.jpg" title="source: imgur.com" /></a>
 
<div class="msgj">Hola, Buena noche.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
hola me llamo pepe
#cambiar_usuario
hola = @conversacion:saludo
hola me llamo = @extractor:hola me llamo
me = @pronombres:me
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
pepe = @nombre:José
 
 
Cuéntame José, ¿qué se te ofrece?
deseo agendar una cita medica
#agendar_cita
deseo = @verbo:desear
deseo = @persona:yo
deseo = @modo_tiempo:indicativo presente
una = @sys-number:1
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
cita medica = @opción:médica
cita medica = @tramite:Salud
medica = @dato:tipo_de_cita
medica = @especialidad:médica
 
¿La cita médica es para ti o es para alguien más?
es para mi tia claudia
#cambiar_usuario
es = @persona:él
es = @persona:ella
es = @verbo:ser
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
mi tia = @temática:tio
tia = @otra_persona:tío
tia = @genero:femenino
claudia = @nombre:Claudia
 
Dime el numero de identificación de claudia
so claro, su numero de cedula es 123213233
#aceptar
so = @preposición:so
numero = @dato:numero_documento
numero de cedula = @tipo_documento:CC
de = @persona:ella
de = @persona:él
de = @preposición:de
de = @verbo:dar
cedula = @dato:numero_documento
es = @persona:ella
es = @persona:él
es = @verbo:ser
123213 = @input_patterns:PEP
123213233 = @sys-number:123213233
 
</br>En este momento estamos enviando tus datos al servicio SAP.</br></br> Pulsa cualquier tecla para continuar.
.
#corregir
 
José tenemos estas opciones disponibles para la cita médica:</br></br>
 
[Multi-option response]
Title: 1. 15 de julio de 2018 a las 10:20 am en CM SUBA
Description (optional):  Elige diciendo: 1, la primera, la del 15 de julio de 2018, o la cita de las 10:20 am, o la de CM SUBA

 
[Multi-option response]
Title: 2. 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR
Description (optional): segunda descripcion

 
3. 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE</br>
 
Elije una o dime otra fecha por favor
la de suba
#corregir
la = @pronombres:la
de = @preposición:de
de = @persona:ella
de = @verbo:dar
de = @persona:él
suba = @centro_médico:CM SUBA
 
por favor dime de nuevo, ¿que centro medico prefieres?
suba
#corregir
suba = @centro_médico:CM SUBA
21:29

---

06/08/2020 @
9:41
PM
1
Intents
21:41
 
Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio MinTic ICETEX IA y Platzi. </br> </br> Por favor oprime cualquier tecla para comenzar...
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13D.jpg" title="source: imgur.com" /></a>
 
<div class="msgj">Hola, Buenas noches.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
me llamo manuel
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
manuel = @nombre:Manuel
 
 
¿Cuál es el motivo de tú visita el día de hoy Manuel?
21:41

---

06/08/2020 @
9:51
PM
3
Intents
21:51
 
Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio MinTic ICETEX IA y Platzi. </br> </br> Por favor oprime cualquier tecla para comenzar...
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13D.jpg" title="source: imgur.com" /></a>
 
<div class="msgj">Hola, Buena noche.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
me llamo ricardo
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
ricardo = @nombre:Ricardo
 
 
¿Cuál es el motivo de tú visita el día de hoy Ricardo?
deseo agendar una cita medica
#agendar_cita
deseo = @verbo:desear
deseo = @persona:yo
deseo = @modo_tiempo:indicativo presente
una = @sys-number:1
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
cita medica = @opción:médica
cita medica = @tramite:Salud
medica = @dato:tipo_de_cita
medica = @especialidad:médica
 
¿La cita médica es para ti o es para alguien más?
es para mi tia manuela
#cambiar_usuario
es = @persona:él
es = @persona:ella
es = @verbo:ser
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
mi tia = @temática:tio
tia = @otra_persona:tío
tia = @genero:femenino
 
Por favor indicame el número de documento de tu tia
su numero de cedula es 123234243
#corregir
numero = @dato:numero_documento
numero de cedula = @tipo_documento:CC
de = @persona:ella
de = @persona:él
de = @preposición:de
de = @verbo:dar
cedula = @dato:numero_documento
es = @persona:ella
es = @persona:él
es = @verbo:ser
123234 = @input_patterns:PEP
123234243 = @sys-number:123234243
 
--- Intercambiando datos con servidor --- </br></br>
 
Ricardo tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. 15 de julio de 2018 a las 10:20 am en CM SUBA
Description (optional):  Elige diciendo: " la primera, la del 15 de julio de 2018, o la cita de las 10:20 am, o la de CM SUBA o simplemente diciendo uno "

 
[Multi-option response]
Title: 2. 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR
Description (optional):  Elige diciendo: " la segunda, la del 15 de julio de 2018, la de las 4:00 pm, o la de CM GRANAHORRAR... o simplemente diciendo dos "

 
[Multi-option response]
Title: 3. 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE</br>
Description (optional): Elige diciendo: " la tercera, la del 26 de julio de 2018, o la de las 1:00 PM, o la de CM PORTAL NORTE... o simplemente diciendo tres "

 
Elije una
21:52

---

06/08/2020 @
10:38
PM
1
Intents
22:38
 
Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio MinTic ICETEX IA y Platzi. </br> </br> Por favor oprime cualquier tecla para comenzar...
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13D.jpg" title="source: imgur.com" /></a>
 
<div class="msgj">Buenas noches.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
angel
#cambiar_usuario
a = @pronombres:me
= @extractor:me llamo
= @verbo:llamar
= @persona:yo
= @modo_tiempo:indicativo presente
 
Antes de comenzar permiteme confirmar si he entendido bien tu nombre </br></br>Te llamas <span style:"text-transform: capitalize;"> ANGEL</span>, ¿es correcto?
22:38

---

06/08/2020 @
10:40
PM
1
Intents
22:40
 
Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio MinTic ICETEX IA y Platzi. </br> </br> Por favor oprime cualquier tecla para comenzar...
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13D.jpg" title="source: imgur.com" /></a>
 
<div class="msgj">Hola, Buenas noches.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
angel
#cambiar_usuario
a = @pronombres:me
= @extractor:me llamo
= @verbo:llamar
= @persona:yo
= @modo_tiempo:indicativo presente
 
Antes de comenzar permiteme confirmar si he entendido bien tu nombre </br></br>Te llamas <span style:"text-transform: capitalize;"> angel</span>, ¿es correcto?


---

06/08/2020 @
10:43
PM
1
Intents
22:43
 
Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio MinTic ICETEX IA y Platzi. </br> </br> Por favor oprime cualquier tecla para comenzar...
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13D.jpg" title="source: imgur.com" /></a>
 
<div class="msgj">Hola, Buenas noches.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
angel
#cambiar_usuario
a = @pronombres:me
= @extractor:me llamo
= @verbo:llamar
= @persona:yo
= @modo_tiempo:indicativo presente
 
Antes de comenzar permiteme confirmar si he entendido bien tu nombre </br></br>Te llamas <span style: text-transform: capitalize; > angel</span>, ¿es correcto?


---

06/08/2020 @
10:44
PM
1
Intents
22:44
 
Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio MinTic ICETEX IA y Platzi. </br> </br> Por favor oprime cualquier tecla para comenzar...
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13D.jpg" title="source: imgur.com" /></a>
 
<div class="msgj">Buenas noches.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
angel
#cambiar_usuario
a = @pronombres:me
= @extractor:me llamo
= @verbo:llamar
= @persona:yo
= @modo_tiempo:indicativo presente
 
Antes de comenzar permiteme confirmar si he entendido bien tu nombre </br></br>Te llamas <span style: 'text-transform: capitalize;'> angel</span>, ¿es correcto?


---

07/08/2020 @
12:22
AM
1
Intents
0:22
 
Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio MinTic ICETEX IA y Platzi. </br> </br> Por favor oprime cualquier tecla para comenzar...
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13D.jpg" title="source: imgur.com" /></a>
 
<div class="msgj">Sin importar la hora, estamos aquí para ti. </div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
cristobuilo
#cambiar_usuario
c = @pronombres:me
cristob = @extractor:me llamo
istob = @verbo:llamar
istob = @persona:yo
istob = @modo_tiempo:indicativo presente
 
Antes de comenzar permiteme confirmar si he entendido bien tu nombre </br></br>¿Tú nombre es ?


---

07/08/2020 @
12:22
AM
1
Intents
0:22
 
Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio MinTic ICETEX IA y Platzi. </br> </br> Por favor oprime cualquier tecla para comenzar...
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13D.jpg" title="source: imgur.com" /></a>
 
<div class="msgj">Sin importar la hora, estamos aquí para ti. </div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
cristobuilo
#cambiar_usuario
c = @pronombres:me
cristob = @extractor:me llamo
istob = @verbo:llamar
istob = @persona:yo
istob = @modo_tiempo:indicativo presente
 
Antes de comenzar permiteme confirmar si he entendido bien tu nombre </br></br>¿Tú nombre es ?
0:23

---


07/08/2020 @
1:50
AM
8
Intents
1:50
 
Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio Platzi - MinTic ICETEX Inteligencia Artificial. </br> </br> Antes que nada ¡¡¡Gracias!!! </br> </br> En el caso de uso que se presenta el chatbot realiza operaciones CRUD sobre una base de datos cloudant la cual ha sido expuesta mediante una API personalizada mediante functions. Todo serverless, una belleza!</br> </br> Es un gran detalle que quieras interactuar con este chatbot te agradezco cualquier comentario o critica constructiva. </br> </br> Para empezar oprime cualquier tecla por favor
.
#corregir
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">De día, de noche e incluso de madrugada estamos aquí para servirte. </div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
me llamo cumbia
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
cumbia = @persona:tú
cumbia = @persona:ella
cumbia = @persona:él
 
No soy muy bueno con los nombres, por eso prefiero asegurarme antes de empezar. </br></br>¿Te llamás Cumbia?
aja
#conversacion
aja = @decisión:sí
 
¿Qué puedo hacer por ti el día de hoy Cumbia?
deseo agendar una cita mdedica
#agendar_cita
deseo = @verbo:desear
deseo = @persona:yo
deseo = @modo_tiempo:indicativo presente
una = @sys-number:1
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
cita mdedica = @opción:médica
mdedica = @especialidad:médica
mdedica = @dato:tipo_de_cita
 
¿La cita médica es para ti o es para alguien más?
es para mi tia juana
#cambiar_usuario
es = @persona:él
es = @persona:ella
es = @verbo:ser
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
mi tia = @temática:tio
tia = @otra_persona:tío
tia = @genero:femenino
 
Por favor indicame el número de documento de tu tia
su numero de ced es q2323423432
#corregir
numero = @dato:numero_documento
de = @preposición:de
de = @persona:ella
de = @verbo:dar
de = @persona:él
ced = @tipo_documento:CC
es = @persona:ella
es = @persona:él
es = @verbo:ser
232342 = @input_patterns:PEP
2323423432 = @input_patterns:CC
 
He interpretado el tipo de documento CC.
 
Ahora dime el número de documento por favor.
234234234
Irrelevant
234234 = @input_patterns:PEP
234234234 = @sys-number:234234234
 
he identificado el número 234234234 --- Intercambiando datos con servidor --- </br></br>
.
#corregir
 
Cumbia tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. 15 de julio de 2018 a las 10:20 am en CM SUBA

 
[Multi-option response]
Title: 2. 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR

 
[Multi-option response]
Title: 3. 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
Description (optional): Elige diciendo: " la primera, la segunda o la tercera, o mencionadola por la fecha y hora directamente si gustas. tambien puedes intentar diciendo la del proximo viernes. usa tu creatividad! "

 
¿Cuál es tu elección?
la primera
#decisión
la = @pronombres:la
la primera = @opción:primera
 
Has elegido la primera opción:
 
Cumbia tu cita médica quedará reservada para el día 15 de julio de 2018 a las 10:20 am en el centro médico CM SUBA, con el documento CC 234234234. </br></br>Recuerda que debes llegar 30 minutos antes y pasar por el punto ágil para facturar tu cuota moderadora.</br></br>Si no puedes ir a tu cita, cancela con 3 horas de anticipación y permite que alguien la tome por ti.</br></br>
 
¿Esta bien?
no
#decisión
no = @decisión:no
 
¿Que deseas corregir?
la hora
#corregir
la = @pronombres:la
hora = @dato:hora
 
Muy bien corregiremos la hora, dímela de nuevo por favor
a las 4 y media pm
#decisión
a = @preposición:a
a las 4 y media pm = @sys-time:16:30:00
las = @pronombres:las
4 = @opción:cuarta
pm = @turno:T
 
¿En que fecha?
el viernes
#emergencia
el = @preposición:la del
el = @pronombres:el
el viernes = @sys-date:2020-08-14
 
Cumbia procederemos a consultar disponbilidad con el documento CC 234234234 para la cita médica, el dia 2020-08-14 a las 16:30:00 </br></br>
 
¿Esta bien?
si claro
#aceptar
si = @decisión:sí
 
--- Intercambiando datos con servidor --- </br></br>
.,
#corregir
 
No fue posible agendarla. Por favor espera un momento mientras buscamos otras opciones disponibles. --- Intercambiando datos con servidor --- </br></br>
.
#corregir
 
Cumbia tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. 15 de julio de 2018 a las 10:20 am en CM SUBA

 
[Multi-option response]
Title: 2. 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR

 
[Multi-option response]
Title: 3. 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
Description (optional): Elige diciendo: " la primera, la segunda o la tercera, o mencionadola por la fecha y hora directamente si gustas. tambien puedes intentar diciendo la del proximo viernes. usa tu creatividad! "

 
¿Te sirve alguna de las anteriores o quieres probar diciéndome una fecha y hora?
1:59

---

07/08/2020 @
5:08
AM
6
Intents
5:08
 
Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio Platzi - MinTic ICETEX Inteligencia Artificial. </br> </br> Antes que nada ¡¡¡Gracias!!! </br> </br> En el caso de uso que se presenta el chatbot realiza operaciones CRUD sobre una base de datos cloudant la cual ha sido expuesta mediante una API personalizada mediante functions. Todo serverless, una belleza!</br> </br> Es un gran detalle que quieras interactuar con este chatbot te agradezco cualquier comentario o critica constructiva. </br> </br> Para empezar oprime cualquier tecla por favor
.
#corregir
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Buenos días.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
me llamo simon
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
 
No soy muy bueno con los nombres, por eso prefiero asegurarme antes de empezar. </br></br>¿Te llamás Simon?
simon
#cambiar_usuario
 
Antes de comenzar permiteme confirmar si he entendido bien tu nombre </br></br>¿Tú nombre es Simon?
sisas
#aceptar
sisas = @persona:tú
 
¿Cuál es el motivo de tú visita el día de hoy Simon?
deseo agendar una cita medica
#agendar_cita
deseo = @verbo:desear
deseo = @persona:yo
deseo = @modo_tiempo:indicativo presente
una = @sys-number:1
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
cita medica = @opción:médica
cita medica = @tramite:Salud
medica = @dato:tipo_de_cita
medica = @especialidad:médica
 
¿La cita médica es para ti o es para alguien más?
es para mi tia paola
#cambiar_usuario
es = @persona:él
es = @persona:ella
es = @verbo:ser
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
mi tia = @temática:tio
tia = @otra_persona:tío
tia = @genero:femenino
paola = @nombre:Paola
 
¿Cuál es el numero de identificación de paola?
tarjeta de identidad 21332434
#corregir
tarjeta de identidad = @tipo_documento:TI
tarjeta de identidad = @dato:numero_documento
de = @preposición:de
de = @persona:ella
de = @verbo:dar
de = @persona:él
213324 = @input_patterns:PEP
21332434 = @sys-number:21332434
 
--- Intercambiando datos con servidor --- </br></br>
 
Simon tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. 15 de julio de 2018 a las 10:20 am en CM SUBA

 
[Multi-option response]
Title: 2. 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR

 
[Multi-option response]
Title: 3. 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
Description (optional): Elige diciendo: " la primera, la segunda o la tercera, o mencionadola por la fecha y hora directamente si gustas. tambien puedes intentar diciendo la del proximo viernes. usa tu creatividad! "

 
¿Te sirve alguna de las anteriores o quieres probar diciéndome una fecha y hora?
la primera
#decisión
la = @pronombres:la
la primera = @opción:primera
 
Has elegido la primera opción:
 
Simon tu cita médica quedará reservada para el día 15 de julio de 2018 a las 10:20 am en el centro médico CM SUBA, con el documento TI 21332434. </br></br>Recuerda que debes llegar 30 minutos antes y pasar por el punto ágil para facturar tu cuota moderadora.</br></br>Si no puedes ir a tu cita, cancela con 3 horas de anticipación y permite que alguien la tome por ti.</br></br>
 
¿Esta bien?
si
#aceptar
si = @decisión:sí
 
{"id":"837c6f061916943dbecee80cece3cc4b","ok":true,"rev":"1-d360b3b6e6e5c83a8c151aa801ffa1d6"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?
si
#aceptar
si = @decisión:sí
 
¿Que otra cosa te gustaría hacer?
deseo agendar una cita odontologica tambien
#agendar_cita
deseo = @verbo:desear
deseo = @persona:yo
deseo = @modo_tiempo:indicativo presente
una = @sys-number:1
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
cita odontologica = @opción:odontológica
odontologica = @dato:tipo_de_cita
odontologica = @especialidad:odontológica
 
¿La cita odontológica es para ti o es para alguien más?
es para mi
#cambiar_usuario
es = @persona:él
es = @persona:ella
es = @verbo:ser
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
 
Dado que es para ti, procederemos a consultar tus preferencias habituales para facilitarte el proceso. --- Intercambiando datos con servidor --- </br></br>
 
--- Intercambiando datos con servidor --- </br></br>
 
Simon tenemos estas opciones disponibles para la cita odontológica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. 15 de julio de 2018 a las 10:20 am en CM SUBA

 
[Multi-option response]
Title: 2. 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR

 
[Multi-option response]
Title: 3. 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
Description (optional): Elige diciendo: " la primera, la segunda o la tercera, o mencionadola por la fecha y hora directamente si gustas. tambien puedes intentar diciendo la del proximo viernes. usa tu creatividad! "

 
Elije una antes que alguien más la reserve
la segunda
#decisión
la = @pronombres:la
la segunda = @opción:segunda
 
Has elegido la segunda opción:
 
Simon tu cita odontológica quedará reservada para el día 15 de julio de 2018 a las 4:00 pm en el centro médico CM SUBA, con el documento TI 21332434. </br></br>Recuerda que debes llegar 30 minutos antes y pasar por el punto ágil para facturar tu cuota moderadora.</br></br>Si no puedes ir a tu cita, cancela con 3 horas de anticipación y permite que alguien la tome por ti.</br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Esta bien?
correcto
#aceptar
correcto = @decisión:sí
 
{"id":"5eac1dfddc60ca64b305e76cb5c75910","ok":true,"rev":"1-f0534e34bc7d29cb55afcb3cb757051b"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?
volver a empezar
#denegar
volver = @verbo:volver
volver = @modo_tiempo:infinitivo
volver a = @persona:ella
volver a = @persona:yo
volver a = @persona:él
a = @preposición:a
empezar = @modo_tiempo:infinitivo
empezar = @verbo:comenzar
 
Hasta luego, ¡vuelve pronto!
5:12


---


07/08/2020 @
5:16
AM
5
Intents
5:16
 
Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio Platzi - MinTic ICETEX Inteligencia Artificial. </br> </br> Antes que nada ¡¡¡Gracias!!! </br> </br> En el caso de uso que se presenta el chatbot realiza operaciones CRUD sobre una base de datos cloudant la cual ha sido expuesta mediante una API personalizada mediante functions. Todo serverless, una belleza!</br> </br> Es un gran detalle que quieras interactuar con este chatbot te agradezco cualquier comentario o critica constructiva. </br> </br> Para empezar oprime cualquier tecla por favor
.
#corregir
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Buenos días.</div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
me llamo jorgito
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
 
Antes de comenzar permiteme confirmar si he entendido bien tu nombre </br></br>¿Tú nombre es Jorgito?
aja
#conversacion
aja = @decisión:sí
 
¿Qué puedo hacer por ti el día de hoy Jorgito?
deseo agendar una cita odontologica con mi cedula 2342345454 para el viernes a las 4 y media pm
#agendar_cita
deseo = @verbo:desear
deseo = @modo_tiempo:indicativo presente
deseo = @persona:yo
una = @sys-number:1
cita = @persona:tú
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
cita = @modo_tiempo:imperativo
cita odontologica = @opción:odontológica
odontologica = @especialidad:odontológica
odontologica = @dato:tipo_de_cita
con = @preposición:con
mi = @pronombres:mí
cedula = @dato:numero_documento
cedula = @tipo_documento:CC
234234 = @input_patterns:PEP
2342345454 = @input_patterns:CC
2342345454 = @sys-number:2342345454
para = @persona:tú
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
para = @preposición:para
para = @modo_tiempo:imperativo
el = @preposición:la del
el = @pronombres:el
el viernes = @sys-date:2020-08-14
a = @preposición:a
a las 4 y media pm = @sys-time:16:30:00
las = @pronombres:las
4 = @opción:cuarta
pm = @turno:T
 
¿La cita odontológica es para ti o es para alguien más?
si
#aceptar
si = @decisión:sí
 
En ese caso podemos usar tus preferencias guardadas para agilizar el proceso. --- Intercambiando datos con servidor --- </br></br>
 
--- Intercambiando datos con servidor --- </br></br>
 
Jorgito tenemos estas opciones disponibles para la cita odontológica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. 15 de julio de 2018 a las 10:20 am en CM SUBA

 
[Multi-option response]
Title: 2. 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR

 
[Multi-option response]
Title: 3. 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
Description (optional): Elige diciendo: " la primera, la segunda o la tercera, o mencionadola por la fecha y hora directamente si gustas. tambien puedes intentar diciendo la del proximo viernes. usa tu creatividad! "

 
¿Alguna de estas opciones te sirve?
5:17

---


07/08/2020 @
5:44
AM
4
Intents
5:44
 
Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio Platzi - MinTic ICETEX Inteligencia Artificial. </br> </br> Antes que nada ¡¡¡Gracias!!! </br> </br> En el caso de uso que se presenta el chatbot realiza operaciones CRUD sobre una base de datos cloudant la cual ha sido expuesta mediante una API personalizada mediante functions. Todo serverless, una belleza!</br> </br> Es un gran detalle que quieras interactuar con este chatbot te agradezco cualquier comentario o critica constructiva. </br> </br> Para empezar oprime cualquier tecla por favor
.
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Ojala estes disfrutando de una hermosa mañana.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
me llamo cumbia
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
cumbia = @persona:tú
cumbia = @persona:ella
cumbia = @persona:él
 
No soy muy bueno con los nombres, por eso prefiero asegurarme antes de empezar. </br></br>¿Te llamás Cumbia?
asi es me llamo cumbia
#aceptar
asi es = @decisión:sí
es = @persona:él
es = @persona:ella
es = @verbo:ser
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
cumbia = @persona:ella
cumbia = @persona:tú
cumbia = @persona:él
 
¿En qué te puedo ayudar Cumbia?
deseo agendar una cita medica con la cedula 12323234 para el domingo al medio dia
#agendar_cita
deseo = @verbo:desear
deseo = @modo_tiempo:indicativo presente
deseo = @persona:yo
una = @sys-number:1
cita = @persona:tú
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
cita = @modo_tiempo:imperativo
cita medica = @opción:médica
cita medica = @tramite:Salud
medica = @dato:tipo_de_cita
medica = @especialidad:médica
con = @preposición:con
la = @pronombres:la
cedula = @dato:numero_documento
cedula = @tipo_documento:CC
123232 = @input_patterns:PEP
12323234 = @sys-number:12323234
para = @persona:tú
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
para = @preposición:para
para = @modo_tiempo:imperativo
el = @preposición:la del
el = @pronombres:el
el domingo = @sys-date:2020-08-09
al medio dia = @turno:T
medio = @sys-number:0.5
dia = @dato:fecha
 
¿La cita médica es para ti o es para alguien más?
si
#aceptar
si = @decisión:sí
 
Procediendo a buscar disponibilidad utilizando tus preferencias guardadas. --- Intercambiando datos con servidor --- </br></br>
 
--- Intercambiando datos con servidor --- </br></br>
 
Cumbia tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. 15 de julio de 2018 a las 10:20 am en CM SUBA

 
[Multi-option response]
Title: 2. 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR

 
[Multi-option response]
Title: 3. 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
Description (optional): Elige diciendo: " la primera, la segunda o la tercera, o mencionadola por la fecha y hora directamente si gustas. tambien puedes intentar diciendo la del proximo viernes. usa tu creatividad! "

 
¿Cuál es tu elección?


---


07/08/2020 @
6:13
AM
1
Intents
6:13
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buenos días.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
me llamo cristobal
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
 
Antes de comenzar permiteme confirmar si he entendido bien tu nombre </br></br>¿Tú nombre es Cristobal?
6:15

---

07/08/2020 @
6:15
AM
2
Intents
6:15
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buen día.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
hugo
 
 
¿Cuál es el motivo de tú visita el día de hoy Hugo?
deseo agendar una cita medica
#agendar_cita
deseo = @verbo:desear
deseo = @persona:yo
deseo = @modo_tiempo:indicativo presente
una = @sys-number:1
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
cita medica = @opción:médica
cita medica = @tramite:Salud
medica = @dato:tipo_de_cita
medica = @especialidad:médica
 
¿La cita médica es para ti o es para alguien más?
6:15

---


07/08/2020 @
6:38
AM
1
Intents
6:38
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Ojala estes disfrutando de una hermosa mañana.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
M3 llamo cumbia
#corregir
M3 llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
cumbia = @persona:tú
cumbia = @persona:ella
cumbia = @persona:él
 
No soy muy bueno con los nombres, por eso prefiero asegurarme antes de empezar. </br></br>¿Te llamás 3 llamo cumbia?


---


07/08/2020 @
6:39
AM
4
Intents
6:39
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Buenos días.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
Me llamo cumbia
#cambiar_usuario
Me = @pronombres:me
Me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
cumbia = @persona:tú
cumbia = @persona:ella
cumbia = @persona:él
 
No soy muy bueno con los nombres, por eso prefiero asegurarme antes de empezar. </br></br>¿Te llamás E llamo cumbia?
No
#decisión
No = @decisión:no
 
Dime tu nombre por favor
Cumbia
Irrelevant
Cumbia = @persona:tú
Cumbia = @persona:ella
Cumbia = @persona:él
 
Tu nombre es Cumbia, ¿es correcto?
Si
#aceptar
Si = @decisión:sí
 
¿En qué te puedo ayudar Cumbia?


---

07/08/2020 @
6:40
AM
1
Intents
6:40
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buenos días.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
Me llamo hugo
#cambiar_usuario
Me = @pronombres:me
Me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
hugo = @nombre:Hugo
 
 
¿Como podemos ayudarte Hugo?


---

07/08/2020 @
6:45
AM
1
Intents
6:45
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Ojala estes disfrutando de una hermosa mañana.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
juliane
#cambiar_usuario
juliane = @nombre:Juliana
 
 
¿Qué puedo hacer por ti el día de hoy Juliana?


---


07/08/2020 @
6:58
AM
3
Intents
6:58
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Buena tarde.</div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
hallo
Irrelevant
hallo = @persona:yo
hallo = @conversacion:saludo
 
Tu nombre es Hallo, ¿es correcto?
ja
#corregir
 
En Watson salud nos gusta ayudarte,</br> Por favor selecciona una de las siguientes opciones: </br></br> 1. Asignar</br> 2. Consultar</br> 3. Reprogramar</br> 4. Eliminar</br>
4
#decisión
4 = @opción:cuarta
4 = @sys-number:4
 
Para comenzar indícanos tu número y tipo de documento
dni
Irrelevant
 
Para comenzar por favor indícame tipo y número de documento del paciente que requiere la cita </br></br>Si la cita es para ti házmelo saber para usar tus preferencias habituales.



---


07/08/2020 @
8:22
AM
3
Intents
8:22
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Buenos días.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
Sergio
#cambiar_usuario
Sergio = @nombre:Sergio
 
 
¿Cuál es el motivo de tú visita el día de hoy Sergio?
Consultar
#consultar_cita
 
Para comenzar indícanos tu número y tipo de documento
C. C 1121959111
#corregir
C. C = @tipo_documento:CC
112195 = @input_patterns:PEP
1121959111 = @input_patterns:CC
1121959111 = @sys-number:1121959111
 
--- Intercambiando datos con servidor --- </br></br>


---

07/08/2020 @
9:08
AM
4
Intents
9:08
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buen día.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
Artu
Irrelevant
 
Tu nombre es Artu, ¿es correcto?
Si
#aceptar
Si = @decisión:sí
 
¿Cuál es el motivo de tú visita el día de hoy Artu?
Quiero hacer un motor de ajedrez
#emergencia
Quiero = @persona:yo
Quiero = @verbo:querer
Quiero = @modo_tiempo:indicativo presente
hacer = @modo_tiempo:infinitivo
hacer = @verbo:hacer
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
 
En Watson salud nos gusta ayudarte,</br> Por favor selecciona una de las siguientes opciones: </br></br> 1. Asignar</br> 2. Consultar</br> 3. Reprogramar</br> 4. Eliminar</br>
2
#decisión
2 = @sys-number:2
4
#decisión
4 = @opción:cuarta
4 = @sys-number:4
 
Para comenzar indícanos tu número y tipo de documento


---

07/08/2020 @
10:32
AM
2
Intents
10:32
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buenos días.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
Hola
#conversacion
Hola = @conversacion:saludo
Hola = @extractor:hola
 
¡Hola! ¿como te va?
Bien. Pará agendar una cita
#agendar_cita
Bien = @adverbio:bien
Bien = @conversacion:bienestar
Pará = @persona:tú
Pará = @persona:él
Pará = @persona:yo
Pará = @persona:ella
una = @sys-number:1
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
 
me alegra saber que estas bien,
 
¿en que te puedo colaborar?
Agendar una cita
#agendar_cita
una = @sys-number:1
cita = @persona:ella
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
 
¿Cuál clase de cita necesitas agendar hoy ? </br> </br>1. Medicina general, </br>2. Odontología Básica.


---

07/08/2020 @
11:51
AM
4
Intents
11:51
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buenos días.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
Hola
#conversacion
Hola = @conversacion:saludo
Hola = @extractor:hola
 
Que bueno verte de nuevo por aquí , ¿Como estas?
Preocupado!
Irrelevant
Preocupado = @verbo:preocupar
Preocupado = @modo_tiempo:participio
 
¿en que te puedo colaborar?
Quiero cambiar mi cita
#agendar_cita
Quiero = @persona:yo
Quiero = @verbo:querer
Quiero = @modo_tiempo:indicativo presente
cambiar = @modo_tiempo:infinitivo
cambiar = @verbo:cambiar
mi = @pronombres:mí
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
 
¿Qué tipo de cita deseas agendar ? </br> </br>1. Medicina general, </br>2. Odontología Básica.
1
#decisión
1 = @sys-number:1
 
¿La cita médica es para ti o es para alguien más?
Mia
#decisión
 
En ese caso podemos usar tus preferencias guardadas para agilizar el proceso. --- Intercambiando datos con servidor --- </br></br>
 
--- Intercambiando datos con servidor --- </br></br>
 
tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. 15 de julio de 2018 a las 10:20 am en CM SUBA

 
[Multi-option response]
Title: 2. 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR

 
[Multi-option response]
Title: 3. 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
Description (optional): Elige diciendo: " la primera, la segunda o la tercera, o mencionadola por la fecha y hora directamente si gustas. tambien puedes intentar diciendo la del proximo viernes. usa tu creatividad! "

 
¿Cuál es tu elección?


---

07/08/2020 @
12:58
PM
3
Intents
12:58
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Buenas tardes.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
Pedrito
Irrelevant
 
Tu nombre es Pedrito, ¿es correcto?
Si
#aceptar
Si = @decisión:sí
 
¿Qué puedo hacer por ti el día de hoy Pedrito?
No lo se
#emergencia
No = @decisión:no
No lo se = @opción:indeterminado
lo = @pronombres:lo
se = @pronombres:se
 
¿Qué te trae por aquí entonces?


---

07/08/2020 @
1:19
PM
2
Intents
13:19
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Buenas tardes.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
Sebastián
#cambiar_usuario
Sebastián = @nombre:Sebastián
 
 
Cuéntame Sebastián, ¿qué se te ofrece?
Información de citas
 
Para comenzar indícanos tu número y tipo de documento


---

07/08/2020 @
2:49
PM
3
Intents
14:49
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Buenas tardes.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
Claudia
#cambiar_usuario
Claudia = @nombre:Claudia
 
 
Cuéntame Claudia, ¿qué se te ofrece?
Necesito una cita
#agendar_cita
Necesito = @persona:yo
Necesito = @verbo:necesitar
Necesito = @modo_tiempo:indicativo presente
una = @sys-number:1
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
 
Cuéntame Claudia, ¿qué tipo de cita se te ofrece? </br> </br>1. Medicina general, </br>2. Odontología Básica.
1
#decisión
1 = @sys-number:1
 
¿La cita médica es para ti o es para alguien más?
Para mi
#cambiar_usuario
Para = @persona:tú
Para = @preposición:para
Para = @modo_tiempo:imperativo
Para = @persona:él
Para = @persona:ella
Para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
 
Siendo así podemos saltarnos un par de pasos y agilizar la búsqueda. --- Intercambiando datos con servidor --- </br></br>
 
--- Intercambiando datos con servidor --- </br></br>
 
Claudia tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. 15 de julio de 2018 a las 10:20 am en CM SUBA

 
[Multi-option response]
Title: 2. 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR

 
[Multi-option response]
Title: 3. 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
Description (optional): Elige diciendo: " la primera, la segunda o la tercera, o mencionadola por la fecha y hora directamente si gustas. tambien puedes intentar diciendo la del proximo viernes. usa tu creatividad! "

 
Elije una antes que alguien más la reserve


---

07/08/2020 @
2:50
PM
2
Intents
14:50
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas tardes.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
Claudia
#cambiar_usuario
Claudia = @nombre:Claudia
 
 
¿Como podemos ayudarte Claudia?
Para una cita
 
Cuéntame Claudia, ¿qué tipo de cita se te ofrece? </br> </br>1. Medicina general, </br>2. Odontología Básica.


---

07/08/2020 @
3:15
PM
1
Intents
15:15
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas tardes.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
Maria
#cambiar_usuario
Maria = @nombre:María
 
 
¿Como podemos ayudarte María?


---

07/08/2020 @
3:17
PM
1
Intents
15:17
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas tardes.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
Me llamo aristoteles campo
#cambiar_usuario
Me = @pronombres:me
Me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
campo = @persona:yo
campo = @verbo:campar
campo = @modo_tiempo:indicativo presente
 
No soy muy bueno con los nombres, por eso prefiero asegurarme antes de empezar. </br></br>¿Te llamás E llamo aristoteles campo?


---

07/08/2020 @
3:18
PM
1
Intents
15:18
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buena tarde.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
Me llamo joselito
#cambiar_usuario
Me = @pronombres:me
Me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
 
Antes de comenzar permiteme confirmar si he entendido bien tu nombre </br></br>¿Tú nombre es E llamo joselito?
15:18

---


07/08/2020 @
3:18
PM
1
Intents
15:18
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buena tarde.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
Mi nombre es joselito
#cambiar_usuario
Mi = @pronombres:mí
Mi nombre es = @extractor:mi nombre es
nombre = @persona:yo
nombre = @modo_tiempo:imperativo
nombre = @persona:él
nombre = @persona:ella
nombre = @modo_tiempo:subjuntivo presente
nombre = @opción:nombre
nombre = @verbo:nombrar
es = @persona:él
es = @persona:ella
es = @verbo:ser
 
No soy muy bueno con los nombres, por eso prefiero asegurarme antes de empezar. </br></br>¿Te llamás I nombre es joselito?
15:18

---

07/08/2020 @
3:26
PM
1
Intents
15:26
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Buenas tardes.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
me llamo cumbia
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
cumbia = @persona:tú
cumbia = @persona:ella
cumbia = @persona:él
 
Antes de comenzar permiteme confirmar si he entendido bien tu nombre </br></br>¿Tú nombre es Cumbia?


---

07/08/2020 @
3:31
PM
1
Intents
15:31
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Buenas tardes.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
Hola
#conversacion
Hola = @conversacion:saludo
Hola = @extractor:hola
 
Hola ¿Qué tal ? ¿como te encuentras hoy?


---


07/08/2020 @
3:37
PM
4
Intents
15:37
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Buenas tardes.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
joselito
Irrelevant
 
Tu nombre es Joselito, ¿es correcto?
si
#aceptar
si = @decisión:sí
 
¿Cuál es el motivo de tú visita el día de hoy Joselito?
necesito agendar una cita medica
#agendar_cita
necesito = @persona:yo
necesito = @verbo:necesitar
necesito = @modo_tiempo:indicativo presente
una = @sys-number:1
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
cita medica = @opción:médica
cita medica = @tramite:Salud
medica = @dato:tipo_de_cita
medica = @especialidad:médica
 
¿La cita médica es para ti o es para alguien más?
para mi tia
#cambiar_usuario
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
mi tia = @temática:tio
tia = @otra_persona:tío
tia = @genero:femenino
 
Por favor indicame el número de documento de tu tia


---

07/08/2020 @
3:37
PM
4
Intents
15:37
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Buenas tardes.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
joselito
Irrelevant
 
Tu nombre es Joselito, ¿es correcto?
si
#aceptar
si = @decisión:sí
 
¿Cuál es el motivo de tú visita el día de hoy Joselito?
necesito agendar una cita medica
#agendar_cita
necesito = @persona:yo
necesito = @verbo:necesitar
necesito = @modo_tiempo:indicativo presente
una = @sys-number:1
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
cita medica = @opción:médica
cita medica = @tramite:Salud
medica = @dato:tipo_de_cita
medica = @especialidad:médica
 
¿La cita médica es para ti o es para alguien más?
para mi tia
#cambiar_usuario
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
mi tia = @temática:tio
tia = @otra_persona:tío
tia = @genero:femenino
 
Por favor indicame el número de documento de tu tia

---

07/08/2020 @
4:11
PM
1
Intents
16:11
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas tardes.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
Me llamo cumbia
#cambiar_usuario
Me = @pronombres:me
Me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
cumbia = @persona:tú
cumbia = @persona:ella
cumbia = @persona:él
 
No soy muy bueno con los nombres, por eso prefiero asegurarme antes de empezar. </br></br>¿Te llamás E llamo cumbia?


---

07/08/2020 @
4:11
PM
6
Intents
16:11
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Buenas tardes.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
Me llamo hugo
#cambiar_usuario
Me = @pronombres:me
Me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
hugo = @nombre:Hugo
 
 
¿Cuál es el motivo de tú visita el día de hoy Hugo?
Deseo afendar una cita medica
#agendar_cita
Deseo = @verbo:desear
Deseo = @persona:yo
Deseo = @modo_tiempo:indicativo presente
una = @sys-number:1
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
cita medica = @opción:médica
cita medica = @tramite:Salud
medica = @dato:tipo_de_cita
medica = @especialidad:médica
 
¿La cita médica es para ti o es para alguien más?
Es para mi tia
#cambiar_usuario
Es = @persona:él
Es = @persona:ella
Es = @verbo:ser
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
mi tia = @temática:tio
tia = @otra_persona:tío
tia = @genero:femenino
 
Por favor indicame el número de documento de tu tia
Su ceduka es 1234456799
#corregir
ceduka = @tipo_documento:CC
ceduka = @dato:numero_documento
es = @persona:ella
es = @persona:él
es = @verbo:ser
123445 = @input_patterns:PEP
1234456799 = @input_patterns:CC
1234456799 = @sys-number:1234456799
 
--- Intercambiando datos con servidor --- </br></br>
 
Hugo tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. 15 de julio de 2018 a las 10:20 am en CM SUBA

 
[Multi-option response]
Title: 2. 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR

 
[Multi-option response]
Title: 3. 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
Description (optional): Elige diciendo: " la primera, la segunda o la tercera, o mencionadola por la fecha y hora directamente si gustas. tambien puedes intentar diciendo la del proximo viernes. usa tu creatividad! "

 
¿Te sirve alguna de las anteriores o quieres probar diciéndome una fecha y hora?
La quiero para el viernes a las 3 pm
#emergencia
La = @pronombres:la
La quiero = @conversacion:amor
quiero = @persona:yo
quiero = @verbo:querer
quiero = @modo_tiempo:indicativo presente
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
el = @preposición:la del
el = @pronombres:el
el viernes = @sys-date:2020-08-14
a = @preposición:a
a las 3 pm = @sys-time:15:00:00
las = @pronombres:las
pm = @turno:T
 
Hugo procederemos a consultar disponbilidad con el documento CC 1234456799 para la cita médica, el dia 2020-08-14 a las 15:00:00 </br></br>
 
¿Esta bien?
Ok
#aceptar
Ok = @decisión:sí
 
{"id":"fd4609b30179d8e8b571a0e3ba49c2ab","ok":true,"rev":"1-f21893329c15ebc48ddb1f3f2b2142e8"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?
Gracias
#conversacion
Gracias = @conversacion:agradecimiento
Gracias = @conversacion:cortesia
 
¿Podemos hacer algo más por ti?
Deseo crear una cita odontologixa
#agendar_cita
Deseo = @verbo:desear
Deseo = @modo_tiempo:indicativo presente
Deseo = @persona:yo
crear = @modo_tiempo:infinitivo
crear = @verbo:crear
una = @sys-number:1
cita = @persona:tú
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
cita = @modo_tiempo:imperativo
cita odontologixa = @opción:odontológica
odontologixa = @especialidad:odontológica
odontologixa = @dato:tipo_de_cita
 
¿La cita médica es para ti o es para alguien más?
Es para mi
#cambiar_usuario
Es = @persona:él
Es = @persona:ella
Es = @verbo:ser
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
 
Procediendo a buscar disponibilidad utilizando tus preferencias guardadas. --- Intercambiando datos con servidor --- </br></br>
 
--- Intercambiando datos con servidor --- </br></br>
 
Hugo tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. 15 de julio de 2018 a las 10:20 am en CM SUBA

 
[Multi-option response]
Title: 2. 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR

 
[Multi-option response]
Title: 3. 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
Description (optional): Elige diciendo: " la primera, la segunda o la tercera, o mencionadola por la fecha y hora directamente si gustas. tambien puedes intentar diciendo la del proximo viernes. usa tu creatividad! "

 
Elije una antes que alguien más la reserve
.
#corregir
 
¿Que deseas corregir?


---

07/08/2020 @
4:28
PM
5
Intents
16:28
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Buena tarde.</div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
Luis
#cambiar_usuario
Luis = @nombre:Luis
 
 
¿En qué te puedo ayudar Luis?
Me duele el diente incisivo
#emergencia
Me = @pronombres:me
duele = @modo_tiempo:imperativo
duele = @persona:él
duele = @persona:tú
duele = @persona:ella
duele = @verbo:doler
duele = @modo_tiempo:indicativo presente
el = @preposición:la del
el = @pronombres:el
diente = @persona:yo
diente = @persona:ella
diente = @persona:tú
diente = @especialidad:odontológica
diente = @persona:él
 
En Watson salud nos gusta ayudarte,</br> Por favor selecciona una de las siguientes opciones: </br></br> 1. Asignar</br> 2. Consultar</br> 3. Reprogramar</br> 4. Eliminar</br>
1
#decisión
1 = @sys-number:1
Asignar
#agendar_cita
1. Asignar
#agendar_cita
1 = @sys-number:1
2
#decisión
2 = @sys-number:2
Consultar
#consultar_cita


---

07/08/2020 @
5:23
PM
5
Intents
17:23
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas tardes.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Para comenzar dime tu nombre por favor
luis
#cambiar_usuario
luis = @nombre:Luis
 
 
Cuéntame Luis, ¿qué se te ofrece?
me duele un incisivo
#emergencia
me = @pronombres:me
duele = @persona:ella
duele = @persona:tú
duele = @modo_tiempo:imperativo
duele = @persona:él
duele = @verbo:doler
duele = @modo_tiempo:indicativo presente
 
Antes de continuar trataremos de evaluar la gravedad de tu emergencia. </br> </br> Descríbeme con el mayor detalle posible tus síntomas. </br>
 
[Image response]
URL: 
https://i.imgur.com/QeQjWkAl.jpg

 
</br>Si lo que deseas es agendar una cita normal puedes decírmelo con confianza para ayudarte con eso.
 
<iframe src="https://www.google.com/maps/embed?pb=!1m16!1m12!1m3!1d254507.63598012045!2d-74.11138866785275!3d4.650720841237783!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!2m1!1scentro+medico+colsubsidio!5e0!3m2!1ses!2sco!4v1531303135509" width="280" height="260" frameborder="0" style="border:0" allowfullscreen></iframe></br></br>por favor selecciona la zona:</br></br>Occidente</br>Norte</br>Sur</br>Centro</br>Clinicas</br>Especialistas</br>Cundinamarca</br>Boyaca</br>Preferencial</br>
occidente
Irrelevant
occidente = @zona:Occidente
 
<iframe src="https://www.google.com/maps/embed?pb=!1m16!1m12!1m3!1d254507.63598012045!2d-74.11138866785275!3d4.650720841237783!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!2m1!1scentro+medico+colsubsidio!5e0!3m2!1ses!2sco!4v1531303135509" width="280" height="260" frameborder="0" style="border:0" allowfullscreen></iframe></br></br>por favor selecciona la zona:</br></br>Occidente</br>Norte</br>Sur</br>Centro</br>Clinicas</br>Especialistas</br>Cundinamarca</br>Boyaca</br>Preferencial</br>
sur
#corregir
sur = @zona:Sur
 
CM CHICALA: Carrera 85 C # 53 - 21 sur</br>Bogotá, D.C.</br></br>
 
CM IPANEMA: Calle 26 sur N. 93D-12, Tierra Buena</br>Bogotá, D.C.</br></br>
 
PLAZA CENTRAL: CENTRO COMERCIAL Carrera 65 # 11 - 50 piso 2local 2-41</br>Bogotá, D.C.</br></br>
 
CM AV 1 MAYO: Avenida 1 de mayo # 42 C – 10 sur</br>Bogotá, D.C.</br></br>
 
CM PORVENIR: Calle 54 F SUR 93C 21 . Centro Comercial MI CENTRO.  Barrio Bosa Porvenir</br>Bogotá, D.C.</br></br>
 
Puedes indicarme otra zona si deseas ver mas centros medicos.
volver a empezar
#denegar
volver = @verbo:volver
volver = @modo_tiempo:infinitivo
volver a = @persona:ella
volver a = @persona:yo
volver a = @persona:él
a = @preposición:a
empezar = @modo_tiempo:infinitivo
empezar = @verbo:comenzar
 
<iframe src="https://www.google.com/maps/embed?pb=!1m16!1m12!1m3!1d254507.63598012045!2d-74.11138866785275!3d4.650720841237783!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!2m1!1scentro+medico+colsubsidio!5e0!3m2!1ses!2sco!4v1531303135509" width="280" height="260" frameborder="0" style="border:0" allowfullscreen></iframe></br></br>por favor selecciona la zona:</br></br>Occidente</br>Norte</br>Sur</br>Centro</br>Clinicas</br>Especialistas</br>Cundinamarca</br>Boyaca</br>Preferencial</br>
17:25

---

07/08/2020 @
9:05
PM
6
Intents
21:05
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas noches.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
me llamo padrino
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
 
Antes de comenzar permiteme confirmar si he entendido bien tu nombre </br></br>¿Tú nombre es Padrino?
seh
#aceptar
 
¿En qué te puedo ayudar Padrino?
consultar
#consultar_cita
 
Para comenzar indícanos tu número y tipo de documento
cc 2132342354
#corregir
cc = @tipo_documento:CC
213234 = @input_patterns:PEP
2132342354 = @input_patterns:CC
2132342354 = @sys-number:2132342354
 
--- Intercambiando datos con servidor --- </br></br>
 
Padrino, estas son las citas agendadas actualmente con el documento CC 2132342354</br></br>
 
 
2. 19 de julio de 2018 a las 10:00 am en CM DUITAMA</br></br>
 
3. 6 de julio de 2018 a las 10:00 am en CM DUITAMA</br></br>
 
4. 19 de julio de 2018 a las 3:00 pm en CL INFANTIL</br></br>
 
5. 19 de julio de 2018 a las 6:30 am en CM SUBA</br></br>
 
Puedo mostrarte tus citas agendadas de cinco en cinco. En total actualmente tienes 13 citas agendadas. Estamos en la pagina 1 de un total de 3.</br></br> Puedes pedirme que avance o retroceda una pagina para ver las demas citas agendadas.</br></br>
 
¿Deseas hacer algo mas?
siguiente
#conversacion
siguiente = @opción:avanzar
 
--- Intercambiando datos con servidor --- </br></br>
 
Padrino, estas son las citas agendadas actualmente con el documento CC 2132342354</br></br>
 
1. 6 de julio de 2018 a las 7:30 am en CM DUITAMA</br></br>
 
2. 19 de julio de 2018 a las 10:00 am en CM DUITAMA</br></br>
 
3. 6 de julio de 2018 a las 10:00 am en CM DUITAMA</br></br>
 
4. 19 de julio de 2018 a las 3:00 pm en CL INFANTIL</br></br>
 
5. 19 de julio de 2018 a las 6:30 am en CM SUBA</br></br>
 
Puedo mostrarte tus citas agendadas de cinco en cinco. En total actualmente tienes 13 citas agendadas. Estamos en la pagina 2 de un total de 3.</br></br> Puedes pedirme que avance o retroceda una pagina para ver las demas citas agendadas.</br></br>
 
¿Deseas hacer algo mas?
vovler
Irrelevant
 
¿Cual es tu elección?
regresar
Irrelevant
regresar = @verbo:regresar
regresar = @modo_tiempo:infinitivo
 
¿Cual es tu elección?


---

07/08/2020 @
5:23
PM
5
Intents
17:23
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas tardes.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Para comenzar dime tu nombre por favor
luis
#cambiar_usuario
luis = @nombre:Luis
 
 
Cuéntame Luis, ¿qué se te ofrece?
me duele un incisivo
#emergencia
me = @pronombres:me
duele = @persona:ella
duele = @persona:tú
duele = @modo_tiempo:imperativo
duele = @persona:él
duele = @verbo:doler
duele = @modo_tiempo:indicativo presente
 
Antes de continuar trataremos de evaluar la gravedad de tu emergencia. </br> </br> Descríbeme con el mayor detalle posible tus síntomas. </br>
 
[Image response]
URL: 
https://i.imgur.com/QeQjWkAl.jpg

 
</br>Si lo que deseas es agendar una cita normal puedes decírmelo con confianza para ayudarte con eso.
 
<iframe src="https://www.google.com/maps/embed?pb=!1m16!1m12!1m3!1d254507.63598012045!2d-74.11138866785275!3d4.650720841237783!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!2m1!1scentro+medico+colsubsidio!5e0!3m2!1ses!2sco!4v1531303135509" width="280" height="260" frameborder="0" style="border:0" allowfullscreen></iframe></br></br>por favor selecciona la zona:</br></br>Occidente</br>Norte</br>Sur</br>Centro</br>Clinicas</br>Especialistas</br>Cundinamarca</br>Boyaca</br>Preferencial</br>
occidente
Irrelevant
occidente = @zona:Occidente
 
<iframe src="https://www.google.com/maps/embed?pb=!1m16!1m12!1m3!1d254507.63598012045!2d-74.11138866785275!3d4.650720841237783!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!2m1!1scentro+medico+colsubsidio!5e0!3m2!1ses!2sco!4v1531303135509" width="280" height="260" frameborder="0" style="border:0" allowfullscreen></iframe></br></br>por favor selecciona la zona:</br></br>Occidente</br>Norte</br>Sur</br>Centro</br>Clinicas</br>Especialistas</br>Cundinamarca</br>Boyaca</br>Preferencial</br>
sur
#corregir
sur = @zona:Sur
 
CM CHICALA: Carrera 85 C # 53 - 21 sur</br>Bogotá, D.C.</br></br>
 
CM IPANEMA: Calle 26 sur N. 93D-12, Tierra Buena</br>Bogotá, D.C.</br></br>
 
PLAZA CENTRAL: CENTRO COMERCIAL Carrera 65 # 11 - 50 piso 2local 2-41</br>Bogotá, D.C.</br></br>
 
CM AV 1 MAYO: Avenida 1 de mayo # 42 C – 10 sur</br>Bogotá, D.C.</br></br>
 
CM PORVENIR: Calle 54 F SUR 93C 21 . Centro Comercial MI CENTRO.  Barrio Bosa Porvenir</br>Bogotá, D.C.</br></br>
 
Puedes indicarme otra zona si deseas ver mas centros medicos.
volver a empezar
#denegar
volver = @verbo:volver
volver = @modo_tiempo:infinitivo
volver a = @persona:ella
volver a = @persona:yo
volver a = @persona:él
a = @preposición:a
empezar = @modo_tiempo:infinitivo
empezar = @verbo:comenzar
 
<iframe src="https://www.google.com/maps/embed?pb=!1m16!1m12!1m3!1d254507.63598012045!2d-74.11138866785275!3d4.650720841237783!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!2m1!1scentro+medico+colsubsidio!5e0!3m2!1ses!2sco!4v1531303135509" width="280" height="260" frameborder="0" style="border:0" allowfullscreen></iframe></br></br>por favor selecciona la zona:</br></br>Occidente</br>Norte</br>Sur</br>Centro</br>Clinicas</br>Especialistas</br>Cundinamarca</br>Boyaca</br>Preferencial</br>


---

07/08/2020 @
9:57
PM
3
Intents
21:57
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buena noche.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
me llamo daniel
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
daniel = @nombre:Daniel
 
 
¿En qué te puedo ayudar Daniel?
deseo consultar mis citas
#consultar_cita
deseo = @verbo:desear
deseo = @persona:yo
deseo = @modo_tiempo:indicativo presente
citas = @persona:tú
citas = @verbo:citar
citas = @modo_tiempo:indicativo presente
 
Para comenzar indícanos tu número y tipo de documento
cc 435354345
#corregir
cc = @tipo_documento:CC
435354 = @input_patterns:PEP
435354345 = @sys-number:435354345
 
 
Daniel, estas son las citas agendadas actualmente con el documento CC 435354345</br></br>
 
 
2. 19 de julio de 2018 a las 10:00 am en CM DUITAMA</br></br>
 
3. 6 de julio de 2018 a las 10:00 am en CM DUITAMA</br></br>
 
4. 19 de julio de 2018 a las 3:00 pm en CL INFANTIL</br></br>
 
5. 19 de julio de 2018 a las 6:30 am en CM SUBA</br></br>
 
Puedo mostrarte tus citas agendadas de cinco en cinco. En total actualmente tienes 13 citas agendadas. Estamos en la pagina 1 de un total de 3.</br></br> Puedes pedirme que avance o retroceda una pagina para ver las demas citas agendadas.</br></br>
 
¿Deseas hacer algo mas?


---

07/08/2020 @
10:09
PM
5
Intents
22:09
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Buenas noches.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
jose
#cambiar_usuario
jose = @nombre:José
 
 
¿Como podemos ayudarte José?
consultar
#consultar_cita
 
Para comenzar indícanos tu número y tipo de documento
cc 345345345
#corregir
cc = @tipo_documento:CC
345345 = @input_patterns:PEP
345345345 = @sys-number:345345345
 
 
José he encontrado 13 citas agendadas con el documento CC 345345345</br></br>
 
[Multi-option response]
Title: 1. 6 de julio de 2018 a las 7:30 am en CM DUITAMA

 
[Multi-option response]
Title: 2. 19 de julio de 2018 a las 10:00 am en CM DUITAMA

 
[Multi-option response]
Title: 3. 6 de julio de 2018 a las 10:00 am en CM DUITAMA

 
[Multi-option response]
Title: 4. 19 de julio de 2018 a las 3:00 pm en CL INFANTIL

 
[Multi-option response]
Title: 5. 19 de julio de 2018 a las 6:30 am en CM SUBA

 
[Multi-option response]
Title: Página 1 de 3

Avanzar: avanzar
Retroceder: reroceder
Salir: salir
 
¿Deseas hacer algo mas?
reroceder
#control_bot
reroceder = @opción:retroceder
 
José he encontrado 13 citas agendadas con el documento CC 345345345</br></br>
 
[Multi-option response]
Title: 1. 6 de julio de 2018 a las 7:30 am en CM DUITAMA

 
[Multi-option response]
Title: 2. 19 de julio de 2018 a las 10:00 am en CM DUITAMA

 
[Multi-option response]
Title: 3. 6 de julio de 2018 a las 10:00 am en CM DUITAMA

 
[Multi-option response]
Title: 4. 19 de julio de 2018 a las 3:00 pm en CL INFANTIL

 
[Multi-option response]
Title: 5. 19 de julio de 2018 a las 6:30 am en CM SUBA

 
[Multi-option response]
Title: Página 0 de 3

Avanzar: avanzar
Retroceder: reroceder
Salir: salir
 
¿Deseas hacer algo mas?
avanzar
#control_bot
avanzar = @opción:avanzar
 
 
José he encontrado 13 citas agendadas con el documento CC 345345345</br></br>
 
[Multi-option response]
Title: 1. 6 de julio de 2018 a las 7:30 am en CM DUITAMA

 
[Multi-option response]
Title: 2. 19 de julio de 2018 a las 10:00 am en CM DUITAMA

 
[Multi-option response]
Title: 3. 6 de julio de 2018 a las 10:00 am en CM DUITAMA

 
[Multi-option response]
Title: 4. 19 de julio de 2018 a las 3:00 pm en CL INFANTIL

 
[Multi-option response]
Title: 5. 19 de julio de 2018 a las 6:30 am en CM SUBA

 
[Multi-option response]
Title: Página 1 de 3

Avanzar: avanzar
Retroceder: reroceder
Salir: salir
 
¿Deseas hacer algo mas?
salir
Irrelevant
salir = @verbo:salir
salir = @modo_tiempo:infinitivo
 
¿Cual es tu elección?


---

07/08/2020 @
10:16
PM
2
Intents
22:16
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Buenas noches.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
jose
#cambiar_usuario
jose = @nombre:José
 
 
¿Cuál es el motivo de tú visita el día de hoy José?
agendar cita medica
#control_bot
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
cita medica = @opción:médica
cita medica = @tramite:Salud
medica = @dato:tipo_de_cita
medica = @especialidad:médica
 
En Watson salud nos gusta ayudarte,</br> Por favor selecciona una de las siguientes opciones: </br></br> 1. Asignar</br> 2. Consultar</br> 3. Reprogramar</br> 4. Eliminar</br>


---

07/08/2020 @
10:16
PM
2
Intents
22:16
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buena noche.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
manuel
#cambiar_usuario
manuel = @nombre:Manuel
 
 
¿Qué puedo hacer por ti el día de hoy Manuel?
agendar cita medica
 
En Watson salud nos gusta ayudarte,</br> Por favor selecciona una de las siguientes opciones: </br></br> 1. Asignar</br> 2. Consultar</br> 3. Reprogramar</br> 4. Eliminar</br>


---

07/08/2020 @
10:21
PM
5
Intents
22:21
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas noches.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
nadando
 
Tu nombre es Nadando, ¿es correcto?
si
#aceptar
si = @decisión:sí
 
¿Cuál es el motivo de tú visita el día de hoy Nadando?
agendar cita
#agendar_cita
cita = @persona:ella
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
 
¿Qué tipo de cita deseas agendar Nadando? </br> </br>1. Medicina general, </br>2. Odontología Básica.
1
#decisión
1 = @sys-number:1
 
¿La cita médica es para ti o es para alguien más?
para mi
#cambiar_usuario
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
 
Dado que es para ti, procederemos a consultar tus preferencias habituales para facilitarte el proceso.
 
 
Nadando tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. 15 de julio de 2018 a las 10:20 am en CM SUBA

15 de julio de 2018 a las 10:20 am en CM SUBA: 15 de julio de 2018 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR

 
[Multi-option response]
Title: 3. 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
Description (optional): Elige diciendo: " la primera, la segunda o la tercera, o mencionadola por la fecha y hora directamente si gustas. tambien puedes intentar diciendo la del proximo viernes. usa tu creatividad! "

 
Elije una antes que alguien más la reserve


---

07/08/2020 @
10:22
PM
3
Intents
22:22
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Buenas noches.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
hugo
#cambiar_usuario
hugo = @nombre:Hugo
 
 
¿Cuál es el motivo de tú visita el día de hoy Hugo?
deseo agendar una cita medica
#agendar_cita
deseo = @verbo:desear
deseo = @persona:yo
deseo = @modo_tiempo:indicativo presente
una = @sys-number:1
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
cita medica = @opción:médica
cita medica = @tramite:Salud
medica = @dato:tipo_de_cita
medica = @especialidad:médica
 
¿La cita médica es para ti o es para alguien más?
para mi
#cambiar_usuario
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
 
Siendo así podemos saltarnos un par de pasos y agilizar la búsqueda.
 
 
Hugo tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1

15 de julio de 2018 a las 10:20 am en CM SUBA: 15 de julio de 2018 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR

 
[Multi-option response]
Title: 3. 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
Description (optional): Elige diciendo: " la primera, la segunda o la tercera, o mencionadola por la fecha y hora directamente si gustas. tambien puedes intentar diciendo la del proximo viernes. usa tu creatividad! "

 
¿Alguna de estas opciones te sirve?
15 de julio de 2018 a las 10:20 am en CM SUBA
Irrelevant
15 de julio de 2018 = @sys-date:2018-07-15
de = @persona:ella
de = @persona:él
de = @preposición:de
de = @verbo:dar
julio = @nombre:Julio
de = @persona:ella
de = @persona:él
de = @preposición:de
de = @verbo:dar
a = @preposición:a
a las 10:20 am = @sys-time:10:20:00
las = @pronombres:las
am = @turno:M
am en = @persona:ellos
en = @preposición:en
CM SUBA = @centro_médico:CM SUBA
 
Hugo procederemos a consultar disponbilidad con el documento CC 31234567890 para la cita médica, el dia 2018-07-15 a las 10:20:00 </br></br>
 
¿Esta bien?


---

07/08/2020 @
10:24
PM
3
Intents
22:24
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buena noche.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
hugo
#cambiar_usuario
hugo = @nombre:Hugo
 
 
¿Como podemos ayudarte Hugo?
deseo agendar una cita medica
#agendar_cita
deseo = @verbo:desear
deseo = @persona:yo
deseo = @modo_tiempo:indicativo presente
una = @sys-number:1
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
cita medica = @opción:médica
cita medica = @tramite:Salud
medica = @dato:tipo_de_cita
medica = @especialidad:médica
 
¿La cita médica es para ti o es para alguien más?
si
#aceptar
si = @decisión:sí
 
Procediendo a buscar disponibilidad utilizando tus preferencias guardadas.
 
 
Hugo tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]

15 de julio de 2018 a las 10:20 am en CM SUBA: 15 de julio de 2018 a las 10:20 am en CM SUBA
 
[Multi-option response]

15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR: 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]

26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE: 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
 
¿Te sirve alguna de las anteriores o quieres probar diciéndome una fecha y hora?


---

07/08/2020 @
10:29
PM
3
Intents
22:29
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Buena noche.</div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
sigilfredo
Irrelevant
 
Tu nombre es Sigilfredo, ¿es correcto?
si
#aceptar
si = @decisión:sí
 
¿En qué te puedo ayudar Sigilfredo?
agendar cita
#agendar_cita
cita = @persona:ella
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
 
¿Qué tipo de cita deseas agendar Sigilfredo? </br> </br>1. Medicina general, </br>2. Odontología Básica.


---

07/08/2020 @
10:33
PM
3
Intents
22:33
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buena noche.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
hug
Irrelevant
 
Tu nombre es Hug, ¿es correcto?
si
#aceptar
si = @decisión:sí
 
¿Cuál es el motivo de tú visita el día de hoy Hug?
agendar cita
#agendar_cita
cita = @persona:ella
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
 
Cuéntame Hug, ¿qué tipo de cita se te ofrece?
 
[Multi-option response]
Title: Opciones disponibles
Description (optional): Opciones disponibles

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
Medicina General
#agendar_cita
Medicina = @especialidad:médica
Medicina = @temática:ciencias naturales
Medicina General = @opción:médica
 
¿La cita médica es para ti o es para alguien más?


---

07/08/2020 @
10:34
PM
2
Intents
22:34
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Buena noche.</div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
hugo
#cambiar_usuario
hugo = @nombre:Hugo
 
 
¿Cuál es el motivo de tú visita el día de hoy Hugo?
agendar cita
#agendar_cita
cita = @persona:ella
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
 
¿Cuál clase de cita necesitas agendar hoy Hugo?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
Odontológia Básica
#agendar_cita
Odontológia = @opción:odontológica
Odontológia = @especialidad:odontológica


---

07/08/2020 @
10:37
PM
2
Intents
22:37
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Buenas noches.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
hugo
#cambiar_usuario
hugo = @nombre:Hugo
 
 
¿Como podemos ayudarte Hugo?
deseo agendar una cita
#agendar_cita
deseo = @verbo:desear
deseo = @persona:yo
deseo = @modo_tiempo:indicativo presente
una = @sys-number:1
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
 
¿Qué tipo de cita deseas agendar Hugo?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
Medicina General
#agendar_cita
Medicina = @especialidad:médica
Medicina = @temática:ciencias naturales
Medicina General = @opción:médica
 
¿La cita médica es para ti o es para alguien más?
para mi
#cambiar_usuario
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
 
 
Hugo tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]

15 de julio de 2018 a las 10:20 am en CM SUBA: 15 de julio de 2018 a las 10:20 am en CM SUBA
 
[Multi-option response]

15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR: 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]

26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE: 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
 
</br>Elije una antes que alguien más la reserve


---

07/08/2020 @
10:38
PM
2
Intents
22:38
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Buenas noches.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
jose
#cambiar_usuario
jose = @nombre:José
 
 
Cuéntame José, ¿qué se te ofrece?
agendar cita
#agendar_cita
cita = @persona:ella
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
 
¿Qué tipo de cita deseas agendar José?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
Odontológia Básica
#agendar_cita
Odontológia = @opción:odontológica
Odontológia = @especialidad:odontológica
 
¿La cita odontológica es para ti o es para alguien más?
para mi
#cambiar_usuario
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
 
 
José tenemos estas opciones disponibles para la cita odontológica que estas solicitando:</br></br>
 
[Multi-option response]

15 de julio de 2018 a las 10:20 am en CM SUBA: 15 de julio de 2018 a las 10:20 am en CM SUBA
 
[Multi-option response]

15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR: 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]

26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE: 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
 
</br>Elije una antes que alguien más la reserve


---

07/08/2020 @
10:41
PM
4
Intents
22:41
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas noches.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
hugo
#cambiar_usuario
hugo = @nombre:Hugo
 
 
Cuéntame Hugo, ¿qué se te ofrece?
agendar cita
#agendar_cita
cita = @persona:ella
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
 
Cuéntame Hugo, ¿qué tipo de cita se te ofrece?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
medician
#control_bot
medician = @especialidad:médica
medician = @opción:médica
 
¿La cita médica es para ti o es para alguien más?
para mi
#cambiar_usuario
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
 
 
Hugo tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: CM SUBA

15 de julio de 2018 a las 10:20 am: 15 de julio de 2018 a las 10:20 am
 
[Multi-option response]
Title: CM GRANAHORRAR

15 de julio de 2018 a las 4:00 pm : 15 de julio de 2018 a las 4:00 pm
 
[Multi-option response]
Title: CM PORTAL NORTE

26 de julio de 2018 a las 1:00 PM: 26 de julio de 2018 a las 1:00 PM
 
</br>¿Alguna de estas opciones te sirve?
15 de julio de 2018 a las 4:00 pm
#cambiar_turno
15 de julio de 2018 = @sys-date:2018-07-15
de = @persona:ella
de = @persona:él
de = @preposición:de
de = @verbo:dar
julio = @nombre:Julio
de = @persona:ella
de = @persona:él
de = @preposición:de
de = @verbo:dar
a = @preposición:a
a las 4:00 pm = @sys-time:16:00:00
las = @pronombres:las
4 = @opción:cuarta
pm = @turno:T
 
Hugo procederemos a consultar disponbilidad con el documento CC 31234567890 para la cita médica, el dia 2018-07-15 a las 16:00:00 </br></br>
 
¿Esta bien?


---

07/08/2020 @
10:46
PM
4
Intents
22:46
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas noches.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
hugo
#cambiar_usuario
hugo = @nombre:Hugo
 
 
¿Cuál es el motivo de tú visita el día de hoy Hugo?
agendar
#agendar_cita
 
Cuéntame Hugo, ¿qué tipo de cita se te ofrece?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
1
#decisión
1 = @sys-number:1
 
¿Qué tipo de cita deseas agendar Hugo?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
Medicina General
#agendar_cita
Medicina = @especialidad:médica
Medicina = @temática:ciencias naturales
Medicina General = @opción:médica
 
¿La cita médica es para ti o es para alguien más?
si
#aceptar
si = @decisión:sí
 
 
Hugo tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. CM SUBA

15 de julio de 2018 a las 10:20 am: 15 de julio de 2018 a las 10:20 am
 
[Multi-option response]
Title: 2. CM GRANAHORRAR

15 de julio de 2018 a las 4:00 pm : 15 de julio de 2018 a las 4:00 pm
 
[Multi-option response]
Title: 3. CM PORTAL NORTE

26 de julio de 2018 a las 1:00 PM: 26 de julio de 2018 a las 1:00 PM
 
</br>¿Te sirve alguna de las anteriores o quieres probar diciéndome una fecha y hora?


---

07/08/2020 @
10:50
PM
4
Intents
22:50
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas noches.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
me llamo hugo
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
hugo = @nombre:Hugo
 
 
¿Qué puedo hacer por ti el día de hoy Hugo?
agendar
#agendar_cita
 
¿Cuál clase de cita necesitas agendar hoy Hugo?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
Medicina General
#agendar_cita
Medicina = @especialidad:médica
Medicina = @temática:ciencias naturales
Medicina General = @opción:médica
 
¿La cita médica es para ti o es para alguien más?
para mi
#cambiar_usuario
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
 
 
Hugo tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

15 de julio de 2018 a las 10:20 am: 15 de julio de 2018 a las 10:20 am
 
[Multi-option response]
Title: 2. Opción segunda enCM GRANAHORRAR

15 de julio de 2018 a las 4:00 pm : 15 de julio de 2018 a las 4:00 pm
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

26 de julio de 2018 a las 1:00 PM: 26 de julio de 2018 a las 1:00 PM
 
</br>¿Cuál es tu elección?
26 de julio de 2018 a las 1:00 PM
#cambiar_turno
26 de julio de 2018 = @sys-date:2018-07-26
de = @persona:ella
de = @persona:él
de = @preposición:de
de = @verbo:dar
julio = @nombre:Julio
de = @persona:ella
de = @persona:él
de = @preposición:de
de = @verbo:dar
a = @preposición:a
a las 1:00 PM = @sys-time:13:00:00
las = @pronombres:las
PM = @turno:T
 
Hugo procederemos a consultar disponbilidad con el documento CC 31234567890 para la cita médica, el dia 2018-07-26 a las 13:00:00 </br></br>
 
¿Esta bien?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
{"id":"cfa97688cf33dda134ee10450fefed0b","ok":true,"rev":"1-8f24572288a4c1987a8371ef0851afe5"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?


---


07/08/2020 @
10:53
PM
2
Intents
22:53
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Buenas noches.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
hugo
#cambiar_usuario
hugo = @nombre:Hugo
 
 
¿En qué te puedo ayudar Hugo?
me duele un incisivo
#emergencia
me = @pronombres:me
duele = @persona:ella
duele = @persona:tú
duele = @modo_tiempo:imperativo
duele = @persona:él
duele = @verbo:doler
duele = @modo_tiempo:indicativo presente
 
[Image response]
URL: 
https://i.imgur.com/QeQjWkAl.jpg

 
Antes de continuar trataremos de evaluar la gravedad de tu emergencia. </br> </br> Descríbeme con el mayor detalle posible tus síntomas. </br>
 
<iframe src="https://www.google.com/maps/embed?pb=!1m16!1m12!1m3!1d254507.63598012045!2d-74.11138866785275!3d4.650720841237783!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!2m1!1scentro+medico+colsubsidio!5e0!3m2!1ses!2sco!4v1531303135509" width="280" height="260" frameborder="0" style="border:0" allowfullscreen></iframe>
 
</br>Si lo que deseas es agendar una cita normal puedes decírmelo con confianza para ayudarte con eso.


---

07/08/2020 @
10:55
PM
3
Intents
22:55
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas noches.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
jose
#cambiar_usuario
jose = @nombre:José
 
 
¿Como podemos ayudarte José?
me duele una muela
#emergencia
me = @pronombres:me
me duele una muela = @emergencia:triage5
duele = @modo_tiempo:imperativo
duele = @persona:él
duele = @persona:tú
duele = @persona:ella
duele = @verbo:doler
duele = @modo_tiempo:indicativo presente
una = @sys-number:1
muela = @especialidad:odontológica
muela = @persona:él
muela = @persona:yo
muela = @persona:ella
 
Antes de continuar trataremos de evaluar la gravedad de tu emergencia. </br> </br> Descríbeme con el mayor detalle posible tus síntomas. </br>
 
[Image response]
URL: 
https://i.imgur.com/QeQjWkAl.jpg

 
<iframe src="https://www.google.com/maps/embed?pb=!1m16!1m12!1m3!1d254507.63598012045!2d-74.11138866785275!3d4.650720841237783!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!2m1!1scentro+medico+colsubsidio!5e0!3m2!1ses!2sco!4v1531303135509" width="280" height="260" frameborder="0" style="border:0" allowfullscreen></iframe>
 
</br>Si lo que deseas es agendar una cita normal puedes decírmelo con confianza para ayudarte con eso.
ok
#aceptar
ok = @decisión:sí
 
<iframe src="https://www.google.com/maps/embed?pb=!1m16!1m12!1m3!1d254507.63598012045!2d-74.11138866785275!3d4.650720841237783!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!2m1!1scentro+medico+colsubsidio!5e0!3m2!1ses!2sco!4v1531303135509" width="280" height="260" frameborder="0" style="border:0" allowfullscreen></iframe>
 
</br>Si lo que deseas es agendar una cita normal puedes decírmelo con confianza para ayudarte con eso.


---

07/08/2020 @
10:55
PM
3
Intents
22:55
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas noches.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
jose
#cambiar_usuario
jose = @nombre:José
 
 
¿Como podemos ayudarte José?
me duele una muela
#emergencia
me = @pronombres:me
me duele una muela = @emergencia:triage5
duele = @modo_tiempo:imperativo
duele = @persona:él
duele = @persona:tú
duele = @persona:ella
duele = @verbo:doler
duele = @modo_tiempo:indicativo presente
una = @sys-number:1
muela = @especialidad:odontológica
muela = @persona:él
muela = @persona:yo
muela = @persona:ella
 
Antes de continuar trataremos de evaluar la gravedad de tu emergencia. </br> </br> Descríbeme con el mayor detalle posible tus síntomas. </br>
 
[Image response]
URL: 
https://i.imgur.com/QeQjWkAl.jpg

 
<iframe src="https://www.google.com/maps/embed?pb=!1m16!1m12!1m3!1d254507.63598012045!2d-74.11138866785275!3d4.650720841237783!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!2m1!1scentro+medico+colsubsidio!5e0!3m2!1ses!2sco!4v1531303135509" width="280" height="260" frameborder="0" style="border:0" allowfullscreen></iframe>
 
</br>Si lo que deseas es agendar una cita normal puedes decírmelo con confianza para ayudarte con eso.
ok
#aceptar
ok = @decisión:sí
 
<iframe src="https://www.google.com/maps/embed?pb=!1m16!1m12!1m3!1d254507.63598012045!2d-74.11138866785275!3d4.650720841237783!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!2m1!1scentro+medico+colsubsidio!5e0!3m2!1ses!2sco!4v1531303135509" width="280" height="260" frameborder="0" style="border:0" allowfullscreen></iframe>
 
</br>Si lo que deseas es agendar una cita normal puedes decírmelo con confianza para ayudarte con eso.


---

07/08/2020 @
10:58
PM
5
Intents
22:58
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Buena noche.</div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
me llamo jose
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
jose = @nombre:José
 
 
Cuéntame José, ¿qué se te ofrece?
agendar
#agendar_cita
 
Cuéntame José, ¿qué tipo de cita se te ofrece?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
Medicina General
#agendar_cita
Medicina = @especialidad:médica
Medicina = @temática:ciencias naturales
Medicina General = @opción:médica
 
¿La cita médica es para ti o es para alguien más?
para mi
#cambiar_usuario
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
 
 
José tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

15 de julio de 2018 a las 10:20 am: 15 de julio de 2018 a las 10:20 am
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

15 de julio de 2018 a las 4:00 pm : 15 de julio de 2018 a las 4:00 pm
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

26 de julio de 2018 a las 1:00 PM: 26 de julio de 2018 a las 1:00 PM
 
</br>Elije una antes que alguien más la reserve
15 de julio de 2018 a las 10:20 am
#cambiar_turno
15 de julio de 2018 = @sys-date:2018-07-15
de = @persona:ella
de = @persona:él
de = @preposición:de
de = @verbo:dar
julio = @nombre:Julio
de = @persona:ella
de = @persona:él
de = @preposición:de
de = @verbo:dar
a = @preposición:a
a las 10:20 am = @sys-time:10:20:00
las = @pronombres:las
am = @turno:M
 
José procederemos a consultar disponbilidad con el documento CC 31234567890 para la cita médica, el dia 2018-07-15 a las 10:20:00 </br></br>
 
¿Esta bien?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
{"id":"fd4609b30179d8e8b571a0e3bac0e7d6","ok":true,"rev":"1-ef0f347baebfd2edfeefbdb294705125"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?
me duele una muela
#emergencia
me = @pronombres:me
me duele una muela = @emergencia:triage5
duele = @modo_tiempo:imperativo
duele = @persona:él
duele = @persona:tú
duele = @persona:ella
duele = @verbo:doler
duele = @modo_tiempo:indicativo presente
una = @sys-number:1
muela = @especialidad:odontológica
muela = @persona:él
muela = @persona:yo
muela = @persona:ella
 
¿Podemos hacer algo más por ti?


---

07/08/2020 @
10:55
PM
3
Intents
22:55
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas noches.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
jose
#cambiar_usuario
jose = @nombre:José
 
 
¿Como podemos ayudarte José?
me duele una muela
#emergencia
me = @pronombres:me
me duele una muela = @emergencia:triage5
duele = @modo_tiempo:imperativo
duele = @persona:él
duele = @persona:tú
duele = @persona:ella
duele = @verbo:doler
duele = @modo_tiempo:indicativo presente
una = @sys-number:1
muela = @especialidad:odontológica
muela = @persona:él
muela = @persona:yo
muela = @persona:ella
 
Antes de continuar trataremos de evaluar la gravedad de tu emergencia. </br> </br> Descríbeme con el mayor detalle posible tus síntomas. </br>
 
[Image response]
URL: 
https://i.imgur.com/QeQjWkAl.jpg

 
<iframe src="https://www.google.com/maps/embed?pb=!1m16!1m12!1m3!1d254507.63598012045!2d-74.11138866785275!3d4.650720841237783!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!2m1!1scentro+medico+colsubsidio!5e0!3m2!1ses!2sco!4v1531303135509" width="280" height="260" frameborder="0" style="border:0" allowfullscreen></iframe>
 
</br>Si lo que deseas es agendar una cita normal puedes decírmelo con confianza para ayudarte con eso.
ok
#aceptar
ok = @decisión:sí
 
<iframe src="https://www.google.com/maps/embed?pb=!1m16!1m12!1m3!1d254507.63598012045!2d-74.11138866785275!3d4.650720841237783!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!2m1!1scentro+medico+colsubsidio!5e0!3m2!1ses!2sco!4v1531303135509" width="280" height="260" frameborder="0" style="border:0" allowfullscreen></iframe>
 
</br>Si lo que deseas es agendar una cita normal puedes decírmelo con confianza para ayudarte con eso.


---

07/08/2020 @
10:58
PM
5
Intents
22:58
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Buena noche.</div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
me llamo jose
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
jose = @nombre:José
 
 
Cuéntame José, ¿qué se te ofrece?
agendar
#agendar_cita
 
Cuéntame José, ¿qué tipo de cita se te ofrece?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
Medicina General
#agendar_cita
Medicina = @especialidad:médica
Medicina = @temática:ciencias naturales
Medicina General = @opción:médica
 
¿La cita médica es para ti o es para alguien más?
para mi
#cambiar_usuario
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
 
 
José tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

15 de julio de 2018 a las 10:20 am: 15 de julio de 2018 a las 10:20 am
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

15 de julio de 2018 a las 4:00 pm : 15 de julio de 2018 a las 4:00 pm
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

26 de julio de 2018 a las 1:00 PM: 26 de julio de 2018 a las 1:00 PM
 
</br>Elije una antes que alguien más la reserve
15 de julio de 2018 a las 10:20 am
#cambiar_turno
15 de julio de 2018 = @sys-date:2018-07-15
de = @persona:ella
de = @persona:él
de = @preposición:de
de = @verbo:dar
julio = @nombre:Julio
de = @persona:ella
de = @persona:él
de = @preposición:de
de = @verbo:dar
a = @preposición:a
a las 10:20 am = @sys-time:10:20:00
las = @pronombres:las
am = @turno:M
 
José procederemos a consultar disponbilidad con el documento CC 31234567890 para la cita médica, el dia 2018-07-15 a las 10:20:00 </br></br>
 
¿Esta bien?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
{"id":"fd4609b30179d8e8b571a0e3bac0e7d6","ok":true,"rev":"1-ef0f347baebfd2edfeefbdb294705125"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?
me duele una muela
#emergencia
me = @pronombres:me
me duele una muela = @emergencia:triage5
duele = @modo_tiempo:imperativo
duele = @persona:él
duele = @persona:tú
duele = @persona:ella
duele = @verbo:doler
duele = @modo_tiempo:indicativo presente
una = @sys-number:1
muela = @especialidad:odontológica
muela = @persona:él
muela = @persona:yo
muela = @persona:ella
 
¿Podemos hacer algo más por ti?
23:01

---

07/08/2020 @
11:06
PM
2
Intents
23:06
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buena noche.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
jose
#cambiar_usuario
jose = @nombre:José
 
 
¿Como podemos ayudarte José?
agendar
#agendar_cita
 
¿Qué tipo de cita deseas agendar José?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
Medicina General
#agendar_cita
Medicina = @especialidad:médica
Medicina = @temática:ciencias naturales
Medicina General = @opción:médica
 
¿La cita médica es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
Es para mí
#cambiar_usuario
Es = @persona:él
Es = @persona:ella
Es = @verbo:ser
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mí = @pronombres:mí
 
 
José tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

15 de julio de 2018 a las 10:20 am: 15 de julio de 2018 a las 10:20 am
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

15 de julio de 2018 a las 4:00 pm : 15 de julio de 2018 a las 4:00 pm
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

26 de julio de 2018 a las 1:00 PM: 26 de julio de 2018 a las 1:00 PM
 
</br>¿Alguna de estas opciones te sirve?
23:06

---

07/08/2020 @
11:06
PM
2
Intents
23:06
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buena noche.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
jose
#cambiar_usuario
jose = @nombre:José
 
 
¿Como podemos ayudarte José?
agendar
#agendar_cita
 
¿Qué tipo de cita deseas agendar José?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
Medicina General
#agendar_cita
Medicina = @especialidad:médica
Medicina = @temática:ciencias naturales
Medicina General = @opción:médica
 
¿La cita médica es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
Es para mí
#cambiar_usuario
Es = @persona:él
Es = @persona:ella
Es = @verbo:ser
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mí = @pronombres:mí
 
 
José tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

15 de julio de 2018 a las 10:20 am: 15 de julio de 2018 a las 10:20 am
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

15 de julio de 2018 a las 4:00 pm : 15 de julio de 2018 a las 4:00 pm
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

26 de julio de 2018 a las 1:00 PM: 26 de julio de 2018 a las 1:00 PM
 
</br>¿Alguna de estas opciones te sirve?
23:06

---

07/08/2020 @
11:09
PM
2
Intents
23:09
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buena noche.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
hugo
#cambiar_usuario
hugo = @nombre:Hugo
 
 
Cuéntame Hugo, ¿qué se te ofrece?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Consultar
#consultar_cita
 
Para comenzar indícanos tu número y tipo de documento
23:09

---

07/08/2020 @
11:09
PM
3
Intents
23:09
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas noches.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
hugo
#cambiar_usuario
hugo = @nombre:Hugo
 
 
¿Cuál es el motivo de tú visita el día de hoy Hugo?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Modificar
#modificar_cita
 
Para comenzar indícanos tu número y tipo de documento
cc 546456
#corregir
cc = @tipo_documento:CC
546456 = @input_patterns:PEP
546456 = @sys-number:546456
 
23:10

---

07/08/2020 @
11:10
PM
3
Intents
23:10
 
<a href="https://imgur.com/fMUI13D"><img src="https://i.imgur.com/fMUI13Dt.jpg" title="diseñado en conjunto por los estudiantes" /></a>
 
<div class="msgj">Hola, Buena noche.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
hugo
#cambiar_usuario
hugo = @nombre:Hugo
 
 
Cuéntame Hugo, ¿qué se te ofrece?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Eliminar
#eliminar_cita
 
Para comenzar indícanos tu número y tipo de documento
cc 435434
#corregir
cc = @tipo_documento:CC
435434 = @input_patterns:PEP
435434 = @sys-number:435434
 
 
Estimado Hugo, estas son las citas agendadas actualmente con el documento CC 435434</br></br>
 
[Multi-option response]
Title: 1. 6 de julio de 2018 a las 7:30 am en CM DUITAMA

 
[Multi-option response]
Title: 2. 19 de julio de 2018 a las 10:00 am en CM DUITAMA<

 
[Multi-option response]
Title: 3. 6 de julio de 2018 a las 10:00 am en CM DUITAMA

 
[Multi-option response]
Title: 4. 19 de julio de 2018 a las 3:00 pm en CL INFANTIL

 
[Multi-option response]
Title: 5. 19 de julio de 2018 a las 6:30 am en CM SUBA

 
Puedo mostrarte tus citas agendadas de cinco en cinco. En total actualmente tienes 13 citas agendadas. Estamos en la pagina 1 de un total de 3.</br></br> Puedes pedirme que avance o retroceda una pagina para ver las demas citas agendadas.</br></br>
 
</br>¿Cuál cita vas a eliminar?
23:10

---















