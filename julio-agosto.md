

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
## hugo
#cambiar_usuario
hugo = @nombre:Hugo
 
 
¿Cuál es el motivo de tú visita el día de hoy Hugo?
## agendar
#agendar_cita
 
Cuéntame Hugo, ¿qué tipo de cita se te ofrece?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
## 1
#decisión
1 = @sys-number:1
 
¿Qué tipo de cita deseas agendar Hugo?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
## Medicina General
#agendar_cita
Medicina = @especialidad:médica
Medicina = @temática:ciencias naturales
Medicina General = @opción:médica
 
¿La cita médica es para ti o es para alguien más?
## si
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
## me llamo hugo
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
hugo = @nombre:Hugo
 
 
¿Qué puedo hacer por ti el día de hoy Hugo?
## agendar
#agendar_cita
 
¿Cuál clase de cita necesitas agendar hoy Hugo?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
## Medicina General
#agendar_cita
Medicina = @especialidad:médica
Medicina = @temática:ciencias naturales
Medicina General = @opción:médica
 
¿La cita médica es para ti o es para alguien más?
## para mi
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
## Sí
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
## hugo
#cambiar_usuario
hugo = @nombre:Hugo
 
 
¿En qué te puedo ayudar Hugo?
## me duele un incisivo
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
## jose
#cambiar_usuario
jose = @nombre:José
 
 
¿Como podemos ayudarte José?
## me duele una muela
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
## ok
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
## jose
#cambiar_usuario
jose = @nombre:José
 
 
¿Como podemos ayudarte José?
## me duele una muela
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
## ok
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
## me llamo jose
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
jose = @nombre:José
 
 
Cuéntame José, ¿qué se te ofrece?
## agendar
#agendar_cita
 
Cuéntame José, ¿qué tipo de cita se te ofrece?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
## Medicina General
#agendar_cita
Medicina = @especialidad:médica
Medicina = @temática:ciencias naturales
Medicina General = @opción:médica
 
¿La cita médica es para ti o es para alguien más?
## para mi
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
## 15 de julio de 2018 a las 10:20 am
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
## Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
{"id":"fd4609b30179d8e8b571a0e3bac0e7d6","ok":true,"rev":"1-ef0f347baebfd2edfeefbdb294705125"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?
## me duele una muela
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
## jose
#cambiar_usuario
jose = @nombre:José
 
 
¿Como podemos ayudarte José?
## me duele una muela
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
## ok
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
## me llamo jose
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
jose = @nombre:José
 
 
Cuéntame José, ¿qué se te ofrece?
## agendar
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
## para mi
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
## Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
{"id":"fd4609b30179d8e8b571a0e3bac0e7d6","ok":true,"rev":"1-ef0f347baebfd2edfeefbdb294705125"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?
## me duele una muela
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
## jose
#cambiar_usuario
jose = @nombre:José
 
 
¿Como podemos ayudarte José?
## agendar
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
## Es para mí
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
## jose
#cambiar_usuario
jose = @nombre:José
 
 
¿Como podemos ayudarte José?
## agendar
#agendar_cita
 
¿Qué tipo de cita deseas agendar José?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
## Medicina General
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
## hugo
#cambiar_usuario
hugo = @nombre:Hugo
 
 
Cuéntame Hugo, ¿qué se te ofrece?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
## Consultar
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
## hugo
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
## cc 546456
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
## hugo
#cambiar_usuario
hugo = @nombre:Hugo
 
 
Cuéntame Hugo, ¿qué se te ofrece?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
## Eliminar
#eliminar_cita
 
Para comenzar indícanos tu número y tipo de documento
## cc 435434
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
## me llamo miguel
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
## Agendar
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
## Es para mí
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
## Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada correctamente ✔️</strong></br></br>Miguel la cita odontológica ha sido agendada para el dia 2018-07-15 a las 10:20:00 en el centro médico CM SUBA.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 31234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>70df5ec470b023d704c078bdb66056d5</strong></br></br>
 
¿Podemos hacer algo más por ti?
## Tal vez
#conversacion
Tal = @adverbio:tal
 
¿Cuál es el motivo de tu visita a este canal?
## :D
#corregir
:D = @emojis:lagrimas de felicidad
 
Que deseas que corrijamos?
## Nada, gracias
#General_Positive_Feedback
Nada = @decisión:no
Nada = @adverbio:nada
Nada = @pronombres:nada
gracias = @conversacion:cortesia
gracias = @conversacion:agradecimiento
 
Que deseas corregir?
## Nada
#denegar
Nada = @decisión:no
Nada = @adverbio:nada
Nada = @pronombres:nada
 
¿Qué te trae por aquí entonces?
## Solo soy un espectador jeje
#conversacion
Solo = @extractor:solo
Solo = @adverbio:solo
soy = @persona:yo
soy = @verbo:ser
jeje = @persona:yo
jeje = @persona:él
jeje = @persona:ella
 
¿de que tema se trata tu necesidad?
## Tengo Covid 19
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
## me llamo miguel
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
## Agendar
 
Cuéntame Miguel, ¿qué tipo de cita se te ofrece?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
## Odontológia Básica
#agendar_cita
Odontológia = @opción:odontológica
Odontológia = @especialidad:odontológica
 
¿La cita odontológica es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
## Es para mi tía
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
## cc 111
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
## Cita odontológica el día 15 de julio de 2018 a las 10:20 am en CM SUBA
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
## Sí
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
## Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
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
## no
#decisión
no = @decisión:no
 
¿Que deseas corregir?
## la identificacion
#corregir
la = @pronombres:la
identificacion = @tramite:Identificacion
 
Por favor indícame, ¿que hay que corregir?
## la cedula
#corregir
la = @pronombres:la
cedula = @tipo_documento:CC
cedula = @dato:numero_documento
 
muy bien por favor dime de nuevo el numero y tipo de documento para realizar la corrección.
## ti 856786
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
## Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
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
## no
#decisión
no = @decisión:no
 
¿Que deseas corregir?
## la identificacion
#corregir
la = @pronombres:la
identificacion = @tramite:Identificacion
identificacion = @dato:numero_documento
 
muy bien por favor dime de nuevo el numero y tipo de documento para realizar la corrección.
## pep 93454754
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
## 3
#decisión
3 = @opción:tercera
3 = @sys-number:3
 
Has elegido la tercera opción:
 
tu cita odontológica quedará reservada para el día 26 de julio de 2018 a las 1:00 PM en el centro médico , con el documento PEP 93454754. </br></br>Recuerda que debes llegar 30 minutos antes y pasar por el punto ágil para facturar tu cuota moderadora.</br></br>Si no puedes ir a tu cita, cancela con 3 horas de anticipación y permite que alguien la tome por ti.</br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Esta bien?
## si
#aceptar
si = @decisión:sí
 
{"id":"d8cf86b42bc7ba6a6234efa0c2ae90b9","ok":true,"rev":"1-60099619550268c4f2621b1319f65046"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?
## si
#aceptar
si = @decisión:sí
 
¿Que otra cosa te gustaría hacer?
## agendar
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
## Es para mi tía
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
## ti 856786
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
## Cita médica el día 15 de julio de 2018 a las 4:00 pm en CM GRANAHORRAR
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
## Hola
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
## Hola
#conversacion
Hola = @conversacion:saludo
Hola = @extractor:hola
 
Buenas, ¿como estas? <break></break>
## bien
#conversacion
bien = @conversacion:bienestar
bien = @adverbio:bien
 
maravilloso,
 
¿como puedo ayudarte?
## cómo te llamas?
#habilidades
te = @pronombres:te
llamas = @verbo:llamar
llamas = @persona:tú
llamas = @modo_tiempo:indicativo presente
? = @conversacion:Pregunta
 
Mi nombre es Santiago, estoy aquí para ayudarte con el agendamiento, modificación y eliminación de citas médicas y odontológicas.
## citas en platzi?
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
## Hola
#conversacion
Hola = @conversacion:saludo
Hola = @extractor:hola
 
Me alegra saludarte ¿como te va?
## Bien gracias
#conversacion
Bien = @adverbio:bien
Bien gracias = @conversacion:bienestar
 
maravilloso,
 
¿de que tema se trata tu necesidad?
## Necesito una cita medica con neurología
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
## Para mi mama
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
 
## Por favor indicame el número de documento de tu mi mama
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
## Cita médica el día 26 de julio de 2018 a las 1:00 PM en CM PORTAL NORTE
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
## Sí
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
## Cita médica el día 15 de julio de 2018 a las 10:20 am en CM SUBA
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
## Sí
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
## Cita médica el día 15 de julio de 2018 a las 10:20 am en CM SUBA
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
## Sí
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


08/14/2020 @
2:35
AM
5
Intents
2:35 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Sin importar la hora, estamos aquí para ti. </div>
 
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
 
 
Cuéntame Miguel, ¿qué se te ofrece?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Agendar
#agendar_cita
 
Cuéntame Miguel, ¿qué tipo de cita se te ofrece?
 
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
cc 3165694
#corregir
cc = @tipo_documento:CC
316569 = @input_patterns:PEP
3165694 = @sys-number:3165694
 
 
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
 
</br>¿Alguna de estas opciones te sirve?
la tre
Irrelevant
la = @pronombres:la
la tre = @opción:tercera
 
¿Cuál es tu elección?
la tres
#decisión
la = @pronombres:la
la tres = @opción:tercera
la tres = @sys-time:03:00:00
 
¿En que fecha?

---


08/14/2020 @
2:36
AM
2
Intents
2:36 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Si tu trasnochas, aquí nos trasnochamos contigo. </div>
 
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
 
Buenas ¿Como va todo? <break></break>
bien y tu¿?
#conversacion
bien = @conversacion:bienestar
bien = @adverbio:bien
tu = @persona:tú
? = @conversacion:Pregunta
 
que chevere que estes bien,
 
¿qué tipo de cita te gustaría solicitar?
deseo agendar una cita medica para mi abuelita el dia martes
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
para = @persona:tú
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
para = @preposición:para
para = @modo_tiempo:imperativo
mi = @pronombres:mí
abuelita = @otra_persona:abuela
el = @preposición:la del
el = @pronombres:el
dia = @dato:fecha
martes = @sys-date:2020-08-18
 
¿La cita médica es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María


---

08/14/2020 @
2:37
AM
4
Intents
2:37 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">De día, de noche e incluso de madrugada estamos aquí para servirte. </div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
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
seh
#aceptar
seh = @decisión:sí
 
¿En qué te puedo ayudar Cumbia?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
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
 
Cuéntame Cumbia, ¿qué tipo de cita se te ofrece?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
con el matasanos
Irrelevant
con = @preposición:con
el = @preposición:la del
el = @pronombres:el
 
Cuéntame, ¿que se te ofrece? </br> </br>1. Medicina general, </br>2. Odontología Básica.


---

08/14/2020 @
2:41
AM
5
Intents
2:41 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Si tu trasnochas, aquí nos trasnochamos contigo. </div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
hola, me llamo jose
#cambiar_usuario
hola = @conversacion:saludo
hola = @extractor:hola
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
jose = @nombre:José
 
 
¿En qué te puedo ayudar José?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
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
 
¿Cuál clase de cita necesitas agendar hoy José?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
con el medico
#corregir
con = @preposición:con
el = @preposición:la del
el = @pronombres:el
medico = @especialidad:médica
medico = @opción:médica
 
¿La cita médica es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
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
 
Por favor indicame el número de documento de tu papa
cc 123456789
#corregir
cc = @tipo_documento:CC
123456 = @input_patterns:PEP
123456789 = @sys-number:123456789
 
 
José tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
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
la del 21 de ago
#decisión
la = @pronombres:la
la del = @preposición:la del
21 = @sys-number:21
de = @preposición:de
de = @persona:ella
de = @verbo:dar
de = @persona:él
 
Has elegido la tercera opción:
 
José tu cita médica quedará reservada para el día 21 de agosto de 2020 a las 1:00 PM en el centro médico CM SUBA, con el documento CC 123456789. </br></br>Recuerda que debes llegar 30 minutos antes y pasar por el punto ágil para facturar tu cuota moderadora.</br></br>Si no puedes ir a tu cita, cancela con 3 horas de anticipación y permite que alguien la tome por ti.</br></br>
 
¿Esta bien?
ok
#aceptar
ok = @decisión:sí
 
{"id":"14165be71e8d3581da2e1036cbb4ac8b","ok":true,"rev":"1-6f1aaf25ef9678e1d49df7a0308605a7"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?
2:43 AM

---

08/14/2020 @
2:43
AM
6
Intents
2:43 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Si tu trasnochas, aquí nos trasnochamos contigo. </div>
 
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
 
Buenas, ¿como estas? <break></break>
bien y tu?
#conversacion
bien = @conversacion:bienestar
bien = @adverbio:bien
tu = @persona:tú
? = @conversacion:Pregunta
 
maravilloso,
 
¿de que tema se trata tu necesidad?
deseo ina cita
#agendar_cita
deseo = @verbo:desear
deseo = @persona:yo
deseo = @modo_tiempo:indicativo presente
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
 
Cuéntame , ¿qué tipo de cita se te ofrece?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
con el matasanos
Irrelevant
con = @preposición:con
el = @preposición:la del
el = @pronombres:el
matasanos = @opción:médica
 
¿Es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
para maria
#cambiar_usuario
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
maria = @nombre:María
 
 
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
la de la 1 pm
#cambiar_turno
la = @pronombres:la
de = @preposición:de
de = @persona:ella
de = @verbo:dar
de = @persona:él
de la 1 pm = @sys-time:13:00:00
la = @pronombres:la
1 = @opción:primera
pm = @turno:T
 
¿En que fecha?
el 21 de ago
#corregir
el = @preposición:la del
el = @pronombres:el
21 = @sys-number:21
de = @preposición:de
de = @persona:ella
de = @verbo:dar
de = @persona:él
 
¿En que fecha?



---

08/14/2020 @
2:46
AM
4
Intents
2:46 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Sin importar la hora, estamos aquí para ti. </div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
hola platzibot vengo a agendar una cita medica
#agendar_cita
hola = @conversacion:saludo
hola = @extractor:hola
vengo = @persona:yo
vengo = @verbo:venir
vengo = @modo_tiempo:indicativo presente
a = @preposición:a
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
 
</br>¿Cuál es tu elección?
la del 19
#decisión
la = @pronombres:la
la del = @preposición:la del
19 = @sys-number:19
 
Has elegido la primera opción:
 
tu cita médica quedará reservada para el día 19 de agosto de 2020 a las 10:20 am en el centro médico CM SUBA, con el documento CC 1234567890. </br></br>Recuerda que debes llegar 30 minutos antes y pasar por el punto ágil para facturar tu cuota moderadora.</br></br>Si no puedes ir a tu cita, cancela con 3 horas de anticipación y permite que alguien la tome por ti.</br></br>
 
¿Esta bien?
si
#aceptar
si = @decisión:sí
 
{"id":"14165be71e8d3581da2e1036cbb4ec2c","ok":true,"rev":"1-b274a3b86c716e4e98f4d836924fe8c8"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?


---

08/14/2020 @
2:47
AM
4
Intents
2:47 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">De día, de noche e incluso de madrugada estamos aquí para servirte. </div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
mi nombre es sofia
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
sofia = @nombre:Sofía
 
 
¿Cuál es el motivo de tú visita el día de hoy Sofía?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
vengo a agendar una cita con el odontologo
#agendar_cita
vengo = @persona:yo
vengo = @verbo:venir
vengo = @modo_tiempo:indicativo presente
a = @preposición:a
una = @sys-number:1
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
con = @preposición:con
el = @preposición:la del
el = @pronombres:el
odontologo = @opción:odontológica
 
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
 
 
Sofía tenemos estas opciones disponibles para la cita odontológica que estas solicitando:</br></br>
 
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
la del 21
#decisión
la = @pronombres:la
la del = @preposición:la del
21 = @sys-number:21
 
Has elegido la tercera opción:
 
Sofía tu cita odontológica quedará reservada para el día 21 de agosto de 2020 a las 1:00 PM en el centro médico CM SUBA, con el documento CC 1234567890. </br></br>Recuerda que debes llegar 30 minutos antes y pasar por el punto ágil para facturar tu cuota moderadora.</br></br>Si no puedes ir a tu cita, cancela con 3 horas de anticipación y permite que alguien la tome por ti.</br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Esta bien?
si
#aceptar
si = @decisión:sí
 
{"id":"8b1f00076b8afe812fccd5e0d8ee125b","ok":true,"rev":"1-d0bf40955f362832b07dcd5dc67b2755"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?


---

08/14/2020 @
2:48
AM
4
Intents
2:48 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">De día, de noche e incluso de madrugada estamos aquí para servirte. </div>
 
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
 
 
¿Como podemos ayudarte Miguel?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Agendar
#agendar_cita
 
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
 
</br>¿Alguna de estas opciones te sirve?
Cita médica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
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
 
¿Me autorizas a reservarla?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada exitosamente ✔️</strong></br></br>La cita médica ha sido agendada para el dia 2020-08-21 a las 13:00:00 en el centro médico CM PORTAL NORTE Miguel.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>48ee446f96281e894d0afb196ef9756f</strong></br></br>
 
¿Podemos hacer algo más por ti?


---

08/14/2020 @
2:48
AM
4
Intents
2:48 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">De día, de noche e incluso de madrugada estamos aquí para servirte. </div>
 
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
 
 
¿Como podemos ayudarte Miguel?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Agendar
#agendar_cita
 
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
 
</br>¿Alguna de estas opciones te sirve?
Cita médica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
 
Vamos a consultar disponibilidad con el documento CC 1234567890 de la cita médica Miguel para el día 2020-08-21 a las 13:00:00 en CM PORTAL NORTE</br></br>
 
¿Me autorizas a reservarla?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada exitosamente ✔️</strong></br></br>La cita médica ha sido agendada para el dia 2020-08-21 a las 13:00:00 en el centro médico CM PORTAL NORTE Miguel.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>48ee446f96281e894d0afb196ef9756f</strong></br></br>
 
¿Podemos hacer algo más por ti?
2:48 AM

---

08/14/2020 @
2:49
AM
6
Intents
2:49 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Aun de madrugada estamos aquí para ti. </div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
hola soy miguel
#cambiar_usuario
hola = @conversacion:saludo
hola = @extractor:hola
soy = @persona:yo
soy = @verbo:ser
miguel = @nombre:Miguel
 
 
¿Cuál es el motivo de tú visita el día de hoy Miguel?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
deseo agendar
 
¿Qué tipo de cita deseas agendar Miguel?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
con el medico
#corregir
con = @preposición:con
el = @preposición:la del
el = @pronombres:el
medico = @especialidad:médica
medico = @opción:médica
 
¿La cita médica es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
para mi solito
#cambiar_usuario
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
 
 
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
 
Vamos a consultar disponibilidad con el documento CC 1234567890 de la cita médica Miguel para el día 2020-08-19 a las 10:20:00 en CM SUBA</br></br>
 
¿Quieres agendarla?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada con éxito ✔️</strong></br></br>Miguel la cita médica ha sido agendada para el dia 2020-08-19 a las 10:20:00 en el centro médico CM SUBA.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>14165be71e8d3581da2e1036cbb50f6c</strong></br></br>
 
¿Podemos hacer algo más por ti?
si
#aceptar
si = @decisión:sí
 
¿Que otra cosa te gustaría hacer?
deseo agendar una cita con el odontologio
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
con = @preposición:con
el = @preposición:la del
el = @pronombres:el
odontologio = @opción:odontológica
 
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
ti 98263962394
#corregir
ti = @tipo_documento:TI
ti = @dato:tipo_documento
ti = @pronombres:ti
982639 = @input_patterns:PEP
9826396239 = @input_patterns:CC
98263962394 = @sys-number:98263962394
 
 
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
 
</br>¿Te sirve alguna de las anteriores o quieres probar diciéndome una fecha y hora?
la del 21
#decisión
la = @pronombres:la
la del = @preposición:la del
21 = @sys-number:21
 
Has elegido la tercera opción:
 
Miguel tu cita odontológica quedará reservada para el día 21 de agosto de 2020 a las 1:00 PM en el centro médico CM SUBA, con el documento TI 98263962394. </br></br>Recuerda que debes llegar 30 minutos antes y pasar por el punto ágil para facturar tu cuota moderadora.</br></br>Si no puedes ir a tu cita, cancela con 3 horas de anticipación y permite que alguien la tome por ti.</br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Esta bien?
ok
#aceptar
ok = @decisión:sí
 
{"id":"0eb9f7fafdf9cfe66229cdeaa5043926","ok":true,"rev":"1-c759c8ef6ced346c843ff446174a021d"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?


---

08/14/2020 @
2:52
AM
1
Intents
2:52 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">De día, de noche e incluso de madrugada estamos aquí para servirte. </div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
hola me llamo erasmo baudilio
#cambiar_usuario
hola = @conversacion:saludo
hola me llamo = @extractor:hola me llamo
me = @pronombres:me
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
 
Antes de comenzar permiteme confirmar si he entendido bien tu nombre </br></br>¿Tú nombre es Erasmo baudilio?


---

08/14/2020 @
2:53
AM
4
Intents
2:53 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">De día, de noche e incluso de madrugada estamos aquí para servirte. </div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
mi nombre es erasmo
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
 
No soy muy bueno con los nombres, por eso prefiero asegurarme antes de empezar. </br></br>¿Te llamás Erasmo?
si
#aceptar
si = @decisión:sí
 
¿Cuál es el motivo de tú visita el día de hoy Erasmo?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
agendaqr una cita medica
#agendar_cita
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
 
 
Erasmo tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
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
la 1
#decisión
la = @pronombres:la
la 1 = @sys-time:01:00:00
1 = @opción:primera
 
¿En que fecha?


---

08/14/2020 @
2:53
AM
2
Intents
2:53 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">De día, de noche e incluso de madrugada estamos aquí para servirte. </div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
hola platzibot no tengo mucho tiempo asi que ire al grano, necesito agendar una cita odontologica para el proximo viernes
#agendar_cita
hola = @conversacion:saludo
hola = @extractor:hola
no tengo = @decisión:impedido
tengo = @persona:yo
tengo = @modo_tiempo:indicativo presente
tengo = @verbo:tener
mucho = @pronombres:mucho
mucho = @adverbio:mucho
necesito = @persona:yo
necesito = @modo_tiempo:indicativo presente
necesito = @verbo:necesitar
una = @sys-number:1
cita = @persona:él
cita = @persona:tú
cita = @verbo:citar
cita = @persona:ella
cita = @modo_tiempo:indicativo presente
cita = @modo_tiempo:imperativo
cita odontologica = @opción:odontológica
odontologica = @dato:tipo_de_cita
odontologica = @especialidad:odontológica
para = @persona:él
para = @persona:tú
para = @persona:ella
para = @modo_tiempo:indicativo presente
para = @preposición:para
para = @modo_tiempo:imperativo
el = @preposición:la del
el = @pronombres:el
el proximo viernes = @sys-date:2020-08-21
proximo = @opción:primera
 
¿La cita odontológica es para ti o es para alguien más?
 
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


---

08/14/2020 @
2:54
AM
1
Intents
2:54 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Aun de madrugada estamos aquí para ti. </div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
hola platzibot vengo de afan, ayudame a agendar una cita medica para el martes a las 6 pm
#cambiar_usuario
hola = @conversacion:saludo
hola = @extractor:hola
vengo = @modo_tiempo:indicativo presente
vengo = @persona:yo
vengo = @verbo:venir
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
afan = @persona:ellos
afan = @nombre:Alan
ayudame = @emergencia:ambulancia
a = @preposición:a
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
para = @persona:tú
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
para = @preposición:para
para = @modo_tiempo:imperativo
el = @preposición:la del
el = @pronombres:el
el martes = @sys-date:2020-08-18
a = @preposición:a
a las 6 pm = @sys-time:18:00:00
las = @pronombres:las
pm = @turno:T
 
 
¿Qué puedo hacer por ti el día de hoy Alan?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar


---

08/14/2020 @
2:54
AM
1
Intents
2:54 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Aun de madrugada estamos aquí para ti. </div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
hola platzibot vengo de afan, ayudame a agendar una cita medica para el martes a las 6 pm
#cambiar_usuario
hola = @conversacion:saludo
hola = @extractor:hola
vengo = @modo_tiempo:indicativo presente
vengo = @persona:yo
vengo = @verbo:venir
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
afan = @persona:ellos
afan = @nombre:Alan
ayudame = @emergencia:ambulancia
a = @preposición:a
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
para = @persona:tú
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
para = @preposición:para
para = @modo_tiempo:imperativo
el = @preposición:la del
el = @pronombres:el
el martes = @sys-date:2020-08-18
a = @preposición:a
a las 6 pm = @sys-time:18:00:00
las = @pronombres:las
pm = @turno:T
 
 
¿Qué puedo hacer por ti el día de hoy Alan?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
2:55 AM

---

08/14/2020 @
2:55
AM
1
Intents
2:55 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">De día, de noche e incluso de madrugada estamos aquí para servirte. </div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
hola platzibot no tengo mucho tiempo, ayudame a agendar una cota con el odotongologo para el dia martes a klas 10 am
#emergencia
hola = @conversacion:saludo
hola = @extractor:hola
no tengo = @decisión:impedido
tengo = @modo_tiempo:indicativo presente
tengo = @verbo:tener
tengo = @persona:yo
mucho = @pronombres:mucho
mucho = @adverbio:mucho
ayudame = @emergencia:ambulancia
a = @preposición:a
una = @sys-number:1
con = @preposición:con
el = @preposición:la del
el = @pronombres:el
para = @persona:tú
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
para = @preposición:para
para = @modo_tiempo:imperativo
para el dia = @sys-date:2020-08-13
para el dia = @sys-date:2020-08-14
el = @preposición:la del
el = @pronombres:el
dia = @dato:fecha
martes = @sys-date:2020-08-18
a = @preposición:a
klas = @pronombres:las
10 am = @sys-time:10:00:00
am = @turno:M
 
No soy muy bueno con los nombres, por eso prefiero asegurarme antes de empezar. </br></br>¿Te llamás Platzibot no tengo mucho tiempo, ayudame a agendar una cota con el odotongologo para el dia martes a klas 10 am?
2:55 AM

---

08/14/2020 @
2:56
AM
3
Intents
2:56 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">De día, de noche e incluso de madrugada estamos aquí para servirte. </div>
 
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
 
Buenas, ¿como estas? <break></break>
genial y tu
#conversacion
genial = @conversacion:bienestar
genial = @decisión:sí
tu = @persona:tú
 
maravilloso,
 
¿Cuál es el motivo de tu visita a este canal?
deseo agendar una cita con el odontologo para el martes a las 10 am
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
con = @preposición:con
el = @preposición:la del
el = @pronombres:el
odontologo = @opción:odontológica
para = @persona:tú
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
para = @preposición:para
para = @modo_tiempo:imperativo
el = @preposición:la del
el = @pronombres:el
el martes = @sys-date:2020-08-18
a = @preposición:a
a las 10 am = @sys-time:10:00:00
las = @pronombres:las
am = @turno:M
 
procederemos a consultar disponbilidad con el documento CC 1234567890 para la cita odontológica, el dia 2020-08-18 a las 10:00:00</br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Esta bien?
ok
#aceptar
ok = @decisión:sí
 
{"id":"50b9d139a4141f43ac7215650a4fad55","ok":true,"rev":"1-c377d24691554e97e8eff2dca90f85e8"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?


---

08/14/2020 @
2:58
AM
4
Intents
2:58 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Sin importar la hora, estamos aquí para ti. </div>
 
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
 
 
¿Cuál es el motivo de tú visita el día de hoy Miguel?
 
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
 
</br>¿Te sirve alguna de las anteriores o quieres probar diciéndome una fecha y hora?
Cita médica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
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
 
Miguel procederemos a consultar disponibilidad con el documento CC 1234567890 para la cita médica, el día 2020-08-21 a las 13:00:00 en CM PORTAL NORTE</br></br>
 
¿Quieres agendarla?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada correctamente ✔️</strong></br></br>Miguel la cita médica ha sido agendada para el dia 2020-08-21 a las 13:00:00 en el centro médico CM PORTAL NORTE.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>f75552bd01e7b3ea21769e6e4ef61d35</strong></br></br>
 
¿Podemos hacer algo más por ti?

---

08/14/2020 @
2:59
AM
5
Intents
2:59 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">De día, de noche e incluso de madrugada estamos aquí para servirte. </div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
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
 
¿Como podemos ayudarte Cumbia?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
agendar cita medica
#agendar_cita
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
si
#aceptar
si = @decisión:sí
 
 
Cumbia tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
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
 
Vamos a consultar disponibilidad con el documento CC 1234567890 de la cita médica Cumbia para el día 2020-08-19 a las 10:20:00 en CM SUBA</br></br>
 
¿Confirmas?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
3:00 AM

---

08/14/2020 @
3:00
AM
6
Intents
3:00 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Aun de madrugada estamos aquí para ti. </div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
hola me llamo cumbia
#cambiar_usuario
hola = @conversacion:saludo
hola me llamo = @extractor:hola me llamo
me = @pronombres:me
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
cumbia = @persona:ella
cumbia = @persona:tú
cumbia = @persona:él
 
No soy muy bueno con los nombres, por eso prefiero asegurarme antes de empezar. </br></br>¿Te llamás Cumbia?
si
#aceptar
si = @decisión:sí
 
¿En qué te puedo ayudar Cumbia?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
vengo a agendar un acita con el odontologo
#agendar_cita
vengo = @persona:yo
vengo = @verbo:venir
vengo = @modo_tiempo:indicativo presente
a = @preposición:a
acita = @persona:tú
acita = @persona:él
acita = @persona:ella
con = @preposición:con
el = @preposición:la del
el = @pronombres:el
odontologo = @opción:odontológica
 
¿Es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
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
tia = @otra_persona:tío
tia = @genero:femenino
 
Por favor indicame el número de documento de tu tia
cc 123456
#corregir
cc = @tipo_documento:CC
123456 = @input_patterns:PEP
123456 = @sys-number:123456
 
 
Cumbia tenemos estas opciones disponibles para la cita odontológica que estas solicitando:</br></br>
 
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
la quiere para el 19 de agosto pero a las 12:30 pm
#cambiar_turno
la = @pronombres:la
la quiere = @conversacion:amor
quiere = @persona:él
quiere = @persona:tú
quiere = @persona:ella
quiere = @modo_tiempo:indicativo presente
quiere = @modo_tiempo:imperativo
quiere = @verbo:querer
para = @persona:tú
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
para = @preposición:para
para = @modo_tiempo:imperativo
el = @preposición:la del
el = @pronombres:el
el 19 de agosto = @sys-date:2020-08-19
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
a = @preposición:a
a las 12:30 pm = @sys-time:12:30:00
las = @pronombres:las
pm = @turno:T
 
Vamos a consultar disponibilidad con el documento CC 123456 de la cita odontológica Cumbia para el día 2020-08-19 a las 12:30:00 en </br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Quieres agendarla?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
si
#aceptar
si = @decisión:sí
 
 
<strong>Agendada con éxito ✔️</strong></br></br>Cumbia la cita odontológica ha sido agendada para el dia 2020-08-19 a las 12:30:00 en el centro médico .</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 123456 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>db0a6da57a327fc7f7a516fc44d98f70</strong></br></br>
 
¿Podemos hacer algo más por ti?
no
#decisión
no = @decisión:no
 
Hasta luego, ¡vuelve pronto!
 
</br> </br>Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio Platzi - MinTic ICETEX Inteligencia Artificial. </br> </br> Antes que nada ¡¡¡Gracias!!! </br> </br> En el caso de uso que se presenta el chatbot realiza operaciones CRUD sobre una base de datos cloudant la cual ha sido expuesta mediante una API personalizada mediante functions. Todo serverless, una belleza!</br> </br> Es un gran detalle que quieras interactuar con este chatbot te agradezco cualquier comentario o critica constructiva. </br> </br>


---

08/14/2020 @
10:24
AM
8
Intents
10:24 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buen día.</div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
 
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
Muy bien
#General_Positive_Feedback
Muy = @adverbio:muy
Muy bien = @conversacion:bienestar
bien = @adverbio:bien
 
gracias por el comentario
hey platzibot, conoces un chiste?
#General_Jokes
conoces = @verbo:conocer
conoces = @persona:tú
conoces = @modo_tiempo:indicativo presente
un chiste = @conversacion:chiste
? = @conversacion:Pregunta
 
Lo gracioso acerca del misterio es lo siguiente
jajajajajajajjaja
Irrelevant
 
¿te puedo ayudar en algo?
pruebo como funcionas
#General_About_You
pruebo = @persona:yo
pruebo = @verbo:probar
pruebo = @modo_tiempo:indicativo presente
como = @adverbio:como
como = @persona:yo
como = @verbo:comer
como = @modo_tiempo:indicativo presente
funcionas = @persona:tú
funcionas = @verbo:funcionar
funcionas = @modo_tiempo:indicativo presente
puedes responder, preguntas emocionales??
#General_Greetings
puedes = @persona:tú
puedes = @verbo:poder
puedes = @modo_tiempo:indicativo presente
responder = @verbo:responder
responder = @modo_tiempo:infinitivo
preguntas = @persona:tú
preguntas = @verbo:preguntar
preguntas = @modo_tiempo:indicativo presente
?? = @conversacion:Pregunta
para cuando crees que te podemos poner en circulacion??
#habilidades
para = @persona:tú
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
para = @preposición:para
para = @modo_tiempo:imperativo
crees = @persona:tú
crees = @verbo:crear
crees = @verbo:creer
crees = @modo_tiempo:indicativo presente
crees = @modo_tiempo:subjuntivo presente
te = @pronombres:te
podemos = @modo_tiempo:indicativo presente
podemos = @verbo:poder
podemos = @persona:nosotros
poner = @modo_tiempo:infinitivo
poner = @verbo:poner
en = @preposición:en
?? = @conversacion:Pregunta
 
Mi nombre es Santiago, estoy aquí para ayudarte con el agendamiento, modificación y eliminación de citas médicas y odontológicas.
como?
#corregir
como = @persona:yo
como = @adverbio:como
como = @verbo:comer
como = @modo_tiempo:indicativo presente
? = @conversacion:Pregunta
 
Vamos dime, ¿qué puedo hacer por ti el día de hoy?
10:30 AM

---

08/14/2020 @
11:03
AM
9
Intents
11:03 AM
 
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
 
Buenas ¿Como va todo? <break></break>
Muy bien
#General_Positive_Feedback
Muy = @adverbio:muy
Muy bien = @conversacion:bienestar
bien = @adverbio:bien
 
soy un robot, no tengo sentimientos pero estoy igual orgulloso por esas palabras
Que bueno
#conversacion
 
¿como puedo ayudarte?
Cual es tu función?
 
Mi nombre es Santiago, estoy aquí para ayudarte con el agendamiento, modificación y eliminación de citas médicas y odontológicas.
Qué médicos hay en tu plantilla?
#listar_centros_medicos
hay = @conversacion:saludo
en = @preposición:en
tu = @persona:tú
? = @conversacion:Pregunta
Quienes son los médicos?
#listar_centros_medicos
son = @persona:ellos
son = @verbo:ser
son = @modo_tiempo:indicativo presente
los = @pronombres:los
? = @conversacion:Pregunta
Bueno
#conversacion
 
¿te puedo ayudar en algo?
Si
#aceptar
Si = @decisión:sí
 
¿en que te puedo colaborar?
Dame una cita
#agendar_cita
Da = @persona:él
Da = @persona:tú
Da = @verbo:dar
Da = @persona:ella
Dame = @extractor:dime
Dame = @decisión:sí
me = @pronombres:me
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
 
</br>¿Te sirve alguna de las anteriores o quieres probar diciéndome una fecha y hora?
Cita médica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
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
 
¿Confirmas?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada exitosamente ✔️</strong></br></br>La cita médica ha sido agendada para el dia 2020-08-21 a las 13:00:00 en el centro médico CM PORTAL NORTE .</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>5fba9827e5f8145fb7bc73f7490f6891</strong></br></br>
 
¿Podemos hacer algo más por ti?


---

08/14/2020 @
12:15
PM
11
Intents
12:15 PM
 
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
 
Buenas, ¿como estas? <break></break>
Muy bien gracias
#General_Positive_Feedback
Muy = @adverbio:muy
Muy bien = @conversacion:bienestar
bien = @adverbio:bien
bien gracias = @conversacion:bienestar
 
soy un robot, no tengo sentimientos pero estoy igual orgulloso por esas palabras
Ok
#aceptar
Ok = @decisión:sí
 
¿te puedo ayudar en algo?
Quiero una cita odontológica
#agendar_cita
Quiero = @persona:yo
Quiero = @verbo:querer
Quiero = @modo_tiempo:indicativo presente
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

19 de agosto de 2020 a las 10:20 am: Cita odontológica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

1 de septiembre de 2020 a las 4:00 pm : Cita odontológica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

21 de agosto de 2020 a las 1:00 PM: Cita odontológica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
 
</br>Elije una antes que alguien más la reserve
Cita odontológica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
#cambiar_turno
Cita = @persona:tú
Cita = @modo_tiempo:imperativo
Cita = @persona:él
Cita = @persona:ella
Cita = @verbo:citar
Cita = @modo_tiempo:indicativo presente
Cita odontológica = @opción:odontológica
odontológica = @especialidad:odontológica
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
 
Vamos a consultar disponibilidad con el documento CC 1234567890 de la cita odontológica para el día 2020-09-01 a las 16:00:00 en CM GRANAHORRAR</br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Confirmas?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada exitosamente ✔️</strong></br></br>La cita odontológica ha sido agendada para el dia 2020-09-01 a las 16:00:00 en el centro médico CM GRANAHORRAR .</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>f7194d14d1e705e24ab021b1c0104bb0</strong></br></br>
 
¿Podemos hacer algo más por ti?
Cómo se llama el doctor
#emergencia
se = @pronombres:se
llama = @modo_tiempo:imperativo
llama = @verbo:llamar
llama = @persona:él
llama = @persona:tú
llama = @persona:ella
llama = @modo_tiempo:indicativo presente
el = @preposición:la del
el = @pronombres:el
doctor = @opción:médica
doctor = @especialidad:médica
 
¿Podemos hacer algo más por ti?
Quiero agendar otra cita
#agendar_cita
Quiero = @persona:yo
Quiero = @verbo:querer
Quiero = @modo_tiempo:indicativo presente
otra = @control_bot:avanzar
otra = @opción:otra
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
 
¿Es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
Para Laura
#cambiar_usuario
Para = @persona:tú
Para = @preposición:para
Para = @modo_tiempo:imperativo
Para = @persona:él
Para = @persona:ella
Para = @modo_tiempo:indicativo presente
Laura = @nombre:Laura
 
 
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
20 de agosto a las 1pm
#emergencia
20 de agosto = @sys-date:2020-08-20
de = @preposición:de
de = @persona:ella
de = @verbo:dar
de = @persona:él
a = @preposición:a
a las 1pm = @sys-time:13:00:00
las = @pronombres:las
 
procederemos a consultar disponibilidad con el documento CC 1234567890 para la cita odontológica, el día 2020-08-20 a las 13:00:00 en </br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Me autorizas a reservarla?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
El lugar ?
#corregir
El = @preposición:la del
El = @pronombres:el
lugar = @dato:centro_medico
? = @conversacion:Pregunta
 
por favor dime de nuevo, ¿que centro medico prefieres?
Palma real
#corregir
 
¿Cual es tu centro medico de preferencia?
Risitas
Irrelevant
Risitas = @persona:tú
 
Si no sabes el nombre exacto del centro médico, no hay problema. Intenta diciendo la zona en la que esta ubicado.
Palmira
Irrelevant
 
¿Cual es tu centro medico de preferencia?
Que opciones tengo ?
#listar_opciones
tengo = @persona:yo
tengo = @verbo:tener
tengo = @modo_tiempo:indicativo presente
? = @conversacion:Pregunta
 
Si no sabes el nombre exacto del centro médico, no hay problema. Intenta diciendo la zona en la que esta ubicado.
Gracias
#General_Positive_Feedback
Gracias = @conversacion:agradecimiento
Gracias = @conversacion:cortesia
 
¿Cual es tu centro medico de preferencia?
Exit
#corregir
 
Si no sabes el nombre exacto del centro médico, no hay problema. Intenta diciendo la zona en la que esta ubicado.
12:20 PM

---


08/14/2020 @
12:31
PM
5
Intents
12:31 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buenas tardes.</div>
 
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
 
 
¿Qué puedo hacer por ti el día de hoy Miguel?
 
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

19 de agosto de 2020 a las 10:20 am: Cita odontológica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

1 de septiembre de 2020 a las 4:00 pm : Cita odontológica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

21 de agosto de 2020 a las 1:00 PM: Cita odontológica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
 
</br>Elije una antes que alguien más la reserve
Cita odontológica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
#cambiar_turno
Cita = @persona:tú
Cita = @modo_tiempo:imperativo
Cita = @persona:él
Cita = @persona:ella
Cita = @verbo:citar
Cita = @modo_tiempo:indicativo presente
Cita odontológica = @opción:odontológica
odontológica = @especialidad:odontológica
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
 
Vamos a consultar disponibilidad con el documento CC 1234567890 de la cita odontológica Miguel para el día 2020-09-01 a las 16:00:00 en CM GRANAHORRAR</br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Confirmas?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada exitosamente ✔️</strong></br></br>La cita odontológica ha sido agendada para el dia 2020-09-01 a las 16:00:00 en el centro médico CM GRANAHORRAR Miguel.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>f7194d14d1e705e24ab021b1c010d353</strong></br></br>
 
¿Podemos hacer algo más por ti?
no, eso es todo
#denegar
no = @decisión:no
eso = @pronombres:eso
es = @persona:ella
es = @persona:él
es = @verbo:ser
todo = @adverbio:todo
 
chao, ¡cuidate!
 
</br> </br>Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio Platzi - MinTic ICETEX Inteligencia Artificial. </br> </br> Antes que nada ¡¡¡Gracias!!! </br> </br> En el caso de uso que se presenta el chatbot realiza operaciones CRUD sobre una base de datos cloudant la cual ha sido expuesta mediante una API personalizada mediante functions. Todo serverless, una belleza!</br> </br> Es un gran detalle que quieras interactuar con este chatbot te agradezco cualquier comentario o critica constructiva. </br> </br>

---

08/14/2020 @
4:07
PM
2
Intents
4:07 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buena tarde.</div>
 
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
 
¡Hola! ¿como te va?
`xxx
Irrelevant
 
¿en que te puedo colaborar?
sdfsdfgsdfg
Irrelevant
dsfsdfsdfdsf
Irrelevant
dsf
Irrelevant
5834
Irrelevant
5834 = @sys-number:5834
hola
#conversacion
hola = @conversacion:saludo
hola = @extractor:hola
 
Hola ¿Como estas?
4:08 PM

----


08/14/2020 @
5:24
PM
2
Intents
5:24 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buena noche.</div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hola me llamo sergio
#cambiar_usuario
Hola = @conversacion:saludo
Hola me llamo = @extractor:hola me llamo
me = @pronombres:me
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
sergio = @nombre:Sergio
 
 
¿Qué puedo hacer por ti el día de hoy Sergio?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Eliminar
#eliminar_cita
 
Para comenzar indícanos tu número y tipo de documento
5:24 PM


---


08/14/2020 @
9:03
PM
2
Intents
9:03 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas noches.</div>
 
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
 
 
¿Qué puedo hacer por ti el día de hoy Miguel?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Agendar
#agendar_cita
 
Cuéntame Miguel, ¿qué tipo de cita se te ofrece?
 
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
9:03 PM


---


08/15/2020 @
1:57
AM
5
Intents
1:57 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Aun de madrugada estamos aquí para ti. </div>
 
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
no
 
¿Que deseas corregir?
mi documento
#recuperar_datos
mi = @pronombres:mí
documento = @dato:numero_documento
 
muy bien por favor dime de nuevo el numero y tipo de documento para realizar la corrección.
documento 5434234
#corregir
documento = @dato:numero_documento
543423 = @input_patterns:PEP
5434234 = @sys-number:5434234
 
 
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
 
</br>Elije una antes que alguien más la reserve
Cita odontológica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
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
 
Vamos a consultar disponibilidad con el documento CC 1234567890 de la cita odontológica para el día 2020-08-21 a las 13:00:00 en CM PORTAL NORTE</br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿La reservamos?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir

---


08/15/2020 @
1:57
AM
5
Intents
1:57 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Aun de madrugada estamos aquí para ti. </div>
 
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
no
 
¿Que deseas corregir?
mi documento
#recuperar_datos
mi = @pronombres:mí
documento = @dato:numero_documento
 
muy bien por favor dime de nuevo el numero y tipo de documento para realizar la corrección.
documento 5434234
#corregir
documento = @dato:numero_documento
543423 = @input_patterns:PEP
5434234 = @sys-number:5434234
 
 
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
 
</br>Elije una antes que alguien más la reserve
Cita odontológica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
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
 
Vamos a consultar disponibilidad con el documento CC 1234567890 de la cita odontológica para el día 2020-08-21 a las 13:00:00 en CM PORTAL NORTE</br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿La reservamos?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir

---


8
Turns
1
Minutes
08/15/2020 @
9:31
AM
4
Intents
9:31 AM
 
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
 
 
¿En qué te puedo ayudar Miguel?
 
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
 
</br>¿Alguna de estas opciones te sirve?
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
 
Vamos a consultar disponibilidad con el documento CC 1234567890 de la cita médica Miguel para el día 2020-08-19 a las 10:20:00 en CM SUBA</br></br>
 
¿Quieres agendarla?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada con éxito ✔️</strong></br></br>Miguel la cita médica ha sido agendada para el dia 2020-08-19 a las 10:20:00 en el centro médico CM SUBA.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>31ab9a469e44021ad9735ae42e407f46</strong></br></br>
 
¿Podemos hacer algo más por ti?
No
#decisión
No = @decisión:no
 
Hasta pronto, te esperamos de vuelta por aqui.
 
</br> </br>Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio Platzi - MinTic ICETEX Inteligencia Artificial. </br> </br> Antes que nada ¡¡¡Gracias!!! </br> </br> En el caso de uso que se presenta el chatbot realiza operaciones CRUD sobre una base de datos cloudant la cual ha sido expuesta mediante una API personalizada mediante functions. Todo serverless, una belleza!</br> </br> Es un gran detalle que quieras interactuar con este chatbot te agradezco cualquier comentario o critica constructiva. </br> </br>
9:33 AM



---


08/15/2020 @
11:05
AM
1
Intents
11:05 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buen día.</div>
 
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
 
¡Hola! ¿como te va?
Bien
#conversacion
Bien = @conversacion:bienestar
Bien = @adverbio:bien
 
genial,
 
¿en que te puedo colaborar?
11:05 AM

---


08/15/2020 @
11:28
AM
4
Intents
11:28 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenos días.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
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
 
{"id":"061fcba17d87a2d6435ba190286906dd","ok":true,"rev":"1-081990dd2d83a9e3e9774789775a9104"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?
si
#aceptar
si = @decisión:sí
 
¿Que otra cosa te gustaría hacer?
hablar con un agente
#General_Connect_to_Agent
hablar = @verbo:hablar
hablar = @modo_tiempo:infinitivo
con = @preposición:con
 
En Watson salud nos gustaría poder ayudarte,</br> Por favor selecciona alguna de las siguientes opciones: </br></br>
 
[Multi-option response]
Title: Opciones

Asignar: Asignar
Consultar: Consultar
Reprogramar: Reprogramar
Eliminar: Eliminar
Consultar
#consultar_cita
 
Para comenzar indícanos tu número y tipo de documento



---


08/15/2020 @
12:03
PM
8
Intents
12:03 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buenas tardes.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
me llamo luisa
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
 
Antes de comenzar permiteme confirmar si he entendido bien tu nombre </br></br>¿Tú nombre es Luisa?
no
#decisión
no = @decisión:no
 
Para comenzar dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
mi nombre es sofia
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
sofia = @nombre:Sofía
 
 
¿En qué te puedo ayudar Sofía?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Agendar
#agendar_cita
 
¿Cuál clase de cita necesitas agendar hoy Sofía?
 
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
 
 
Sofía tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

19 de agosto de 2020 a las 10:20 am: Cita médica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

1 de septiembre de 2020 a las 4:00 pm : Cita médica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

21 de agosto de 2020 a las 1:00 PM: Cita médica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
 
</br>¿Alguna de estas opciones te sirve?
no
#decisión
no = @decisión:no
 
¿Que deseas corregir?
fech
#cambiar_fecha
fech = @dato:fecha
fech = @opción:fecha
 
Entendido. Corregiremos la fecha, dímela de nuevo por favor
16/8/2020
#corregir
16/8/2020 = @sys-date:2020-08-16
 
A que hora la prefieres?
13:00
#corregir
13:00 = @sys-time:13:00:00
 
Por favor intenta decirme de nuevo la hora indicando si es por la mañana o la tarde.
1 PM
#cambiar_turno
1 = @opción:primera
1 PM = @sys-time:13:00:00
PM = @turno:T
 
Sofía procederemos a consultar disponbilidad con el documento CC 1234567890 para la cita médica, el dia 2020-08-16 a las 13:00:00 </br></br>
 
¿Esta bien?
SI
#aceptar
SI = @decisión:sí
 
{"id":"31ab9a469e44021ad9735ae42e612c63","ok":true,"rev":"1-9bdfc17c253e2e63a7bdd6aa9774ccdc"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?
no gracias
#General_Positive_Feedback
no = @decisión:no
gracias = @conversacion:agradecimiento
gracias = @conversacion:cortesia
 
Hasta luego, ¡vuelve pronto!
 
</br> </br>Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio Platzi - MinTic ICETEX Inteligencia Artificial. </br> </br> Antes que nada ¡¡¡Gracias!!! </br> </br> En el caso de uso que se presenta el chatbot realiza operaciones CRUD sobre una base de datos cloudant la cual ha sido expuesta mediante una API personalizada mediante functions. Todo serverless, una belleza!</br> </br> Es un gran detalle que quieras interactuar con este chatbot te agradezco cualquier comentario o critica constructiva. </br> </br>
12:05 PM

---

08/15/2020 @
12:32
PM
1
Intents
12:32 PM
 
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
 
Me alegra saludarte ¿como te va?
12:32 PM

---

08/15/2020 @
12:54
PM
1
Intents
12:54 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buena tarde.</div>
 
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
 
Buenas ¿Como va todo? <break></break>

----

08/15/2020 @
12:58
PM
7
Intents
12:58 PM
 
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
 
Hola, ¿como te encuentras hoy? <break></break>
Muy bien. Mi nombre es Aaron
#cambiar_usuario
Muy = @adverbio:muy
Muy bien = @conversacion:bienestar
bien = @adverbio:bien
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
Aaron = @persona:ellos
 
que alegria saber que todo esta bien para ti,
 
¿Cuál es el motivo de tu visita a este canal?
Me gustaría agendar una consulta
#agendar_cita
Me = @pronombres:me
gustaría = @persona:ella
gustaría = @modo_tiempo:potencial
gustaría = @persona:él
gustaría = @persona:yo
gustaría = @verbo:gustar
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
 
</br>Elije una antes que alguien más la reserve
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
 
¿Está bien?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada exitosamente ✔️</strong></br></br>La cita médica ha sido agendada para el dia 2020-09-01 a las 16:00:00 en el centro médico CM GRANAHORRAR .</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>d725e8c0b05658f2ea4fb398a25fe6e4</strong></br></br>
 
¿Podemos hacer algo más por ti?
Cancelalo
Irrelevant
 
¿Podemos hacer algo más por ti?
Anulalo
Irrelevant
 
¿Podemos hacer algo más por ti?
Anularlo
#aceptar
lo = @pronombres:lo
 
¿Que otra cosa te gustaría hacer?

---
08/15/2020 @
6:14
PM
3
Intents
6:14 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas noches.</div>
 
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
No se
Irrelevant
No = @decisión:no
No se = @opción:indeterminado
se = @pronombres:se
 
¿Que deseas corregir?
Mi vida
#conversacion
Mi = @pronombres:mí
Mi vida = @otra_persona:esposa
vida = @temática:vida
 
Por favor indícame, ¿que hay que corregir?



---


08/15/2020 @
6:14
PM
3
Intents
6:14 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas noches.</div>
 
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
No se
Irrelevant
No = @decisión:no
No se = @opción:indeterminado
se = @pronombres:se
 
¿Que deseas corregir?
Mi vida
#conversacion
Mi = @pronombres:mí
Mi vida = @otra_persona:esposa
vida = @temática:vida
 
Por favor indícame, ¿que hay que corregir?
6:15 PM

---

08/15/2020 @
10:50
PM
5
Intents
10:50 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buena noche.</div>
 
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
 
Hola, ¿como te encuentras hoy? <break></break>
bien, gracias
#conversacion
bien = @conversacion:bienestar
bien = @adverbio:bien
gracias = @conversacion:agradecimiento
gracias = @conversacion:cortesia
 
con gusto.
quiero agendar
#agendar_cita
quiero = @persona:yo
quiero = @verbo:querer
quiero = @modo_tiempo:indicativo presente
 
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
 
</br>¿Alguna de estas opciones te sirve?
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
 
 
<strong>Agendada exitosamente ✔️</strong></br></br> la cita médica ha sido agendada para el dia 2020-09-01 a las 16:00:00 en el centro médico CM GRANAHORRAR.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>272d09b3ced3d1d980c55ed68e0b70cc</strong></br></br>
 
¿Podemos hacer algo más por ti?
no
#decisión
no = @decisión:no
 
chao, ¡cuidate!
 
</br> </br>Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio Platzi - MinTic ICETEX Inteligencia Artificial. </br> </br> Antes que nada ¡¡¡Gracias!!! </br> </br> En el caso de uso que se presenta el chatbot realiza operaciones CRUD sobre una base de datos cloudant la cual ha sido expuesta mediante una API personalizada mediante functions. Todo serverless, una belleza!</br> </br> Es un gran detalle que quieras interactuar con este chatbot te agradezco cualquier comentario o critica constructiva. </br> </br>
10:51 PM



---

08/16/2020 @
12:16
AM
3
Intents
12:16 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Si tu trasnochas, aquí nos trasnochamos contigo. </div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
hi
#conversacion
hi = @conversacion:saludo
 
Hola ¿Qué tal ? ¿como te encuentras hoy?
bien y tu?
#conversacion
bien = @conversacion:bienestar
bien = @adverbio:bien
tu = @persona:tú
? = @conversacion:Pregunta
 
maravilloso,
 
¿qué tipo de cita te gustaría solicitar?
sabes mi nombre
#recuperar_datos
sabes = @persona:tú
sabes = @verbo:saber
sabes = @modo_tiempo:indicativo presente
mi = @pronombres:mí
nombre = @persona:yo
nombre = @modo_tiempo:imperativo
nombre = @persona:él
nombre = @persona:ella
nombre = @modo_tiempo:subjuntivo presente
nombre = @opción:nombre
nombre = @verbo:nombrar
cual es mi nombre?
#cambiar_usuario
es = @persona:él
es = @persona:ella
es = @verbo:ser
es mi nombre = @extractor:es mi nombre
mi = @pronombres:mí
nombre = @persona:yo
nombre = @modo_tiempo:imperativo
nombre = @persona:él
nombre = @persona:ella
nombre = @modo_tiempo:subjuntivo presente
nombre = @opción:nombre
nombre = @verbo:nombrar
? = @conversacion:Pregunta
me llamo andres
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
andres = @nombre:Andrés
andres = @persona:tú
andres = @nombre:Andrea



----


08/16/2020 @
12:17
AM
2
Intents
12:17 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">De día, de noche e incluso de madrugada estamos aquí para servirte. </div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
mi nombre es sofia
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
sofia = @nombre:Sofía
 
 
¿Como podemos ayudarte Sofía?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Agendar
#agendar_cita
 
¿Qué tipo de cita deseas agendar Sofía?
 
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
Es para María
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
María = @nombre:María
 
 
Sofía tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

19 de agosto de 2020 a las 10:20 am: Cita médica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

1 de septiembre de 2020 a las 4:00 pm : Cita médica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

21 de agosto de 2020 a las 1:00 PM: Cita médica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
 
</br>¿Alguna de estas opciones te sirve?


---

08/16/2020 @
12:16
AM
3
Intents
12:16 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Si tu trasnochas, aquí nos trasnochamos contigo. </div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
hi
#conversacion
hi = @conversacion:saludo
 
Hola ¿Qué tal ? ¿como te encuentras hoy?
bien y tu?
#conversacion
bien = @conversacion:bienestar
bien = @adverbio:bien
tu = @persona:tú
? = @conversacion:Pregunta
 
maravilloso,
 
¿qué tipo de cita te gustaría solicitar?
sabes mi nombre
#recuperar_datos
sabes = @persona:tú
sabes = @verbo:saber
sabes = @modo_tiempo:indicativo presente
mi = @pronombres:mí
nombre = @persona:yo
nombre = @modo_tiempo:imperativo
nombre = @persona:él
nombre = @persona:ella
nombre = @modo_tiempo:subjuntivo presente
nombre = @opción:nombre
nombre = @verbo:nombrar
cual es mi nombre?
#cambiar_usuario
es = @persona:él
es = @persona:ella
es = @verbo:ser
es mi nombre = @extractor:es mi nombre
mi = @pronombres:mí
nombre = @persona:yo
nombre = @modo_tiempo:imperativo
nombre = @persona:él
nombre = @persona:ella
nombre = @modo_tiempo:subjuntivo presente
nombre = @opción:nombre
nombre = @verbo:nombrar
? = @conversacion:Pregunta
me llamo andres
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
andres = @nombre:Andrés
andres = @persona:tú
andres = @nombre:Andrea


---

08/16/2020 @
12:18
AM
4
Intents
12:18 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">De día, de noche e incluso de madrugada estamos aquí para servirte. </div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hoka
#corregir
Hoka = @dato:hora
Hoka = @conversacion:saludo
Hoka = @extractor:hola
 
Antes de comenzar permiteme confirmar si he entendido bien tu nombre </br></br>¿Tú nombre es Oka?
No
#decisión
No = @decisión:no
 
¿Cual es tú nombre?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Me llamo pepe
#cambiar_usuario
Me = @pronombres:me
Me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
pepe = @nombre:José
 
 
Cuéntame José, ¿qué se te ofrece?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Agendar
#agendar_cita
 
¿Qué tipo de cita deseas agendar José?
 
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
Es para María
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
María = @nombre:María
 
 
José tenemos estas opciones disponibles para la cita odontológica que estas solicitando:</br></br>
 
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


---

08/16/2020 @
12:25
AM
7
Intents
12:25 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Si tu trasnochas, aquí nos trasnochamos contigo. </div>
 
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
 
Hola ¿Qué tal ? ¿como te encuentras hoy?
Bien
#conversacion
Bien = @conversacion:bienestar
Bien = @adverbio:bien
 
maravilloso,
 
¿de que tema se trata tu necesidad?
Quiero turno con el dentista
#agendar_cita
Quiero = @persona:yo
Quiero = @verbo:querer
Quiero = @modo_tiempo:indicativo presente
turno = @dato:turno
con = @preposición:con
el = @preposición:la del
el = @pronombres:el
dentista = @opción:odontológica
 
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
15 de Agosto?
#corregir
15 de Agosto = @sys-date:2021-08-15
de = @preposición:de
de = @persona:ella
de = @verbo:dar
de = @persona:él
? = @conversacion:Pregunta
 
A que hora la prefieres?
19 pm
#cambiar_turno
19 pm = @sys-time:19:00:00
pm = @turno:T
 
procederemos a consultar disponbilidad con el documento CC 1234567890 para la cita odontológica, el dia 2021-08-15 a las 19:00:00 </br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Esta bien?
Es un robo
#decisión
Es = @persona:ella
Es = @persona:él
Es = @verbo:ser
Ok esta bien
#aceptar
Ok = @decisión:sí
esta = @pronombres:esta
bien = @adverbio:bien
bien = @conversacion:bienestar
 
{"id":"3074bd3c57a2e0de9f63ace5f66b3bc5","ok":true,"rev":"1-5ac2d29e486e44e4257883daf97e0293"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?


---

08/16/2020 @
12:28
AM
1
Intents
12:28 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Sin importar la hora, estamos aquí para ti. </div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
mi nombre es andres
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
andres = @nombre:Andrés
andres = @persona:tú
andres = @nombre:Andrea
 
 
12:28 AM

---


08/16/2020 @
12:34
AM
11
Intents
12:34 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Aun de madrugada estamos aquí para ti. </div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hola soy samuel
#cambiar_usuario
Hola = @conversacion:saludo
Hola = @extractor:hola
soy = @persona:yo
soy = @verbo:ser
samuel = @nombre:Samuel
 
 
¿Como podemos ayudarte Samuel?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Quiero hacer una cita
#agendar_cita
Quiero = @persona:yo
Quiero = @verbo:querer
Quiero = @modo_tiempo:indicativo presente
hacer = @modo_tiempo:infinitivo
hacer = @verbo:hacer
una = @sys-number:1
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
 
¿Cuál clase de cita necesitas agendar hoy Samuel?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
Del dentista
#agendar_cita
dentista = @opción:odontológica
 
¿La cita odontológica es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
Yo
#corregir
Yo = @persona:yo
Yo = @pronombres:yo
 
 
Samuel tenemos estas opciones disponibles para la cita odontológica que estas solicitando:</br></br>
 
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
No se
Irrelevant
No = @decisión:no
No se = @opción:indeterminado
se = @pronombres:se
 
¿Que deseas corregir?
A ver la 3
#decisión
A = @preposición:a
ver = @verbo:ver
ver = @modo_tiempo:infinitivo
la = @pronombres:la
la 3 = @sys-time:03:00:00
3 = @opción:tercera
 
Por favor indícame, ¿que hay que corregir?
Nada
#denegar
Nada = @decisión:no
Nada = @adverbio:nada
Nada = @pronombres:nada
 
¿Que deseas que corrijamos?
Nah
Irrelevant
 
¿Que deseas corregir?
Nada
#denegar
Nada = @decisión:no
Nada = @adverbio:nada
Nada = @pronombres:nada
 
Por favor indícame, ¿que hay que corregir?
Nada
#denegar
Nada = @decisión:no
Nada = @adverbio:nada
Nada = @pronombres:nada
 
¿Que deseas que corrijamos?
No
#decisión
No = @decisión:no
 
¿Que deseas corregir?
La opción 3
#decisión
La = @pronombres:la
opción = @opción:opción
3 = @opción:tercera
3 = @sys-number:3
 
Por favor indícame, ¿que hay que corregir?
La cita
#agendar_cita
La = @pronombres:la
cita = @persona:ella
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
 
¿Que deseas que corrijamos?
La fecha
#corregir
La = @pronombres:la
fecha = @dato:fecha
fecha = @opción:fecha
 
Entendido. Corregiremos la fecha, dímela de nuevo por favor
La fecha
#corregir
La = @pronombres:la
fecha = @dato:fecha
fecha = @opción:fecha
 
Ok, por favor dime la fecha
19 de agosto de 2020
#corregir
19 de agosto de 2020 = @sys-date:2020-08-19
de = @preposición:de
de = @persona:ella
de = @verbo:dar
de = @persona:él
de = @preposición:de
de = @persona:ella
de = @verbo:dar
de = @persona:él
 
A que hora la prefieres?
A las 5
#emergencia
A = @preposición:a
A las 5 = @sys-time:05:00:00
las = @pronombres:las
 
Por favor intenta decirme de nuevo la hora indicando si es por la mañana o la tarde.
A las 5 de la tarde
#cambiar_turno
A = @preposición:a
A las 5 de la tarde = @sys-time:17:00:00
las = @pronombres:las
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
la = @pronombres:la
tarde = @modo_tiempo:imperativo
tarde = @persona:él
tarde = @verbo:tardar
tarde = @adverbio:tarde
tarde = @modo_tiempo:subjuntivo presente
tarde = @persona:ella
tarde = @turno:T
tarde = @dato:turno
tarde = @persona:yo
 
Samuel procederemos a consultar disponbilidad con el documento CC 1234567890 para la cita odontológica, el dia 2020-08-19 a las 17:00:00 </br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Esta bien?
Si
#aceptar
Si = @decisión:sí
 
{"id":"4b0e091dca21a83ca08bce5048180a0c","ok":true,"rev":"1-70793bae83b994dad36c66faec8b9369"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?
Sería todo
#conversacion
Sería = @persona:ella
Sería = @modo_tiempo:potencial
Sería = @persona:él
Sería = @persona:yo
Sería = @verbo:ser
todo = @adverbio:todo
 
¿en que te puedo colaborar?
Gracias
#General_Positive_Feedback
Gracias = @conversacion:agradecimiento
Gracias = @conversacion:cortesia
12:38 AM

---

08/16/2020 @
12:52
AM
3
Intents
12:52 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">De día, de noche e incluso de madrugada estamos aquí para servirte. </div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
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
bien y tu
#conversacion
bien = @conversacion:bienestar
bien = @adverbio:bien
tu = @persona:tú
 
que chevere que estes bien,
 
¿Cuál es el motivo de tu visita a este canal?
ehh me llaman carmen pero me puedes decir car-men
#cambiar_usuario
me = @pronombres:me
me llaman = @extractor:me llaman
llaman = @verbo:llamar
llaman = @persona:ellos
llaman = @modo_tiempo:indicativo presente
carmen = @nombre:Carmen
me = @pronombres:me
me puedes decir = @extractor:me puedes decir
puedes = @persona:tú
puedes = @verbo:poder
puedes = @modo_tiempo:indicativo presente
decir = @verbo:decir
decir = @modo_tiempo:infinitivo
hola?
#conversacion
hola = @conversacion:saludo
hola = @extractor:hola
? = @conversacion:Pregunta
 
Hola ¿Qué hay de nuevo?
ajaja nada que me llaman carmen
#cambiar_usuario
nada = @decisión:no
nada = @adverbio:nada
nada = @pronombres:nada
que me = @persona:yo
que me = @persona:ella
que me = @persona:él
me = @pronombres:me
me llaman = @extractor:me llaman
llaman = @verbo:llamar
llaman = @persona:ellos
llaman = @modo_tiempo:indicativo presente
carmen = @nombre:Carmen
 
¿en que te puedo colaborar?
sabes mi nombre?
#recuperar_datos
sabes = @persona:tú
sabes = @verbo:saber
sabes = @modo_tiempo:indicativo presente
mi = @pronombres:mí
nombre = @persona:yo
nombre = @modo_tiempo:imperativo
nombre = @persona:él
nombre = @persona:ella
nombre = @modo_tiempo:subjuntivo presente
nombre = @opción:nombre
nombre = @verbo:nombrar
? = @conversacion:Pregunta
me llamo carmen
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
carmen = @nombre:Carmen
hola
#conversacion
hola = @conversacion:saludo
hola = @extractor:hola
 
Hola ¿Qué tal ? ¿como te encuentras hoy?
me llamo carmen
#cambiar_usuario
me = @pronombres:me
me llamo = @extractor:me llamo
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
carmen = @nombre:Carmen
12:53 AM

---

08/16/2020 @
12:53
AM
9
Intents
12:53 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">De día, de noche e incluso de madrugada estamos aquí para servirte. </div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
hola me llamo carmen
#cambiar_usuario
hola = @conversacion:saludo
hola me llamo = @extractor:hola me llamo
me = @pronombres:me
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
carmen = @nombre:Carmen
 
 
¿Cuál es el motivo de tú visita el día de hoy Carmen?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Agendar
#agendar_cita
 
¿Cuál clase de cita necesitas agendar hoy Carmen?
 
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
ffff
Irrelevant
 
 
Carmen tenemos estas opciones disponibles para la cita odontológica que estas solicitando:</br></br>
 
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
Cita odontológica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
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
 
Carmen procederemos a consultar disponibilidad con el documento CC 1234567890 para la cita odontológica, el día 2020-08-21 a las 13:00:00 en CM PORTAL NORTE</br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Quieres agendarla?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Corregir
#corregir
 
¿Que deseas corregir?
no hay cita para diciembre?
#agendar_cita
no = @decisión:no
hay = @conversacion:saludo
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
diciembre = @sys-date:2020-12-01
diciembre = @sys-date:2020-12-31
? = @conversacion:Pregunta
 
Por favor indícame, ¿que hay que corregir?
fecha
#corregir
fecha = @dato:fecha
fecha = @opción:fecha
 
Entendido. Corregiremos la fecha, dímela de nuevo por favor
diciembre 25
#agendar_cita
diciembre 25 = @sys-date:2020-12-25
 
A que hora la prefieres?
10 am
#cambiar_turno
10 am = @sys-time:10:00:00
am = @turno:M
 
Carmen procederemos a consultar disponbilidad con el documento CC 1234567890 para la cita odontológica, el dia 2020-12-25 a las 10:00:00 </br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Esta bien?
ok
#aceptar
ok = @decisión:sí
 
{"id":"fac462131de8cc2fa5fc67813e382346","ok":true,"rev":"1-87b3b4d5c052b8bbd561d31b510141fd"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?
pero es un robo eh
#aceptar
es = @persona:ella
es = @persona:él
es = @verbo:ser
 
¿Que otra cosa te gustaría hacer?
jajaja nada bro
#denegar
nada = @decisión:no
nada = @adverbio:nada
nada = @pronombres:nada
bro = @otra_persona:hermano
 
¿Qué te trae por aquí entonces?
ya duerme ya
#General_Ending
ya = @adverbio:ya
duerme = @persona:ella
duerme = @modo_tiempo:imperativo
duerme = @persona:él
duerme = @persona:tú
duerme = @verbo:dormir
duerme = @modo_tiempo:indicativo presente
ya = @adverbio:ya
 
En Watson salud nos gustaría poder ayudarte,</br> Por favor selecciona alguna de las siguientes opciones: </br></br>
 
[Multi-option response]
Title: Opciones

Asignar: Asignar
Consultar: Consultar
Reprogramar: Reprogramar
Eliminar: Eliminar
no pasa nada
#denegar
no = @decisión:no
pasa = @persona:tú
pasa = @modo_tiempo:imperativo
pasa = @persona:él
pasa = @verbo:pasar
pasa = @persona:ella
pasa = @modo_tiempo:indicativo presente
nada = @decisión:no
nada = @adverbio:nada
nada = @pronombres:nada
 
porque no?
porque asi es la vida ps causa
#aceptar
asi es = @decisión:sí
es = @persona:ella
es = @persona:él
es = @verbo:ser
la = @pronombres:la
la vida = @temática:vida
 
¿en que te puedo colaborar?
nada
#denegar
nada = @decisión:no
nada = @adverbio:nada
nada = @pronombres:nada
 
¿Qué te trae por aquí entonces?
nada de nada
 
¿Qué te trae por aquí entonces?
nah
Irrelevant
hola
#conversacion
hola = @conversacion:saludo
hola = @extractor:hola
 
¡Hola! ¿como te va? Carmen
12:56 AM

---

08/16/2020 @
1:04
AM
6
Intents
1:04 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">De día, de noche e incluso de madrugada estamos aquí para servirte. </div>
 
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
 
Hola, ¿como te encuentras hoy? <break></break>
bien
#conversacion
bien = @conversacion:bienestar
bien = @adverbio:bien
 
maravilloso,
 
¿como puedo ayudarte?
como quieras
#corregir
como = @adverbio:como
como = @persona:yo
como = @verbo:comer
como = @modo_tiempo:indicativo presente
quieras = @persona:tú
quieras = @modo_tiempo:subjuntivo presente
quieras = @verbo:querer
 
Deja el misterio cuéntame, ¿que se te ofrece?
que ofreces?
#listar_opciones
ofreces = @persona:tú
ofreces = @verbo:ofrecer
ofreces = @modo_tiempo:indicativo presente
? = @conversacion:Pregunta
 
Que deseas corregir?
muchas cosas
#conversacion
muchas = @pronombres:muchas
cosas = @persona:tú
cosas = @verbo:coser
cosas = @modo_tiempo:subjuntivo presente
 
¿qué tipo de cita te gustaría solicitar?
what?
#traducir
? = @conversacion:Pregunta
 
¿Que texto quieres traducir?
1
#decisión
1 = @opción:primera
1 = @sys-number:1
 
<? $webhook_result_1.translations[0].translation ?>
payaso
Irrelevant
1:07 AM

---

08/16/2020 @
1:22
AM
3
Intents
1:22 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">De día, de noche e incluso de madrugada estamos aquí para servirte. </div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
lorena
Irrelevant
 
Tu nombre es Lorena, ¿es correcto?
si
#aceptar
si = @decisión:sí
 
¿Cuál es el motivo de tú visita el día de hoy Lorena?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
consultar
#consultar_cita
 
Para comenzar indícanos tu número y tipo de documento
456789123
Irrelevant
456789 = @input_patterns:PEP
456789123 = @sys-number:456789123
 
 
Lorena he encontrado 13 citas agendadas con el documento PEP 456789123</br></br>
 
Lorena, estas son las citas agendadas actualmente con el documento PEP 456789123</br></br>
 
Cita <? $webhook_result_2.rows[0].doc.params.tipo_de_cita ?> reservada por <? $webhook_result_2.rows[0].doc.params.firstname ?> para el día <? $webhook_result_2.rows[0].doc.params.selected_date ?> a las <? $webhook_result_2.rows[0].doc.params.selected_time ?> en el centro medico <? $webhook_result_2.rows[0].doc.params.selected_medical_centre ?>
 
[Multi-option response]
Title: 2. 19 de julio de 2020 a las 10:00 am en CM GRANAHORRAR

 
Cita <? $webhook_result_2.rows[1].doc.params.tipo_de_cita ?> reservada por <? $webhook_result_2.rows[1].doc.params.firstname ?> para el día <? $webhook_result_2.rows[1].doc.params.selected_date ?> a las <? $webhook_result_2.rows[1].doc.params.selected_time ?> en el centro medico <? $webhook_result_2.rows[1].doc.params.selected_medical_centre ?>
 
[Multi-option response]
Title: 3. 6 de julio de 2020 a las 10:00 am en CM DUITAMA

 
Cita <? $webhook_result_2.rows[2].doc.params.tipo_de_cita ?> reservada por <? $webhook_result_2.rows[2].doc.params.firstname ?> para el día <? $webhook_result_2.rows[2].doc.params.selected_date ?> a las <? $webhook_result_2.rows[2].doc.params.selected_time ?> en el centro medico <? $webhook_result_2.rows[2].doc.params.selected_medical_centre ?>
 
[Multi-option response]
Title: 4. 19 de julio de 2020 a las 3:00 pm en CL INFANTIL

 
[Multi-option response]
Title: 5. 19 de julio de 2020 a las 6:30 am en CM SUBA

 
[Multi-option response]
Title: Página 1 de 3

Avanzar: avanzar
Retroceder: reroceder
Salir: salir
 
¿Deseas hacer algo mas?

---

08/16/2020 @
2:12
AM
7
Intents
2:12 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">De día, de noche e incluso de madrugada estamos aquí para servirte. </div>
 
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
 
Buenas, ¿como estas? <break></break>
mas o menos
#control_bot
menos = @adverbio:menos
menos = @preposición:menos
 
¿en que te puedo colaborar?
que ofreces?
#listar_opciones
ofreces = @persona:tú
ofreces = @verbo:ofrecer
ofreces = @modo_tiempo:indicativo presente
? = @conversacion:Pregunta
 
las siguientes son las opciones disponibles: agendar cita, modificar cita o eliminar cita.
agendar cita
#agendar_cita
cita = @persona:ella
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
 
¿Qué tipo de cita deseas agendar ?
 
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
 
¿Confirmas?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada exitosamente ✔️</strong></br></br> la cita médica ha sido agendada para el dia 2020-08-19 a las 10:20:00 en el centro médico CM SUBA.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>3402d0a919929138d28f5a39a0415833</strong></br></br>
 
¿Podemos hacer algo más por ti?
no, muchas gracias
#conversacion
no = @decisión:no
muchas = @pronombres:muchas
muchas gracias = @conversacion:cortesia
muchas gracias = @conversacion:agradecimiento
 
¡Gracias por utilizar nuestro servicio de citas online vuelve pronto!
 
</br> </br>Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio Platzi - MinTic ICETEX Inteligencia Artificial. </br> </br> Antes que nada ¡¡¡Gracias!!! </br> </br> En el caso de uso que se presenta el chatbot realiza operaciones CRUD sobre una base de datos cloudant la cual ha sido expuesta mediante una API personalizada mediante functions. Todo serverless, una belleza!</br> </br> Es un gran detalle que quieras interactuar con este chatbot te agradezco cualquier comentario o critica constructiva. </br> </br>
2:14 AM

---
08/16/2020 @
4:43
AM
5
Intents
4:43 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Ojala estes disfrutando de una hermosa mañana.</div>
 
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
 
Hola ¿Qué hay de nuevo?
Hola
#conversacion
Hola = @conversacion:saludo
Hola = @extractor:hola
 
Buenas ¿Como va todo? <break></break>
Bien
#conversacion
Bien = @conversacion:bienestar
Bien = @adverbio:bien
 
me alegra saber que estas bien,
 
¿Cuál es el motivo de tu visita a este canal?
consulta
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
19065373
Irrelevant
190653 = @input_patterns:PEP
19065373 = @sys-number:19065373
 
 
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
 
 
<strong>Agendada correctamente ✔️</strong></br></br> la cita médica ha sido agendada para el dia 2020-08-21 a las 13:00:00 en el centro médico CM PORTAL NORTE.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>3074bd3c57a2e0de9f63ace5f69837a6</strong></br></br>
 
¿Podemos hacer algo más por ti?
4:46 AM


---

08/16/2020 @
4:43
AM
5
Intents
4:43 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Ojala estes disfrutando de una hermosa mañana.</div>
 
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
 
Hola ¿Qué hay de nuevo?
Hola
#conversacion
Hola = @conversacion:saludo
Hola = @extractor:hola
 
Buenas ¿Como va todo? <break></break>
Bien
#conversacion
Bien = @conversacion:bienestar
Bien = @adverbio:bien
 
me alegra saber que estas bien,
 
¿Cuál es el motivo de tu visita a este canal?
consulta
 
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
19065373
Irrelevant
190653 = @input_patterns:PEP
19065373 = @sys-number:19065373
 
 
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
 
 
<strong>Agendada correctamente ✔️</strong></br></br> la cita médica ha sido agendada para el dia 2020-08-21 a las 13:00:00 en el centro médico CM PORTAL NORTE.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>3074bd3c57a2e0de9f63ace5f69837a6</strong></br></br>
 
¿Podemos hacer algo más por ti?


---

08/16/2020 @
7:08
AM
2
Intents
7:08 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenos días.</div>
 
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
 
Hola ¿Como estas?
error
#corregir
 
¿como puedo ayudarte?
7:08 AM


---


08/16/2020 @
7:08
AM
2
Intents
7:08 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenos días.</div>
 
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
 
Hola ¿Como estas?
error
#corregir
 
¿como puedo ayudarte?
7:08 AM


---

08/16/2020 @
7:10
AM
1
Intents
7:10 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buen día.</div>
 
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
 
Hola ¿Como estas?

---

08/16/2020 @
8:52
AM
7
Intents
8:52 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buen día.</div>
 
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
 
Hola ¿Qué hay de nuevo?
necesito una cita
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
 
Cuéntame , ¿qué tipo de cita se te ofrece?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
medica general
#corregir
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
 
</br>¿Cuál es tu elección?
3
#decisión
3 = @opción:tercera
3 = @sys-number:3
 
Has elegido la tercera opción:
 
tu cita médica quedará reservada para el día 21 de agosto de 2020 a las 1:00 PM en el centro médico CM SUBA, con el documento CC 1234567890. </br></br>Recuerda que debes llegar 30 minutos antes y pasar por el punto ágil para facturar tu cuota moderadora.</br></br>Si no puedes ir a tu cita, cancela con 3 horas de anticipación y permite que alguien la tome por ti.</br></br>
 
¿Esta bien?
no
#decisión
no = @decisión:no
 
¿Que deseas corregir?
la CC
#corregir
la = @pronombres:la
CC = @tipo_documento:CC
 
Corregiremos el tipo de documento. Por favor dime de nuevo el tipo de documento correspondiente.
98717046
Irrelevant
987170 = @input_patterns:PEP
98717046 = @sys-number:98717046
 
He interpretado el numero 98717046, ¿es correcto?
si
#aceptar
si = @decisión:sí
 
No he recibido el tipo de documento que acompaña el numero que me acabas de dar. Por favor repitemelo de nuevo.


---

9
Turns
1
Minutes
08/16/2020 @
9:32
AM
6
Intents
9:32 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buen día.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
ayida
Irrelevant
ayida = @persona:tú
ayida = @persona:él
ayida = @persona:ella
 
Tu nombre es Ayida, ¿es correcto?
no
#decisión
no = @decisión:no
 
¿Cual es tú nombre?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
mi nombre es sofia
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
sofia = @nombre:Sofía
 
 
¿Qué puedo hacer por ti el día de hoy Sofía?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Modificar
#modificar_cita
 
Para comenzar indícanos tu número y tipo de documento
98717046 CC
#corregir
987170 = @input_patterns:PEP
98717046 = @sys-number:98717046
CC = @tipo_documento:CC
 
 
Estimado Sofía, estas son las citas agendadas actualmente con el documento CC 98717046</br></br>
 
1. 6 de julio de 2020 a las 7:30 am en CM FONTIBON</br></br>
 
2. 19 de julio de 2020 a las 10:00 am en CM GRANAHORRAR</br></br>
 
3. 6 de julio de 2020 a las 10:00 am en CM DUITAMA</br></br>
 
4. 19 de julio de 2020 a las 3:00 pm en CL INFANTIL</br></br>
 
5. 19 de julio de 2020 a las 6:30 am en CM SUBA</br></br>
 
Puedo mostrarte tus citas agendadas de cinco en cinco. En total actualmente tienes 13 citas agendadas. Estamos en la pagina 1 de un total de 3.</br></br> Puedes pedirme que avance o retroceda una pagina para ver las demas citas agendadas.</br></br>
 
¿Cuál cita deseas modificar?
5
#corregir
5 = @sys-number:5
 
5 no hace parte de las opciones mostradas. Puedes seleccionar una cita indicando la primera, la segunda o la tercera. Ademas si ninguna de las opciones se ajusta a tus necesidades, puedes solicitarme que busque nuevas opciones.
1
#decisión
1 = @opción:primera
1 = @sys-number:1
 
Has elegido la primera opción:
 
Sofía tu cita del día 6 de julio de 2020 a las 7:30 am en el centro médico CM FONTIBON, con el documento CC 98717046 sera modificada.
 
¿Es correcto?
si
#aceptar
si = @decisión:sí
 
 
9:34 AM

---

08/16/2020 @
11:08
AM
5
Intents
11:08 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas tardes.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
juan
#cambiar_usuario
juan = @nombre:Juan
 
 
¿Como podemos ayudarte Juan?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
quiero consultar un problema
#consultar_cita
quiero = @persona:yo
quiero = @verbo:querer
quiero = @modo_tiempo:indicativo presente
 
Para comenzar indícanos tu número y tipo de documento
278 id
#corregir
278 = @sys-number:278
id = @persona:vosotros
id = @modo_tiempo:imperativo
id = @dato:numero_documento
id = @verbo:ir
 
He interpretado el numero 278, ¿es correcto?
si papi
#aceptar
si = @decisión:sí
papi = @otra_persona:padre
 
No he recibido el tipo de documento que acompaña el numero que me acabas de dar. Por favor repitemelo de nuevo.
pasaporte
Irrelevant
 
No he recibido el tipo de documento que acompaña el numero que me acabas de dar. Por favor repitemelo de nuevo.
cedula
#corregir
cedula = @tipo_documento:CC
cedula = @dato:tipo_documento
cedula = @dato:numero_documento
 
he identificado CC
 
Juan he encontrado 13 citas agendadas con el documento CC 278</br></br>
 
Juan, estas son las citas agendadas actualmente con el documento CC 278</br></br>
 
Cita <? $webhook_result_2.rows[0].doc.params.tipo_de_cita ?> reservada por <? $webhook_result_2.rows[0].doc.params.firstname ?> para el día <? $webhook_result_2.rows[0].doc.params.selected_date ?> a las <? $webhook_result_2.rows[0].doc.params.selected_time ?> en el centro medico <? $webhook_result_2.rows[0].doc.params.selected_medical_centre ?>
 
[Multi-option response]
Title: 2. 19 de julio de 2020 a las 10:00 am en CM GRANAHORRAR

 
Cita <? $webhook_result_2.rows[1].doc.params.tipo_de_cita ?> reservada por <? $webhook_result_2.rows[1].doc.params.firstname ?> para el día <? $webhook_result_2.rows[1].doc.params.selected_date ?> a las <? $webhook_result_2.rows[1].doc.params.selected_time ?> en el centro medico <? $webhook_result_2.rows[1].doc.params.selected_medical_centre ?>
 
[Multi-option response]
Title: 3. 6 de julio de 2020 a las 10:00 am en CM DUITAMA

 
Cita <? $webhook_result_2.rows[2].doc.params.tipo_de_cita ?> reservada por <? $webhook_result_2.rows[2].doc.params.firstname ?> para el día <? $webhook_result_2.rows[2].doc.params.selected_date ?> a las <? $webhook_result_2.rows[2].doc.params.selected_time ?> en el centro medico <? $webhook_result_2.rows[2].doc.params.selected_medical_centre ?>
 
[Multi-option response]
Title: 4. 19 de julio de 2020 a las 3:00 pm en CL INFANTIL

 
[Multi-option response]
Title: 5. 19 de julio de 2020 a las 6:30 am en CM SUBA

 
[Multi-option response]
Title: Página 1 de 3

Avanzar: avanzar
Retroceder: reroceder
Salir: salir
 
¿Deseas hacer algo mas?
11:09 AM

---

08/16/2020 @
11:25
AM
2
Intents
11:25 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buen día.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
asdasd
Irrelevant
 
Tu nombre es Asdasd, ¿es correcto?
si
#aceptar
si = @decisión:sí
 
¿En qué te puedo ayudar Asdasd?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
11:26 AM


----

08/16/2020 @
3:08
PM
2
Intents
3:08 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buena tarde.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
¿Cual es tú nombre?
 
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
si
#aceptar
si = @decisión:sí
 
{"id":"8dbcbb2f0b59ad1a429277b9de499920","ok":true,"rev":"1-2af071eda201331fd4cb65540fe28a2b"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?
si
#aceptar
si = @decisión:sí
 
¿Que otra cosa te gustaría hacer?
3:09 PM

---
08/16/2020 @
4:05
PM
8
Intents
4:05 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas tardes.</div>
 
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
 
Me alegra saludarte ¿como te va?
muy bien
#General_Positive_Feedback
muy = @adverbio:muy
muy bien = @conversacion:bienestar
bien = @adverbio:bien
 
gracias por esas palabras
como vas tu
#habilidades
como = @persona:yo
como = @adverbio:como
como = @verbo:comer
como = @modo_tiempo:indicativo presente
vas = @persona:tú
vas = @verbo:ir
vas = @modo_tiempo:indicativo presente
tu = @persona:tú
 
Mi nombre es Santiago, estoy aquí para ayudarte con el agendamiento, modificación y eliminación de citas médicas y odontológicas.
solo medicaS?
#conversacion
solo = @extractor:solo
solo = @adverbio:solo
medicaS = @especialidad:médica
medicaS = @opción:médica
medicaS = @dato:tipo_de_cita
? = @conversacion:Pregunta
 
¿en que te puedo colaborar?
quiero un curso
#aceptar
quiero = @persona:yo
quiero = @verbo:querer
quiero = @modo_tiempo:indicativo presente
 
¿te puedo ayudar en algo?
matriuclarme
Irrelevant
cita medica
#agendar_cita
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
 
</br>¿Te sirve alguna de las anteriores o quieres probar diciéndome una fecha y hora?
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
 
Vamos a consultar disponibilidad con el documento CC 1234567890 de la cita médica para el día 2020-08-19 a las 10:20:00 en CM SUBA</br></br>
 
¿Me autorizas a reservarla?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada correctamente ✔️</strong></br></br> la cita médica ha sido agendada para el dia 2020-08-19 a las 10:20:00 en el centro médico CM SUBA.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>b583d3cdcb05dd6b71a06b6b6ee80593</strong></br></br>
 
¿Podemos hacer algo más por ti?
gracias
#General_Positive_Feedback
gracias = @conversacion:agradecimiento
gracias = @conversacion:cortesia
 
¿Podemos hacer algo más por ti?
no
#decisión
no = @decisión:no
 
Hasta luego, ¡vuelve pronto!
 
</br> </br>Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio Platzi - MinTic ICETEX Inteligencia Artificial. </br> </br> Antes que nada ¡¡¡Gracias!!! </br> </br> En el caso de uso que se presenta el chatbot realiza operaciones CRUD sobre una base de datos cloudant la cual ha sido expuesta mediante una API personalizada mediante functions. Todo serverless, una belleza!</br> </br> Es un gran detalle que quieras interactuar con este chatbot te agradezco cualquier comentario o critica constructiva. </br> </br>


---
08/16/2020 @
5:35
PM
1
Intents
5:35 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buena noche.</div>
 
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
 
Me alegra saludarte ¿como te va?


---
08/16/2020 @
5:37
PM
4
Intents
5:37 PM
 
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
 
Hola ¿Qué hay de nuevo?
quien es donald trump
#estoy_confundido
es = @persona:ella
es = @persona:él
es = @verbo:ser
 
¿en que te puedo colaborar?
quien eres
#General_Greetings
eres = @persona:tú
eres = @verbo:ser
?
#corregir
? = @conversacion:Pregunta
 
Que deseas que corrijamos?
la hora
#corregir
la = @pronombres:la
hora = @dato:hora


---

08/16/2020 @
5:42
PM
6
Intents
5:42 PM
 
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
 
Buenas, ¿como estas? <break></break>
bien gracias
#conversacion
bien = @adverbio:bien
bien gracias = @conversacion:bienestar
 
que alegria saber que todo esta bien para ti,
 
¿te puedo ayudar en algo?
depende
Irrelevant
yo te puedo ayudar?
#habilidades
yo = @pronombres:yo
yo = @persona:yo
te = @pronombres:te
puedo = @verbo:poder
puedo = @persona:yo
puedo = @modo_tiempo:indicativo presente
ayudar = @modo_tiempo:infinitivo
ayudar = @verbo:ayudar
? = @conversacion:Pregunta
 
te puedo colaborar con citas medicas o de odontología.
genial, me vendría bien una revisión de dientes
#conversacion
genial = @decisión:sí
genial = @conversacion:bienestar
me = @pronombres:me
vendría = @modo_tiempo:potencial
vendría = @persona:él
vendría = @persona:ella
vendría = @persona:yo
vendría = @verbo:venir
bien = @adverbio:bien
bien = @conversacion:bienestar
una = @sys-number:1
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
dientes = @especialidad:odontológica
 
me alegra saber que estas bien,
 
¿en que te puedo colaborar?
quiero agendar con estomatología
#agendar_cita
quiero = @persona:yo
quiero = @verbo:querer
quiero = @modo_tiempo:indicativo presente
con = @preposición:con
 
¿Cuál clase de cita necesitas agendar hoy ?
 
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
Es para María
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
María = @nombre:María
 
 
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
 
</br>Elije una antes que alguien más la reserve
Cita odontológica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
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
 
Vamos a consultar disponibilidad con el documento CC 1234567890 de la cita odontológica para el día 2020-08-19 a las 10:20:00 en CM SUBA</br></br>
 
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
 
 
<strong>Agendada exitosamente ✔️</strong></br></br> la cita odontológica ha sido agendada para el dia 2020-08-19 a las 10:20:00 en el centro médico CM SUBA.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>fcada36faae7fdb45d8cd4fe3571f517</strong></br></br>
 
¿Podemos hacer algo más por ti?
depende
Irrelevant
 
¿Podemos hacer algo más por ti?
5:46 PM


----

08/16/2020 @
5:47
PM
2
Intents
5:47 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buenas noches.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
hola, mi nombre es cristian
#cambiar_usuario
hola = @conversacion:saludo
hola = @extractor:hola
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
cristian = @nombre:Christian
 
 
¿En qué te puedo ayudar Christian?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Eliminar
#eliminar_cita
 
Para comenzar indícanos tu número y tipo de documento
5:47 PM

---

08/16/2020 @
5:49
PM
5
Intents
5:49 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buena tarde.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
mi nombre es sofia
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
sofia = @nombre:Sofía
 
 
¿Como podemos ayudarte Sofía?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Consultar
 
Para comenzar indícanos tu número y tipo de documento
10124789652
Irrelevant
101247 = @input_patterns:PEP
1012478965 = @input_patterns:CC
10124789652 = @sys-number:10124789652
 
 
Sofía he encontrado 13 citas agendadas con el documento PEP 10124789652</br></br>
 
Sofía, estas son las citas agendadas actualmente con el documento PEP 10124789652</br></br>
 
Cita <? $webhook_result_2.rows[0].doc.params.tipo_de_cita ?> reservada por <? $webhook_result_2.rows[0].doc.params.firstname ?> para el día <? $webhook_result_2.rows[0].doc.params.selected_date ?> a las <? $webhook_result_2.rows[0].doc.params.selected_time ?> en el centro medico <? $webhook_result_2.rows[0].doc.params.selected_medical_centre ?>
 
[Multi-option response]
Title: 2. 19 de julio de 2020 a las 10:00 am en CM GRANAHORRAR

 
Cita <? $webhook_result_2.rows[1].doc.params.tipo_de_cita ?> reservada por <? $webhook_result_2.rows[1].doc.params.firstname ?> para el día <? $webhook_result_2.rows[1].doc.params.selected_date ?> a las <? $webhook_result_2.rows[1].doc.params.selected_time ?> en el centro medico <? $webhook_result_2.rows[1].doc.params.selected_medical_centre ?>
 
[Multi-option response]
Title: 3. 6 de julio de 2020 a las 10:00 am en CM DUITAMA

 
Cita <? $webhook_result_2.rows[2].doc.params.tipo_de_cita ?> reservada por <? $webhook_result_2.rows[2].doc.params.firstname ?> para el día <? $webhook_result_2.rows[2].doc.params.selected_date ?> a las <? $webhook_result_2.rows[2].doc.params.selected_time ?> en el centro medico <? $webhook_result_2.rows[2].doc.params.selected_medical_centre ?>
 
[Multi-option response]
Title: 4. 19 de julio de 2020 a las 3:00 pm en CL INFANTIL

 
[Multi-option response]
Title: 5. 19 de julio de 2020 a las 6:30 am en CM SUBA

 
[Multi-option response]
Title: Página 1 de 3

Avanzar: avanzar
Retroceder: reroceder
Salir: salir
 
¿Deseas hacer algo mas?
avanzar
#control_bot
avanzar = @control_bot:avanzar
 
¿Cual es tu elección?
eliminar
#eliminar_cita
 
Para comenzar indícanos tu número y tipo de documento



---

08/16/2020 @
5:58
PM
4
Intents
5:58 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buena noche.</div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Joel
#cambiar_usuario
Joel = @nombre:Joel
 
 
¿Cuál es el motivo de tú visita el día de hoy Joel?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Consultar
#consultar_cita
 
Para comenzar indícanos tu número y tipo de documento
1123512
Irrelevant
112351 = @input_patterns:PEP
1123512 = @sys-number:1123512
 
 
Joel he encontrado 13 citas agendadas con el documento PEP 1123512</br></br>
 
Joel, estas son las citas agendadas actualmente con el documento PEP 1123512</br></br>
 
Cita <? $webhook_result_2.rows[0].doc.params.tipo_de_cita ?> reservada por <? $webhook_result_2.rows[0].doc.params.firstname ?> para el día <? $webhook_result_2.rows[0].doc.params.selected_date ?> a las <? $webhook_result_2.rows[0].doc.params.selected_time ?> en el centro medico <? $webhook_result_2.rows[0].doc.params.selected_medical_centre ?>
 
[Multi-option response]
Title: 2. 19 de julio de 2020 a las 10:00 am en CM GRANAHORRAR

 
Cita <? $webhook_result_2.rows[1].doc.params.tipo_de_cita ?> reservada por <? $webhook_result_2.rows[1].doc.params.firstname ?> para el día <? $webhook_result_2.rows[1].doc.params.selected_date ?> a las <? $webhook_result_2.rows[1].doc.params.selected_time ?> en el centro medico <? $webhook_result_2.rows[1].doc.params.selected_medical_centre ?>
 
[Multi-option response]
Title: 3. 6 de julio de 2020 a las 10:00 am en CM DUITAMA

 
Cita <? $webhook_result_2.rows[2].doc.params.tipo_de_cita ?> reservada por <? $webhook_result_2.rows[2].doc.params.firstname ?> para el día <? $webhook_result_2.rows[2].doc.params.selected_date ?> a las <? $webhook_result_2.rows[2].doc.params.selected_time ?> en el centro medico <? $webhook_result_2.rows[2].doc.params.selected_medical_centre ?>
 
[Multi-option response]
Title: 4. 19 de julio de 2020 a las 3:00 pm en CL INFANTIL

 
[Multi-option response]
Title: 5. 19 de julio de 2020 a las 6:30 am en CM SUBA

 
[Multi-option response]
Title: Página 1 de 3

Avanzar: avanzar
Retroceder: reroceder
Salir: salir
 
¿Deseas hacer algo mas?
avanzar
#control_bot
avanzar = @control_bot:avanzar
 
¿Cual es tu elección?
5:59 PM


---

08/16/2020 @
6:26
PM
4
Intents
6:26 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buena noche.</div>
 
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
 
 
¿Qué puedo hacer por ti el día de hoy Miguel?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Consultar
#consultar_cita
 
Para comenzar indícanos tu número y tipo de documento
5658111
Irrelevant
565811 = @input_patterns:PEP
5658111 = @sys-number:5658111
 
 
Miguel he encontrado 13 citas agendadas con el documento PEP 5658111</br></br>
 
Miguel, estas son las citas agendadas actualmente con el documento PEP 5658111</br></br>
 
Cita <? $webhook_result_2.rows[0].doc.params.tipo_de_cita ?> reservada por <? $webhook_result_2.rows[0].doc.params.firstname ?> para el día <? $webhook_result_2.rows[0].doc.params.selected_date ?> a las <? $webhook_result_2.rows[0].doc.params.selected_time ?> en el centro medico <? $webhook_result_2.rows[0].doc.params.selected_medical_centre ?>
 
[Multi-option response]
Title: 2. 19 de julio de 2020 a las 10:00 am en CM GRANAHORRAR

 
Cita <? $webhook_result_2.rows[1].doc.params.tipo_de_cita ?> reservada por <? $webhook_result_2.rows[1].doc.params.firstname ?> para el día <? $webhook_result_2.rows[1].doc.params.selected_date ?> a las <? $webhook_result_2.rows[1].doc.params.selected_time ?> en el centro medico <? $webhook_result_2.rows[1].doc.params.selected_medical_centre ?>
 
[Multi-option response]
Title: 3. 6 de julio de 2020 a las 10:00 am en CM DUITAMA

 
Cita <? $webhook_result_2.rows[2].doc.params.tipo_de_cita ?> reservada por <? $webhook_result_2.rows[2].doc.params.firstname ?> para el día <? $webhook_result_2.rows[2].doc.params.selected_date ?> a las <? $webhook_result_2.rows[2].doc.params.selected_time ?> en el centro medico <? $webhook_result_2.rows[2].doc.params.selected_medical_centre ?>
 
[Multi-option response]
Title: 4. 19 de julio de 2020 a las 3:00 pm en CL INFANTIL

 
[Multi-option response]
Title: 5. 19 de julio de 2020 a las 6:30 am en CM SUBA

 
[Multi-option response]
Title: Página 1 de 3

Avanzar: avanzar
Retroceder: reroceder
Salir: salir
 
¿Deseas hacer algo mas?
avanzar
#control_bot
avanzar = @control_bot:avanzar
 
¿Cual es tu elección?
Salir
 
¿Cual es tu elección?
6:27 PM


---

08/16/2020 @
6:32
PM
5
Intents
6:32 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buenas noches.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Jason
Irrelevant
 
Tu nombre es Jason, ¿es correcto?
Si
 
¿Como podemos ayudarte Jason?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Agendar
#agendar_cita
 
¿Qué tipo de cita deseas agendar Jason?
 
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
 
 
Jason tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
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
 
Jason procederemos a consultar disponibilidad con el documento CC 1234567890 para la cita médica, el día 2020-08-21 a las 13:00:00 en CM PORTAL NORTE</br></br>
 
¿Me autorizas a reservarla?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada exitosamente ✔️</strong></br></br>La cita médica ha sido agendada para el dia 2020-08-21 a las 13:00:00 en el centro médico CM PORTAL NORTE Jason.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>3402d0a919929138d28f5a39a0e524fc</strong></br></br>
 
¿Podemos hacer algo más por ti?
Graca
Irrelevant
 
¿Podemos hacer algo más por ti?
Oie
Irrelevant
 
¿Podemos hacer algo más por ti?
Jason
Irrelevant
 
¿Podemos hacer algo más por ti?
No
#decisión
No = @decisión:no
 
chao, ¡cuidate!
 
</br> </br>Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio Platzi - MinTic ICETEX Inteligencia Artificial. </br> </br> Antes que nada ¡¡¡Gracias!!! </br> </br> En el caso de uso que se presenta el chatbot realiza operaciones CRUD sobre una base de datos cloudant la cual ha sido expuesta mediante una API personalizada mediante functions. Todo serverless, una belleza!</br> </br> Es un gran detalle que quieras interactuar con este chatbot te agradezco cualquier comentario o critica constructiva. </br> </br>
Ok
#aceptar
Ok = @decisión:sí
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buena noche.</div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media


---

08/16/2020 @
6:42
PM
3
Intents
6:42 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas noches.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
mi nombre es sofia
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
sofia = @nombre:Sofía
 
 
¿Qué puedo hacer por ti el día de hoy Sofía?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Agendar
 
Cuéntame Sofía, ¿qué tipo de cita se te ofrece?
 
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
Es para María
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
María = @nombre:María
 
 
Sofía tenemos estas opciones disponibles para la cita odontológica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

19 de agosto de 2020 a las 10:20 am: Cita odontológica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

1 de septiembre de 2020 a las 4:00 pm : Cita odontológica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

21 de agosto de 2020 a las 1:00 PM: Cita odontológica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
 
</br>Elije una antes que alguien más la reserve
Cita odontológica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
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
 
Vamos a consultar disponibilidad con el documento CC 1234567890 de la cita odontológica Sofía para el día 2020-08-19 a las 10:20:00 en CM SUBA</br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Me autorizas a reservarla?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir



---

08/16/2020 @
9:59
PM
1
Intents
9:59 PM
la fecha de cumpleaños
#corregir
la = @pronombres:la
fecha = @dato:fecha
fecha = @opción:fecha
de = @preposición:de
de = @persona:ella
de = @verbo:dar
de = @persona:él
9:59 PM

---

08/16/2020 @
9:59
PM
2
Intents
9:59 PM
vine a molestarte
#conversacion
vine = @modo_tiempo:indicativo pasado
vine = @persona:yo
vine = @verbo:venir
a = @preposición:a
te = @pronombres:te
 
¿te puedo ayudar en algo?
no
 
¿Qué te trae por aquí entonces?
9:59 PM

---

08/16/2020 @
11:14
PM
3
Intents
11:14 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Aun de madrugada estamos aquí para ti. </div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
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
 
¡Hola! ¿como te va?
Medicina General
 
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
 
</br>¿Alguna de estas opciones te sirve?


---


08/16/2020 @
11:22
PM
8
Intents
11:22 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas noches.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Mal
#corregir
Mal = @adverbio:mal
 
¿de que tema se trata tu necesidad?
Ir al odontólogo
#despedidas
Ir = @verbo:ir
Ir = @modo_tiempo:infinitivo
odontólogo = @opción:odontológica
 
chao, ¡cuidate!
 
</br> </br>Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio Platzi - MinTic ICETEX Inteligencia Artificial. </br> </br> Antes que nada ¡¡¡Gracias!!! </br> </br> En el caso de uso que se presenta el chatbot realiza operaciones CRUD sobre una base de datos cloudant la cual ha sido expuesta mediante una API personalizada mediante functions. Todo serverless, una belleza!</br> </br> Es un gran detalle que quieras interactuar con este chatbot te agradezco cualquier comentario o critica constructiva. </br> </br>
Hola
#conversacion
Hola = @conversacion:saludo
Hola = @extractor:hola
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buena noche.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Mi nombre es cuper
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
cuper = @conversacion:bienestar
cuper = @decisión:sí
 
Antes de comenzar permiteme confirmar si he entendido bien tu nombre </br></br>¿Tú nombre es I nombre es cuper?
Si
#aceptar
Si = @decisión:sí
 
¿Cuál es el motivo de tú visita el día de hoy I nombre es cuper?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Agendar
#agendar_cita
 
Cuéntame I nombre es cuper, ¿qué tipo de cita se te ofrece?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
Para mí mama
#cambiar_usuario
Para = @persona:tú
Para = @preposición:para
Para = @modo_tiempo:imperativo
Para = @persona:él
Para = @persona:ella
Para = @modo_tiempo:indicativo presente
mí = @pronombres:mí
mama = @otra_persona:madre
mama = @genero:femenino
mama = @temática:madre
 
Por favor indicame el número de documento de tu mama
79128
Irrelevant
79128 = @sys-number:79128
 
 
I nombre es cuper tenemos estas opciones disponibles para la cita odontológica que estas solicitando:</br></br>
 
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
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada exitosamente ✔️</strong></br></br>La cita odontológica ha sido agendada para el dia 2020-08-21 a las 13:00:00 en el centro médico CM PORTAL NORTE I nombre es cuper.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>b9863cadfe5b29adb2250a476f4f6023</strong></br></br>
 
¿Podemos hacer algo más por ti?
11:24 PM


---

08/16/2020 @
11:48
PM
1
Intents
11:48 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buena noche.</div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
mi nombre es sofia
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
sofia = @nombre:Sofía
 
 
¿Como podemos ayudarte Sofía?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar



---

08/16/2020 @
11:53
PM
2
Intents
11:53 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buenas noches.</div>
 
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
 
Hola ¿Qué hay de nuevo?
como te llamas?
#habilidades
como = @adverbio:como
como = @persona:yo
como = @verbo:comer
como = @modo_tiempo:indicativo presente
te = @pronombres:te
llamas = @verbo:llamar
llamas = @persona:tú
llamas = @modo_tiempo:indicativo presente
? = @conversacion:Pregunta
 
Mi nombre es Santiago, estoy aquí para ayudarte con el agendamiento, modificación y eliminación de citas médicas y odontológicas.


---

08/17/2020 @
1:29
AM
1
Intents
1:29 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Sin importar la hora, estamos aquí para ti. </div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hola, soy Luis
#cambiar_usuario
Hola = @conversacion:saludo
Hola = @extractor:hola
soy = @persona:yo
soy = @verbo:ser
Luis = @nombre:Luis
 
 
Cuéntame Luis, ¿qué se te ofrece?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar


---

08/17/2020 @
1:32
AM
4
Intents
1:32 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">De día, de noche e incluso de madrugada estamos aquí para servirte. </div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Xochitl
Irrelevant
 
Tu nombre es Xochitl, ¿es correcto?
no
#decisión
no = @decisión:no
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Xochitl
Irrelevant
 
Tu nombre es Xochitl, ¿es correcto?
si
#aceptar
si = @decisión:sí
 
¿Qué puedo hacer por ti el día de hoy Xochitl?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Consultar
#consultar_cita
 
Para comenzar indícanos tu número y tipo de documento
1234
Irrelevant
1234 = @sys-number:1234
 
He interpretado el numero 1234, ¿es correcto?
sí
#decisión
sí = @decisión:sí
sí = @pronombres:sí
 
No he recibido el tipo de documento que acompaña el numero que me acabas de dar. Por favor repitemelo de nuevo.
1:33 AM

---


08/17/2020 @
1:33
AM
5
Intents
1:33 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Aun de madrugada estamos aquí para ti. </div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Lui
Irrelevant
 
Tu nombre es Lui, ¿es correcto?
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
¿En qué te puedo ayudar Lui?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Eliminar
#eliminar_cita
 
Para comenzar indícanos tu número y tipo de documento
¿Cuál documento?
#corregir
documento = @dato:numero_documento
? = @conversacion:Pregunta
 
Para comenzar por favor indícame tipo y número de documento del paciente que requiere la cita </br></br>Si la cita es para ti házmelo saber para usar tus preferencias habituales.
No sé qué documento
#denegar
No = @decisión:no
No sé = @opción:indeterminado
sé = @modo_tiempo:imperativo
sé = @persona:yo
sé = @persona:tú
sé = @verbo:ser
sé = @verbo:saber
sé = @modo_tiempo:indicativo presente
documento = @dato:numero_documento
 
Para comenzar indícanos tu número y tipo de documento
No sé que documento
#denegar
No = @decisión:no
No sé = @opción:indeterminado
sé = @modo_tiempo:imperativo
sé = @persona:yo
sé = @persona:tú
sé = @verbo:ser
sé = @verbo:saber
sé = @modo_tiempo:indicativo presente
documento = @dato:numero_documento
 
Para comenzar por favor indícame tipo y número de documento del paciente que requiere la cita </br></br>Si la cita es para ti házmelo saber para usar tus preferencias habituales.
1:36 AM


---


08/17/2020 @
4:32
AM
8
Intents
4:32 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Si tu trasnochas, aquí nos trasnochamos contigo. </div>
 
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
 
¡Hola! ¿como te va?
bn gracias
#General_Positive_Feedback
gracias = @conversacion:agradecimiento
gracias = @conversacion:cortesia
 
de nada.
ivan
#cambiar_usuario
ivan = @persona:ellos
ivan = @nombre:Iván
 
¿en que te puedo colaborar?
dientes
#corregir
dientes = @especialidad:odontológica
 
Que deseas que corrijamos?
cita odontologica
#agendar_cita
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
cita odontologica = @opción:odontológica
odontologica = @dato:tipo_de_cita
odontologica = @especialidad:odontológica
hola
#conversacion
hola = @conversacion:saludo
hola = @extractor:hola
 
Que deseas corregir?
todo
#conversacion
todo = @adverbio:todo
 
¿de que tema se trata tu necesidad?
cita medica
#agendar_cita
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
3
#decisión
3 = @opción:tercera
3 = @sys-number:3
 
Has elegido la tercera opción:
 
tu cita médica quedará reservada para el día 21 de agosto de 2020 a las 1:00 PM en el centro médico CM SUBA, con el documento CC 1234567890. </br></br>Recuerda que debes llegar 30 minutos antes y pasar por el punto ágil para facturar tu cuota moderadora.</br></br>Si no puedes ir a tu cita, cancela con 3 horas de anticipación y permite que alguien la tome por ti.</br></br>
 
¿Esta bien?
no
#decisión
no = @decisión:no
 
¿Que deseas corregir?
numero de documento
#corregir
numero de documento = @dato:numero_documento
de = @preposición:de
de = @persona:ella
de = @verbo:dar
de = @persona:él
 
muy bien por favor dime de nuevo el numero y tipo de documento para realizar la corrección.
456789654
Irrelevant
456789 = @input_patterns:PEP
456789654 = @sys-number:456789654
 
 
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
 
</br>¿Alguna de estas opciones te sirve?
1
#decisión
1 = @opción:primera
1 = @sys-number:1
 
Has elegido la primera opción:
 
tu cita médica quedará reservada para el día 19 de agosto de 2020 a las 10:20 am en el centro médico CM SUBA, con el documento CC 1234567890. </br></br>Recuerda que debes llegar 30 minutos antes y pasar por el punto ágil para facturar tu cuota moderadora.</br></br>Si no puedes ir a tu cita, cancela con 3 horas de anticipación y permite que alguien la tome por ti.</br></br>
 
¿Esta bien?
salir
#control_bot
salir = @opción:Salir
salir = @control_bot:salir
salir = @verbo:salir
salir = @modo_tiempo:infinitivo
4:35 AM


---


08/17/2020 @
4:36
AM
4
Intents
4:36 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Aun de madrugada estamos aquí para ti. </div>
 
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
 
 
¿En qué te puedo ayudar Miguel?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Consultar
 
Para comenzar indícanos tu número y tipo de documento
1234
Irrelevant
1234 = @sys-number:1234
 
He interpretado el numero 1234, ¿es correcto?
si
#aceptar
si = @decisión:sí
 
No he recibido el tipo de documento que acompaña el numero que me acabas de dar. Por favor repitemelo de nuevo.


---

08/17/2020 @
1:50
PM
6
Intents
1:50 PM
 
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
una cita
#agendar_cita
una = @sys-number:1
cita = @persona:ella
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
 
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
45612378
Irrelevant
456123 = @input_patterns:PEP
45612378 = @sys-number:45612378
 
 
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
 
</br>¿Te sirve alguna de las anteriores o quieres probar diciéndome una fecha y hora?
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
 
 
<strong>Agendada exitosamente ✔️</strong></br></br> la cita médica ha sido agendada para el dia 2020-09-01 a las 16:00:00 en el centro médico CM GRANAHORRAR.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>a72f661af6417931106af9703d5c3005</strong></br></br>
 
¿Podemos hacer algo más por ti?
No
#decisión
No = @decisión:no
 
¡Gracias por utilizar nuestro servicio de citas online vuelve pronto!
 
</br> </br>Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio Platzi - MinTic ICETEX Inteligencia Artificial. </br> </br> Antes que nada ¡¡¡Gracias!!! </br> </br> En el caso de uso que se presenta el chatbot realiza operaciones CRUD sobre una base de datos cloudant la cual ha sido expuesta mediante una API personalizada mediante functions. Todo serverless, una belleza!</br> </br> Es un gran detalle que quieras interactuar con este chatbot te agradezco cualquier comentario o critica constructiva. </br> </br>


---

08/17/2020 @
6:59
PM
2
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
Eliminar
#eliminar_cita
 
Para comenzar indícanos tu número y tipo de documento
7:00 PM

---


08/17/2020 @
9:18
PM
5
Intents
9:18 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buena noche.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
me llamo miguel
 
 
¿Qué puedo hacer por ti el día de hoy Miguel?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Agendar
 
¿Qué tipo de cita deseas agendar Miguel?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
Medicina General
 
¿La cita médica es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
Es para mí
 
 
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
Cita médica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
 
Vamos a consultar disponibilidad con el documento CC 1234567890 de la cita médica Miguel para el día 2020-08-19 a las 10:20:00 en CM SUBA</br></br>
 
¿Quieres agendarla?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
 
 
<strong>Agendada exitosamente ✔️</strong></br></br>Miguel la cita médica ha sido agendada para el dia 2020-08-19 a las 10:20:00 en el centro médico CM SUBA.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>36e411aa194dffd46d1beb4fd79e1f61</strong></br></br>
 
¿Podemos hacer algo más por ti?
chupala
Irrelevant
 
¿Podemos hacer algo más por ti?
adios
#despedidas
adios = @conversacion:despedida
 
chao, ¡cuidate!
 
</br> </br>Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio Platzi - MinTic ICETEX Inteligencia Artificial. </br> </br> Antes que nada ¡¡¡Gracias!!! </br> </br> En el caso de uso que se presenta el chatbot realiza operaciones CRUD sobre una base de datos cloudant la cual ha sido expuesta mediante una API personalizada mediante functions. Todo serverless, una belleza!</br> </br> Es un gran detalle que quieras interactuar con este chatbot te agradezco cualquier comentario o critica constructiva. </br> </br>


---

08/17/2020 @
9:18
PM
5
Intents
9:18 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buena noche.</div>
 
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
 
 
¿Qué puedo hacer por ti el día de hoy Miguel?
 
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
 
Vamos a consultar disponibilidad con el documento CC 1234567890 de la cita médica Miguel para el día 2020-08-19 a las 10:20:00 en CM SUBA</br></br>
 
¿Quieres agendarla?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada exitosamente ✔️</strong></br></br>Miguel la cita médica ha sido agendada para el dia 2020-08-19 a las 10:20:00 en el centro médico CM SUBA.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>36e411aa194dffd46d1beb4fd79e1f61</strong></br></br>
 
¿Podemos hacer algo más por ti?
chupala
Irrelevant
 
¿Podemos hacer algo más por ti?
adios
#despedidas
adios = @conversacion:despedida
 
chao, ¡cuidate!
 
</br> </br>Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio Platzi - MinTic ICETEX Inteligencia Artificial. </br> </br> Antes que nada ¡¡¡Gracias!!! </br> </br> En el caso de uso que se presenta el chatbot realiza operaciones CRUD sobre una base de datos cloudant la cual ha sido expuesta mediante una API personalizada mediante functions. Todo serverless, una belleza!</br> </br> Es un gran detalle que quieras interactuar con este chatbot te agradezco cualquier comentario o critica constructiva. </br> </br>

---

08/17/2020 @
11:08
PM
1
Intents
11:08 PM
Hola
#conversacion
Hola = @conversacion:saludo
Hola = @extractor:hola
 
Que bueno verte de nuevo por aquí , ¿Como estas?

---

08/18/2020 @
12:03
AM
1
Intents
12:03 AM
 
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
 
Buenas ¿Como va todo? <break></break>
bien
#conversacion
bien = @conversacion:bienestar
bien = @adverbio:bien
 
que alegria saber que todo esta bien para ti,
 
¿te puedo ayudar en algo?
12:05 AM

---

08/18/2020 @
1:30
AM
9
Intents
1:30 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Si tu trasnochas, aquí nos trasnochamos contigo. </div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
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
bien y a ti?
#conversacion
bien = @conversacion:bienestar
bien = @adverbio:bien
a = @preposición:a
ti = @dato:tipo_documento
ti = @pronombres:ti
ti? = @tipo_documento:TI
? = @conversacion:Pregunta
 
maravilloso,
 
¿como puedo ayudarte?
quiero
#aceptar
quiero = @persona:yo
quiero = @verbo:querer
quiero = @modo_tiempo:indicativo presente
 
¿Cuál es el motivo de tu visita a este canal?
una
Irrelevant
una = @sys-number:1
cita
#agendar_cita
cita = @persona:ella
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
 
Cuéntame , ¿qué tipo de cita se te ofrece?
 
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
12a28iswhq8
Irrelevant
 
 
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
 
</br>¿Alguna de estas opciones te sirve?
me equivoqué
#corregir
me = @pronombres:me
 
¿Que deseas corregir?
El NUMero de dcumento de mi TIA
#recuperar_datos
El = @preposición:la del
El = @pronombres:el
El NUMero de = @opción:teléfono
NUMero de dcumento = @dato:numero_documento
de = @persona:ella
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
de = @persona:él
de = @preposición:de
de = @verbo:dar
mi = @pronombres:mí
mi TIA = @temática:tio
TIA = @genero:femenino
TIA = @otra_persona:tío
 
muy bien por favor dime de nuevo el numero y tipo de documento para realizar la corrección.
12345678
Irrelevant
123456 = @input_patterns:PEP
12345678 = @sys-number:12345678
 
 
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
 
</br>¿Te sirve alguna de las anteriores o quieres probar diciéndome una fecha y hora?
la del 19 de agosto a las 10
#emergencia
la = @pronombres:la
la del = @preposición:la del
19 de agosto = @sys-date:2020-08-19
de = @preposición:de
de = @persona:ella
de = @verbo:dar
de = @persona:él
a = @preposición:a
a las 10 = @sys-time:10:00:00
las = @pronombres:las
 
Vamos a consultar disponibilidad con el documento CC 1234567890 de la cita médica para el día 2020-08-19 a las 10:00:00 en </br></br>
 
¿Está bien?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada con éxito ✔️</strong></br></br> la cita médica ha sido agendada para el dia 2020-08-19 a las 10:00:00 en el centro médico .</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>7f6a4948a29af2b3c0c53ead77dca234</strong></br></br>
 
¿Podemos hacer algo más por ti?


---

08/18/2020 @
10:02
AM
8
Intents
10:02 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buenos días.</div>
 
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
 
 
¿Como podemos ayudarte Miguel?
 
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
nada
#denegar
nada = @decisión:no
nada = @adverbio:nada
nada = @pronombres:nada
 
¿En ese caso, por favor indicame el tipo y número de documento de identificación de la persona que necesita la cita?
98717046
Irrelevant
987170 = @input_patterns:PEP
98717046 = @sys-number:98717046
 
 
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
 
</br>¿Alguna de estas opciones te sirve?
3
#decisión
3 = @opción:tercera
3 = @sys-number:3
 
Has elegido la tercera opción:
 
Miguel tu cita médica quedará reservada para el día 21 de agosto de 2020 a las 1:00 PM en el centro médico CM SUBA, con el documento CC 1234567890. </br></br>Recuerda que debes llegar 30 minutos antes y pasar por el punto ágil para facturar tu cuota moderadora.</br></br>Si no puedes ir a tu cita, cancela con 3 horas de anticipación y permite que alguien la tome por ti.</br></br>
 
¿Esta bien?
no
#decisión
no = @decisión:no
 
¿Que deseas corregir?
hora
#corregir
hora = @dato:hora
 
Muy bien corregiremos la hora, dímela de nuevo por favor
4:00 pm
#cambiar_turno
4 = @opción:cuarta
4:00 pm = @sys-time:16:00:00
pm = @turno:T
 
¿En que fecha?
30 de agosto
#corregir
30 de agosto = @sys-date:2020-08-30
de = @preposición:de
de = @persona:ella
de = @verbo:dar
de = @persona:él
 
Vamos a consultar disponibilidad con el documento CC 1234567890 de la cita médica Miguel para el día 2020-08-30 a las 16:00:00 en CM PORTAL NORTE</br></br>
 
¿Está bien?
 
[Multi-option response]

Sí: Sí
No: No
Corregir: Corregir
Sí
#decisión
Sí = @decisión:sí
Sí = @pronombres:sí
 
 
<strong>Agendada exitosamente ✔️</strong></br></br>Miguel la cita médica ha sido agendada para el dia 2020-08-30 a las 16:00:00 en el centro médico CM PORTAL NORTE.</br></br>Es necesario presentarse 20 minutos antes con el documento de identificación CC 1234567890 y pasar por el punto de pago a cancelar la cuota co-pago correspondiente.</br></br> <a href="https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=2c556620-03e4-4828-9aad-341320d9effe&serviceInstanceID=c851319f-2f12-41f0-822d-b86311301578">Código de Confirmación:</a> </br><strong>def3c23830cfd159489630b9c790edfe</strong></br></br>
 
¿Podemos hacer algo más por ti?
no muchas gracias
#conversacion
no = @decisión:no
muchas = @pronombres:muchas
muchas gracias = @conversacion:cortesia
muchas gracias = @conversacion:agradecimiento
 
chao, ¡cuidate!
 
</br> </br>Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio Platzi - MinTic ICETEX Inteligencia Artificial. </br> </br> Antes que nada ¡¡¡Gracias!!! </br> </br> En el caso de uso que se presenta el chatbot realiza operaciones CRUD sobre una base de datos cloudant la cual ha sido expuesta mediante una API personalizada mediante functions. Todo serverless, una belleza!</br> </br> Es un gran detalle que quieras interactuar con este chatbot te agradezco cualquier comentario o critica constructiva. </br> </br>



----

08/18/2020 @
3:32
PM
5
Intents
3:32 PM
 
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
que puedo hacer?
#habilidades
que puedo hacer? = @emergencia:quehacer
puedo = @verbo:poder
puedo = @persona:yo
puedo = @modo_tiempo:indicativo presente
hacer = @modo_tiempo:infinitivo
hacer = @verbo:hacer
? = @conversacion:Pregunta
 
Lo mas importante de todo es guardar la calma.
vale
#corregir
vale = @verbo:valer
vale = @persona:ella
vale = @persona:tú
vale = @decisión:sí
vale = @modo_tiempo:imperativo
vale = @persona:él
vale = @modo_tiempo:indicativo presente
 
¿y cual es el tipo de documento?
 
Lo mas importante de todo es guardar la calma.
que documento?
#corregir
documento = @dato:numero_documento
? = @conversacion:Pregunta
 
Que deseas que corrijamos?
mi cuenta
#recuperar_datos
mi = @pronombres:mí
cuenta = @persona:ella
cuenta = @modo_tiempo:imperativo
cuenta = @persona:él
cuenta = @persona:tú
cuenta = @verbo:contar
cuenta = @modo_tiempo:indicativo presente
 
Que deseas corregir?
 
Lo mas importante de todo es guardar la calma.
mis credenciales
#emergencia
hola?
#conversacion
hola = @conversacion:saludo
hola = @extractor:hola
? = @conversacion:Pregunta
 
Hola, ¿como te encuentras hoy? <break></break>
bien
#conversacion
bien = @conversacion:bienestar
bien = @adverbio:bien
 
genial,
 
¿Cuál es el motivo de tu visita a este canal?
y tu?
#conversacion
tu = @persona:tú
? = @conversacion:Pregunta
 
¿Cuál es el motivo de tu visita a este canal?
3:34 PM

---

08/18/2020 @
6:07
PM
1
Intents
6:07 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas noches.</div>
 
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
bien
#conversacion
bien = @conversacion:bienestar
bien = @adverbio:bien
 
genial,
 
¿en que te puedo colaborar?

---

08/18/2020 @
8:06
PM
4
Intents
8:06 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas noches.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
mi nombre es sofia
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
sofia = @nombre:Sofía
 
 
¿Qué puedo hacer por ti el día de hoy Sofía?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Consultar
#consultar_cita
 
Para comenzar indícanos tu número y tipo de documento
hghg 45411
Irrelevant
45411 = @sys-number:45411
 
He interpretado el numero 45411, ¿es correcto?
si
#aceptar
si = @decisión:sí
 
No he recibido el tipo de documento que acompaña el numero que me acabas de dar. Por favor repitemelo de nuevo.


---


08/18/2020 @
9:55
PM
4
Intents
9:55 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buena noche.</div>
 
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
 
Hola ¿Qué hay de nuevo?
que opciones tienes?
#listar_opciones
tienes = @persona:tú
tienes = @verbo:tener
tienes = @modo_tiempo:indicativo presente
? = @conversacion:Pregunta
 
Tenemos servicio de agendamiento, consulta, modificación y eliminación de citas médicas y odontológicas. ¿en que te puedo ayudar el día de hoy?
quiero hacer una consulta
#agendar_cita
quiero = @persona:yo
quiero = @verbo:querer
quiero = @modo_tiempo:indicativo presente
hacer = @verbo:hacer
hacer = @modo_tiempo:infinitivo
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
 
¿La cita médica es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
para un niño
#emergencia
para = @persona:tú
para = @preposición:para
para = @modo_tiempo:imperativo
para = @persona:él
para = @persona:ella
para = @modo_tiempo:indicativo presente
niño = @especialidad:pediatría
 
 
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


---

08/19/2020 @
3:31
PM
9
Intents
3:31 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buena tarde.</div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
hola fer
#General_Greetings
hola = @conversacion:saludo
hola = @extractor:hola
 
Buenas ¿Como va todo? <break></break>
bien
#conversacion
bien = @conversacion:bienestar
bien = @adverbio:bien
 
que chevere que estes bien,
 
¿de que tema se trata tu necesidad?
y tu
#conversacion
tu = @persona:tú
 
¿de que tema se trata tu necesidad?
cita
#agendar_cita
cita = @persona:ella
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
 
Cuéntame , ¿qué tipo de cita se te ofrece?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
medicina
#agendar_cita
medicina = @especialidad:médica
medicina = @opción:médica
medicina = @temática:ciencias naturales
 
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

19 de agosto de 2020 a las 10:20 am: Cita médica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

1 de septiembre de 2020 a las 4:00 pm : Cita médica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

21 de agosto de 2020 a las 1:00 PM: Cita médica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
 
</br>¿Alguna de estas opciones te sirve?
no
#decisión
no = @decisión:no
 
¿Que deseas corregir?
fecha
#corregir
fecha = @dato:fecha
fecha = @opción:fecha
 
Entendido. Corregiremos la fecha, dímela de nuevo por favor
2021
Irrelevant
2021 = @sys-date:2021-01-01
2021 = @sys-date:2021-12-31
2021 = @sys-number:2021
 
A que hora la prefieres?
4
#decisión
4 = @opción:cuarta
4 = @sys-number:4
 
procederemos a consultar disponbilidad con el documento CC 1234567890 para la cita médica, el dia 2021-01-01 a las por la tarde</br></br>
 
¿Esta bien?
si
#aceptar
si = @decisión:sí
 
{"id":"84245254fb8be3b1562bd1ccaa0d5162","ok":true,"rev":"1-366302ae80d42dbcfc25b74096684807"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?
no
#decisión
no = @decisión:no
 
Hasta luego, ¡vuelve pronto!
 
</br> </br>Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio Platzi - MinTic ICETEX Inteligencia Artificial. </br> </br> Antes que nada ¡¡¡Gracias!!! </br> </br> En el caso de uso que se presenta el chatbot realiza operaciones CRUD sobre una base de datos cloudant la cual ha sido expuesta mediante una API personalizada mediante functions. Todo serverless, una belleza!</br> </br> Es un gran detalle que quieras interactuar con este chatbot te agradezco cualquier comentario o critica constructiva. </br> </br>
muy bien, por el ejemplo
#General_Positive_Feedback
muy = @adverbio:muy
muy bien = @conversacion:bienestar
bien = @adverbio:bien
por = @preposición:por
el = @preposición:la del
el = @pronombres:el
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buena tarde.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media


---


08/19/2020 @
7:19
PM
3
Intents
7:19 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas noches.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hi
#conversacion
Hi = @conversacion:saludo
 
Hola ¿Como estas?
Fine and you ?
#despedidas
Fine = @persona:yo
? = @conversacion:Pregunta
 
¿como puedo ayudarte?
Necesito un asesor
 
Que deseas que corrijamos?
7:19 PM

---

08/19/2020 @
7:20
PM
7
Intents
7:20 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buena noche.</div>
 
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
Dame una cita
#agendar_cita
Da = @persona:él
Da = @persona:tú
Da = @verbo:dar
Da = @persona:ella
Dame = @decisión:sí
me = @pronombres:me
una = @sys-number:1
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
 
Cuéntame , ¿qué tipo de cita se te ofrece?
 
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
Para mi tía Esperanza
#cambiar_usuario
Para = @persona:tú
Para = @preposición:para
Para = @modo_tiempo:imperativo
Para = @persona:él
Para = @persona:ella
Para = @modo_tiempo:indicativo presente
mi = @pronombres:mí
tía = @otra_persona:tío
 
Por favor indicame el número de documento de tu tía
23489012
Irrelevant
234890 = @input_patterns:PEP
23489012 = @sys-number:23489012
 
 
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
3
#decisión
3 = @opción:tercera
3 = @sys-number:3
 
Has elegido la tercera opción:
 
tu cita médica quedará reservada para el día 21 de agosto de 2020 a las 1:00 PM en el centro médico CM SUBA, con el documento CC 1234567890. </br></br>Recuerda que debes llegar 30 minutos antes y pasar por el punto ágil para facturar tu cuota moderadora.</br></br>Si no puedes ir a tu cita, cancela con 3 horas de anticipación y permite que alguien la tome por ti.</br></br>
 
¿Esta bien?
Si, me puedes dar los datos de mi tia
#recuperar_datos
Si = @decisión:sí
me = @pronombres:me
puedes = @persona:tú
puedes = @verbo:poder
puedes = @modo_tiempo:indicativo presente
dar = @verbo:dar
dar = @modo_tiempo:infinitivo
los = @pronombres:los
de = @persona:él
de = @preposición:de
de = @verbo:dar
de = @persona:ella
mi = @pronombres:mí
mi tia = @temática:tio
tia = @otra_persona:tío
tia = @genero:femenino
 
{"id":"5f89f97fa6ec55a747a35731acd1f8df","ok":true,"rev":"1-eab217a4ca559918a27651a9e34bd87b"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?
Como quedó agendada la cita
#consultar_cita
Como = @adverbio:como
Como = @modo_tiempo:indicativo presente
Como = @persona:yo
Como = @verbo:comer
quedó = @persona:él
quedó = @modo_tiempo:indicativo pasado
quedó = @persona:ella
quedó = @verbo:quedar
la = @pronombres:la
cita = @persona:tú
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
cita = @modo_tiempo:imperativo
 
Para comenzar indícanos tu número y tipo de documento

---

08/19/2020 @
7:21
PM
5
Intents
7:21 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buena noche.</div>
 
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
 
Buenas ¿Como va todo? <break></break>
Bien
#conversacion
Bien = @conversacion:bienestar
Bien = @adverbio:bien
 
genial,
 
¿Cuál es el motivo de tu visita a este canal?
Citas
#consultar_cita
Citas = @persona:tú
Citas = @verbo:citar
Citas = @modo_tiempo:indicativo presente
 
Para comenzar indícanos tu número y tipo de documento
CC 53056789
#corregir
CC = @tipo_documento:CC
530567 = @input_patterns:PEP
53056789 = @sys-number:53056789
 
 
he encontrado 13 citas agendadas con el documento CC 53056789</br></br>
 
, estas son las citas agendadas actualmente con el documento CC 53056789</br></br>
 
Cita <? $webhook_result_2.rows[0].doc.params.tipo_de_cita ?> reservada por <? $webhook_result_2.rows[0].doc.params.firstname ?> para el día <? $webhook_result_2.rows[0].doc.params.selected_date ?> a las <? $webhook_result_2.rows[0].doc.params.selected_time ?> en el centro medico <? $webhook_result_2.rows[0].doc.params.selected_medical_centre ?>
 
[Multi-option response]
Title: 2. 19 de julio de 2020 a las 10:00 am en CM GRANAHORRAR

 
Cita <? $webhook_result_2.rows[1].doc.params.tipo_de_cita ?> reservada por <? $webhook_result_2.rows[1].doc.params.firstname ?> para el día <? $webhook_result_2.rows[1].doc.params.selected_date ?> a las <? $webhook_result_2.rows[1].doc.params.selected_time ?> en el centro medico <? $webhook_result_2.rows[1].doc.params.selected_medical_centre ?>
 
[Multi-option response]
Title: 3. 6 de julio de 2020 a las 10:00 am en CM DUITAMA

 
Cita <? $webhook_result_2.rows[2].doc.params.tipo_de_cita ?> reservada por <? $webhook_result_2.rows[2].doc.params.firstname ?> para el día <? $webhook_result_2.rows[2].doc.params.selected_date ?> a las <? $webhook_result_2.rows[2].doc.params.selected_time ?> en el centro medico <? $webhook_result_2.rows[2].doc.params.selected_medical_centre ?>
 
[Multi-option response]
Title: 4. 19 de julio de 2020 a las 3:00 pm en CL INFANTIL

 
[Multi-option response]
Title: 5. 19 de julio de 2020 a las 6:30 am en CM SUBA

 
[Multi-option response]
Title: Página 1 de 3

Avanzar: avanzar
Retroceder: reroceder
Salir: salir
 
¿Deseas hacer algo mas?
avanzar
#control_bot
avanzar = @control_bot:avanzar
 
¿Cual es tu elección?
5
#corregir
5 = @sys-number:5
 
5 no hace parte de las opciones mostradas. Puedes seleccionar una cita indicando la primera, la segunda o la tercera. Ademas si ninguna de las opciones se ajusta a tus necesidades, puedes solicitarme que busque nuevas opciones.
2
#decisión
2 = @opción:segunda
2 = @sys-number:2
 
Has elegido la segunda opción:
 
Estimado , por favor ingresa tu fecha de nacimiento
20/08/2001
#corregir
20/08/2001 = @sys-date:2001-08-20
 
No hemos podido cotejar tu información proporcionada con la base de datos. La cita no ha sido eliminada. Vamos a intentarlo de nuevo.
 
Estimado , por favor ingresa tu fecha de nacimiento

---

08/19/2020 @
7:21
PM
5
Intents
7:21 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buena noche.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hola
 
Buenas ¿Como va todo? <break></break>
Bien
 
genial,
 
¿Cuál es el motivo de tu visita a este canal?
Citas
 
Para comenzar indícanos tu número y tipo de documento
CC 53056789
 
 
he encontrado 13 citas agendadas con el documento CC 53056789</br></br>
 
, estas son las citas agendadas actualmente con el documento CC 53056789</br></br>
 
Cita <? $webhook_result_2.rows[0].doc.params.tipo_de_cita ?> reservada por <? $webhook_result_2.rows[0].doc.params.firstname ?> para el día <? $webhook_result_2.rows[0].doc.params.selected_date ?> a las <? $webhook_result_2.rows[0].doc.params.selected_time ?> en el centro medico <? $webhook_result_2.rows[0].doc.params.selected_medical_centre ?>
 
[Multi-option response]
Title: 2. 19 de julio de 2020 a las 10:00 am en CM GRANAHORRAR

 
Cita <? $webhook_result_2.rows[1].doc.params.tipo_de_cita ?> reservada por <? $webhook_result_2.rows[1].doc.params.firstname ?> para el día <? $webhook_result_2.rows[1].doc.params.selected_date ?> a las <? $webhook_result_2.rows[1].doc.params.selected_time ?> en el centro medico <? $webhook_result_2.rows[1].doc.params.selected_medical_centre ?>
 
[Multi-option response]
Title: 3. 6 de julio de 2020 a las 10:00 am en CM DUITAMA

 
Cita <? $webhook_result_2.rows[2].doc.params.tipo_de_cita ?> reservada por <? $webhook_result_2.rows[2].doc.params.firstname ?> para el día <? $webhook_result_2.rows[2].doc.params.selected_date ?> a las <? $webhook_result_2.rows[2].doc.params.selected_time ?> en el centro medico <? $webhook_result_2.rows[2].doc.params.selected_medical_centre ?>
 
[Multi-option response]
Title: 4. 19 de julio de 2020 a las 3:00 pm en CL INFANTIL

 
[Multi-option response]
Title: 5. 19 de julio de 2020 a las 6:30 am en CM SUBA

 
[Multi-option response]
Title: Página 1 de 3

Avanzar: avanzar
Retroceder: reroceder
Salir: salir
 
¿Deseas hacer algo mas?
avanzar
#control_bot
avanzar = @control_bot:avanzar
 
¿Cual es tu elección?
5
#corregir
5 = @sys-number:5
 
5 no hace parte de las opciones mostradas. Puedes seleccionar una cita indicando la primera, la segunda o la tercera. Ademas si ninguna de las opciones se ajusta a tus necesidades, puedes solicitarme que busque nuevas opciones.
2
#decisión
2 = @opción:segunda
2 = @sys-number:2
 
Has elegido la segunda opción:
 
Estimado , por favor ingresa tu fecha de nacimiento
20/08/2001
#corregir
20/08/2001 = @sys-date:2001-08-20
 
No hemos podido cotejar tu información proporcionada con la base de datos. La cita no ha sido eliminada. Vamos a intentarlo de nuevo.
 
Estimado , por favor ingresa tu fecha de nacimiento
7:23 PM

---

08/19/2020 @
8:57
PM
2
Intents
8:57 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas noches.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Para comenzar dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
mi nombre es sofia
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
sofia = @nombre:Sofía
 
 
Cuéntame Sofía, ¿qué se te ofrece?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Consultar
#consultar_cita
 
Para comenzar indícanos tu número y tipo de documento


---

08/20/2020 @
8:27
AM
7
Intents
8:27 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buenos días.</div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Juan
#cambiar_usuario
Juan = @nombre:Juan
 
 
¿En qué te puedo ayudar Juan?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Consulta
#agendar_cita
 
Cuéntame Juan, ¿qué tipo de cita se te ofrece?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
Odonto
Irrelevant
 
Cuéntame, ¿que se te ofrece? </br> </br>1. Medicina general, </br>2. Odontología Básica.
Odontologa
#corregir
Odontologa = @especialidad:odontológica
 
Cuéntame, ¿que se te ofrece? </br> </br>1. Medicina general, </br>2. Odontología Básica.
2
#decisión
2 = @opción:segunda
2 = @sys-number:2
 
¿Es para ti o es para alguien más?
 
[Multi-option response]

Para mí: Es para mí
Para mi tía: Es para mi tía
Para María: Es para María
Otro
#cambiar_agente
Otro = @opción:otra
 
 
Juan tenemos estas opciones disponibles para la cita odontológica que estas solicitando:</br></br>
 
[Multi-option response]
Title: 1. Opción primera en CM SUBA

19 de agosto de 2020 a las 10:20 am: Cita odontológica el día 19 de agosto de 2020 a las 10:20 am en CM SUBA
 
[Multi-option response]
Title: 2. Opción segunda en CM GRANAHORRAR

1 de septiembre de 2020 a las 4:00 pm : Cita odontológica el día 1 de septiembre de 2020 a las 4:00 pm en CM GRANAHORRAR
 
[Multi-option response]
Title: 3. Opción tercera en CM PORTAL NORTE

21 de agosto de 2020 a las 1:00 PM: Cita odontológica el día 21 de agosto de 2020 a las 1:00 PM en CM PORTAL NORTE
 
</br>Elije una antes que alguien más la reserve
1
#decisión
1 = @opción:primera
1 = @sys-number:1
 
Has elegido la primera opción:
 
Juan tu cita odontológica quedará reservada para el día 19 de agosto de 2020 a las 10:20 am en el centro médico CM SUBA, con el documento CC 1234567890. </br></br>Recuerda que debes llegar 30 minutos antes y pasar por el punto ágil para facturar tu cuota moderadora.</br></br>Si no puedes ir a tu cita, cancela con 3 horas de anticipación y permite que alguien la tome por ti.</br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Esta bien?
N
#corregir
 
¿Que deseas corregir?
Todo
#conversacion
Todo = @adverbio:todo
 
Por favor indícame, ¿que hay que corregir?
H
#corregir
 
¿Que deseas que corrijamos?
8:29 AM


---

08/20/2020 @
8:53
AM
3
Intents
8:53 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenos días.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
Para comenzar dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hola me llamo rafa
#cambiar_usuario
Hola = @conversacion:saludo
Hola me llamo = @extractor:hola me llamo
me = @pronombres:me
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
 
Antes de comenzar permiteme confirmar si he entendido bien tu nombre </br></br>¿Tú nombre es Ola me llamo rafa?
Rafa
Irrelevant
 
No soy muy bueno con los nombres, por eso prefiero asegurarme antes de empezar. </br></br>¿Te llamás Ola me llamo rafa?
rafa
Irrelevant
 
Antes de comenzar permiteme confirmar si he entendido bien tu nombre </br></br>¿Tú nombre es Ola me llamo rafa?
SI
 
¿Qué puedo hacer por ti el día de hoy Ola me llamo rafa?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
8:57 AM

---

08/20/2020 @
10:11
AM
2
Intents
10:11 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenos días.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hello!
#conversacion
Hello = @conversacion:saludo
 
Hola ¿Qué hay de nuevo?
Can't complain and you?
#cambiar_turno
t = @turno:T
? = @conversacion:Pregunta
 
¿de que tema se trata tu necesidad?
How to live forever?
#conversacion
? = @conversacion:Pregunta
 
¿Cuál es el motivo de tu visita a este canal?
10:12 AM

---

08/20/2020 @
10:11
AM
3
Intents
10:11 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buen día.</div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hola mi nombre es Carlos
#cambiar_usuario
Hola = @conversacion:saludo
Hola = @extractor:hola
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
Carlos = @nombre:Carlos
 
 
¿En qué te puedo ayudar Carlos?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
felicitarte.
#conversacion
te = @pronombres:te
te. = @tipo_documento:TI
te. = @tipo_documento:CE
 
¿como puedo ayudarte?
Modificar
#modificar_cita
 
Para comenzar indícanos tu número y tipo de documento
10:12 AM

---

08/20/2020 @
10:15
AM
3
Intents
10:15 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buenos días.</div>
 
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
 
Hola ¿Qué tal ? ¿como te encuentras hoy?
mal
#corregir
mal = @adverbio:mal
 
¿de que tema se trata tu necesidad?
caries
#corregir
caries = @especialidad:odontológica
 
Vamos dime, ¿qué puedo hacer por ti el día de hoy?
cita
#agendar_cita
cita = @persona:ella
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
 
Que deseas corregir?


---

08/20/2020 @
11:41
AM
4
Intents
11:41 AM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buenos días.</div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Cual es tú nombre?
 
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
el lunes = @sys-date:2020-08-24
las = @pronombres:las
las 5 y media = @sys-time:05:30:00
 
procederemos a consultar disponbilidad con el documento CC 1234567890 para la cita odontológica, el dia 2020-08-24 a las 05:30:00</br></br>
 
Ten presente que si no asistes se genera multa por un valor de $ 12.000.
 
¿Esta bien?
No
#decisión
No = @decisión:no
 
¿Que deseas corregir?
Cancela
#denegar
 
Por favor indícame, ¿que hay que corregir?
cc
#corregir
cc = @tipo_documento:CC
 
Corregiremos el tipo de documento. Por favor dime de nuevo el tipo de documento correspondiente.
ti
#corregir
ti = @tipo_documento:TI
ti = @dato:tipo_documento
ti = @pronombres:ti
 
He interpretado el tipo de documento TI.
 
Ahora dime el número de documento por favor.
11:42 AM


---

08/20/2020 @
12:46
PM
4
Intents
12:46 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buena tarde.</div>
 
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
 
 
¿Como podemos ayudarte Miguel?
 
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
 
</br>¿Alguna de estas opciones te sirve?
no
#decisión
no = @decisión:no
 
¿Que deseas corregir?
fecha
#corregir
fecha = @dato:fecha
fecha = @opción:fecha
 
Entendido. Corregiremos la fecha, dímela de nuevo por favor
12:47 PM

---

08/20/2020 @
2:51
PM
3
Intents
2:51 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buenas tardes.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
¿Como te llamas?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Ok
#aceptar
Ok = @decisión:sí
 
Tu nombre es Ok, ¿es correcto?
No
#decisión
No = @decisión:no
 
¿Cual es tú nombre?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Diego
#cambiar_usuario
Diego = @nombre:Diego
 
 
¿Como podemos ayudarte Diego?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
2:51 PM

---

08/20/2020 @
3:01
PM
8
Intents
3:01 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buenas tardes.</div>
 
<div class="msgj">Mi nombre es Platzibot y estoy aquí para ayudarte con la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
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
 
Hola, ¿como te encuentras hoy? <break></break>
Bien gracias
#conversacion
Bien = @adverbio:bien
Bien gracias = @conversacion:bienestar
 
genial,
 
¿de que tema se trata tu necesidad?
Quiero una cita
#agendar_cita
Quiero = @persona:yo
Quiero = @verbo:querer
Quiero = @modo_tiempo:indicativo presente
una = @sys-number:1
cita = @persona:tú
cita = @modo_tiempo:imperativo
cita = @persona:él
cita = @persona:ella
cita = @verbo:citar
cita = @modo_tiempo:indicativo presente
 
Cuéntame , ¿qué tipo de cita se te ofrece?
 
[Multi-option response]

Medicina General: Medicina General
Odontológia Básica: Odontológia Básica
Ginecologia
Irrelevant
 
Cuéntame, ¿que se te ofrece? </br> </br>1. Medicina general, </br>2. Odontología Básica.
1
#decisión
1 = @opción:primera
1 = @sys-number:1
 
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
 
</br>¿Te sirve alguna de las anteriores o quieres probar diciéndome una fecha y hora?
No
#decisión
No = @decisión:no
 
¿Que deseas corregir?
La direccion
#corregir
La = @pronombres:la
La direccion = @opción:direccion
 
Por favor indícame, ¿que hay que corregir?
No mentiras esta bien
#aceptar
No = @decisión:no
esta = @pronombres:esta
bien = @adverbio:bien
bien = @conversacion:bienestar
 
¿Que deseas que corrijamos?
Nada
#denegar
Nada = @decisión:no
Nada = @adverbio:nada
Nada = @pronombres:nada
 
¿Que deseas corregir?



---

08/20/2020 @
3:23
PM
4
Intents
3:23 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas tardes.</div>
 
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
mañ
Irrelevant
 
¿de que tema se trata tu necesidad?
mal
#corregir
mal = @adverbio:mal
 
Que deseas que corrijamos?
todo
#conversacion
todo = @adverbio:todo
 
Que deseas corregir?
me tengo que ir
#despedidas
me = @pronombres:me
me tengo que ir = @conversacion:despedida
tengo = @persona:yo
tengo = @verbo:tener
tengo = @modo_tiempo:indicativo presente
ir = @verbo:ir
ir = @modo_tiempo:infinitivo
 
¡Gracias por utilizar nuestro servicio de citas online vuelve pronto!
 
</br> </br>Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio Platzi - MinTic ICETEX Inteligencia Artificial. </br> </br> Antes que nada ¡¡¡Gracias!!! </br> </br> En el caso de uso que se presenta el chatbot realiza operaciones CRUD sobre una base de datos cloudant la cual ha sido expuesta mediante una API personalizada mediante functions. Todo serverless, una belleza!</br> </br> Es un gran detalle que quieras interactuar con este chatbot te agradezco cualquier comentario o critica constructiva. </br> </br>


---

08/20/2020 @
3:47
PM
1
Intents
3:47 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buena tarde.</div>
 
<div class="msgj">Me llamo Platzibot y mediante este canal puedes agendar, consultar, reprogramar y eliminar citas médicas y odontológicas siempre que lo necesites.</div>
 
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
 
¡Hola! ¿como te va?



---

08/20/2020 @
5:44
PM
7
Intents
5:44 PM
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Buena tarde.</div>
 
<div class="msgj">Puedes llamarme Platzibot y, te recuerdo que mi labor es asistirte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Para comenzar dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Hola me llamo Roselmayer
#cambiar_usuario
Hola = @conversacion:saludo
Hola me llamo = @extractor:hola me llamo
me = @pronombres:me
llamo = @verbo:llamar
llamo = @persona:yo
llamo = @modo_tiempo:indicativo presente
 
Antes de comenzar permiteme confirmar si he entendido bien tu nombre </br></br>¿Tú nombre es Ola me llamo roselmayer?
Roselmayer
Irrelevant
 
No soy muy bueno con los nombres, por eso prefiero asegurarme antes de empezar. </br></br>¿Te llamás Ola me llamo roselmayer?
No
#decisión
No = @decisión:no
 
¿Cual es tú nombre?
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
Roselmayer
 
Tu nombre es Roselmayer, ¿es correcto?
Si
#aceptar
Si = @decisión:sí
 
¿Cuál es el motivo de tú visita el día de hoy Roselmayer?
 
[Multi-option response]

Agendar: Agendar
Consultar: Consultar
Modificar: Modificar
Eliminar: Eliminar
Agendar
#agendar_cita
 
¿Qué tipo de cita deseas agendar Roselmayer?
 
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
 
 
Roselmayer tenemos estas opciones disponibles para la cita médica que estas solicitando:</br></br>
 
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
3
#decisión
3 = @opción:tercera
3 = @sys-number:3
 
Has elegido la tercera opción:
 
Roselmayer tu cita médica quedará reservada para el día 21 de agosto de 2020 a las 1:00 PM en el centro médico CM SUBA, con el documento CC 1234567890. </br></br>Recuerda que debes llegar 30 minutos antes y pasar por el punto ágil para facturar tu cuota moderadora.</br></br>Si no puedes ir a tu cita, cancela con 3 horas de anticipación y permite que alguien la tome por ti.</br></br>
 
¿Esta bien?
Excelente. Gracias!
#General_Positive_Feedback
Excelente = @conversacion:bienestar
Excelente = @decisión:sí
Gracias = @conversacion:agradecimiento
Gracias = @conversacion:cortesia
 
{"id":"8ececd1fb4ac437fc692ef72113c2880","ok":true,"rev":"1-96bb1ce28052f4f948548006f8860546"}
 
Agendada con exito
 
¿Podemos hacer algo más por ti?
Nada mas
#control_bot
Nada = @decisión:no
Nada = @adverbio:nada
Nada = @pronombres:nada
 
Hasta pronto, te esperamos de vuelta por aqui.
 
</br> </br>Este es un proyecto estudiantil que busca desarrollar las competencias adquiridas dentro del convenio Platzi - MinTic ICETEX Inteligencia Artificial. </br> </br> Antes que nada ¡¡¡Gracias!!! </br> </br> En el caso de uso que se presenta el chatbot realiza operaciones CRUD sobre una base de datos cloudant la cual ha sido expuesta mediante una API personalizada mediante functions. Todo serverless, una belleza!</br> </br> Es un gran detalle que quieras interactuar con este chatbot te agradezco cualquier comentario o critica constructiva. </br> </br>
Excelente trabajo, muchachos.
#General_Positive_Feedback
Excelente = @conversacion:bienestar
Excelente = @decisión:sí
trabajo = @persona:yo
trabajo = @verbo:trabajar
trabajo = @temática:trabajo
trabajo = @modo_tiempo:indicativo presente
 
<a href="https://i.imgur.com/zz2zQsO.png"><img src="https://i.imgur.com/zz2zQsO.png" title="Este es uno de los diseños realizados en colaboración entre los estudiantes" /></a>
 
<div class="msgj">Hola, Buenas tardes.</div>
 
<div class="msgj">Soy Platzibot, mi labor es colaborarte en la programación, consulta, modificación y cancelación de citas médicas y odontológicas.</div>
 
Dime tu nombre por favor
 
[Multi-option response]

Hola: Hola
me llamo miguel: me llamo miguel
mi nombre es sofia: mi nombre es sofia
Hola me gustaria agendar una cita odontologica para el lunes las 5 y media: Hola me gustaria agendar una cita odontologica para el lunes las 5 y media
5:48 PM

