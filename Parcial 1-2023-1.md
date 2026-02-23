# Parcial 1 (2023-1)



## Ejercicio 1

Se lanza un proyectil con una velocidad inicial de 200 m/s y un angulo de 60 grados con respecto a la horizontal. Cuando el proyectil cae, lo hace golpeando un plano inclinado 20 grados tambien respecto a la horizontal.  
  
1. Hacer un diagrama indigando el sistema de referencia empleado para la solucion del problema.  
2. Escriba las condiciones iniciales del problema y calcule las ecuaciones cinematicas para el proyectil.  
3. Asumiendo que el proyectil impacta con el plano inclinado en el punto B, calcule las cordenadas (x,y) de ese punto.  
4. Calcular la velocidad a la cual el proyectil alcanza el punto B.  

*
### Solucion
*
  
1. *Sistema de referencia*: (0,0) en el punto A. Con x positivo a la derecha. 
[]  
<br> <br/>

2. *Condiciones iniciales*:  
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
  
    *Ecuaciones cinematicas*:  
      
    - v(t)= [(200cos(60)) i + (C - 9.8t) j + 0 k) m/s
    = [(200cos(60)) i + (200sen(60) - 9.8t) j + 0 k] m/s  
    - s(t)= [(200cos(60)t + C) i + (200sen(60)t + C - 4.9t^2^ + C) j + 0 k] m
    = [(200cos(60)t) i + (200sen(60)t - 4.9t^2^) j + 0 k] m  
<br> <br/>
  
3. *Cordenadas B (x,y)*:  
Encontramos la ecuacion de la recta:
y= x tan ß
= 200cos(60)t) tan(20)  
  
    Igualamos (y) para encontrar t:
    200cos(60)t) tan(20) = (200sen(60)t) - 4.9t^2^
    = 100t * 0.36 = 173.2t - 4.9t^2^
    = 4.9t^2^ - 73.2t + 36 t
    = 4.9t^2^ - 37t → t(4.9t - 37) = 0
    t= 7.5 s  
  
    Remplazamos t en la ecuacion de la recta:
    y= (200cos(60) * 7.5) tan(20)
    = 750 * 0.36
    y= 270 m, x= 750 m  
  
    (750,270)

4. *Velocidad en B*:
Cuando nos piden hallar la velocidad en un punto, se refieren a la magnitud del vector ll v ll = $\sqrt{a^2 + b^2 + c^2}$ 

    ll v ll = $\sqrt{100^2 + 1023.4^2 + 0^2}$ 
    = 1028.274 m/s


*

MÓVIL QUE SE MUEVE A LA DERECH  
  
a(t) = (4t + 1) m/s2  
v(0) = 2 m/s  
x(0) = 0 m  
  
condiciones iniciales  
x0 = (0i + 0j + 0k) m  
v0 = (2i + 0j + 0k) m/s  
a0 = (1i + 0j + 0k) m/s2  
---------------------------------------------  
ecuaciones x, v, a  
a(t) = [(4t + 1)i + 0j + 0k] m/s2  
v(t) = [(2t**2 + t + 2) i+ 0j + 0k] m/s  
x(t) = [(2/3 t**3 + 0.5t**2 + 2t )i + 0j + 0k] m  
  
  
  
DOS BOLAS QUE SE TIRAN AL AIRE CON LA MISMA VELOCIDAD INICIAL, UNO 4 SEGUNDOS DESPUÉS DEL OTRO  
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
-----------------------------------------  
ecuaciones de a [a,v,y]  
  
a(t) = (0i - gj + 0k) m/s**2  
v(t) = [0i +(20 - gta)j + 0k] m/s  
y(t) = [0i + (20ta - 0.5gta**2)j + 0k] m  
  
ecuaciones de b [a,v,y]  
  
a(t) = (0i - gj + 0k) m/s**2  
v(t) = [0i +(20 - gtb)j + 0k] m/s  
y(t) = [0i + (20tb - 0.5gtb**2)j + 0k] m  
  
  
------------------------------  
en qué instante t se encuentran  
  
20tb - 0.5gtb**2 = 20(tb + 4) - 0.5g(tb + 4)**2  
20tb - 0.5gtb**2 = 20tb + 80 - 0.5gtb**2 - 4gtb-8g  
20tb = 20tb + 80 - 4gtb-8g  
0 = 80 - 4gtb- 8g  
4gtb = 80 - 8g  
tb = (80 - 8g)/4g s  
  
  
  
  
TIRO PARABOLICO BALONCESTO  
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
  
  
  
  
El C en estos ejercicios siempre corresponde a la condicion inicial para dicha ecuacion,  
  
ejemplo  
a(t) = 2t + 1 m/s**2  
con v(0) = 0 m/s  
  
entonces  
v(t) = t**2 + c  
por la condicion inical conocemos que cuando t = 0, v = 0, entonces reemplazamos en lo que obtuvimos integrando la acelaracion  
v(0) = 0**2 + c  
c = 0  
y entonces v(t) es  
  
v(t) = t**2  
  
  
otra forma es, cuando integras, de una vez dejas que esa c es la condicion inicial  
  
v(t) = 2t + 1  
entonces  
x(t) = t**2 + t + x(0)  
  
  
  
1. Problema de Encuentro (MRU y MRUV)  
  
Un automóvil está detenido frente a un semáforo. En el instante en que la luz cambia a verde, el auto arranca con una *aceleración constante* de 2.2m/s**2 . En ese mismo momento, un camión que se desplaza con una *velocidad constante* de 15 m/s, lo adelanta.  

  *A)* ¿A qué distancia del semáforo alcanzará el automóvil al camión?  
    
  *B)* ¿Qué velocidad tendrá el automóvil en el momento del encuentro?  
    
  *C)* Realice un bosquejo de la gráfica de *posición vs. tiempo* para ambos vehículos en un mismo plano.  
    

  
  
Marco de referencia: El semaforo (0,0). Se mueven en el eje x positivo  
  
Condiciones iniciales:  
  
t= 0 s  
x= 0 m  
  
a. Carro:  
s(0)= (0 i + 0 j + 0 k) m  
v(0)= (0 i + 0 j + 0 k) m/s  
a(0)= (2.2 i + 0 j + 0 k) m/s**2  
  
b. Camion:  
s(0)= (0 i + 0 j + 0 k) m  
v(0)= (15 i + 0 j + 0 k) m/s  
a(0)= (0 i + 0 j + 0 k) m/s**2  
  
Ecuaciones de movimiento:  
  
a. Carro:  
v(t)= [(2.2 t + C) i + 0 j + 0 k] m/s → v(t)= [(2.2 t) i + 0 j + 0 k] m/s  
s(t)= [(1.1 t**2 + C) i + 0 j + 0 k] m → s(t)= [(1.1 t**2) i + 0 j + 0 k] m  
  
b. Camion:  
s(t)= [(15 t + C) i + 0 j + 0 k] m → s(t)= [(15 t) i + 0 j + 0 k] m  
  
*A)* ¿A qué distancia del semáforo alcanzará el automóvil al camión?  
  
Encuentro en que t se encuentran en la misma posicion:  
[(1.1 t**2) i + 0 j + 0 k] m = [(15 t) i + 0 j + 0 k] m → t= 13.64 s  
[(15 * 13.64 s) i + 0 j + 0 k] m → (204.6 i + 0 j + 0 k) m  
  
*B)* ¿Qué velocidad tendrá el automóvil en el momento del encuentro?  
  
[(2.2 * 13.64 s) i + 0 j + 0 k] m/s → (30.008 i + 0 j + 0 k) m/s  
  
  
  
  
2. Lanzamiento de Proyectiles (Movimiento Parabólico)  
Un rescatista lanza un paquete de suministros desde un avión que vuela horizontalmente a una altura de 120 m con una velocidad de 180 km/h  
. El objetivo es que el paquete caiga en un campamento ubicado en el suelo.  

  *A)* ¿Cuántos metros antes de sobrevolar el campamento debe soltar el paquete para que impacte en el blanco?  
    
  *B)* ¿Cuál es la *magnitud de la velocidad* resultante del paquete justo antes de tocar el suelo?  
    
  *C)* Calcule el *ángulo de impacto* con respecto a la horizontal.  
    

3. Movimiento Vertical y Caída Libre  
Desde la azotea de un edificio de 40 m de altura, se lanza una piedra hacia arriba con una velocidad inicial de 15 m/s . En su camino de caída, la piedra pasa frente a una ventana que está a 15 m del suelo.  

  *A)* ¿Cuál es la *altura máxima* que alcanza la piedra respecto al suelo?  
    
  *B)* ¿Cuánto tiempo transcurre desde que se lanza la piedra hasta que pasa frente a la ventana?  
    
  *C)* Si un segundo objeto se dejara caer desde la misma azotea 1 s después de lanzar la primera piedra, ¿cuál de los dos llegaría primero al suelo?  
    

Un jugador de baloncesto lanza un balón desde una altura de 2m con una velocidad inicial de 8.5 m/s y un ángulo de inclinación de 60 ⌂  
sobre la horizontal. La canasta se encuentra a una distancia horizontal de 6 m y tiene una altura de 3.05 m .  

  *A)* ¿Logra el balón entrar en la canasta?  
    
  *B)* ¿Cuál es la *velocidad del balón* (magnitud y dirección) justo en el instante en que alcanza la posición de la canasta?  
    
  *C)* ¿Cuánto tiempo permanece el balón en el aire?  
    

5. Movimiento Circular Uniforme (MCU)  
Un satélite de comunicaciones orbita la Tierra a una altura constante, manteniendo una rapidez de 28000 km/h . Si el radio de la Tierra es de 6370 km y el satélite se encuentra a 500 km sobre la superficie:  

  *A)* Calcula el *periodo de revolución* (tiempo en dar una vuelta completa) en minutos.  
    
  *B)* Determina la *aceleración centrípeta* del satélite en  
    

.  

  *C)* ¿Cuál es la *velocidad angular* ( ) en radianes por segundo?
