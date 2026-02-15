## Introducción
Este proyecto es una herramienta interactiva diseñada para visualizar y comparar dos de los algoritmos de asignación de memoria más comunes en los Sistemas Operativos: Best Fit (Mejor Ajuste) y Worst Fit (Peor Ajuste).
El simulador permite gestionar bloques de memoria de tamaño variable y observar en tiempo real cómo se distribuyen los procesos entrantes, calculando automáticamente la fragmentación interna y externa resultante para determinar qué algoritmo es más eficiente.

---
## Instrucciones
1. Configurar la Memoria: En el panel de control, ingrese los tamaños de los bloques de memoria disponibles separados por comas (ej. 100, 500, 200).

2. Definir los Procesos: Ingrese los tamaños de los procesos que desea asignar (ej. 212, 417, 112).

3. Inicializar: Haga clic en "Inicializar Memoria" para preparar los espacios.

4. Ejecutar: Puede elegir entre "Ejecutar Simulación" para ver todo el proceso automático o "Paso a Paso" para analizar cada asignación individualmente.

¿Qué se va a observar?

Animaciones en tiempo real: los bloques cambian de color (Azul para libre, Rojo/Naranja para ocupado) cuando un proceso es asignado.

Barras de progreso: la representación visual dentro de cada bloque que muestra el porcentaje de espacio utilizado.

Lista de procesos: un indicador que muestra qué procesos han sido asignados exitosamente y cuáles están en espera.

¿Qué significan los resultados?

Fragmentación: Es el espacio sobrante dentro de los bloques que no puede ser utilizado por otros procesos en ese momento.

Análisis Comparativo: El sistema resaltará en verde el algoritmo que logró una menor fragmentación total, indicando un uso más optimizado de los recursos.

---
## Explicación de los algortimos

Best Fit (Mejor Ajuste) este algoritmo recorre toda la lista de bloques de memoria y coloca el proceso en el bloque más pequeño disponible que sea lo suficientemente grande para contenerlo.

Worst Fit (Peor Ajuste)  es todo lo contrario, este algoritmo asigna el proceso al bloque más grande disponible.

---
## Reflexión

Este actividad me gusto porque poniamos en pratica lo que vimos en clase con programacion (por lo que ingrese a la carrera) y permite que se entienda de una manera mas didactica el hecho de como funcionan los algoritmos aparte de mejorar mis habilidades en la programacion porque tuve que investigar como se hacia

---
## Referencias
[1] Ann Mciver, Ida M. Flynn, "Understanding Operating Systems". Course Technology,
Cengage Learning, 2011.

[2] Tanenbau, andrew S, "Sistemas Operativos Modernos". Pearson Educacion, 2009.

[3] Abraham Silberschatz, Peter B. Gael, Greg Gagne, "Fundamentos De Sistemas Operativos".
Mc Graw Hill, 2005.

[4] J. Carretero, P. De Miguel, F. García y F. Pérez, "Sistemas Operativos Una vision aplicada".
Mc Graw Hill, 2001.

---
## Uso de IA:

Nombre del estudiante: Joaquin Uriona

IA utilizada: Chatgpt

Fecha de uso: 2026-02-14

Propósito: inspiracion

Prompt utilizado:

hola queria chargpt, querria ver si me podrias ayudar tirando ideas de como podria hacer este punto
de mi tarea, solo ideas pra inspitacion, este es el punto: Simulador HTML Interactivo Crear una
página HTML interactiva que simule los algoritmos Best Fit y Worst Fit Debe incluir: Interfaz visual
para configurar memoria y procesos Animación de asignación de memoria Cálculo de fragmentación
Comparación entre ambos algoritmos. solo necesito eso y nada mas

Archivos suministrados: N/A

Respuesta en crudo (raw):

Claro ��. Acá tenés ideas de inspiración (no implementación) para encarar el Simulador HTML Interactivo

de Best Fit y Worst Fit, organizadas por cada requisito del punto.

1. Interfaz visual para configurar memoria y procesos

Ideas:

Representar la memoria como una barra horizontal dividida en bloques (particiones libres).

Usar inputs numéricos para:

Tamaño total de la memoria.

Tamaño de cada bloque libre (lista editable).

Tamaño de los procesos a cargar (uno por uno o en lista).

Botones:

“Agregar proceso”

“Ejecutar Best Fit”

“Ejecutar Worst Fit”

Colores distintos:

Gris → memoria libre

Verde/Azul → bloques asignados

Rojo → fragmentación

2. Animación de asignación de memoria

Ideas:

Mostrar el proceso “moviendo” visualmente hacia el bloque elegido.

Resaltar temporalmente:

En Best Fit: el bloque libre más pequeño que alcance.

En Worst Fit: el bloque libre más grande.

Usar:

Transiciones CSS (transition) para que la asignación no sea instantánea.

Un pequeño delay entre procesos para que se vea el paso a paso.

Mostrar mensajes tipo:

“Proceso P3 asignado al bloque de 120 KB (Best Fit)”.

4. Cálculo de fragmentación

Ideas:

Mostrar:

Fragmentación interna: espacio desperdiciado dentro de bloques asignados.

Fragmentación externa: suma de bloques libres no contiguos.

Presentarlo como:

Número total (ej. “Fragmentación: 45 KB”).

Porcentaje sobre la memoria total.

Visual:

Rayas o sombreado dentro de los bloques para indicar espacio desperdiciado.

Actualizar el cálculo después de cada asignación.

5. Comparación entre Best Fit y Worst Fit

Ideas:

Dividir la pantalla en dos columnas:

Izquierda → Best Fit

Derecha → Worst Fit

Usar los mismos procesos y memoria inicial para ambos.

Comparar:

Fragmentación total

Cantidad de procesos asignados

Espacio libre restante

Mostrar una conclusión automática:

“Best Fit generó menos fragmentación interna”

“Worst Fit dejó bloques libres más grandes”

Opcional: gráfico simple (barras) comparando fragmentación.

Idea general de enfoque

Pensalo como un laboratorio visual de Sistemas Operativos:

El usuario configura memoria y procesos.

Ve cómo el algoritmo decide.

Observa las consecuencias (fragmentación).

Compara resultados de forma clara y visual.

Si después querés, puedo ayudarte a:

Bajar estas ideas a un mockup

Armar la estructura HTML/CSS

O traducirlo a lenguaje más académico para entregar la tarea ��

---

## 📧 Contacto

- *Email Institucional:* joaquin.uriona@tecdesoftware.edu.mx
- *GitHub:* Joako601(https://github.com/Joako601)

---

<div align="center">

## 📄 Licencia

Este proyecto es parte de las actividades académicas del *Tecnológico de Software* y está bajo la licencia MIT.

<div align="center">

---

<div align="center">
  
## ✨ Autor

<div align="center">

*⭐ Si te gustó este proyecto, dale una estrella ⭐*

Hecho con 💙 por Joaquin Uriona - 2026

</div>
