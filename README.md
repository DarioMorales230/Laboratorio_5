# Laboratorio_5

1. OBJETIVOS

1.1. Objetivo General.

• Demostrar y desarrollo correctamente el teorema de la Thévenin, de manera teórica, experimental y matemática, mediante el desarrollo de una serie de pasos lo cual dese llevara de forma matemática, de igual manera una comparación de los resultados obtenido apoyados con la simulación del circuito planteado para la práctica.

1.2. Objetivos Especificos.

• Calcular la complejidad del circuito eléctrico planteado para la práctica, utilizando el teorema de la Thévenin; para facilitar su análisis y validar la consistencia de lo solicitado confrontando los parámetros calculados con los simulados y medidos en el laboratorio.

• Determinar el circuito equivalente Thévenin de un arreglo de resistencias y fuente de voltaje rediseñando a un circuito resistivo con una fuente independiente de voltaje que satisfaga la relación entre el voltaje y la corriente mediante la simulación y la parte matemática de la práctica.

• Interpretar con la mejor claridad posible todos los conceptos básicos referentes al teorema de Thévenin y demostrar matemáticamente para inferir todos los datos reales necesarias para el circuito simulado.

2. MARCO TEORICO

![WhatsApp Image 2021-07-25 at 18 49 34](https://user-images.githubusercontent.com/85144847/126936517-549af73b-5dde-423b-905b-d2a161c00d26.jpeg)

3. EXPLICACION DEL PROCEDIMIENTO

3.1. Revisar el tema a tratar con las respectivas indicaciones dadas por el docente y ver el material de experimentacion, en este caso es un circuito resistivo mixto donde nos indica que debemos obtener el voltaje y corriente Thevenin y de la resistencia 5.

![image](https://user-images.githubusercontent.com/85144847/126949252-d51bf489-ec51-42e9-9c10-ffa0d463ec7b.png)

3.2. Con la lectura previa y la revision de lo que debemos realizar procederemos a ver cuantos componentes tiene de forma receptora y generadora como nos indica la figura por ende nos quedaria de la siguiente forma los componentes.

![image](https://user-images.githubusercontent.com/85144847/126949363-fd8fe3f4-0d47-4cb2-8529-b635cf6c8dc9.png)

3.3. Teniendo ya todos los materiales del circuito mixto nos dirigiremos a nuestro simulador que en este caso es Tinkercad que nos permite diseñar circuitos en forma pictografica con sus respectivas mediciones.

![image](https://user-images.githubusercontent.com/85144847/126949544-39e4ce03-5131-4875-9512-6160845e256f.png)

3.4. Una vez ya en tinkercad procederemos hacer el circuito como nos indica el material de experimentacion por ende iremos escogiendo nuestros componentes señalados anteriormente, una vez ubicados y señalados nos quedaria tipo asi el circuito sin conectar.

![image](https://user-images.githubusercontent.com/85144847/126950444-42d7cdde-2891-4bbb-9a2b-c73f486d6f6f.png)

3.5. Y conectando los componenetes como nos indica la guia de experimentacion nos quedaria de la siguiente manera aqui hay que tener en cuenta algo y es que nosotros debemos conectar con codigo de colores de cable es decir el color rojo va a indicar que es positvio y el color negro negativo.

![image](https://user-images.githubusercontent.com/85144847/126950290-f8b2693d-74b1-4ebf-8ce2-1ff8c9bff325.png)

3.6. Ya concluido el armado del circuito y puesto a simulacion se procede a realizar las respectivas mediciones de voltaje y corriente de la resistencia 5 con la ayuda de un multímetro obtenemos lo siguiente:

- Voltaje

![image](https://user-images.githubusercontent.com/85144847/126951755-b0660459-f69b-43d5-83be-8bceca616ac3.png)

- Intensidad Electrica

![image](https://user-images.githubusercontent.com/85144847/126952008-cf5edbd4-c15f-48dd-83ff-7cff5a8e2b8b.png)

3.7. Concluida la parte de encontrar el voltaje y la corriente que pasa por R5 procederemos a encontrar ahora el voltaje Thevenin con su respectiva corriente electrica para ello el circuito sera dividido en 2 casos de la siguiente manera:

Caso A

- Voltaje 

![image](https://user-images.githubusercontent.com/85144847/126953356-750166e0-1ee1-4d22-a038-d587d90edf30.png)

- Intensidad Electrica

![image](https://user-images.githubusercontent.com/85144847/126953749-3b5d76e6-5193-4a50-af95-e65654551fb6.png)

Caso B

- Voltaje

![image](https://user-images.githubusercontent.com/85144847/126954337-afe6be95-4e9c-4a88-9f4e-3c32ef0fc4fe.png)

- Intensidad Electrica

![image](https://user-images.githubusercontent.com/85144847/126954235-902cb1c2-848b-413b-b71f-f4c8ca597dc1.png)

3.8. Como punto final de la practica procederemos a reducir el circuito en su maxima expresion esto para poder obtener el voltaje y corriente Thévenin y tambien con ello comprobamos los datos obtenidos analiticamente.

![image](https://user-images.githubusercontent.com/85144847/126955144-165629cd-4c6a-4394-b8b7-5581d0f11bc8.png)


4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

Para el desarrollo matemático del siguiente circuito de nuestra practica lo que vamos hacer es establecer ciertos puntos donde iremos detallando la practica..

4.1. Vamos a obtener la resistencia equivalente de Thévenin del circuito indicado de la siguiente manera:

•	No tomamos en cuenta las fuentes de voltaje ni la resistencia que vamos a calcular su corriente y su diferencia de potencial.

![image](https://user-images.githubusercontent.com/85144847/126941566-1952801a-9609-425b-a415-a7f4ad6b981b.png)

Donde: Ra = R1 ∥ R2 ∥ R3

![image](https://user-images.githubusercontent.com/85144847/126941760-e9865117-f4c4-4a46-87c5-f8c0efeb8315.png)

4.2. Para calcular el voltaje Vab utilizaremos el teorema de superposición. 

•	Como tenemos dos fuentes de voltaje dividiremos en un caso con la fuente de un voltaje de 12 V y en el otro caso con la fuente de voltaje de 2 V.

-	CASO A = 12V

![image](https://user-images.githubusercontent.com/85144847/126942974-9d6a184d-ec48-4192-a27f-5fedc952688a.png)

![image](https://user-images.githubusercontent.com/85144847/126943151-ac00dd2d-cef5-453f-8f18-340dcd98a7a8.png)

Para obtener el voltaje señalado el cual es Vab tenemos que ocupar un divisor de voltaje de la siguiente manera:

![image](https://user-images.githubusercontent.com/85144847/126943785-8c3af146-5947-4db8-a950-df0c9f7371fb.png)

- CASO B = 2V

![image](https://user-images.githubusercontent.com/85144847/126943902-551c9422-649f-4265-8f17-5b277051d43e.png)

Req = Rc+R3

Req = 500.38+330

Req = 830.38Ω

- Utilizamos nuevamente el divisor de voltaje para Vab y tenemos:

![image](https://user-images.githubusercontent.com/85144847/126944053-d4ecafe7-0462-4969-9c36-aaaccd727834.png)

- Para el Vth tenemos lo siguiente:

Vth = Vab1+Vab2

Vth = 4.26+0.79

Vth = 5.05 v

4.3. Para finalizar volvemos a nuestro circuito original.

![image](https://user-images.githubusercontent.com/85144847/126944256-e2cf4013-3501-4cb5-8104-b6120506052f.png)

•	Lo reducimos con los datos obtenidos anteriormente y tenemos:

![image](https://user-images.githubusercontent.com/85144847/126944364-f690a132-71bf-40f2-ab6d-b77ac7b4be0f.png)

Reqth = Ra+R5

Reqth = 1000+298.35

Reqth = 1298.35 Ω

•	Utilizamos el divisor de voltaje para encontrar el voltaje que pasa por R5 y tenemos:

![image](https://user-images.githubusercontent.com/85144847/126944469-52c7a09b-a425-4688-a78d-778533bf365b.png)

•	Calculamos la intensidad de R5 con la Ley de Ohm y obtenemos:

![image](https://user-images.githubusercontent.com/85144847/126944785-d70963e0-0313-47e5-9594-bff00f3f35ed.png)

4.4. Completando las tablas con los datos obtenidos tenemos:

![image](https://user-images.githubusercontent.com/85144847/126955506-7cb273f4-2b95-40cd-b4d6-758c12f1094b.png)

![image](https://user-images.githubusercontent.com/85144847/126955540-b12fce55-5595-4f32-bfa5-447bd8556def.png)

5. VIDEO DE YOUTUBE



6. CONCLUSIONES

- Como demuestra la práctica del laboratorio debemos colocar todas las fuentes independientes a cero. Para hacerlas igual a cero, las fuentes de voltaje se sustituyen por un cortocircuito y las fuentes de corriente se sustituyen por un circuito abierto.

- Está claro que algunos errores pueden ser negativos cuando el valor exacto es mayor que el valor experimental, y algunos valores son casi nulos ya que el valor exacto y el valor experimental son aproximadamente iguales ya que el porcentaje de error se considera insubsistente.

- El reconocer e identificar las modalidades de cortocircuito y circuito abierto, son de vital importancia en establecer estos procesos de análisis en los teoremas de Thévenin ya que permiten sintetizar cualquier circuito eléctrico, siendo estos los pilares de los teoremas de red. 

7. BIBLIOGRAFIA

• Análisis de Circuitos -Robbins

• Cuaderno de Electrotecnia I –Ing. Wilmer Loza

• Circuitos I –Ing. Wilmer Loza
