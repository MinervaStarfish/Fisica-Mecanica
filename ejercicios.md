# Parcial 1 2023-2



## Cinemática de dos cuerpos: Lanzamiento parabólico y MRU  

Jugador izquierda golpea una pelota**
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

|-------------------------------------------------------------------------------------------|

# Parcial 1 2023-1
## Lanzamiento de proyectil  en plano inclinado

Se lanza un proyectil a una velocidad inicial de 200 m/s y un angulo de 60° con respecto a la horizontal. Cuando el proyectil cae, lo hace golpenado un plano inclinado 20° tambien con respecto a la horizontal.

1. Sistema de referencia
2. Condiciones iniciales
3. Ecuaciones cinematicas
4. Asumiendo que el proyectil impacta con el plano inclinado en el punto B, calcule las coordenadas de dicho punto
5. Calcular la velocidad con la cual el proyectil alcanza el punto b

Sistema de referencia 
---
(0,0) en A. Con x paralela con la horizontal.

Condiciones iniciales
---
- r0 = [0 i + 0 j + 0 k] m
- v0 = [v0x i + v0y j + 0 k] m/s

v0x = 200cos(60) = 100
v0y = 200sin(60) = 173.205080757

Ecuaciones cinematicas
---
a(t)= [0 i - g j + 0 k] m/s^2
v(t)= [v0x i + (v0y - gt) j + 0 k] m/s 
→ [200cos(60) i + (200sin(60) - gt) j + 0 k] m/s
r(t)= [(x0 + v0xt) i + (y0 + v0yt - 1/2*gt^2 ] m 
→ [(200cos(60)t) i + (200sin(60)t - 4.9*t^2) j + 0 k] m

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

Velocidad con la cual el proyectil alcanza el punto b
---
v(t)= [v0x + (v0y - gt) j + 0 k] m/s 
→ [100 i + (173.21 - 9.8*27.92) j + 0 k] m/s

vxb= 100
vyb= 173.21 - 9.8*27.92 = - 100.41

vb = sqrt(100^2 + (- 100.41)^2) 
= 141.71 m/s
