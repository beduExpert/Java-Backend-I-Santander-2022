## Sesi贸n 1: Construcci贸n de proyectos con Gradle :elephant:

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gradle/gradle-plain.svg" align="right" height="120" hspace="10">

<div style="text-align: justify;">
 
### 1. Objetivos :dart:

- Aprender el uso de la herramienta Gradle para construir y ejecutar proyectos en lenguaje Java.

### 2. Contenido :blue_book:

#### 馃憖 Antes de comenzar...

Debemos verificar que nuestro equipo tenga correctamente instalado **Java** y **Gradle**:

- Para verificar la versi贸n instalada de **Java** ejecuta el comando `java -version`:

<img src="../.github/assets/img/java-version.png" alt="Versi贸n de Java" />

*Nota: Usaremos la versi贸n 11 de Java aunque puedes usar la m谩s reciente.*

- Para verificar la versi贸n instalada de **Gradle** ejecuta el comando `gradle -version`:

<img src="../.github/assets/img/gradle-version.png" alt="Versi贸n de Gradle" />

*Nota: Usaremos la versi贸n 7 de Gradle aunque puedes usar la m谩s reciente.*

En este m贸dulo aprenderemos:
- Creaci贸n de archivo `build.gradle`
- Compilaci贸n de c贸digo Java usando Gradle
- Ejecuci贸n de programas en c贸digo Java usando Gradle
- Instalaci贸n y uso de plugins de Gradle

---

<img src=".github/assets/img/Build-Tools.jpg" align="right" height="90" hspace="10">

#### <ins>Tema 1: 驴Qu茅 es Gradle?</ins>

Todo proyecto que utilice Gradle como herramienta de construcci贸n debe tener un archivo llamado `gradle.build` el cual contiene las instrucciones necesarias (en lenguaje Groovy) para ejecutar **tareas** que ayuden a realizar alguna acci贸n sobre c贸digo.

Comenzaremos con el [primer ejemplo](./Ejemplo-01) creando nuestras propias tareas personalizadas para conocer el uso b谩sico de Gradle.

- [**`EJEMPLO 1`**](./Ejemplo-01)

---

<img src=".github/assets/img/command-line.jpg" align="right" height="90" hspace="10">

#### <ins>Tema 2: Compilaci贸n y ejecuci贸n con Gradle.</ins>

Ahora que conocemos el uso general de Gradle, veremos c贸mo usarlo para el desarrollo de aplicaciones Java. En el [segundo ejemplo](./Ejemplo-02) lo usaremos para compilar una aplicaci贸n desde l铆nea de comandos (as铆 es, sin usar un IDE) y posteriormente, en el [tercer ejemplo](./Ejemplo-03) generaremos un jar para su ejecuci贸n usando el mismo Gradle.

Es aqu铆 donde tendr谩s tu [primer reto](./Reto-01) en el que tendr谩s que escribir tu primera aplicaci贸n, compilarla y generar un archivo `.jar`.

- [**`EJEMPLO 2`**](./Ejemplo-02)
- [**`EJEMPLO 3`**](./Ejemplo-03)
- [**`Reto 1`**](./Reto-01)

---

 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" align="right" height="90" hspace="10">

#### <ins>Tema 3: Compilaci贸n y ejecuci贸n de aplicaciones Javas.</ins>

Aqu铆 aprender谩s como compilar y ejecutar tu aplicaci贸n sin tener que generar el archivo `.jar`. Para eso usaremos un plugin de Gradle, `application` el cual nos simplificar谩 la vida. 

- Compilaci贸n y ejecuci贸n de aplicaciones Java

- [**`EJEMPLO 4`**](./Ejemplo-04)
- [**`Reto 2`**](./Reto-02)

---

### 3. Postwork :memo:

Encuentra las indicaciones y consejos para reflejar los avances de tu proyecto de este m贸dulo.
 
- [**`POSTWORK SESI脫N 1`**](./Postwork/)
  
<br/>

</div>
