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


