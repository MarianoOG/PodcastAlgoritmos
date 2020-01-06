---
layout: episode
category: Podcast
cap: "001"
img: "001.jpg"
tagline: En este episodio discutimos sobre las decisiones. Diferencias y similitudes en el proceso para tomar una decisión entre una computadora y un humano. ¿Crees que una computadora puede tomar decisiones similares a un humano?
author: MarianoOG
css: 
js: 
keywords: Programación, IA, Inteligencia Artificial, Algoritmos, Machine Learning, Ciencia de Datos, Software, marianoog, PodcastAlgoritmos
canonical: https://marianoog.github.io
---
{% include JB/setup %}

# 001 DECISIONES

En este episodio discutimos sobre las decisiones. Diferencias y similitudes en el proceso para tomar una decisión entre una computadora y un humano. ¿Crees que una computadora puede tomar decisiones similares a un humano?

## Introducción

Tomamos decisiones todo el tiempo. En ocasiones, sin consecuencias graves como cargar con un paraguas o no. En otras, demasiado difíciles que nos estresan o incluso llegamos a evitar. Según el diccionario una decisión es: *determinación, resolución que se toma o se da en una cosa dudosa*.<sup>[1](https://dle.rae.es/?id=BxP6lay)</sup> Hacer algo, otra cosa o dejar de hacer. Están determinadas por los objetivos que tenemos, las opciones que vemos en ese momento y las consecuencias que pueden ocasionar. Las decisiones están en todos lados. Las encontramos cada vez que queremos comprar o vender algo, al querer dejar de beber o al elegir pareja. Y se ven influenciadas por las experiencias, los deseos y los sueños de cada quien.

**Cada vez se crean inteligencias artificiales que pueden tomar decisiones más complejas por nosotros**. Muy útiles y obvias en ocasiones como guardar de forma automática un archivo o apagar automáticamente una pantalla después de cierto tiempo sin usarla. Otras decisiones más sutiles y elegantes las podemos encontrar en nuestras redes sociales, donde un programa computacional decide por nosotros qué es lo que queremos ver. Están determinados por parámetros, datos y en ocasiones por el resultado de miles de simulaciones.

### Humanos decidiendo por nosotros

Siempre dejamos que otros decidan por nosotros; queramos aceptarlo o no. Hay decisiones que son personales y que simplemente no se las dejaríamos a alguien más, mucho menos a una máquina. Pero dejar que otros decidan por nosotros tampoco es algo nuevo, lo hacemos cada vez que contratamos a un experto para que realice un servicio para nosotros. A lo mejor será un contador que nos ayuda a pagar impuestos o, tal vez, un mecánico que nos dice que pieza comprar para reparar nuestro vehículo. Incluso, podemos delegar decisiones de forma más compleja al elegir representantes. Estos tomarán decisiones por nosotros y otras personas. Y no solo hablo de representantes políticos también en nuestras familias, en el trabajo o en la escuela. Personas decidiendo por nosotros todo el tiempo.

### Máquinas decidiendo por nosotros

Siempre dejamos que máquinas decidan por nosotros; nos demos cuenta o no. Hay decisiones que son monótonas y que simplemente no vale la pena volver a realizarlas, mucho menos si alguien más tiene una mejor respuesta que la nuestra. Pero la automatización tampoco es algo ajeno, lo hacemos cada vez que utilizamos algún servicio digital. A lo mejor será una subscripción con cargo a nuestra tarjeta de crédito o, tal vez, un automóvil que frena y se estaciona solo. Incluso, podemos delegar decisiones más complejas al compartir más de nuestros datos. Estos serán combinados con nuestro historial y datos de otras personas. Y no solo hablo de realizar anuncios personalizados también para descubrimientos en la educación, -las ciencias o la salud. Máquinas decidiendo por nosotros todo el tiempo.

### Es nuestra responsabilidad

Aunque el servicio lo haga alguien más (o algo más) yo considero que la responsabilidad sigue siendo nuestra. De la misma forma en la que pensamos en quién depositar nuestra confianza tenemos que reflexionar sobre a qué depositamos nuestros datos. Saber distinguir entre el experto y un farsante es nuestra tarea, ya sean humanos o máquinas. Nosotros decidimos que servicio utilizar.

## ¿Cómo deciden las máquinas?

Las máquinas pueden tomar decisiones racionales. Son aquellas donde podemos calcular el riesgo, observar pros y contras así como estimar resultados o utilidades. En algunos casos podemos utilizar "estimadores" llamados heurísticas, algunos otros están determinados por el azar.

### Condiciones booleanas

Son aquellas que pueden ser verdaderas o falsas y no pueden tomar otro valor, las utilizaremos como ejemplo para tomar decisiones con dos
opciones.

Utilizaremos pseudocódigo, es una guía informal, una herramienta para pensar un programa computacional y comunicar las ideas a otras personas. La claridad es el objetivo principal del pseudocódigo. Utilizaremos esta herramienta para describir los ejemplos vistos en el episodio.

### Estructura condicional

Utiliza una condición booleana para determinar la acción a tomar.
```
Si la condición es cierta,
  hacer acción verdadera.
Sino,
  hacer acción falsa
```

#### Ejemplos:

Cruzar o no una calle cuando el semáforo está en rojo o verde.
```
Si el semáforo es verde,
    cruzar la calle
Sino,
    no cruzar la calle
```

Prender o apagar la luz si es de día o noche.
```
Si es de noche,
    Si queremos dormir.
        apagar la luz
    Sino:
        dejarla prendida
Sino es de noche:
     apagar la luz
```
