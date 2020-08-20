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

08/09/2020 @
12:52
PM
9
Intents
12:52 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buena tarde.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
me llamo miguel
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
miguel = @nombre:Miguel
 
 
Cuéntame Miguel, ¿qué se te ofrece?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Agendar
#agendar_cita
 
¿Qué tipo de cita deseas agendar Miguel?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
Odontológia Básica
#agendar_cita
Odontológia = @opción:odontológica
Odontológia = @especialidad:odontológica
 
¿La cita odontológica es para ti o es para alguien más?
 
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
 
 
Miguel tenemos estas opciones disponibles para la cita odontológica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

15 de julio de 2018 a las 10:20 am: Cita odontológica el día 15 de julio de 2018 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

15 de julio de 2018 a las 4:00 pm : Cita odontológica el día 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

26 de julio de 2018 a las 1:00 PM: Cita odontológica el día 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
 
</br>¿Cuál es tu elección?
Cita odontológica el día 15 de julio de 2018 a las 10:20 am en CM SUBA
Irrelevant
Cita = @persona:tú
Cita = @persona:él
Cita = @persona:ella
Cita = @verbo:citar
Cita = @modo_tiempo:indicativo presente
Cita = @modo_tiempo:imperativo
Cita odontológica = @opción:odontológica
odontológica = @especialidad:odontológica
el = @preposición:la del
el = @pronombres:el
el día 15 de julio de 2018 = @sys-date:2018-07-15
día = @dato:fecha
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
julio = @nombre:Julio
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
a = @preposición:a
a las 10:20 am = @sys-time:10:20:00
las = @pronombres:las
am = @turno:M
am en = @persona:ellos
en = @preposición:en
CM SUBA = @centro_médico:CM SUBA
 
Vamos a consultar disponibilidad con el documento CC 31234567890 de la cita odontológica Miguel para el día 2018-07-15 a las 10:20:00 en CM SUBA</br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Me autorizas a reservarla?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada correctamente ✔️</strong></br></br>Miguel la cita odontológica ha sido agendada para el dia 2018-07-15 a las 10:20:00 en el centro médico CM SUBA.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 31234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>70df5ec470b023d704c078bdb66056d5</strong></br></br>
 
¿Podemos hacer algo más por ti?
Tal vez
#conversacion
Tal = @adverbio:tal
 
¿Cuál es el motivo de tu visita a este canal?
:D
#corregir
:D = @emojis:lagrimas de felicidad
 
Que deseas que corrijamos?
Nada, gracias
#General_Positive_Feedback
Nada = @decisión:no
Nada = @adverbio:nada
Nada = @pronombres:nada
gracias = @conversacion:cortesia
gracias = @conversacion:agradecimiento
 
Que deseas corregir?
Nada
#denegar
Nada = @decisión:no
Nada = @adverbio:nada
Nada = @pronombres:nada
 
¿Qué te trae por aquí entonces?
Solo soy un espectador jeje
#conversacion
Solo = @extractor:solo
Solo = @adverbio:solo
soy = @persona:yo
soy = @verbo:ser
jeje = @persona:yo
jeje = @persona:él
jeje = @persona:ella
 
¿de que tema se trata tu necesidad?
Tengo Covid 19
#emergencia
Tengo = @persona:yo
Tengo = @verbo:tener
Tengo = @modo_tiempo:indicativo presente
19 = @sys-number:19
12:55 PM

---

08/09/2020 @
3:37
PM
5
Intents
3:37 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas tardes.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
me llamo miguel
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
miguel = @nombre:Miguel
 
 
¿Cuál es el motivo de tú visita el día de hoy Miguel?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Agendar
 
Cuéntame Miguel, ¿qué tipo de cita se te ofrece?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
Odontológia Básica
#agendar_cita
Odontológia = @opción:odontológica
Odontológia = @especialidad:odontológica
 
¿La cita odontológica es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
Es para mi tía
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
tía = @otra_persona:tío
 
Por favor indicame el número de documento de tu tía
cc 111
#corregir
cc = @tipo_documento:CC
111 = @sys-number:111
 
 
Miguel tenemos estas opciones disponibles para la cita odontológica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

15 de julio de 2018 a las 10:20 am: Cita odontológica el día 15 de julio de 2018 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

15 de julio de 2018 a las 4:00 pm : Cita odontológica el día 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

26 de julio de 2018 a las 1:00 PM: Cita odontológica el día 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
 
</br>¿Te sirve alguna de las anteriores o quieres probar diciéndome una fecha y hora?
Cita odontológica el día 15 de julio de 2018 a las 10:20 am en CM SUBA
Irrelevant
Cita = @persona:tú
Cita = @persona:él
Cita = @persona:ella
Cita = @verbo:citar
Cita = @modo_tiempo:indicativo presente
Cita = @modo_tiempo:imperativo
Cita odontológica = @opción:odontológica
odontológica = @especialidad:odontológica
el = @preposición:la del
el = @pronombres:el
el día 15 de julio de 2018 = @sys-date:2018-07-15
día = @dato:fecha
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
julio = @nombre:Julio
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
a = @preposición:a
a las 10:20 am = @sys-time:10:20:00
las = @pronombres:las
am = @turno:M
am en = @persona:ellos
en = @preposición:en
CM SUBA = @centro_médico:CM SUBA
 
Vamos a consultar disponibilidad con el documento CC 111 de la cita odontológica Miguel para el día 2018-07-15 a las 10:20:00 en CM SUBA</br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Quieres agendarla?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada con éxito ✔️</strong></br></br>Miguel la cita odontológica ha sido agendada para el dia 2018-07-15 a las 10:20:00 en el centro médico CM SUBA.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 111 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>eb70bdfae2c8414eeaa8d9da225d90ff</strong></br></br>
 
¿Podemos hacer algo más por ti?



---



08/09/2020 @
6:37
PM
3
Intents
6:37 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buenas noches.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
#agendar_cita
Hola = @conversacion:saludo
Hola = @extractor:hola
me = @pronombres:me
gustaria = @persona:ella
gustaria = @persona:yo
gustaria = @persona:él
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
para = @persona:tú
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
para = @preposición:para
para = @modo_tiempo:imperativo
el = @preposición:la del
el = @pronombres:el
el lunes = @sys-date:2020-08-10
las = @pronombres:las
las 5 y media = @sys-time:05:30:00
 
procederemos a consultar disponbilidad con el documento CC 31234567890 para la cita odontológica, el dia 2020-08-10 a las 05:30:00</br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Esta bien?
no
#decisión
no = @decisión:no
 
¿Que deseas corregir?
la identificacion
#corregir
la = @pronombres:la
identificacion = @tramite:Identificacion
 
Por favor indícame, ¿que hay que corregir?
la cedula
#corregir
la = @pronombres:la
cedula = @tipo_documento:CC
cedula = @dato:numero_documento
 
muy bien por favor dime de nuevo el numero y tipo de documento para realizar la corrección.
ti 856786
#corregir
ti = @tipo_documento:TI
ti = @pronombres:ti
856786 = @input_patterns:PEP
856786 = @sys-number:856786
 
 
tenemos estas opciones disponibles para la cita odontológica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

15 de julio de 2018 a las 10:20 am: Cita odontológica el día 15 de julio de 2018 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

15 de julio de 2018 a las 4:00 pm : Cita odontológica el día 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

26 de julio de 2018 a las 1:00 PM: Cita odontológica el día 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
 
</br>¿Cuál es tu elección?
6:39 PM


---

08/09/2020 @
6:59
PM
6
Intents
6:59 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buena noche.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
#agendar_cita
Hola = @conversacion:saludo
Hola = @extractor:hola
me = @pronombres:me
gustaria = @persona:ella
gustaria = @persona:yo
gustaria = @persona:él
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
para = @persona:tú
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
para = @preposición:para
para = @modo_tiempo:imperativo
el = @preposición:la del
el = @pronombres:el
el lunes = @sys-date:2020-08-10
las = @pronombres:las
las 5 y media = @sys-time:05:30:00
 
procederemos a consultar disponbilidad con el documento CC 31234567890 para la cita odontológica, el dia 2020-08-10 a las 05:30:00</br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Esta bien?
no
#decisión
no = @decisión:no
 
¿Que deseas corregir?
la identificacion
#corregir
la = @pronombres:la
identificacion = @tramite:Identificacion
identificacion = @dato:numero_documento
 
muy bien por favor dime de nuevo el numero y tipo de documento para realizar la corrección.
pep 93454754
#corregir
pep = @dato:tipo_documento
pep = @tipo_documento:PEP
934547 = @input_patterns:PEP
93454754 = @sys-number:93454754
 
 
tenemos estas opciones disponibles para la cita odontológica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

15 de julio de 2018 a las 10:20 am: Cita odontológica el día 15 de julio de 2018 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

15 de julio de 2018 a las 4:00 pm : Cita odontológica el día 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

26 de julio de 2018 a las 1:00 PM: Cita odontológica el día 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
 
</br>Elije una antes que alguien más la reserve
3
#decisión
3 = @opción:tercera
3 = @sys-number:3
 
Has elegido la tercera opción:
 
tu cita odontológica quedará reservada para el día 26 de julio de 2018 a las 1:00 PM en el centro médico , con el documento PEP 93454754. </br></br>Recuerda que debes llegar 30 minutos antes y pasar por el punto ágil para facturar tu cuota moderadora.</br></br>Si no puedes ir a tu cita, cancela con 3 horas de anticipación y permite que alguien la tome por ti.</br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Esta bien?
si
#aceptar
si = @decisión:sí
 
{"id":"d8cf86b42bc7ba6a6234efa0c2ae90b9","ok":true,"rev":"1-60099619550268c4f2621b1319f65046"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?
si
#aceptar
si = @decisión:sí
 
¿Que otra cosa te gustaría hacer?
agendar
#agendar_cita
 
¿Qué tipo de cita deseas agendar ?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
Medicina General
#agendar_cita
Medicina = @especialidad:médica
Medicina = @temática:ciencias naturales
Medicina General = @opción:médica
 
¿Es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
Es para mi tía
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
tía = @otra_persona:tío
 
Por favor indicame el número de documento de tu tía
ti 856786
#corregir
ti = @tipo_documento:TI
ti = @dato:tipo_documento
ti = @pronombres:ti
856786 = @input_patterns:PEP
856786 = @sys-number:856786
 
 
tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

15 de julio de 2018 a las 10:20 am: Cita médica el día 15 de julio de 2018 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

15 de julio de 2018 a las 4:00 pm : Cita médica el día 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

26 de julio de 2018 a las 1:00 PM: Cita médica el día 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
 
</br>¿Alguna de estas opciones te sirve?
Cita médica el día 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR
#cambiar_turno
Cita = @persona:tú
Cita = @modo_tiempo:imperativo
Cita = @persona:él
Cita = @persona:ella
Cita = @verbo:citar
Cita = @modo_tiempo:indicativo presente
Cita médica = @opción:médica
médica = @especialidad:médica
el = @preposición:la del
el = @pronombres:el
el día 15 de julio de 2018 = @sys-date:2018-07-15
día = @dato:fecha
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
julio = @nombre:Julio
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
a = @preposición:a
a las 4:00 pm = @sys-time:16:00:00
las = @pronombres:las
4 = @opción:cuarta
pm = @turno:T
en = @preposición:en
CM GRANAHORRAR = @centro_médico:CM GRANAHORRAR
 
Vamos a consultar disponibilidad con el documento TI 856786 de la cita médica para el día 2018-07-15 a las 16:00:00 en CM GRANAHORRAR</br></br>
 
¿Quieres agendarla?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada correctamente ✔️</strong></br></br> la cita médica ha sido agendada para el dia 2018-07-15 a las 16:00:00 en el centro médico CM GRANAHORRAR.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación TI 856786 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>77f39e5dd7e1cf8efcae803dedcc303b</strong></br></br>
 
¿Podemos hacer algo más por ti?


---


08/09/2020 @
8:26
PM
1
Intents
8:26 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas noches.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hola
#conversacion
Hola = @conversacion:saludo
Hola = @extractor:hola
 
Me alegra saludarte ¿como te va?


---

08/10/2020 @
1:52
AM
3
Intents
1:52 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Sin importar la hora, estamos aquí para ti. </div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hola
#conversacion
Hola = @conversacion:saludo
Hola = @extractor:hola
 
Buenas, ¿como estas? <break></break>
bien
#conversacion
bien = @conversacion:bienestar
bien = @adverbio:bien
 
maravilloso,
 
¿como puedo ayudarte?
cómo te llamas?
#habilidades
te = @pronombres:te
llamas = @verbo:llamar
llamas = @persona:tú
llamas = @modo_tiempo:indicativo presente
? = @conversacion:Pregunta
 
Mi nombre es Santiago, estoy aquí para ayudarte con el agendamiento, modificación y eliminación de citas médicas y odontológicas.
citas en platzi?
#consultar_cita
citas = @persona:tú
citas = @verbo:citar
citas = @modo_tiempo:indicativo presente
en = @preposición:en
? = @conversacion:Pregunta
 
Para comenzar indícanos tu número y tipo de documento
1:52 AM

---

08/10/2020 @
12:46
PM
6
Intents
12:46 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buena tarde.</div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hola
#conversacion
Hola = @conversacion:saludo
Hola = @extractor:hola
 
Me alegra saludarte ¿como te va?
Bien gracias
#conversacion
Bien = @adverbio:bien
Bien gracias = @conversacion:bienestar
 
maravilloso,
 
¿de que tema se trata tu necesidad?
Necesito una cita medica con neurología
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
cita medica = @opción:médica
cita medica = @tramite:Salud
medica = @dato:tipo_de_cita
medica = @especialidad:médica
con = @preposición:con
neurología = @especialidad:neurología
neurología = @fuera_de_entrenamiento:neurología
 
¿Es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
Para mi mama
#cambiar_usuario
Para = @persona:tú
Para = @preposición:para
Para = @modo_tiempo:imperativo
Para = @persona:él
Para = @persona:ella
Para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
mi mama = @otra_persona:madre
mama = @genero:femenino
mama = @temática:madre
 
Por favor indicame el número de documento de tu mi mama
1045729i789
Irrelevant
104572 = @input_patterns:PEP
045729i789 = @input_patterns:CC
 
 
tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

15 de julio de 2018 a las 10:20 am: Cita médica el día 15 de julio de 2018 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

15 de julio de 2018 a las 4:00 pm : Cita médica el día 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

26 de julio de 2018 a las 1:00 PM: Cita médica el día 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
 
</br>¿Te sirve alguna de las anteriores o quieres probar diciéndome una fecha y hora?
Cita médica el día 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
#cambiar_turno
Cita = @persona:tú
Cita = @persona:él
Cita = @persona:ella
Cita = @verbo:citar
Cita = @modo_tiempo:indicativo presente
Cita = @modo_tiempo:imperativo
Cita médica = @opción:médica
médica = @especialidad:médica
el = @preposición:la del
el = @pronombres:el
el día 26 de julio de 2018 = @sys-date:2018-07-26
día = @dato:fecha
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
julio = @nombre:Julio
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
a = @preposición:a
a las 1:00 PM = @sys-time:13:00:00
las = @pronombres:las
1 = @opción:primera
PM = @turno:T
en = @preposición:en
CM PORTAL NORTE = @centro_médico:CM PORTAL NORTE
NORTE = @zona:Norte
 
procederemos a consultar disponibilidad con el documento CC 31234567890 para la cita médica, el día 2018-07-26 a las 13:00:00 en CM PORTAL NORTE</br></br>
 
¿Quieres agendarla?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
No fue posible agendarla. Por favor espera un momento mientras buscamos otras opciones disponibles.
 
tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

15 de julio de 2018 a las 10:20 am: Cita médica el día 15 de julio de 2018 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

15 de julio de 2018 a las 4:00 pm : Cita médica el día 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

26 de julio de 2018 a las 1:00 PM: Cita médica el día 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
 
</br>¿Cuál es tu elección?
Cita médica el día 15 de julio de 2018 a las 10:20 am en CM SUBA
Irrelevant
Cita = @persona:tú
Cita = @persona:él
Cita = @persona:ella
Cita = @verbo:citar
Cita = @modo_tiempo:indicativo presente
Cita = @modo_tiempo:imperativo
Cita médica = @opción:médica
médica = @especialidad:médica
el = @preposición:la del
el = @pronombres:el
el día 15 de julio de 2018 = @sys-date:2018-07-15
día = @dato:fecha
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
julio = @nombre:Julio
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
a = @preposición:a
a las 10:20 am = @sys-time:10:20:00
las = @pronombres:las
am = @turno:M
am en = @persona:ellos
en = @preposición:en
CM SUBA = @centro_médico:CM SUBA
 
Vamos a consultar disponibilidad con el documento CC 31234567890 de la cita médica para el día 2018-07-15 a las 10:20:00 en CM SUBA</br></br>
 
¿Confirmas?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
No fue posible agendarla. Por favor espera un momento mientras buscamos otras opciones disponibles.
 
tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

15 de julio de 2018 a las 10:20 am: Cita médica el día 15 de julio de 2018 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

15 de julio de 2018 a las 4:00 pm : Cita médica el día 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

26 de julio de 2018 a las 1:00 PM: Cita médica el día 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
 
</br>Elije una antes que alguien más la reserve
Cita médica el día 15 de julio de 2018 a las 10:20 am en CM SUBA
Irrelevant
Cita = @persona:tú
Cita = @persona:él
Cita = @persona:ella
Cita = @verbo:citar
Cita = @modo_tiempo:indicativo presente
Cita = @modo_tiempo:imperativo
Cita médica = @opción:médica
médica = @especialidad:médica
el = @preposición:la del
el = @pronombres:el
el día 15 de julio de 2018 = @sys-date:2018-07-15
día = @dato:fecha
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
julio = @nombre:Julio
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
a = @preposición:a
a las 10:20 am = @sys-time:10:20:00
las = @pronombres:las
am = @turno:M
am en = @persona:ellos
en = @preposición:en
CM SUBA = @centro_médico:CM SUBA
 
Vamos a consultar disponibilidad con el documento CC 31234567890 de la cita médica para el día 2018-07-15 a las 10:20:00 en CM SUBA</br></br>
 
¿La reservamos?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada correctamente ✔️</strong></br></br> la cita médica ha sido agendada para el dia 2018-07-15 a las 10:20:00 en el centro médico CM SUBA.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 31234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>33dc142511171a3924665d1fc8cfd095</strong></br></br>
 
¿Podemos hacer algo más por ti?


---

08/10/2020 @
5:36
PM
6
Intents
5:36 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buena tarde.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hola
#conversacion
Hola = @conversacion:saludo
Hola = @extractor:hola
 
Hola, ¿como te encuentras hoy? <break></break>
So
#despedidas
So = @preposición:so
 
¿en que te puedo colaborar?
Cita
#agendar_cita
Cita = @persona:ella
Cita = @persona:tú
Cita = @modo_tiempo:imperativo
Cita = @persona:él
Cita = @verbo:citar
Cita = @modo_tiempo:indicativo presente
 
Cuéntame , ¿qué tipo de cita se te ofrece?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
Odontológia Básica
#agendar_cita
Odontológia = @opción:odontológica
Odontológia = @especialidad:odontológica
 
¿Es para ti o es para alguien más?
 
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
 
 
tenemos estas opciones disponibles para la cita odontológica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

15 de julio de 2018 a las 10:20 am: Cita odontológica el día 15 de julio de 2018 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

15 de julio de 2018 a las 4:00 pm : Cita odontológica el día 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

26 de julio de 2018 a las 1:00 PM: Cita odontológica el día 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
 
</br>¿Alguna de estas opciones te sirve?
Cita odontológica el día 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
#cambiar_turno
Cita = @persona:tú
Cita = @persona:él
Cita = @persona:ella
Cita = @verbo:citar
Cita = @modo_tiempo:indicativo presente
Cita = @modo_tiempo:imperativo
Cita odontológica = @opción:odontológica
odontológica = @especialidad:odontológica
el = @preposición:la del
el = @pronombres:el
el día 26 de julio de 2018 = @sys-date:2018-07-26
día = @dato:fecha
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
julio = @nombre:Julio
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
a = @preposición:a
a las 1:00 PM = @sys-time:13:00:00
las = @pronombres:las
1 = @opción:primera
PM = @turno:T
en = @preposición:en
CM PORTAL NORTE = @centro_médico:CM PORTAL NORTE
NORTE = @zona:Norte
 
procederemos a consultar disponibilidad con el documento CC 31234567890 para la cita odontológica, el día 2018-07-26 a las 13:00:00 en CM PORTAL NORTE</br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Me autorizas a reservarla?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada exitosamente ✔️</strong></br></br>La cita odontológica ha sido agendada para el dia 2018-07-26 a las 13:00:00 en el centro médico CM PORTAL NORTE .</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 31234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>3ffec9d350dc5f395579b65b8fe5c727</strong></br></br>
 
¿Podemos hacer algo más por ti?


---

08/11/2020 @
1:03
AM
7
Intents
1:03 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Si tu trasnochas, aquí nos trasnochamos contigo. </div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
hola
#conversacion
hola = @conversacion:saludo
hola = @extractor:hola
 
Que bueno verte de nuevo por aquí , ¿Como estas?
bien y tu?
#conversacion
bien = @conversacion:bienestar
bien = @adverbio:bien
tu = @persona:tú
? = @conversacion:Pregunta
 
maravilloso,
 
¿Cuál es el motivo de tu visita a este canal?
quisiera agendar una cita medica
#agendar_cita
quisiera = @persona:él
quisiera = @persona:ella
quisiera = @persona:yo
quisiera = @verbo:querer
quisiera = @modo_tiempo:subjuntivo imperfecto
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
 
¿Es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
mi
#recuperar_datos
mi = @pronombres:mí
 
 
tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

15 de julio de 2018 a las 10:20 am: Cita médica el día 15 de julio de 2018 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

15 de julio de 2018 a las 4:00 pm : Cita médica el día 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

26 de julio de 2018 a las 1:00 PM: Cita médica el día 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
 
</br>¿Alguna de estas opciones te sirve?
la necesito en medellin
#agendar_cita
la = @pronombres:la
necesito = @verbo:necesitar
necesito = @persona:yo
necesito = @modo_tiempo:indicativo presente
en = @preposición:en
medellin = @ciudad_pais:Medellin
 
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
 
 
tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

15 de julio de 2018 a las 10:20 am: Cita médica el día 15 de julio de 2018 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

15 de julio de 2018 a las 4:00 pm : Cita médica el día 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

26 de julio de 2018 a las 1:00 PM: Cita médica el día 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
 
</br>¿Cuál es tu elección?
Cita médica el día 15 de julio de 2018 a las 10:20 am en CM SUBA
Irrelevant
Cita = @persona:tú
Cita = @persona:él
Cita = @persona:ella
Cita = @verbo:citar
Cita = @modo_tiempo:indicativo presente
Cita = @modo_tiempo:imperativo
Cita médica = @opción:médica
médica = @especialidad:médica
el = @preposición:la del
el = @pronombres:el
el día 15 de julio de 2018 = @sys-date:2018-07-15
día = @dato:fecha
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
julio = @nombre:Julio
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
a = @preposición:a
a las 10:20 am = @sys-time:10:20:00
las = @pronombres:las
am = @turno:M
am en = @persona:ellos
en = @preposición:en
CM SUBA = @centro_médico:CM SUBA
 
Vamos a consultar disponibilidad con el documento CC 31234567890 de la cita médica para el día 2018-07-15 a las 10:20:00 en CM SUBA</br></br>
 
¿La reservamos?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
ese no es mi documento
#cambiar_usuario
ese = @forma_tipo:adjetivo demostrativo
ese = @pronombres:ese
no = @decisión:no
no es = @opción:indeterminado
es = @persona:ella
es = @persona:él
es = @verbo:ser
mi = @pronombres:mí
documento = @dato:numero_documento
 
muy bien por favor dime de nuevo el numero y tipo de documento para realizar la corrección.
85230514
Irrelevant
852305 = @input_patterns:PEP
85230514 = @sys-number:85230514
 
 
tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

15 de julio de 2018 a las 10:20 am: Cita médica el día 15 de julio de 2018 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

15 de julio de 2018 a las 4:00 pm : Cita médica el día 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

26 de julio de 2018 a las 1:00 PM: Cita médica el día 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
 
</br>Elije una antes que alguien más la reserve
Cita médica el día 15 de julio de 2018 a las 10:20 am en CM SUBA
Irrelevant
Cita = @persona:tú
Cita = @persona:él
Cita = @persona:ella
Cita = @verbo:citar
Cita = @modo_tiempo:indicativo presente
Cita = @modo_tiempo:imperativo
Cita médica = @opción:médica
médica = @especialidad:médica
el = @preposición:la del
el = @pronombres:el
el día 15 de julio de 2018 = @sys-date:2018-07-15
día = @dato:fecha
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
julio = @nombre:Julio
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
a = @preposición:a
a las 10:20 am = @sys-time:10:20:00
las = @pronombres:las
am = @turno:M
am en = @persona:ellos
en = @preposición:en
CM SUBA = @centro_médico:CM SUBA
 
Vamos a consultar disponibilidad con el documento CC 31234567890 de la cita médica para el día 2018-07-15 a las 10:20:00 en CM SUBA</br></br>
 
¿Quieres agendarla?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Corregir
#corregir
 
¿Que deseas corregir?
documento
#corregir
documento = @dato:numero_documento
 
muy bien por favor dime de nuevo el numero y tipo de documento para realizar la corrección.
cc 85230514
#corregir
cc = @tipo_documento:CC
852305 = @input_patterns:PEP
85230514 = @sys-number:85230514
 
 
tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

15 de julio de 2018 a las 10:20 am: Cita médica el día 15 de julio de 2018 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

15 de julio de 2018 a las 4:00 pm : Cita médica el día 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

26 de julio de 2018 a las 1:00 PM: Cita médica el día 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
 
</br>¿Te sirve alguna de las anteriores o quieres probar diciéndome una fecha y hora?
Cita médica el día 15 de julio de 2018 a las 10:20 am en CM SUBA
Irrelevant
Cita = @persona:tú
Cita = @persona:él
Cita = @persona:ella
Cita = @verbo:citar
Cita = @modo_tiempo:indicativo presente
Cita = @modo_tiempo:imperativo
Cita médica = @opción:médica
médica = @especialidad:médica
el = @preposición:la del
el = @pronombres:el
el día 15 de julio de 2018 = @sys-date:2018-07-15
día = @dato:fecha
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
julio = @nombre:Julio
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
a = @preposición:a
a las 10:20 am = @sys-time:10:20:00
las = @pronombres:las
am = @turno:M
am en = @persona:ellos
en = @preposición:en
CM SUBA = @centro_médico:CM SUBA
 
procederemos a consultar disponibilidad con el documento CC 85230514 para la cita médica, el día 2018-07-15 a las 10:20:00 en CM SUBA</br></br>
 
¿Está bien?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada exitosamente ✔️</strong></br></br> la cita médica ha sido agendada para el dia 2018-07-15 a las 10:20:00 en el centro médico CM SUBA.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 85230514 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>77a40921c935aa2c3b89f0f732d24f33</strong></br></br>
 
¿Podemos hacer algo más por ti?


---

08/12/2020 @
2:45
PM
10
Intents
2:45 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buenas tardes.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hola
#conversacion
Hola = @conversacion:saludo
Hola = @extractor:hola
 
Me alegra saludarte ¿como te va?
mal
#corregir
mal = @adverbio:mal
 
¿Cuál es el motivo de tu visita a este canal?
:(
Irrelevant
 
¿en que te puedo colaborar?
ayudame a reslver mi problema
#emergencia
ayudame = @emergencia:ambulancia
a = @preposición:a
mi = @pronombres:mí
oe que fue
#habilidades
fue = @modo_tiempo:indicativo pasado
fue = @persona:ella
fue = @persona:él
fue = @verbo:ir
fue = @verbo:ser
 
te puedo ayudar a realizar solicitudes de citas medicas y odontológicas.
si neciso un psicologo
#aceptar
si = @decisión:sí
 
¿como puedo ayudarte?
tengo ambre
#emergencia
tengo = @persona:yo
tengo = @verbo:tener
tengo = @modo_tiempo:indicativo presente
ambre = @persona:tú
ambre = @persona:él
ambre = @persona:ella
habla pe ctm
#conversacion
habla = @persona:ella
habla = @persona:tú
habla = @modo_tiempo:imperativo
habla = @persona:él
habla = @verbo:hablar
habla = @conversacion:iniciar
habla = @modo_tiempo:indicativo presente
 
Buenas, ¿como estas? <break></break>
mal
#corregir
mal = @adverbio:mal
 
¿te puedo ayudar en algo?
si
#aceptar
si = @decisión:sí
 
¿qué tipo de cita te gustaría solicitar?
medica
#agendar_cita
medica = @especialidad:médica
medica = @dato:tipo_de_cita
medica = @opción:médica
 
¿La cita médica es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
para mi
#cambiar_usuario
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
 
 
tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

19 de agosto de 2020 a las 10:20 am: Cita médica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

1 de septiembre de 2020 a las 4:00 pm : Cita médica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

21 de agosto de 2020 a las 1:00 PM: Cita médica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
 
</br>Elije una antes que alguien más la reserve
Cita médica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
#cambiar_turno
Cita = @persona:tú
Cita = @persona:él
Cita = @persona:ella
Cita = @verbo:citar
Cita = @modo_tiempo:indicativo presente
Cita = @modo_tiempo:imperativo
Cita médica = @opción:médica
médica = @especialidad:médica
el = @preposición:la del
el = @pronombres:el
el día 21 de agosto de 2020 = @sys-date:2020-08-21
día = @dato:fecha
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
a = @preposición:a
a las 1:00 PM = @sys-time:13:00:00
las = @pronombres:las
1 = @opción:primera
PM = @turno:T
en = @preposición:en
CM PORTAL NORTE = @centro_médico:CM PORTAL NORTE
NORTE = @zona:Norte
 
Vamos a consultar disponibilidad con el documento CC 1234567890 de la cita médica para el día 2020-08-21 a las 13:00:00 en CM PORTAL NORTE</br></br>
 
¿Quieres agendarla?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada con éxito ✔️</strong></br></br> la cita médica ha sido agendada para el dia 2020-08-21 a las 13:00:00 en el centro médico CM PORTAL NORTE.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>30d0826f4caabd6565d833163a80ed20</strong></br></br>
 
¿Podemos hacer algo más por ti?



---

08/12/2020 @
2:42
PM
3
Intents
2:42 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buenas tardes.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Para comenzar dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
#agendar_cita
Hola = @conversacion:saludo
Hola = @extractor:hola
me = @pronombres:me
gustaria = @persona:ella
gustaria = @persona:yo
gustaria = @persona:él
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
para = @persona:tú
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
para = @preposición:para
para = @modo_tiempo:imperativo
el = @preposición:la del
el = @pronombres:el
el lunes = @sys-date:2020-08-17
las = @pronombres:las
las 5 y media = @sys-time:05:30:00
 
procederemos a consultar disponbilidad con el documento CC 1234567890 para la cita odontológica, el dia 2020-08-17 a las 05:30:00</br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Esta bien?
ok
#aceptar
ok = @decisión:sí
 
{"id":"8f87d505304be2eeffedac0d48235a42","ok":true,"rev":"1-9ccf834d394f6d36235f527d441a5262"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?
na todo chido :v
#conversacion
todo = @adverbio:todo
chido = @persona:yo
 
¿en que te puedo colaborar?


---

08/12/2020 @
2:45
PM
10
Intents
2:45 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buenas tardes.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hola
#conversacion
Hola = @conversacion:saludo
Hola = @extractor:hola
 
Me alegra saludarte ¿como te va?
mal
#corregir
mal = @adverbio:mal
 
¿Cuál es el motivo de tu visita a este canal?
:(
Irrelevant
 
¿en que te puedo colaborar?
ayudame a reslver mi problema
#emergencia
ayudame = @emergencia:ambulancia
a = @preposición:a
mi = @pronombres:mí
oe que fue
#habilidades
fue = @modo_tiempo:indicativo pasado
fue = @persona:ella
fue = @persona:él
fue = @verbo:ir
fue = @verbo:ser
 
te puedo ayudar a realizar solicitudes de citas medicas y odontológicas.
si neciso un psicologo
#aceptar
si = @decisión:sí
 
¿como puedo ayudarte?
tengo ambre
#emergencia
tengo = @persona:yo
tengo = @verbo:tener
tengo = @modo_tiempo:indicativo presente
ambre = @persona:tú
ambre = @persona:él
ambre = @persona:ella
habla pe ctm
#conversacion
habla = @persona:ella
habla = @persona:tú
habla = @modo_tiempo:imperativo
habla = @persona:él
habla = @verbo:hablar
habla = @conversacion:iniciar
habla = @modo_tiempo:indicativo presente
 
Buenas, ¿como estas? <break></break>
mal
#corregir
mal = @adverbio:mal
 
¿te puedo ayudar en algo?
si
#aceptar
si = @decisión:sí
 
¿qué tipo de cita te gustaría solicitar?
medica
#agendar_cita
medica = @especialidad:médica
medica = @dato:tipo_de_cita
medica = @opción:médica
 
¿La cita médica es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
para mi
#cambiar_usuario
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
 
 
tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

19 de agosto de 2020 a las 10:20 am: Cita médica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

1 de septiembre de 2020 a las 4:00 pm : Cita médica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

21 de agosto de 2020 a las 1:00 PM: Cita médica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
 
</br>Elije una antes que alguien más la reserve
Cita médica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
#cambiar_turno
Cita = @persona:tú
Cita = @persona:él
Cita = @persona:ella
Cita = @verbo:citar
Cita = @modo_tiempo:indicativo presente
Cita = @modo_tiempo:imperativo
Cita médica = @opción:médica
médica = @especialidad:médica
el = @preposición:la del
el = @pronombres:el
el día 21 de agosto de 2020 = @sys-date:2020-08-21
día = @dato:fecha
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
a = @preposición:a
a las 1:00 PM = @sys-time:13:00:00
las = @pronombres:las
1 = @opción:primera
PM = @turno:T
en = @preposición:en
CM PORTAL NORTE = @centro_médico:CM PORTAL NORTE
NORTE = @zona:Norte
 
Vamos a consultar disponibilidad con el documento CC 1234567890 de la cita médica para el día 2020-08-21 a las 13:00:00 en CM PORTAL NORTE</br></br>
 
¿Quieres agendarla?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada con éxito ✔️</strong></br></br> la cita médica ha sido agendada para el dia 2020-08-21 a las 13:00:00 en el centro médico CM PORTAL NORTE.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>30d0826f4caabd6565d833163a80ed20</strong></br></br>
 
¿Podemos hacer algo más por ti?


---

08/12/2020 @
2:45
PM
7
Intents
2:45 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas tardes.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
@BrayanPotosi esta aqui
#General_Greetings
esta = @pronombres:esta
aqui = @adverbio:aquí
 
Que bueno verte de nuevo por aquí , ¿Como estas?
Muy bienn gracias y tu?
#General_Positive_Feedback
Muy = @adverbio:muy
Muy bienn = @conversacion:bienestar
bienn = @adverbio:bien
bienn gracias = @conversacion:bienestar
tu = @persona:tú
? = @conversacion:Pregunta
 
soy un robot, no tengo sentimientos pero estoy igual orgulloso por esas palabras
si no tienes sentimientos como puedes estar orgulloso?
#decisión
si = @decisión:sí
no = @decisión:no
tienes = @persona:tú
tienes = @modo_tiempo:indicativo presente
tienes = @verbo:tener
como = @adverbio:como
como = @modo_tiempo:indicativo presente
como = @persona:yo
como = @verbo:comer
puedes = @persona:tú
puedes = @modo_tiempo:indicativo presente
puedes = @verbo:poder
estar = @modo_tiempo:infinitivo
estar = @verbo:estar
? = @conversacion:Pregunta
 
me encuentro genial
 
¿como puedo ayudarte?
que puedes hacer?
#habilidades
puedes = @persona:tú
puedes = @verbo:poder
puedes = @modo_tiempo:indicativo presente
hacer = @modo_tiempo:infinitivo
hacer = @verbo:hacer
? = @conversacion:Pregunta
 
Mi nombre es Santiago, estoy aquí para ayudarte con el agendamiento, modificación y eliminación de citas médicas y odontológicas.
quien es tu creador?
#habilidades
es = @persona:ella
es = @persona:él
es = @verbo:ser
tu = @persona:tú
? = @conversacion:Pregunta
 
Mi nombre es Santiago, estoy aquí para ayudarte con el agendamiento, modificación y eliminación de citas médicas y odontológicas.
quiero una cita
#agendar_cita
quiero = @persona:yo
quiero = @verbo:querer
quiero = @modo_tiempo:indicativo presente
una = @sys-number:1
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
 
¿Cuál clase de cita necesitas agendar hoy ?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
otro
#cambiar_agente
otro = @opción:otra
 
¿Deseas hablar con un humano?
si
#aceptar
si = @decisión:sí
 
Hola, aunque probablemente no te llames , antes que nada en nombre del equipo de trabajo detras de la creacion de este canal de ayuda, te agradecemos por tu tiempo y por darnos la oportunidad de probar nuevas formas de comunicarnos con nuestros clientes. </br></br>Mi nombre es Luis Mojica, soy el entrenador del chatbot y tal vez llegaste aquí porque no has tenido una buena experiencia con la aplicación, por lo cual en primera instancia en nombre de nuestro equipo de trabajo te pido disculpas y espero poder contar con tus comentarios para mejorar aquellos aspectos que aun pueden funcionar mejor. </br> </br>Por favor no ahorres palabras a continuación, todo lo que digas sera tomado en cuenta en nuestro proceso de mejora continua.</br> </br> Gracias por tu tiempo.


---

08/12/2020 @
2:46
PM
7
Intents
2:46 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas tardes.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hola
#conversacion
Hola = @conversacion:saludo
Hola = @extractor:hola
 
Hola ¿Qué hay de nuevo?
nada
#denegar
nada = @decisión:no
nada = @adverbio:nada
nada = @pronombres:nada
 
¿en que te puedo colaborar?
no lo sé , que puedes hacer?
#habilidades
no = @decisión:no
no lo sé = @opción:indeterminado
lo = @pronombres:lo
sé = @modo_tiempo:imperativo
sé = @persona:tú
sé = @verbo:saber
sé = @persona:yo
sé = @verbo:ser
sé = @modo_tiempo:indicativo presente
puedes = @persona:tú
puedes = @verbo:poder
puedes = @modo_tiempo:indicativo presente
hacer = @modo_tiempo:infinitivo
hacer = @verbo:hacer
? = @conversacion:Pregunta
 
te puedo ayudar con citas médicas y odontológicas.
necesito una cita odontológica
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
cita odontológica = @opción:odontológica
odontológica = @especialidad:odontológica
 
¿La cita odontológica es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
Para Elon Musk
Irrelevant
Para = @persona:tú
Para = @preposición:para
Para = @modo_tiempo:imperativo
Para = @persona:él
Para = @persona:ella
Para = @modo_tiempo:indicativo presente
 
 
tenemos estas opciones disponibles para la cita odontológica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

19 de agosto de 2020 a las 10:20 am: Cita odontológica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

1 de septiembre de 2020 a las 4:00 pm : Cita odontológica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

21 de agosto de 2020 a las 1:00 PM: Cita odontológica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
 
</br>¿Cuál es tu elección?
tienes mas opciones?
#control_bot
tienes = @persona:tú
tienes = @verbo:tener
tienes = @modo_tiempo:indicativo presente
? = @conversacion:Pregunta
 
¿Cuál es tu elección?
ninguna de las mostradas
#denegar
ninguna = @pronombres:ninguna
ninguna = @decisión:no
de = @persona:ella
de = @persona:él
de = @preposición:de
de = @verbo:dar
las = @pronombres:las
mostradas = @persona:tú
 
¿Que deseas corregir?
me voy
#despedidas
me = @pronombres:me
me voy = @conversacion:despedida
me voy = @control_bot:salir
voy = @verbo:ir
voy = @persona:yo
voy = @modo_tiempo:indicativo presente
 
Por favor indícame, ¿que hay que corregir?
nada, no sirves
#denegar
nada = @decisión:no
nada = @adverbio:nada
nada = @pronombres:nada
no = @decisión:no
 
¿Que deseas que corrijamos?
adios
#despedidas
adios = @conversacion:despedida
 
¿Que deseas corregir?


---


08/12/2020 @
2:46
PM
8
Intents
2:46 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas tardes.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hola
#conversacion
Hola = @conversacion:saludo
Hola = @extractor:hola
 
Que bueno verte de nuevo por aquí , ¿Como estas?
bien gracias
#conversacion
bien = @adverbio:bien
bien gracias = @conversacion:bienestar
 
me alegra saber que estas bien,
 
¿te puedo ayudar en algo?
si, quisiera agendar una hora medica
#agendar_cita
si = @decisión:sí
quisiera = @persona:él
quisiera = @persona:ella
quisiera = @persona:yo
quisiera = @verbo:querer
quisiera = @modo_tiempo:subjuntivo imperfecto
una hora = @sys-time:01:00:00
hora = @dato:hora
medica = @dato:tipo_de_cita
medica = @opción:médica
medica = @especialidad:médica
 
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
 
 
tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

19 de agosto de 2020 a las 10:20 am: Cita médica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

1 de septiembre de 2020 a las 4:00 pm : Cita médica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

21 de agosto de 2020 a las 1:00 PM: Cita médica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
 
</br>¿Cuál es tu elección?
Cita médica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
#cambiar_turno
Cita = @persona:tú
Cita = @modo_tiempo:imperativo
Cita = @persona:él
Cita = @persona:ella
Cita = @verbo:citar
Cita = @modo_tiempo:indicativo presente
Cita médica = @opción:médica
médica = @especialidad:médica
el = @preposición:la del
el = @pronombres:el
el día 1 de septiembre de 2020 = @sys-date:2020-09-01
día = @dato:fecha
1 = @opción:primera
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
a = @preposición:a
a las 4:00 pm = @sys-time:16:00:00
las = @pronombres:las
4 = @opción:cuarta
pm = @turno:T
en = @preposición:en
CM GRANAHORRAR = @centro_médico:CM GRANAHORRAR
 
Vamos a consultar disponibilidad con el documento CC 1234567890 de la cita médica para el día 2020-09-01 a las 16:00:00 en CM GRANAHORRAR</br></br>
 
¿Confirmas?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada correctamente ✔️</strong></br></br> la cita médica ha sido agendada para el dia 2020-09-01 a las 16:00:00 en el centro médico CM GRANAHORRAR.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>bc26eac9104421f7191659b5baa53917</strong></br></br>
 
¿Podemos hacer algo más por ti?
cual es la dirección?
#recuperar_datos
es = @persona:ella
es = @persona:él
es = @verbo:ser
la = @pronombres:la
la dirección = @opción:direccion
? = @conversacion:Pregunta
 
¿Podemos hacer algo más por ti?
si
#aceptar
si = @decisión:sí
 
¿Que otra cosa te gustaría hacer?
adios
#despedidas
adios = @conversacion:despedida
 
chao, ¡cuidate!
 
</br> </br>Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio Platzi - MinTic ICETEX Inteligencia Artificial. </br> </br> Antes que nada ¡¡¡Gracias!!! </br> </br> En el caso de uso que se presenta el chatbot realiza operaciones CRUD sobre una base de datos cloudant la cual ha sido expuesta mediante una API personalizada mediante functions. Todo serverless, una belleza!</br> </br> Es un gran detalle que quieras interactuar con este chatbot te agradezco cualquier comentario o critica constructiva. </br> </br>
Está interesante, aunque creo que abría que filtrar algunos resultados personalizados que aparecen al inicio por ejemplo "mi nombre es miguel", "me llamo sofia" porque le quita formalidad si es que la persona no se llama así. Esa e smi critica constructiva
#cambiar_usuario
Está = @persona:él
Está = @persona:tú
Está = @persona:ella
Está = @modo_tiempo:indicativo presente
Está = @modo_tiempo:imperativo
Está = @verbo:estar
creo = @persona:yo
creo = @verbo:crear
creo = @verbo:creer
creo = @modo_tiempo:indicativo presente
abría = @persona:él
abría = @persona:yo
abría = @verbo:abrir
abría = @persona:ella
abría = @modo_tiempo:indicativo imperfecto
algunos = @pronombres:algunos
por = @preposición:por
mi = @pronombres:mí
mi nombre es = @extractor:mi nombre es
nombre = @persona:yo
nombre = @persona:él
nombre = @persona:ella
nombre = @modo_tiempo:subjuntivo presente
nombre = @opción:nombre
nombre = @modo_tiempo:imperativo
nombre = @verbo:nombrar
es = @persona:él
es = @verbo:ser
es = @persona:ella
miguel = @nombre:Miguel
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @persona:yo
llamo = @verbo:llamar
llamo = @modo_tiempo:indicativo presente
sofia = @nombre:Sofía
le = @pronombres:le
si = @decisión:sí
es = @persona:él
es = @verbo:ser
es = @persona:ella
la = @pronombres:la
no = @decisión:no
no se = @opción:indeterminado
se = @pronombres:se
llama = @persona:él
llama = @persona:tú
llama = @verbo:llamar
llama = @persona:ella
llama = @modo_tiempo:indicativo presente
llama = @modo_tiempo:imperativo
así = @adverbio:así
Esa = @pronombres:esa
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buenas tardes.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media


---

08/12/2020 @
2:46
PM
7
Intents
2:46 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas tardes.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hola
#conversacion
Hola = @conversacion:saludo
Hola = @extractor:hola
 
Hola ¿Qué hay de nuevo?
nada
#denegar
nada = @decisión:no
nada = @adverbio:nada
nada = @pronombres:nada
 
¿en que te puedo colaborar?
no lo sé , que puedes hacer?
#habilidades
no = @decisión:no
no lo sé = @opción:indeterminado
lo = @pronombres:lo
sé = @modo_tiempo:imperativo
sé = @persona:tú
sé = @verbo:saber
sé = @persona:yo
sé = @verbo:ser
sé = @modo_tiempo:indicativo presente
puedes = @persona:tú
puedes = @verbo:poder
puedes = @modo_tiempo:indicativo presente
hacer = @modo_tiempo:infinitivo
hacer = @verbo:hacer
? = @conversacion:Pregunta
 
te puedo ayudar con citas médicas y odontológicas.
necesito una cita odontológica
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
cita odontológica = @opción:odontológica
odontológica = @especialidad:odontológica
 
¿La cita odontológica es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
Para Elon Musk
Irrelevant
Para = @persona:tú
Para = @preposición:para
Para = @modo_tiempo:imperativo
Para = @persona:él
Para = @persona:ella
Para = @modo_tiempo:indicativo presente
 
 
tenemos estas opciones disponibles para la cita odontológica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

19 de agosto de 2020 a las 10:20 am: Cita odontológica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

1 de septiembre de 2020 a las 4:00 pm : Cita odontológica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

21 de agosto de 2020 a las 1:00 PM: Cita odontológica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
 
</br>¿Cuál es tu elección?
tienes mas opciones?
#control_bot
tienes = @persona:tú
tienes = @verbo:tener
tienes = @modo_tiempo:indicativo presente
? = @conversacion:Pregunta
 
¿Cuál es tu elección?
ninguna de las mostradas
#denegar
ninguna = @pronombres:ninguna
ninguna = @decisión:no
de = @persona:ella
de = @persona:él
de = @preposición:de
de = @verbo:dar
las = @pronombres:las
mostradas = @persona:tú
 
¿Que deseas corregir?
me voy
#despedidas
me = @pronombres:me
me voy = @conversacion:despedida
me voy = @control_bot:salir
voy = @verbo:ir
voy = @persona:yo
voy = @modo_tiempo:indicativo presente
 
Por favor indícame, ¿que hay que corregir?
nada, no sirves
#denegar
nada = @decisión:no
nada = @adverbio:nada
nada = @pronombres:nada
no = @decisión:no
 
¿Que deseas que corrijamos?
adios
#despedidas
adios = @conversacion:despedida
 
¿Que deseas corregir?

---

08/12/2020 @
2:46
PM
3
Intents
2:46 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buenas tardes.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hola
#conversacion
Hola = @conversacion:saludo
Hola = @extractor:hola
 
Hola ¿Como estas?
Hola, mi nombre es Epimenio, me gustaría agenda una cita para medicina general, para el próximo Viernes, en horas de la tarde.
#cambiar_usuario
Hola = @conversacion:saludo
Hola = @extractor:hola
mi = @pronombres:mí
mi nombre es = @extractor:mi nombre es
nombre = @persona:yo
nombre = @persona:él
nombre = @persona:ella
nombre = @modo_tiempo:subjuntivo presente
nombre = @opción:nombre
nombre = @modo_tiempo:imperativo
nombre = @verbo:nombrar
es = @persona:él
es = @verbo:ser
es = @persona:ella
me = @pronombres:me
gustaría = @modo_tiempo:potencial
gustaría = @persona:él
gustaría = @persona:ella
gustaría = @persona:yo
gustaría = @verbo:gustar
una = @sys-number:1
cita = @persona:él
cita = @persona:tú
cita = @verbo:citar
cita = @persona:ella
cita = @modo_tiempo:indicativo presente
cita = @modo_tiempo:imperativo
para = @persona:él
para = @persona:tú
para = @persona:ella
para = @modo_tiempo:indicativo presente
para = @preposición:para
para = @modo_tiempo:imperativo
medicina = @especialidad:médica
medicina = @temática:ciencias naturales
medicina general = @opción:médica
para = @persona:él
para = @persona:tú
para = @persona:ella
para = @modo_tiempo:indicativo presente
para = @preposición:para
para = @modo_tiempo:imperativo
el = @preposición:la del
el = @pronombres:el
el próximo Viernes = @sys-date:2020-08-14
en = @preposición:en
en horas = @sys-date:2020-08-12
en horas = @sys-time:15:49:39
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
de la tarde = @sys-time:12:00:00
de la tarde = @sys-time:18:00:00
la = @pronombres:la
tarde = @persona:él
tarde = @adverbio:tarde
tarde = @modo_tiempo:subjuntivo presente
tarde = @dato:turno
tarde = @persona:yo
tarde = @verbo:tardar
tarde = @persona:ella
tarde = @modo_tiempo:imperativo
tarde = @turno:T
 
Que bueno verte de nuevo por aquí , ¿Como estas?
Bien, gracias a Dios.
#conversacion
Bien = @adverbio:bien
Bien = @conversacion:bienestar
gracias a = @preposición:gracias a
gracias a Dios = @conversacion:gracias a Dios
 
Amén.
 
¿como puedo ayudarte?
Mi tía me comentó de un proyecto que esta haciendo, como va?
#General_Greetings
Mi = @pronombres:mí
tía = @otra_persona:tío
me = @pronombres:me
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
esta = @pronombres:esta
haciendo = @modo_tiempo:gerundio
haciendo = @verbo:hacer
como = @adverbio:como
como = @modo_tiempo:indicativo presente
como = @persona:yo
como = @verbo:comer
va = @persona:él
va = @persona:ella
va = @modo_tiempo:indicativo presente
va = @verbo:ir
? = @conversacion:Pregunta



---

08/12/2020 @
2:51
PM
7
Intents
2:51 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buena tarde.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
hola
#conversacion
hola = @conversacion:saludo
hola = @extractor:hola
 
Hola ¿Qué tal ? ¿como te encuentras hoy?
mi nombre es Brayan Potosi
#cambiar_usuario
mi = @pronombres:mí
mi nombre es = @extractor:mi nombre es
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
 
¿qué tipo de cita te gustaría solicitar?
ninguna
#denegar
ninguna = @decisión:no
ninguna = @pronombres:ninguna
 
¿Qué te trae por aquí entonces?
quisiera hablar contigo
#conversacion
quisiera = @persona:él
quisiera = @persona:ella
quisiera = @persona:yo
quisiera = @verbo:querer
quisiera = @modo_tiempo:subjuntivo imperfecto
hablar = @verbo:hablar
hablar = @modo_tiempo:infinitivo
contigo = @pronombres:contigo
 
¿te puedo ayudar en algo?
si
#aceptar
si = @decisión:sí
 
¿de que tema se trata tu necesidad?
sabes quien es santiago?
#habilidades
sabes = @persona:tú
sabes = @verbo:saber
sabes = @modo_tiempo:indicativo presente
es = @persona:ella
es = @persona:él
es = @verbo:ser
santiago = @nombre:Santiago
? = @conversacion:Pregunta
 
te puedo ayudar con citas médicas y odontológicas.
no gracias
#General_Positive_Feedback
no = @decisión:no
gracias = @conversacion:agradecimiento
gracias = @conversacion:cortesia
 
¿Qué te trae por aquí entonces?
tu
#sin_especificar
tu = @persona:tú
hola?
#conversacion
hola = @conversacion:saludo
hola = @extractor:hola
? = @conversacion:Pregunta
 
Buenas, ¿como estas? <break></break>


---

08/12/2020 @
2:46
PM
8
Intents
2:46 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas tardes.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hola
#conversacion
Hola = @conversacion:saludo
Hola = @extractor:hola
 
Que bueno verte de nuevo por aquí , ¿Como estas?
bien gracias
#conversacion
bien = @adverbio:bien
bien gracias = @conversacion:bienestar
 
me alegra saber que estas bien,
 
¿te puedo ayudar en algo?
si, quisiera agendar una hora medica
#agendar_cita
si = @decisión:sí
quisiera = @persona:él
quisiera = @persona:ella
quisiera = @persona:yo
quisiera = @verbo:querer
quisiera = @modo_tiempo:subjuntivo imperfecto
una hora = @sys-time:01:00:00
hora = @dato:hora
medica = @dato:tipo_de_cita
medica = @opción:médica
medica = @especialidad:médica
 
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
 
 
tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

19 de agosto de 2020 a las 10:20 am: Cita médica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

1 de septiembre de 2020 a las 4:00 pm : Cita médica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

21 de agosto de 2020 a las 1:00 PM: Cita médica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
 
</br>¿Cuál es tu elección?
Cita médica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
#cambiar_turno
Cita = @persona:tú
Cita = @modo_tiempo:imperativo
Cita = @persona:él
Cita = @persona:ella
Cita = @verbo:citar
Cita = @modo_tiempo:indicativo presente
Cita médica = @opción:médica
médica = @especialidad:médica
el = @preposición:la del
el = @pronombres:el
el día 1 de septiembre de 2020 = @sys-date:2020-09-01
día = @dato:fecha
1 = @opción:primera
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
a = @preposición:a
a las 4:00 pm = @sys-time:16:00:00
las = @pronombres:las
4 = @opción:cuarta
pm = @turno:T
en = @preposición:en
CM GRANAHORRAR = @centro_médico:CM GRANAHORRAR
 
Vamos a consultar disponibilidad con el documento CC 1234567890 de la cita médica para el día 2020-09-01 a las 16:00:00 en CM GRANAHORRAR</br></br>
 
¿Confirmas?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada correctamente ✔️</strong></br></br> la cita médica ha sido agendada para el dia 2020-09-01 a las 16:00:00 en el centro médico CM GRANAHORRAR.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>bc26eac9104421f7191659b5baa53917</strong></br></br>
 
¿Podemos hacer algo más por ti?
cual es la dirección?
#recuperar_datos
es = @persona:ella
es = @persona:él
es = @verbo:ser
la = @pronombres:la
la dirección = @opción:direccion
? = @conversacion:Pregunta
 
¿Podemos hacer algo más por ti?
si
#aceptar
si = @decisión:sí
 
¿Que otra cosa te gustaría hacer?
adios
#despedidas
adios = @conversacion:despedida
 
chao, ¡cuidate!
 
</br> </br>Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio Platzi - MinTic ICETEX Inteligencia Artificial. </br> </br> Antes que nada ¡¡¡Gracias!!! </br> </br> En el caso de uso que se presenta el chatbot realiza operaciones CRUD sobre una base de datos cloudant la cual ha sido expuesta mediante una API personalizada mediante functions. Todo serverless, una belleza!</br> </br> Es un gran detalle que quieras interactuar con este chatbot te agradezco cualquier comentario o critica constructiva. </br> </br>
Está interesante, aunque creo que abría que filtrar algunos resultados personalizados que aparecen al inicio por ejemplo "mi nombre es miguel", "me llamo sofia" porque le quita formalidad si es que la persona no se llama así. Esa e smi critica constructiva
#cambiar_usuario
Está = @persona:él
Está = @persona:tú
Está = @persona:ella
Está = @modo_tiempo:indicativo presente
Está = @modo_tiempo:imperativo
Está = @verbo:estar
creo = @persona:yo
creo = @verbo:crear
creo = @verbo:creer
creo = @modo_tiempo:indicativo presente
abría = @persona:él
abría = @persona:yo
abría = @verbo:abrir
abría = @persona:ella
abría = @modo_tiempo:indicativo imperfecto
algunos = @pronombres:algunos
por = @preposición:por
mi = @pronombres:mí
mi nombre es = @extractor:mi nombre es
nombre = @persona:yo
nombre = @persona:él
nombre = @persona:ella
nombre = @modo_tiempo:subjuntivo presente
nombre = @opción:nombre
nombre = @modo_tiempo:imperativo
nombre = @verbo:nombrar
es = @persona:él
es = @verbo:ser
es = @persona:ella
miguel = @nombre:Miguel
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @persona:yo
llamo = @verbo:llamar
llamo = @modo_tiempo:indicativo presente
sofia = @nombre:Sofía
le = @pronombres:le
si = @decisión:sí
es = @persona:él
es = @verbo:ser
es = @persona:ella
la = @pronombres:la
no = @decisión:no
no se = @opción:indeterminado
se = @pronombres:se
llama = @persona:él
llama = @persona:tú
llama = @verbo:llamar
llama = @persona:ella
llama = @modo_tiempo:indicativo presente
llama = @modo_tiempo:imperativo
así = @adverbio:así
Esa = @pronombres:esa
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buenas tardes.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media


---

08/12/2020 @
3:40
PM
2
Intents
3:40 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buena tarde.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
hola que hace
#General_Greetings
hola = @conversacion:saludo
hola = @extractor:hola
hace = @persona:ella
hace = @verbo:hacer
hace = @persona:él
hace = @modo_tiempo:indicativo presente
 
Hola, ¿como te encuentras hoy? <break></break>
hola que hace
#General_Greetings
hola = @conversacion:saludo
hola = @extractor:hola
hace = @persona:ella
hace = @verbo:hacer
hace = @persona:él
hace = @modo_tiempo:indicativo presente
 
Hola ¿Qué hay de nuevo?
hola que hace
#General_Greetings
hola = @conversacion:saludo
hola = @extractor:hola
hace = @persona:ella
hace = @verbo:hacer
hace = @persona:él
hace = @modo_tiempo:indicativo presente
 
Hola ¿Como estas?
hola que hace
#General_Greetings
hola = @conversacion:saludo
hola = @extractor:hola
hace = @persona:ella
hace = @verbo:hacer
hace = @persona:él
hace = @modo_tiempo:indicativo presente
 
Me alegra saludarte ¿como te va?
hola que hace
#General_Greetings
hola = @conversacion:saludo
hola = @extractor:hola
hace = @persona:ella
hace = @verbo:hacer
hace = @persona:él
hace = @modo_tiempo:indicativo presente
 
Hola ¿Qué tal ? ¿como te encuentras hoy?
hola que hace
#General_Greetings
hola = @conversacion:saludo
hola = @extractor:hola
hace = @persona:ella
hace = @verbo:hacer
hace = @persona:él
hace = @modo_tiempo:indicativo presente
 
¡Hola! ¿como te va?
que eres
#habilidades
eres = @persona:tú
eres = @verbo:ser
 
Mi nombre es Santiago, estoy aquí para ayudarte con el agendamiento, modificación y eliminación de citas médicas y odontológicas.


---

08/12/2020 @
3:41
PM
1
Intents
3:41 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buenas tardes.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
#agendar_cita
Hola = @conversacion:saludo
Hola = @extractor:hola
me = @pronombres:me
gustaria = @persona:ella
gustaria = @persona:yo
gustaria = @persona:él
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
para = @persona:tú
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
para = @preposición:para
para = @modo_tiempo:imperativo
el = @preposición:la del
el = @pronombres:el
el lunes = @sys-date:2020-08-17
las = @pronombres:las
las 5 y media = @sys-time:05:30:00
 
procederemos a consultar disponbilidad con el documento CC 1234567890 para la cita odontológica, el dia 2020-08-17 a las 05:30:00</br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Esta bien?


---

08/12/2020 @
3:41
PM
8
Intents
3:41 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buenas tardes.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
#agendar_cita
Hola = @conversacion:saludo
Hola = @extractor:hola
me = @pronombres:me
gustaria = @persona:ella
gustaria = @persona:yo
gustaria = @persona:él
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
para = @persona:tú
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
para = @preposición:para
para = @modo_tiempo:imperativo
el = @preposición:la del
el = @pronombres:el
el lunes = @sys-date:2020-08-17
las = @pronombres:las
las 5 y media = @sys-time:05:30:00
 
procederemos a consultar disponbilidad con el documento CC 1234567890 para la cita odontológica, el dia 2020-08-17 a las 05:30:00</br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Esta bien?
creo que si
#aceptar
creo = @verbo:crear
creo = @verbo:creer
creo = @persona:yo
creo = @modo_tiempo:indicativo presente
si = @decisión:sí
 
{"id":"5aadb779382af134c1b59f413a90ca56","ok":true,"rev":"1-5dafeede3c2a45ff35da2da7998f5a96"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?
quiero una pizza
#aceptar
quiero = @persona:yo
quiero = @verbo:querer
quiero = @modo_tiempo:indicativo presente
una = @sys-number:1
 
¿Que otra cosa te gustaría hacer?
Quiero comer pizza
#aceptar
Quiero = @persona:yo
Quiero = @verbo:querer
Quiero = @modo_tiempo:indicativo presente
comer = @modo_tiempo:infinitivo
comer = @verbo:comer
 
¿como puedo ayudarte?
Hola, soy cba
#conversacion
Hola = @conversacion:saludo
Hola = @extractor:hola
soy = @persona:yo
soy = @verbo:ser
 
¡Hola! ¿como te va?
bieny a ti?
#corregir
bieny = @conversacion:bienestar
bieny = @adverbio:bien
a = @preposición:a
ti = @dato:tipo_documento
ti = @pronombres:ti
ti? = @tipo_documento:TI
? = @conversacion:Pregunta
 
que chevere que estes bien,
 
¿Cuál es el motivo de tu visita a este canal?
Quiero comprar una pizza
#agendar_cita
Quiero = @persona:yo
Quiero = @verbo:querer
Quiero = @modo_tiempo:indicativo presente
comprar = @modo_tiempo:infinitivo
comprar = @verbo:comprar
una = @sys-number:1
 
¿Cuál clase de cita necesitas agendar hoy ?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
Medicina General
#agendar_cita
Medicina = @especialidad:médica
Medicina = @temática:ciencias naturales
Medicina General = @opción:médica
 
¿Es para ti o es para alguien más?
 
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
 
 
tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

19 de agosto de 2020 a las 10:20 am: Cita médica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

1 de septiembre de 2020 a las 4:00 pm : Cita médica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

21 de agosto de 2020 a las 1:00 PM: Cita médica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
 
</br>Elije una antes que alguien más la reserve
Cita médica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
Irrelevant
Cita = @persona:tú
Cita = @persona:él
Cita = @persona:ella
Cita = @verbo:citar
Cita = @modo_tiempo:indicativo presente
Cita = @modo_tiempo:imperativo
Cita médica = @opción:médica
médica = @especialidad:médica
el = @preposición:la del
el = @pronombres:el
el día 19 de agosto de 2020 = @sys-date:2020-08-19
día = @dato:fecha
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
a = @preposición:a
a las 10:20 am = @sys-time:10:20:00
las = @pronombres:las
am = @turno:M
am en = @persona:ellos
en = @preposición:en
CM SUBA = @centro_médico:CM SUBA
 
procederemos a consultar disponibilidad con el documento CC 1234567890 para la cita médica, el día 2020-08-19 a las 10:20:00 en CM SUBA</br></br>
 
¿Quieres agendarla?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Corregir
#corregir
 
¿Que deseas corregir?
La hora
#corregir
La = @pronombres:la
hora = @dato:hora
 
Muy bien corregiremos la hora, dímela de nuevo por favor
 
A que hora la prefieres?
10.25
Irrelevant
10.25 = @sys-time:10:25:00
 
Por favor intenta decirme de nuevo la hora indicando si es por la mañana o la tarde.
10.25 pm
#cambiar_turno
10.25 pm = @sys-time:22:25:00
pm = @turno:T
 
procederemos a consultar disponbilidad con el documento CC 1234567890 para la cita médica, el dia 2020-08-19 a las 22:25:00 </br></br>
 
¿Esta bien?
si
#aceptar
si = @decisión:sí
 
{"id":"30d0826f4caabd6565d833163a8393c0","ok":true,"rev":"1-2f05793e5590d6702f9885a54a0d56f2"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?
no
#decisión
no = @decisión:no
 
¡Gracias por utilizar nuestro servicio de citas online vuelve pronto!
 
</br> </br>Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio Platzi - MinTic ICETEX Inteligencia Artificial. </br> </br> Antes que nada ¡¡¡Gracias!!! </br> </br> En el caso de uso que se presenta el chatbot realiza operaciones CRUD sobre una base de datos cloudant la cual ha sido expuesta mediante una API personalizada mediante functions. Todo serverless, una belleza!</br> </br> Es un gran detalle que quieras interactuar con este chatbot te agradezco cualquier comentario o critica constructiva. </br> </br>


---

08/12/2020 @
4:01
PM
2
Intents
4:01 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buena tarde.</div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
John
#cambiar_usuario
John = @nombre:John
 
 
¿Qué puedo hacer por ti el día de hoy John?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Consultar
#consultar_cita
 
Para comenzar indícanos tu número y tipo de documento
4:02 PM

---

08/12/2020 @
8:49
PM
4
Intents
8:49 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buena noche.</div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
me llamo miguel
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
miguel = @nombre:Miguel
 
 
¿En qué te puedo ayudar Miguel?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Agendar
 
Cuéntame Miguel, ¿qué tipo de cita se te ofrece?
 
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
 
 
Miguel tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

19 de agosto de 2020 a las 10:20 am: Cita médica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

1 de septiembre de 2020 a las 4:00 pm : Cita médica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

21 de agosto de 2020 a las 1:00 PM: Cita médica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
 
</br>¿Cuál es tu elección?
Cita médica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
#cambiar_turno
Cita = @persona:tú
Cita = @persona:él
Cita = @persona:ella
Cita = @verbo:citar
Cita = @modo_tiempo:indicativo presente
Cita = @modo_tiempo:imperativo
Cita médica = @opción:médica
médica = @especialidad:médica
el = @preposición:la del
el = @pronombres:el
el día 21 de agosto de 2020 = @sys-date:2020-08-21
día = @dato:fecha
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
a = @preposición:a
a las 1:00 PM = @sys-time:13:00:00
las = @pronombres:las
1 = @opción:primera
PM = @turno:T
en = @preposición:en
CM PORTAL NORTE = @centro_médico:CM PORTAL NORTE
NORTE = @zona:Norte
 
Vamos a consultar disponibilidad con el documento CC 1234567890 de la cita médica Miguel para el día 2020-08-21 a las 13:00:00 en CM PORTAL NORTE</br></br>
 
¿La reservamos?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada exitosamente ✔️</strong></br></br>La cita médica ha sido agendada para el dia 2020-08-21 a las 13:00:00 en el centro médico CM PORTAL NORTE Miguel.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>db0a6da57a327fc7f7a516fc4418aa5d</strong></br></br>
 
¿Podemos hacer algo más por ti?
no
#decisión
no = @decisión:no
 
chao, ¡cuidate!
 
</br> </br>Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio Platzi - MinTic ICETEX Inteligencia Artificial. </br> </br> Antes que nada ¡¡¡Gracias!!! </br> </br> En el caso de uso que se presenta el chatbot realiza operaciones CRUD sobre una base de datos cloudant la cual ha sido expuesta mediante una API personalizada mediante functions. Todo serverless, una belleza!</br> </br> Es un gran detalle que quieras interactuar con este chatbot te agradezco cualquier comentario o critica constructiva. </br> </br>


---

08/13/2020 @
10:33
AM
3
Intents
10:33 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buen día.</div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
hola
#conversacion
hola = @conversacion:saludo
hola = @extractor:hola
 
Que bueno verte de nuevo por aquí , ¿Como estas?
Muy bien
#General_Positive_Feedback
Muy = @adverbio:muy
Muy bien = @conversacion:bienestar
bien = @adverbio:bien
 
gracias por el comentario
y tu?
#conversacion
tu = @persona:tú
? = @conversacion:Pregunta
 
¿te puedo ayudar en algo?
me podria indicar el precio de la cita
#cambiar_tipo_de_cita
me = @pronombres:me
podria = @persona:yo
podria = @persona:ella
podria = @persona:él
el = @preposición:la del
el = @pronombres:el
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
la = @pronombres:la
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
10:34 AM

---

08/13/2020 @
10:33
AM
3
Intents
10:33 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buen día.</div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
hola
#conversacion
hola = @conversacion:saludo
hola = @extractor:hola
 
Que bueno verte de nuevo por aquí , ¿Como estas?
Muy bien
#General_Positive_Feedback
Muy = @adverbio:muy
Muy bien = @conversacion:bienestar
bien = @adverbio:bien
 
gracias por el comentario
y tu?
#conversacion
tu = @persona:tú
? = @conversacion:Pregunta
 
¿te puedo ayudar en algo?
me podria indicar el precio de la cita
#cambiar_tipo_de_cita
me = @pronombres:me
podria = @persona:yo
podria = @persona:ella
podria = @persona:él
el = @preposición:la del
el = @pronombres:el
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
la = @pronombres:la
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente


---

08/13/2020 @
10:41
AM
3
Intents
10:41 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buen día.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
me llamo miguel
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
miguel = @nombre:Miguel
 
 
Cuéntame Miguel, ¿qué se te ofrece?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Agendar
#agendar_cita
 
¿Cuál clase de cita necesitas agendar hoy Miguel?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
Odontológia Básica
#agendar_cita
Odontológia = @opción:odontológica
Odontológia = @especialidad:odontológica
 
¿La cita odontológica es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
Para mi mama
#cambiar_usuario
Para = @persona:tú
Para = @preposición:para
Para = @modo_tiempo:imperativo
Para = @persona:él
Para = @persona:ella
Para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
mi mama = @otra_persona:madre
mama = @genero:femenino
mama = @temática:madre
 
Por favor indicame el número de documento de tu mi mama
6778987
Irrelevant
677898 = @input_patterns:PEP
6778987 = @sys-number:6778987
 
 
Miguel tenemos estas opciones disponibles para la cita odontológica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

19 de agosto de 2020 a las 10:20 am: Cita odontológica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

1 de septiembre de 2020 a las 4:00 pm : Cita odontológica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

21 de agosto de 2020 a las 1:00 PM: Cita odontológica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
 
</br>¿Cuál es tu elección?


---

08/13/2020 @
8:52
PM
5
Intents
8:52 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas noches.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Me llamo oscar
#cambiar_usuario
Me = @pronombres:me
Me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
oscar = @temática:oscar
 
No soy muy bueno con los nombres, por eso prefiero asegurarme antes de empezar. </br></br>¿Te llamás E llamo oscar?
si
#aceptar
si = @decisión:sí
 
¿Como podemos ayudarte E llamo oscar?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
agendar
#agendar_cita
 
¿Cuál clase de cita necesitas agendar hoy E llamo oscar?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
odontologia
#agendar_cita
odontologia = @opción:odontológica
odontologia = @dato:tipo_de_cita
odontologia = @especialidad:odontológica
 
¿La cita odontológica es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
mi
#recuperar_datos
mi = @pronombres:mí
 
 
E llamo oscar tenemos estas opciones disponibles para la cita odontológica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

19 de agosto de 2020 a las 10:20 am: Cita odontológica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

1 de septiembre de 2020 a las 4:00 pm : Cita odontológica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

21 de agosto de 2020 a las 1:00 PM: Cita odontológica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
 
</br>¿Alguna de estas opciones te sirve?
no
#decisión
no = @decisión:no
 
¿Que deseas corregir?


---

08/13/2020 @
8:52
PM
5
Intents
8:52 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas noches.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Me llamo oscar
#cambiar_usuario
Me = @pronombres:me
Me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
oscar = @temática:oscar
 
No soy muy bueno con los nombres, por eso prefiero asegurarme antes de empezar. </br></br>¿Te llamás E llamo oscar?
si
#aceptar
si = @decisión:sí
 
¿Como podemos ayudarte E llamo oscar?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
agendar
#agendar_cita
 
¿Cuál clase de cita necesitas agendar hoy E llamo oscar?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
odontologia
#agendar_cita
odontologia = @opción:odontológica
odontologia = @dato:tipo_de_cita
odontologia = @especialidad:odontológica
 
¿La cita odontológica es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
mi
#recuperar_datos
mi = @pronombres:mí
 
 
E llamo oscar tenemos estas opciones disponibles para la cita odontológica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

19 de agosto de 2020 a las 10:20 am: Cita odontológica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

1 de septiembre de 2020 a las 4:00 pm : Cita odontológica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

21 de agosto de 2020 a las 1:00 PM: Cita odontológica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
 
</br>¿Alguna de estas opciones te sirve?
no
#decisión
no = @decisión:no
 
¿Que deseas corregir?


---

08/14/2020 @
2:16
AM
6
Intents
2:16 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">De día, de noche e incluso de madrugada estamos aquí para servirte. </div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
hola me llamo joselito
#cambiar_usuario
hola = @conversacion:saludo
hola me llamo = @extractor:hola me llamo
me = @pronombres:me
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
 
Antes de comenzar permiteme confirmar si he entendido bien tu nombre </br></br>¿Tú nombre es Joselito?
aja
#conversacion
aja = @decisión:sí
 
¿Qué puedo hacer por ti el día de hoy Joselito?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
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
 
¿Es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
es para mi tia josefa
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
cc 12345677889
#corregir
cc = @tipo_documento:CC
123456 = @input_patterns:PEP
1234567788 = @input_patterns:CC
12345677889 = @sys-number:12345677889
 
 
Joselito tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

19 de agosto de 2020 a las 10:20 am: Cita médica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

1 de septiembre de 2020 a las 4:00 pm : Cita médica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

21 de agosto de 2020 a las 1:00 PM: Cita médica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
 
</br>¿Te sirve alguna de las anteriores o quieres probar diciéndome una fecha y hora?
la del 1 de sep
#decisión
la = @pronombres:la
la del = @preposición:la del
1 = @opción:primera
1 = @sys-number:1
de = @preposición:de
de = @persona:ella
de = @verbo:dar
de = @persona:él
 
Has elegido la segunda opción:
 
Joselito tu cita médica quedará reservada para el día 1 de septiembre de 2020 a las 4:00 pm en el centro médico CM SUBA, con el documento CC 12345677889. </br></br>Recuerda que debes llegar 30 minutos antes y pasar por el punto ágil para facturar tu cuota moderadora.</br></br>Si no puedes ir a tu cita, cancela con 3 horas de anticipación y permite que alguien la tome por ti.</br></br>
 
¿Esta bien?
seh
#aceptar
 
{"id":"c1c61cfced2085f80fa35d9d024322f3","ok":true,"rev":"1-d26879d787e9f90d7512f3d64192662c"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?


---

08/14/2020 @
2:24
AM
6
Intents
2:24 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Sin importar la hora, estamos aquí para ti. </div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
hola me llamo joselito
#cambiar_usuario
hola = @conversacion:saludo
hola me llamo = @extractor:hola me llamo
me = @pronombres:me
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
 
Antes de comenzar permiteme confirmar si he entendido bien tu nombre </br></br>¿Tú nombre es Joselito?
aja
#conversacion
aja = @decisión:sí
 
¿Cuál es el motivo de tú visita el día de hoy Joselito?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
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
 
¿Es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
es para mi abuelita
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
abuelita = @otra_persona:abuela
 
Por favor indicame el número de documento de tu abuelita
cc 9283649236492
#corregir
cc = @tipo_documento:CC
928364 = @input_patterns:PEP
9283649236 = @input_patterns:CC
9283649236492 = @input_patterns:CC
9283649236492 = @sys-number:9283649236492
923649 = @input_patterns:PEP
 
 
Joselito tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

19 de agosto de 2020 a las 10:20 am: Cita médica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

1 de septiembre de 2020 a las 4:00 pm : Cita médica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

21 de agosto de 2020 a las 1:00 PM: Cita médica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
 
</br>Elije una antes que alguien más la reserve
la del 1 de sep
#decisión
la = @pronombres:la
la del = @preposición:la del
1 = @opción:primera
1 = @sys-number:1
de = @preposición:de
de = @persona:ella
de = @verbo:dar
de = @persona:él
 
Has elegido la segunda opción:
 
Joselito tu cita médica quedará reservada para el día 1 de septiembre de 2020 a las 4:00 pm en el centro médico CM SUBA, con el documento CC 9283649236492. </br></br>Recuerda que debes llegar 30 minutos antes y pasar por el punto ágil para facturar tu cuota moderadora.</br></br>Si no puedes ir a tu cita, cancela con 3 horas de anticipación y permite que alguien la tome por ti.</br></br>
 
¿Esta bien?
perfecto
#General_Positive_Feedback
2:26 AM

---

08/14/2020 @
2:29
AM
6
Intents
2:29 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Sin importar la hora, estamos aquí para ti. </div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
hola
#conversacion
hola = @conversacion:saludo
hola = @extractor:hola
 
Hola ¿Como estas?
bien y tu?
#conversacion
bien = @conversacion:bienestar
bien = @adverbio:bien
tu = @persona:tú
? = @conversacion:Pregunta
 
me alegra saber que estas bien,
 
¿en que te puedo colaborar?
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
 
¿Qué tipo de cita deseas agendar ?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
con el odontologo
#agendar_cita
con = @preposición:con
el = @preposición:la del
el = @pronombres:el
odontologo = @opción:odontológica
 
¿La cita odontológica es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
para mi abuelita
#cambiar_usuario
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
abuelita = @otra_persona:abuela
 
Por favor indicame el número de documento de tu abuelita
cc 2837648723648732
#corregir
cc = @tipo_documento:CC
283764 = @input_patterns:PEP
2837648723 = @input_patterns:CC
2837648723648 = @input_patterns:CC
2837648723648732 = @sys-number:2837648723648732
872364 = @input_patterns:PEP
 
 
tenemos estas opciones disponibles para la cita odontológica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

19 de agosto de 2020 a las 10:20 am: Cita odontológica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

1 de septiembre de 2020 a las 4:00 pm : Cita odontológica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

21 de agosto de 2020 a las 1:00 PM: Cita odontológica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
 
</br>¿Te sirve alguna de las anteriores o quieres probar diciéndome una fecha y hora?
la del 1 de sep
#decisión
la = @pronombres:la
la del = @preposición:la del
1 = @opción:primera
1 = @sys-number:1
de = @preposición:de
de = @persona:ella
de = @verbo:dar
de = @persona:él
 
Has elegido la segunda opción:
 
tu cita odontológica quedará reservada para el día 1 de septiembre de 2020 a las 4:00 pm en el centro médico CM SUBA, con el documento CC 2837648723648732. </br></br>Recuerda que debes llegar 30 minutos antes y pasar por el punto ágil para facturar tu cuota moderadora.</br></br>Si no puedes ir a tu cita, cancela con 3 horas de anticipación y permite que alguien la tome por ti.</br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Esta bien?
ok
#aceptar
ok = @decisión:sí
 
{"id":"f75552bd01e7b3ea21769e6e4ef41543","ok":true,"rev":"1-f2a9d84a5f15291364901225866789b7"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?
si
#aceptar
si = @decisión:sí
 
¿Que otra cosa te gustaría hacer?
deseo agfendar una cita medica
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
 
¿Es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
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
 
 
tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

19 de agosto de 2020 a las 10:20 am: Cita médica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

1 de septiembre de 2020 a las 4:00 pm : Cita médica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

21 de agosto de 2020 a las 1:00 PM: Cita médica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
 
</br>Elije una antes que alguien más la reserve
la primera
#decisión
la = @pronombres:la
la primera = @opción:primera
 
Has elegido la primera opción:
 
tu cita médica quedará reservada para el día 19 de agosto de 2020 a las 10:20 am en el centro médico CM SUBA, con el documento CC 2837648723648732. </br></br>Recuerda que debes llegar 30 minutos antes y pasar por el punto ágil para facturar tu cuota moderadora.</br></br>Si no puedes ir a tu cita, cancela con 3 horas de anticipación y permite que alguien la tome por ti.</br></br>
 
¿Esta bien?
correcto
#aceptar
correcto = @decisión:sí
 
{"id":"3ab2c8dc1d2943bac67733f4fbf16722","ok":true,"rev":"1-9f8649230e7273dd8a04b50504b50d16"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?
2:33 AM

---


08/14/2020 @
2:34
AM
2
Intents
2:34 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Si tu trasnochas, aquí nos trasnochamos contigo. </div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
¿Como te llamas?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
#agendar_cita
Hola = @conversacion:saludo
Hola = @extractor:hola
me = @pronombres:me
gustaria = @persona:ella
gustaria = @persona:yo
gustaria = @persona:él
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
para = @persona:tú
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
para = @preposición:para
para = @modo_tiempo:imperativo
el = @preposición:la del
el = @pronombres:el
el lunes = @sys-date:2020-08-17
las = @pronombres:las
las 5 y media = @sys-time:05:30:00
 
procederemos a consultar disponbilidad con el documento CC 1234567890 para la cita odontológica, el dia 2020-08-17 a las 05:30:00</br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Esta bien?
ok
#aceptar
ok = @decisión:sí
 
{"id":"95632b6e21aba5eae85025b480fb6d13","ok":true,"rev":"1-c5f71fee5003347fbc545a0bbc29e5ca"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?


---

































