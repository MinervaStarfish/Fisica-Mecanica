
# Ejercicios Cinematica

***
## Ejercicio: Desplazamiento de un movil


***  
### Solucion  
***  
^d^^^^^
a(t) = (4t + 1) m/s^2^  
v(0) = 2 m/s  
x(0) = 0 m  
  
condiciones iniciales  
x0 = (0i + 0j + 0k) m  
v0 = (2i + 0j + 0k) m/s  
a0 = (1i + 0j + 0k) m/s2  

ecuaciones x, v, a  
a(t) = [(4t + 1)i + 0j + 0k] m/s2  
v(t) = [(2t**2 + t + 2) i+ 0j + 0k] m/s  
x(t) = [(2/3 t**3 + 0.5t**2 + 2t )i + 0j + 0k] m
<br> <br/>

***
## Ejercicio:  Encuentro (MRU y MRUV)  
  
Un automóvil está detenido frente a un semáforo. En el instante en que la luz cambia a verde, el auto arranca con una aceleración constante de 2.2 m/s^2^. En ese mismo momento, un camión que se desplaza con una velocidad constante de 15 m/s, lo adelanta.  

1. Sistema de referencia
2. Condiciones iniciales y ecuaciones cinematicas   
3. ¿A qué distancia del semáforo alcanzará el automóvil al camión?  
4. ¿Qué velocidad tendrá el automóvil en el momento del encuentro?   

***  
### Solucion  
***  
1. **Marco de referencia**: El semaforo (0,0). Se mueven en el eje x positivo  
<br> <br/> 
  
2. **Condiciones iniciales**:  
  
	t= 0 s  
	x= 0 m  
  
	a. **Carro**:  
	- s(0)= (0 i + 0 j + 0 k) m  
	- v(0)= (0 i + 0 j + 0 k) m/s  
	- a(0)= (2.2 i + 0 j + 0 k) m/s^2^
	  
	b. Camion:  
	- s(0)= (0 i + 0 j + 0 k) m  
	- v(0)= (15 i + 0 j + 0 k) m/s  
	- a(0)= (0 i + 0 j + 0 k) m/s^2^
  
	**Ecuaciones de movimiento**:  
	  
	a. **Automovil**:  
	- v(t)= [(2.2 t + C) i + 0 j + 0 k] m/s
	= [(2.2 t) i + 0 j + 0 k] m/s  
	- s(t)= [(1.1 t^2^ + C) i + 0 j + 0 k] m
	= [(1.1 t^2^) i + 0 j + 0 k] m  
  
	b. **Camion**:  
	- s(t)= [(15 t + C) i + 0 j + 0 k] m
	= [(15 t) i + 0 j + 0 k] m  
<br> <br/> 
  
3. **Distancia de encuentro**:  
  
	- Igualamos la s(t) para encontrar t:  
	[(1.1 t**2) i + 0 j + 0 k] m = [(15 t) i + 0 j + 0 k] m
	t= 13.64 s  
	- Remplazamos s(13.64), en cualquiera de las dos:
	s= [(15 * 13.64 s) i + 0 j + 0 k] m
	= (204.6 i + 0 j + 0 k) m  
<br> <br/>
  
4. **Velocidad automovil en el encuentro**:

	- Remplazamos v(13.64) del automovil:
	v= [(2.2 * 13.64 s) i + 0 j + 0 k] m/s
	= (30.008 i + 0 j + 0 k) m/s
<br> <br/>

***
## Ejercicio: Encuentro retardado (parcial 1 2026-1)

DOS BOLAS QUE SE TIRAN AL AIRE CON LA MISMA VELOCIDAD INICIAL, UNO 4 SEGUNDOS DESPUÉS DEL OTRO

***  
### Solucion  
***  

cond iniciales  
Va(0) = 20 m/s  
Vb(0) = 20 m/s  
Ya(0) = 0 m  
Yb(0) = 0 m  
Aa = -g  
Ab = -g  
ta = tb + 4  
ta >= 0  
tb >= 0

cuaciones de a [a,v,y]  
  
a(t) = (0i - gj + 0k) m/s**2  
v(t) = [0i +(20 - gta)j + 0k] m/s  
y(t) = [0i + (20ta - 0.5gta**2)j + 0k] m  
  
ecuaciones de b [a,v,y]  
  
a(t) = (0i - gj + 0k) m/s**2  
v(t) = [0i +(20 - gtb)j + 0k] m/s  
y(t) = [0i + (20tb - 0.5gtb**2)j + 0k] m

en qué instante t se encuentran  
  
20tb - 0.5gtb**2 = 20(tb + 4) - 0.5g(tb + 4)**2  
20tb - 0.5gtb**2 = 20tb + 80 - 0.5gtb**2 - 4gtb-8g  
20tb = 20tb + 80 - 4gtb-8g  
0 = 80 - 4gtb- 8g  
4gtb = 80 - 8g  
tb = (80 - 8g)/4g s
<br> <br/>

***
## Ejercicio: Movimiento Vertical y Caída Libre 

Desde la azotea de un edificio de 40 m de altura, se lanza una piedra hacia arriba con una velocidad inicial de 15 m/s . En su camino de caída, la piedra pasa frente a una ventana que está a 15 m del suelo.  
  
1. ¿Cuál es la **altura máxima** que alcanza la piedra respecto al suelo?  
2. ¿Cuánto tiempo transcurre desde que se lanza la piedra hasta que pasa frente a la ventana?  
3. Si un segundo objeto se dejara caer desde la misma azotea 1 s después de lanzar la primera piedra, ¿cuál de los dos llegaría primero al suelo?

***  
### Solucion  
***  


<br> <br/>

***
## Ejercicio: Tiro parabolico baloncesto

Descomposicion de vectores, condiciones iniciales y ecuaciones cinematicas.

***  
### Solucion  
***  

v(0) = 20 m/s  
Hs = 2 m  
Ha = 3 m  
S = 14 m  
θ = 30 °  
Vx(0) = 20cos30 ° m/s  
Vy(0) = 20sin30 ° m/s  
  
a(t) = (0i -gj + 0k) m/s**2  
v(t) = (20cos30°)i + (-gt + 20sin30°)j + 0k m/s  
  
x(t) = (20cos30°t)i + (-0.5gt**2 + 20sin30°t ) j + 0k m
<br> <br/>

***
## Tiro parabolico baloncesto 2 (parcial 1 2026-1)

Un jugador de baloncesto lanza un balón desde una altura de 2m con una velocidad inicial de 8.5 m/s y un ángulo de inclinación de 60 ⌂  
sobre la horizontal. La canasta se encuentra a una distancia horizontal de 6 m y tiene una altura de 3.05 m .  
  
**A)** ¿Logra el balón entrar en la canasta?  
  
**B)** ¿Cuál es la **velocidad del balón** (magnitud y dirección) justo en el instante en que alcanza la posición de la canasta?  
  
**C)** ¿Cuánto tiempo permanece el balón en el aire?

***  
### Solucion  
***  

<br> <br/>

***
## Lanzamiento de Proyectiles

Un rescatista lanza un paquete de suministros desde un avión que vuela horizontalmente a una altura de 120 m con una velocidad de 180 km/h. El objetivo es que el paquete caiga en un campamento ubicado en el suelo.

1. ¿Cuántos metros antes de sobrevolar el campamento debe soltar el paquete para que impacte en el blanco?  
2. ¿Cuál es la **magnitud de la velocidad** resultante del paquete justo antes de tocar el suelo?  
3. Calcule el **ángulo de impacto** con respecto a la horizontal.

***  
### Solucion  
***  

<br> <br/>

***
## Cinemática de dos cuerpos: Lanzamiento parabólico y MRU (parcial 1 2023-2)
Un bateador de besibol golpea la bola a una altura h= 0.85 m respecto al suelo, de modo que adquiere una rapidez de v0= 15 m/s, haciendo un angulo de θ= 27º con respecto a la horizontal. Un segundo jugador, parado a la derecha del bateador, a una distancia de d= 30 m y en el mismo plano de la trayectoria de la pelota, corre hacia este en el mismo instante en que golpea la bola. Si el segundo jugador, corriendo con una velocidad constante trapa la pelota a una altura h= 1.9 m respecto al suelo, entonces:  

1. Sistema de referencia  
2. Condiciones iniciales del sistema y ecuaciones cinematicas para la pelota y para el segundo jugador  
3. Calcule la velocidad minima que debe tener el segundo jugador y la distancia que recorre para lograr atrapar la pelota con las condiciones del sistema

***
### Solucion
***

1. **Sistema de referencia**: (0,0) a los pies del bateador
<br> <br/>

2. **Condiciones iniciales**:
θ= 27º

a. **Bola**:
s= (0 i + 0.85 j + 0 k) m
v= (15cos27 i + 15sen27 j + 0 k) m/s
a= (0 i - 9.8 j + 0 k) m/s^2^

b. **Jugador 2**:
s= (30 i + 0 j + 0 k) m
v constante negativa

Ecuaciones cinematicas**:

a. **Bola**:
a(t)= (0 i - 9.8 j + 0 k) m/s^2^
v(t)= (15cos27 i + (15sen27 - 9.8t) j + 0 k) m/s
s(t)= (15cos27t i + (15sen27t - 4.9t^2^ + 0.85) j + 0 k) m

b. **Jugador 2**:
a(t)= (0 i + 0 j + 0 k) m/s^2^
$v(t)= (- v_{j} i + 0 j + 0 k) m/s$
$s(t)= ((30 - v_{j}t) i + 0 j + 0 k) m$
<br> <br/>

3. **Velocidad y distancia recorrida del jugador 2 al atrapar la pelota**:

Hallamos t igualando la posicion en y:
$15sen27t - 4.9t^2 + 0.85 = 1.9$
$6.81t - 4.9t^2 - 1.05 = 0$

$x = \frac{-6.81 \pm \sqrt{(6.81)^2 - 4(-4.9)(-1.05)}}{2(-4.9)}$
$t_{1}= 0.1766 s$ → A menor tiempo, mayor velocidad
==$t_{2}= 1.2132 s$ → A mayor tiempo, menor velocidad==

Primero debemos hallar la distancia en la que se atrapa la bola, entonces remplazamos s(1.2132) *en la posicion de la bola*:

$$15cos27t$
$s_{j}(t)= (13.365)(1.2132)$ 
$= 16.214 m$

$d_{j}= 30 - 16.214$
$d_{j}= 13.786 m$

Ahora podemos hallar la velocidad igualando las posiciones:
$15cos27t = 30 - v_{j}t$
$16.214 = 30 - v_{j}(1.2132)$
$-13.786 = - v_{j}(1.2132)$
$v_{j}= \frac{13.786}{1.2132}$
$v_{j}= 11.363 m/s$

---
Jugador izquierda golpea una pelota  
h= 0.85 m  
v0= 15 m/s  
θ= 27°  
  
Jugador derecha  
d= 30 m  
corre a la izquierda hasta llegar y atrapar la pelota en  
h= 1.9 m  
  
a. Diagrama de referencia  
-  
- (0,0) en el inicio golpe de la bola, en h= 0.85 m  
- Esto significa que a la derecha h= 1.05  
  
b. Condiciones iniciales  
-  
- v0= [15cos(27) i + 15sin(27) j + 0 k] m/s  
- r0= [0 i + 0 j + 0 k] m  
  
v0x= 15cos(27) = 13.37 m/s  
v0y= 15sin(27) = 6.81 m/s  
- v0= [13.37 i + 6.81 j + 0 k] m/s  
  
c. Ecuaciones cinematicas  
-  
a(t)= [0 i - g j + 0 k] m/s^2  
v(t)= [15cos(27) i + (15sin(27) - gt) j + 0 k] m/s  
r(t)= [(x0 +15cos(27)t) i + (y0 + 15sin(27)t - 1/2*gt^2) j + 0 k] m  
  
d. Velocidad minima segundo jugador y distancia que recorre para lograr atrapar la pelota  
-  
Con la EC3 usamos el componente y para encontrar t:  
y(t)= y0 + v0yt - 1/2*gt^2  
1.05= 0 + 6.81t - 4.9t^2  
4.9t^2 - 6.81t + 1.05 = 0  
  
$$ax^2 + bx + c = 0$$  
  
Aplicamos formula del estudiante:  
a= 4.9  
b= - 6.8  
c= 1.05  
  
$$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$  
  
t1= 0.177 s  
t2= 1.213 s  
  
Hallamos el punto x al que tiene que llegar el jugador 2 para atrapar, con la EC3 usamos el componente x:  
x(t)= x0 + v0xt  
x(1.213)= 0 + 13.37*1.213  
x(1.213)= 16.21 m  
  
Para hallar la distancia que recorre el jugador para atrapar la pelota:  
dr= d - x(13.37)  
dr= 30 - 16.21  
dr= 13.79 m  
  
Para encontrar la velocidad minima del jugador 2 debo hacer las ecuaciones para el jugador:  
x(t)= x0 - vxt → (v y no v0 porque es la rapidez. J2 solo se mueve en x, no en y. y porque tiene velocidad constante)  
x(1.213)= 16.21 m  
16.21 m = 30 - v0x*1.213  
v0x = 11.36 m/s

***
## Ejercicio 1: Proyectil sobre una pendiente (parcial 1 2023-1)
  
Se lanza un proyectil con una velocidad inicial de 200 m/s y un angulo de 60 grados con respecto a la horizontal. Cuando el proyectil cae, lo hace golpeando un plano inclinado 20 grados tambien respecto a la horizontal.  
  
1. Hacer un diagrama indigando el sistema de referencia empleado para la solucion del problema.  
2. Escriba las condiciones iniciales del problema y calcule las ecuaciones cinematicas para el proyectil.  
3. Asumiendo que el proyectil impacta con el plano inclinado en el punto B, calcule las cordenadas (x,y) de ese punto.  
4. Calcular la velocidad a la cual el proyectil alcanza el punto B.  
  
***  
### Solucion  
***  

1. **Sistema de referencia**: (0,0) en el punto A. Con x positivo a la derecha.  
<br> <br/>  
  
2. **Condiciones iniciales**:  
	- θ= 60 °  
	- ß= 20 °  
	- V(0)= 200 m/s  
	- Vx(0)= 200cos(60) m/s  
	- Vy(0)= 200sen(60) m/s  
	- A= (0,0)  
	- B= (x,y)  

- r0 = [0 i + 0 j + 0 k] m  
- v0 = [v0x i + v0y j + 0 k] m/s  
  
v0x = 200cos(60) = 100  
v0y = 200sin(60) = 173.205080757



- v= [(200cos(60)) i + (200sen(60)) j + 0 k] m/s  
- s= (0 i + 0 j + 0 k) m  
  
	**Ecuaciones cinematicas**:  
	- a(t)= [0 i - g j + 0 k] m/s^2  
	- v(t)= [v0x i + (v0y - gt) j + 0 k] m/s  
		→ [200cos(60) i + (200sin(60) - gt) j + 0 k] m/s  
	- r(t)= [(x0 + v0xt) i + (y0 + v0yt - 1/2*gt^2 ] m  
		→ [(200cos(60)t) i + (200sin(60)t - 4.9*t^2) j + 0 k] m

<br> <br/>  
  
Calcular coordenadas  
---  
y= mx +b  
m= tan(20) = 0.36397  
No necesitamos b porque la rampa comienza exactamente en el origen  
y= 0.36397x  
  
Necesitamos encontrar tb:  
y= tan(20)x  
200sin(60)tb - 4.9*tb^2 = tan(20)*200cos(60)tb  
tb= 27.92 s  
  
x = 200cos(60)(27.92)  
= 2792  
y= tan(20)*2792  
= 1016.20489407  
  
B= (2792, 1016.2)  
  
Introduciendo tb en las ecuaciones de posición obtenemos las coordenadas finales de B:  
xb= 200cos(60)*27.92 = 2792.00 m  
yb= 200sin(60)*27.92 - 4.9(27.92)^2 = 1016.21 m  

---
  
Velocidad con la cual el proyectil alcanza el punto b  
---  
v(t)= [v0x + (v0y - gt) j + 0 k] m/s  
→ [100 i + (173.21 - 9.8*27.92) j + 0 k] m/s  
  
vxb= 100  
vyb= 173.21 - 9.8*27.92 = - 100.41  
  
vb = sqrt(100^2 + (- 100.41)^2)  
= 141.71 m/s

<br> <br/>

***
## Ejercicio: Movimiento Circular Uniforme (MCU)

Un satélite de comunicaciones orbita la Tierra a una altura constante, manteniendo una rapidez de 28000 km/h . Si el radio de la Tierra es de 6370 km y el satélite se encuentra a 500 km sobre la superficie:  
  
**A)** Calcula el **periodo de revolución** (tiempo en dar una vuelta completa) en minutos.  
  
**B)** Determina la **aceleración centrípeta** del satélite en  
  
  
.  
  
**C)** ¿Cuál es la **velocidad angular** ( ) en radianes por segundo?

***  
### Solucion  
***  

<br> <br/>
