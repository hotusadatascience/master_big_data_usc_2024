# Caso de negocio: Eurostars Hotel Company

En un día aparentemente normal, recibimos una llamada de una directora y revenue manager de un céntrico hotel de Roma que nos cae especialmente bien: Raquel. Un poco agobiada nos comenta que necesita algo de ayuda con su trabajo. 

Por un lado, cada mañana debe estimar cuáles serán los ingresos de los próximos 60 días. A pesar de que tiene mucho conocimiento del negocio y lleva ya bastantes años realizando esto, le resulta algo tedioso y piensa en que quizás con todos estos avances de la IA y del big data algo se podrá hacer para mejorar sus resultados. 

Por otro lado, el departamento de mejoras le dice que por fin se pondrán en marcha las obras en el hotel, solucionando así gran parte de las quejas de los clientes. Sin embargo, para ello es necesario cerrarlo completamente durante 10 días seguidos. 

Con toda esta situación, Raquel nos dice que una previsión de los ingresos del hotel para cada día de los próximos dos meses sería una información muy valiosa que le ayudaría a tomar esta decisión y perder la menor cantidad de dinero posible. 


## Datos

Como no tenemos ni idea de por dónde empezar, le preguntamos a Raquel en qué se basa ella para hacer sus previsiones. Nos dice que cada día recoge distintos datos que agrupa en un excel y que, más o menos, le sirven para ir encontrando patrones y similitudes. Aún así, nos avisa de que muchas veces hay datos que no encuentra y que no le queda otra que dejar en blanco. Muy amablemente, nos lo pasa en formato csv (**datos_esei.csv**), con unas columnas que tienen los siguientes significados:
 
* _Fecha_generacion_: Fecha de generación de los datos
* _Fecha_evaluacion_: Fecha que se evalúa (para la que se generan los datos)
* _Antelacion_: Número de días que quedan para _Fecha_evaluacion_
* _Numero_habitaciones_hotel_: Número de habitaciones del hotel
* _Numero_habitaciones_bloqueadas_: Número de habitaciones del hotel que no puedo vender porque están en mantenimiento (ej: se ha estropeado el lavabo)
* _Room_nights_individuales_actuales_: Habitaciones ocupadas por clientes individuales
* _Room_nights_grupos_actuales_: Habitaciones ocupadas por grupos (ej: un equipo de fútbol)
* _Precio_actual_: Precio al que estoy vendiendo la noche
* _Revenue_individual_actual_: Revenue que llevo actualmente proveniente de clientes individuales
* _Revenue_grupos_actual_: Revenue que llevo actualmente proveniente de grupos 
* _Precio_competidor1_: Precio del competidor 1
* _Precio_competidor2_: Precio del competidor 2
* _Precio_competidor3_: Precio del competidor 3
* _Cancelaciones_: Número de cancelaciones que llevo para este día 
* _Evento_muy_grande_: ¿Hay un evento especialmente grande en Roma?
* _Evento_grande_: ¿Hay un evento grande en Roma?
* _Duracion_evento_: Duración del evento
* _Horas_sol_: Horas de sol hay previstas para este día (_Fecha_evaluacion_)
* _Temperatura_minima_: Temperatura mínima prevista para este día (_Fecha_evaluacion_)
* _Temperatura_maxima_: Temperatura máxima prevista para este día (_Fecha_evaluacion_)

Ejemplo: si _Fecha_generacion_ = "2024-02-01" y _Fecha_evaluacion_ = "2024-02-20", estoy en el día 1 de febrero evaluando cuántas habitaciones tengo ocupadas/canceladas para el 20 de febrero en mi hotel.

## Objetivos

Sabiendo que Raquel es nuestra revenue manager favorita y que queremos ayudarla:

* ¿Serías capaz de hacer una predicción de los ingresos para los próximos 60 días? ¿Sabrías cómo medir el acierto de esta predicción?

* Basándote en lo anterior, ¿qué días le dirías que cerrase el hotel? 


## Entrega

Entrega tus resultados en un notebook o en un link al repositorio en Github a alejandra.comesana@eurostarshotelcompany.com o ignacio.freire@eurostarshotelcompany.com

En caso de haber una solución particularmente buena, esta será recompensada con una estancia de dos noches en un hotel de la cadena (se aplican excepciones en cuanto a fechas y hoteles seleccionables).


