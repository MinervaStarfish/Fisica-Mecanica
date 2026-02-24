PARTE C

1 - 4 - 8 - 14 - 21 - 28

Si se añade el nodo 18, busca su sucesor de la misma forma en que lo haria con una llave normal (partiendo de un nodo conocido, con closest preceding node), solo que ese sucesor no seria responsable de 18, solo nos daría la información de su ID.

successor (18) = 21

Tambien, 21 sabe que predecessor(21) = 14
por lo que ahora, predecessor(18) = 14

21 actualiza,  predecessor(21) = 18, con un notify(18)

Hasta este punto, 14 no tiene informacion de su nuevo sucesor, esto se soluciona con stabilize(), que se ejecuta periodicamente,
entonces se ejecuta stabilize(14),  A 21, que le devuelve su predecesor, como no es igual a 14, 14 actualiza su sucesor successor(14) = 18

finger table de 18
i   start-i  successor(start-i)

1 19  21
2 20  21
3 22  28
4 26  28
5 2    4

Hasta ahora, ningun finger de las demas finger tables apunta a 18, esto se va actualizando con fix_fingers(), que se ejecuta para cada entrada de cada finger table, y recalcula el finger para uno de los saltos.

stabilize(n), pregunta a successor(n) cual es su predecesor, si es diferente que n, entonces successor(n) cambia.
notify(n), n pregunta a successor(n), cual es su predecesor, si es diferente y n es mayor, entonces el predecesor de successor(n), cambia
fix_fingers(), se ejecuta periodicamente y aleatoriamente, para un indice de cualqueir finger table de los nodos, y recalcula el finger para dicho salto, actualizando sus referencias

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
PARTE D


# Ejercicios Cinematica
  
https://github.com/yonatanmgr/mathberet
https://github.com/gillescastel/lecture-notes?tab=readme-ov-file
https://github.com/gillescastel/masterthesis/blob/master/thesis/todo.tex
https://www.galassi.org/mark/markgalassi-documentation-builds/rest-tutorial/rest-tutorial.pdf

https://www.markdownguide.org/basic-syntax/
https://rpruim.github.io/s341/S19/from-class/MathinRmd.html
https://support.typora.io/Draw-Diagrams-With-Markdown/

https://github.com/f0nzie/tikz_favorites/tree/master
http://math.et.info.free.fr/TikZ/bdd/TikZ-Impatient.pdf
https://indico.kit.edu/event/48/contributions/3405/attachments/1693/2321/tikz_tutorial.pdf
https://tikz.net/

https://www.google.com/imgres?q=markdown%20notes&imgurl=https%3A%2F%2Fi.redd.it%2Fc6amj988bsp91.png&imgrefurl=https%3A%2F%2Fwww.reddit.com%2Fr%2Funixporn%2Fcomments%2Fxmpet0%2Fbspwm_rate_my_lightweight_notetaking_setup%2F&docid=zDHbDRd95DjleM&tbnid=4C1Cbezap57oBM&vet=12ahUKEwiknZng9PCSAxWAN2IAHU2tJG0QnPAOegQIGxAA..i&w=1920&h=1080&hcb=2&itg=1&ved=2ahUKEwiknZng9PCSAxWAN2IAHU2tJG0QnPAOegQIGxAA

$E=mc^2$.

$\vec{v} =$
$\hat{x}$

$$
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

$x^{n}$
$x_{n}$

$\sin(x)$

$\theta$
$\beta$
$\alpha$
$\pi$
$\sigma$



```
This is a multi-line code block.
It preserves all formatting and spacing.
```


```python
def hello():
    print("Hello, world!")
```
> [!NOTE]

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
## Ejercicio: Encuentro retardado

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
## Ejercicio: Tiro parabolico baloncesto 2

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
## Ejercicio: Lanzamiento de Proyectiles

Un rescatista lanza un paquete de suministros desde un avión que vuela horizontalmente a una altura de 120 m con una velocidad de 180 km/h. El objetivo es que el paquete caiga en un campamento ubicado en el suelo.

1. ¿Cuántos metros antes de sobrevolar el campamento debe soltar el paquete para que impacte en el blanco?  
2. ¿Cuál es la **magnitud de la velocidad** resultante del paquete justo antes de tocar el suelo?  
3. Calcule el **ángulo de impacto** con respecto a la horizontal.

***  
### Solucion  
***  

<br> <br/>

***
## Ejercicio: Beisbol

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

<br> <br/>

***
## Ejercicio 1: Proyectil sobre una pendiente 
  
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
	- a= (0 i - 9.8 j + 0 k) m/s**2  
	- v= [(200cos(60)) i + (200sen(60)) j + 0 k] m/s  
	- s= (0 i + 0 j + 0 k) m  
  
	**Ecuaciones cinematicas**:  
  
	- v(t)= [(200cos(60)) i + (C - 9.8t) j + 0 k) m/s  
	= [(200cos(60)) i + (200sen(60) - 9.8t) j + 0 k] m/s  
	- s(t)= [(200cos(60)t + C) i + (200sen(60)t + C - 4.9t^2^ + C) j + 0 k] m  
	= [(200cos(60)t) i + (200sen(60)t - 4.9t^2^) j + 0 k] m  
<br> <br/>  
  
3. **Cordenadas B (x,y)**:  
	- Encontramos la ecuacion de la recta:  
	y= x tan ß  
	= 200cos(60)t) tan(20)  
  
	- Igualamos (y) para encontrar t:  
	200cos(60)t) tan(20) = (200sen(60)t) - 4.9t^2^  
	100t * 0.36 = 173.2t - 4.9t^2^  
	= 4.9t^2^ - 73.2t + 36 t  
	= 4.9t^2^ - 37t 
	t(4.9t - 37) = 0  
	t= 7.5 s  
  
	- Remplazamos t en la ecuacion de la recta:  
	y= (200cos(60) * 7.5) tan(20)  
	= 750 * 0.36  
	y= 270 m, x= 750 m  
  
	B(x,y)= (750,270)  
<br> <br/>  
  
4. **Velocidad en B**:  
Cuando nos piden hallar la velocidad en un punto, se refieren a la magnitud del vector llvll = $\sqrt{a^2 + b^2 + c^2}$  
  
	llvll = $\sqrt{100^2 + 1023.4^2 + 0^2}$  
	= 1028.274 m/s
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
