# CONTROL DE MOVIMIENTO - CLASE_3
# Motores

Los motores son dispositivos diseñados para convertir energía en movimiento mecánico. Se pueden clasificar en diferentes tipos según su fuente de energía y su principio de funcionamiento.
##
### Servomotor
Servo, palabra que hace referencia a que una variable se mueve hacia un valor objetivo en el dominio del tiempo, viene de la palabra latina "servos" cuyo significado es esclavo, sigue comandos de posición, velocidad o torque por medio de un sistema de control, estas mismas son las variables a controlar.  

Componentes
1. Sección de comando: Controlador
2. Sección de controlador: Amplificación de servo
3. Sección de controlador y etector: Motor de servo
##
## Tipos de motores
### Motores DC
Utiliza una fuente de corriente continua para generar movimiento rotatorio.

**Partes**  

-Estator : Es el encargado de generar el campo magnético de excitación. Está compuesto por una corona de material ferromagnético llamada culata , dentro de la cual se encuentran los polos. Alrededor de estos polos se enrollan los devanados de excitación que generan el campo magnético cuando una corriente circula por ellos.

-Rotor : Es una pieza cilíndrica ranurada hecha de material ferromagnético. En las ranuras del rotor se aloja el devanado inducido cerrado , que es donde se genera el movimiento cuando el motor está en funcionamiento.  

-Colector de delgas : Se trata de un conjunto de láminas de cobre aisladas entre sí, que giran junto con el rotor. Estas láminas están conectadas eléctricamente a los bobinados del devanado inducido y permiten la conexión del motor con el exterior.

**Aplicaciones**

-Molienda de caña de azucar  
-Cintas transportadoras 

##

### Motor de corriente alterna (AC) 
##
#### Motor síncrono  

**Definición :** Son máquinas eléctricas cuya velocidad de rotación está vinculada a la frecuencia de la red AC. La velocidad del rotor y la velocidad del campo magnético del estator son iguales. Posee imanes o bobinas montadas sobre el rotor, las cuales se excitan con corriente continua. Las bobinas de armadura están divididas en tres partes y se alimentan con corriente trifásica.

**Partes :**   

-Estator : Contiene un bobinado trifásico que genera el campo magnético giratorio.   
-Rotor : Puede tener imanes o bobinas de excitación alimentadas con corriente continua, lo que le permite girar a la velocidad del campo magnético.  
-Anillos rozantes : Son anillos metálicos que permiten la alimentación de corriente continua al rotor.  

**Funcionamiento :**

-Para iniciar el motor, se aplica una señal alterna trifásica al estator.  
-Se suministra corriente continua a las bobinas del rotor, lo que genera un campo magnético con polaridad fija.  
-La interacción entre el campo magnético del estator y el del rotor produce el giro del ro.  

**Aplicaciones:**  
-Bombas.  
-Laminación siderúgica
##
#### Motor asíncrono  

**Funcionamiento:** El motor asíncrono genera un campo magnético giratorio en el estator, que al inducir corrientes en el rotor produce fuerzas electromagnéticas. Estas corrientes generan una reacción que permite el giro del motor a una velocidad inferior a la de sincronismo.

**Motor jaula de ardilla**  

![Figura de prueba](IMAGES/JAULA.png)








- **Motor paso a paso**: Se mueve en pasos discretos y es utilizado en aplicaciones de control de precisión.
- **Motor sin escobillas (BLDC)**: Ofrece mayor eficiencia y durabilidad que los motores de escobillas tradicionales.

##### Motores de Combustión Interna
Estos motores generan energía mecánica a partir de la combustión de un combustible.
- **Motor de gasolina**: Utiliza gasolina como combustible y funciona con un ciclo de cuatro tiempos.
- **Motor diésel**: Similar al motor de gasolina, pero con una eficiencia térmica mayor debido a la ignición por compresión.
- **Motor rotativo (Wankel)**: Posee un diseño diferente al de los pistones tradicionales, utilizando rotores para generar movimiento.

##### Motores Neumáticos
Estos motores utilizan aire comprimido para generar movimiento. Se utilizan en herramientas industriales y maquinaria neumática.

##### Motores Hidráulicos
Utilizan la presión de un fluido para generar movimiento, siendo empleados en maquinaria pesada y sistemas hidráulicos.

### Ejemplos
#### Ejemplo 1
Un motor eléctrico de corriente continua se usa en juguetes eléctricos y ventiladores de computadoras.

#### Ejemplo 2
Un motor de combustión interna es utilizado en automóviles y motocicletas.

### Ecuaciones
$$
P = T \cdot \omega
$$
Donde:
- \( P \) es la potencia del motor.
- \( T \) es el torque.
- \( \omega \) es la velocidad angular.

### Figuras
![Motor eléctrico](ruta/de/la/imagen_motor.png)

### Tablas
| Tipo de Motor | Fuente de Energía | Aplicaciones |
|--------------|-----------------|--------------|
| Eléctrico (DC) | Batería | Juguetes, ventiladores |
| Eléctrico (AC) | Red eléctrica | Electrodomésticos |
| Combustión Interna | Gasolina/Diésel | Automóviles |
| Neumático | Aire comprimido | Herramientas neumáticas |
| Hidráulico | Fluido a presión | Maquinaria pesada |

### Ejercicios
1. Explica la diferencia entre un motor de corriente continua y un motor de corriente alterna.
2. Describe el funcionamiento de un motor de combustión interna y menciona sus principales componentes.
3. ¿En qué aplicaciones se usan motores neumáticos y cuáles son sus ventajas?

### Conclusiones
Los motores desempeñan un papel fundamental en la tecnología moderna, permitiendo la automatización y el transporte en diversas industrias. Su correcta selección depende del tipo de aplicación y los requerimientos energéticos.

### Referencias
1. Autor 1. *Fundamentos de motores eléctricos*. Editorial, Año.
2. Autor 2. *Motores de combustión interna y su aplicación*. Revista, Volumen(Número), Año.
