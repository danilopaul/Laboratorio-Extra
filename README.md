# Laboratorio-Extra

                                      Universidad de las Fuerzas Armadas - ESPE
                                       Fundamentos de Circuitos Electróinicos

Nombre: Paul Danilo Cholca Quilo.

Asignatura: Fundamnetos de circuitos Electronicos.

NRC:7318

Tema: Aplicacion del Teorema de Thevenin y Superposicion.

1.Objetivos

1.1. Objetivo General:

•	Conocer el concepto del teorema de Thevenin y le teorema de superposición en los circuitos, mediante la investigación de información concisa referente a los temas, para aplicar dichos teoremas en la construcción de los circuitos, a través del uso de simuladores.

1.2. Objetivos Especificos:

•	Describir el proceso de aplicación del teorema de tevenin en un circuito mixto, para obtener su circuito equivalente y determinar el voltaje, resistencia equivalente de Thevenin y la potencia suministrada.

•	Describir el proceso de aplicación del teorema de superposición en un circuito mixto, para encontrar la corriente y el voltaje que pasa por la resistencia solicitada.

•	Usar el simulador de Tinkercard y ACDCLab, para el armado de los circuitos y mediante estos presentar las respectivas soluciones de los datos solicitados.

2.Marco Teorico:

![teorema de thevenin](https://user-images.githubusercontent.com/105687375/184732945-ff17565b-bb93-4344-9a7d-5aebcc0c8218.jpg)

![image](https://user-images.githubusercontent.com/105687375/184733246-c4811eab-d420-43f8-811d-b32a0020d7de.png)

3.Explicacion del Procedimiento:
  
EQUIPO Y MATERIAL REQUERIDO:

![image](https://user-images.githubusercontent.com/105687375/184736243-234497b8-02f7-4af5-8d3a-b0e0767b3feb.png)

3.1. Armar el circuito #1:

![image](https://user-images.githubusercontent.com/105687375/184739366-6126de8c-5fae-4326-8ba6-4831f4085564.png)

Armamos el circuito en el simulador y medimos la corriente entre R2 y R3:

![image](https://user-images.githubusercontent.com/105687375/184780997-4991d01b-1c32-4922-a33f-4ec0147fe3f6.png)

Desconectamos la fuente de energia de 16V y medimos la corriente de entre R2 y R3 y el voltaje a traves de la resistencia de 12Ω:

![image](https://user-images.githubusercontent.com/105687375/184783400-7b9ecfff-6dcd-40c9-a5f1-fdc9722f61b6.png)

Desconectamos la fuente de voltaje de 10V y medimos la corriente entre R2 y R3 y el volatje entre la resistencia de 12Ω:

![image](https://user-images.githubusercontent.com/105687375/184783605-6de70fef-15bf-48c4-92b2-2eb572a27bd9.png)

Entonces aplicando el teorema del superposicion, al desconecta la fuente de 16V la corriente  a traves de la resistencia 12Ω es:

I=500 mA

Al desconectar la fuente de voltaje de 10 V, ls corriente que pasa a traves de las resistecia de 12Ω:

I= -400 mA

Entonces:

I=500mA - 400mA = 100mA

Como la corriente E1 esta subiendo  y la corriente E2 esta en sentido opuesto, estas se restan, por lo cual tambien el voltaje se resta:

V= 6V -  4.80V = 1.20V

3.2. Circuito #2:

- Empleando el circuito equivalente de Thevenin determine la potencia suministrada a la resistencia R3:

![image](https://user-images.githubusercontent.com/105687375/184784492-c1f2d63f-047a-4de1-bb3d-f63fbcac5f9b.png)

•	Simulación de circuito principal:

![image](https://user-images.githubusercontent.com/105687375/184785085-0f9b5170-7f86-465e-9624-e0deb0efe67d.png)

•	Aplicar el teorema de Thevenin que menciona que se puede reducir un circuito a una sola fuente de voltaje en serie con una sola resistencia, denominadas equivalentes de Thevenin.

Desconertar la resistencia  de 2.2kΩ, para obtener el voltaje y resistencia de Thevenin:

El voltaje de Thevenin es:

![image](https://user-images.githubusercontent.com/105687375/184787139-1547febb-1471-48e9-94fe-b192f7172f72.png)

VTH=  8.32V

Por lo tanto, la Resistencia equivalente de Thevenin es:

![image](https://user-images.githubusercontent.com/105687375/184787506-dddf2efd-7fd2-498d-a41b-06ddbd1793e2.png)

RTH= 4.7 kΩ

El circuito equivalente de Thevenin es:

![image](https://user-images.githubusercontent.com/105687375/184788856-389b20a3-95a0-4c31-b03c-914c4b67de33.png)

•	Utilizamos el potenciómetro, para obtener el valor preciso de la resistencia equivalente de Thevenin. Una vez obtenido estos datos se procede a calcular la potencia que existen en R3 o RL.

P= I * V

P= 3.78mA *  8.32V

P= 31.44 mW

![image](https://user-images.githubusercontent.com/105687375/184791263-0d4e23b7-232b-42f5-b2dd-883637e45ee2.png)

•	Utilizar ACDCLab, para comprobar el resultado, esto mediante un vatímetro que permite medir la potencia.

3.3. Circuito #3:

- Calcular  la intensidad I que pasara por la resistencia 5Ω utilizando utilizando Thevenin.

![image](https://user-images.githubusercontent.com/105687375/184791676-293eb968-83d2-4a4b-9d9e-b823146ce45f.png)

•	Medimos la resistencia que pasara por la resistencia de 5Ω

![image](https://user-images.githubusercontent.com/105687375/184793242-b37de0b6-4349-47dc-b09d-573f862f8114.png)

•	Medimos el voltaje equivalente de Thevenin:

![image](https://user-images.githubusercontent.com/105687375/184793789-c1b775b3-b053-403b-9416-ef1ef089e0e0.png)

VTH= 10.0V

•	Desconectamos las fuentes de voltaje y quitamos la resistencia de 5Ω y medimos la resistencia equivalente de Thevenin.

![image](https://user-images.githubusercontent.com/105687375/184794310-3212952d-6f62-48d8-b3f5-4946de3aca4e.png)

RTH=  5Ω 

•	Entonces, la corriente que pasa por la resistencia 5Ω, aplicando el teorema de Thevenin es

![image](https://user-images.githubusercontent.com/105687375/184795506-1b66e06a-b49b-45ca-b489-7a57839f8628.png)

4.Video:

https://youtu.be/JeJOKdRS7zw

5.Conclusiones:

•	En conclusión, en un circuito que presenta dos o más fuentes de voltaje, se es recomendable aplicar el teorema de superposición, los cuales siguen una serie de pasos, para obtener los datos desconocidos, como es el caso de la corriente que pasa a través de una resistencia en específico.

•	Mediante la aplicación del teorema de Thevenin, se pudo apreciar que la resistencia equivalente Thevenin, se obtiene al reemplazar las fuentes de voltaje por circuitos cerrados, las fuentes de corrientes por circuitos abiertos, y para la resistencia que se desea calcular, se la pone en corto, esto permite obtener una única resistencia que es equivalente a la resistencia total.

•	Para obtener el voltaje de Thevenin, se debe poner en corto la resistencia que se desea calcular y mediante los diferentes métodos como; malla, ramas y nodos, se obtendría el valor de este voltaje equivalente.

•	Los usos de los simuladores permiten comprender de mejor manera el proceso que se debe tener para obtener el valor de resistencia, corriente y voltaje, cuando se aplican los teoremas ya mencionados.

6.Bibliografia:

Floyd, TL (2007). Principios de Circuitos Eléctricos. CDMX: Persona Educación.
