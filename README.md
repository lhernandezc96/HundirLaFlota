<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Hundir la Flota</title>
</head>
<body>

<h1>Hundir la Flota</h1>

<h2>Descripción</h2>
<p>Este proyecto implementa el juego clásico "Hundir la Flota" en Python. El juego involucra dos jugadores, cada uno con su propio tablero de barcos. El objetivo es hundir todos los barcos del oponente mediante disparos a sus coordenadas.</p>

<h2>Autor</h2>
<p>Luis Hernández Casado</p>

<h2>Librerías Utilizadas</h2>
<ul>
    <li>NumPy</li>
</ul>

<h2>Recursos Utilizados</h2>
<ul>
    <li>Python 3.x</li>
    <li>IDE o entorno de desarrollo</li>
</ul>

<h2>Archivos</h2>

<h3>funciones.py</h3>
<p>Este archivo contiene funciones esenciales para el juego, incluyendo la posición de los barcos, la generación aleatoria de nuevos barcos y funciones para realizar disparos en los tableros.</p>

<h3>tablero.py</h3>
<p>La clase <code>Tablero</code> se define en este archivo. Cada jugador tiene su propio tablero, donde se colocan y registran los barcos.</p>

<h3>jugar.py</h3>
<p>El script principal <code>jugar.py</code> inicia y gestiona el juego. Los jugadores pueden realizar disparos alternos hasta que todos los barcos de un jugador sean hundidos.</p>

<h2>Ejecución</h2>
<p>Para iniciar el juego, simplemente ejecute el script <code>jugar.py</code>. Siga las instrucciones en la consola para ingresar coordenadas y jugar contra la máquina.</p>

<pre><code>python jugar.py</code></pre>

<h2>Reglas del Juego</h2>
<ol>
    <li>Cada jugador tiene barcos de diferentes longitudes:</li>
    <ul>
        <li>4 barcos de 1 posición de eslora</li>
        <li>3 barcos de 2 posiciones de eslora</li>
        <li>2 barcos de 3 posiciones de eslora</li>
        <li>1 barco de 4 posiciones de eslora</li>
    </ul>
    <li>Los jugadores toman turnos para disparar a las coordenadas del oponente.</li>
    <li>El juego continúa hasta que todos los barcos de un jugador sean hundidos.</li>
    <li>Las coordenadas se ingresan como pares de números (fila, columna) del 0 al 9.</li>
    <li>El juego incluye tres niveles de dificultad en la toma de decisiones de la máquina.</li>
</ol>

<h2>Salida del Juego</h2>
<p>El juego imprime en la consola el resultado del juego, ya sea que el jugador o la máquina haya ganado. ¡Disfruta hundiendo la flota!</p>

</body>
</html>
