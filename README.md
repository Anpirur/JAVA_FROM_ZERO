# ☕ Learning Java

Repositorio práctico de aprendizaje y profundización en **Java**. Incluye una colección completa de ejercicios, algoritmos, proyectos modulares y ejemplos prácticos que abarcan desde los fundamentos de la programación orientada a objetos (POO) hasta interfaces gráficas (Swing), concurrencia (Threads), comunicación en red (Sockets) y persistencia (JDBC).

---

## 📚 Contenido del Repositorio

El código está estructurado por módulos temáticos dentro de `src/main/java/`:

### 1. Fundamentos de Java (`/basico`)

* **Variables y Tipos de Datos:** Declaración, casteo y operaciones primitivas.


* **Entrada de Datos:** Uso de `Scanner` y lectura por consola.


* **Estructuras Condicionales:** Sentencias `if-else`, `switch-case` y resolución de problemas de lógica.


* **Bucles y Control de Flujo:** `for`, `while`, `do-while`, manipulación con `StringBuilder` y algoritmos numéricos (más de 60 ejercicios resueltos).


* **Números Aleatorios y Métodos Matemáticos:** Uso de `Math.random()`, cálculos de potencias y redondeos.



### 2. Estructuras de Datos y Algoritmos

* **Arrays Unidimensionales y Bidimensionales (`/arrays`):** Recorridos, matrices, búsqueda de patrones y minijuegos por consola (p. ej., *Buscatesoros*, simulación de movimientos de ajedrez).


* **Colecciones (`/colecciones`):**
* `ArrayList` y `LinkedList`.


* Conjuntos: `HashSet` (`coleccionSet`) y `TreeSet`.


* Mapas: `HashMap` / `Map`.


* Comparaciones de objetos y sobreescritura de `equals()` / `hashCode()`.





### 3. Programación Orientada a Objetos (`/poo`)

* **Clases y Métodos:** Modelado de dominios reales (Bancos, Colegios, Paquetería, Pizzerías, Vehículos, etc.).


* **Herencia y Polimorfismo:** Jerarquías de clases y reutilización de código.


* **Clases Abstractas e Interfaces:** Abstracción y contratos de comportamiento.


* **Clases Internas:** Encapsulación y temporizadores.


* **Modificadores de Acceso:** Encapsulamiento y visibilidad (`public`, `private`, `protected`).



### 4. Interfaces Gráficas con Java Swing (`/swing` & `/procesadorTexto`)

* **Contenedores y Componentes:** `JFrame`, `JPanel`, `JButton`, `JTextField`, `JSlider`, `JSpinner`, `JComboBox`, `JRadioButton`, menús y barras de herramientas.


* **Gestores de Diseño (Layouts):** `FlowLayout`, `BorderLayout`, `GridLayout` y diseño de calculadoras.


* **Manejo de Eventos (`/eventos`):** `ActionListener`, eventos de ratón (`MouseListener`), teclado (`KeyListener`), focos y ventanas con clases adaptadoras.


* **Gráficos 2D:** Dibujo de formas vectoriales, renderizado de fuentes e imágenes.


* **Procesador de Texto:** Aplicación de edición de texto con formato (negrita, cursiva, subrayado, alineación y cambio de colores).



### 5. Conceptos Avanzados

* **Gestión de Excepciones (`/excepciones`):** Control de errores con `try-catch-finally`, propagación `throws` y creación de excepciones personalizadas.


* **I/O y Ficheros (`/accesoFicheros`, `/archivosExternos`):** Lectura y escritura de ficheros con `FileReader`, `FileWriter`, `BufferedReader`, manipulación de rutas y creación de directorios.


* **Serialización de Objetos (`/serializando`):** Persistencia en binario con `ObjectOutputStream` y `ObjectInputStream`.


* **Hilos y Concurrencia (`/threads`):** Creación de hilos, sincronización (`synchronized`) y animaciones concurrentes (*PelotaRebota*).


* **Sockets y Red (`/sockets`):** Comunicación cliente-servidor mediante sockets TCP.


* **Bases de Datos con JDBC (`/jdbc`):** Conexión a bases de datos relacionales y ejecución de sentencias SQL (DML/DDL).



---

## 🛠 Tecnologías y Herramientas

* **Lenguaje:** Java (compatible con Java 8 / 11 / 17 / 21)


* **Gestor de Dependencias y Construcción:** Maven (`pom.xml`)


* **Testing:** JUnit 4 / Hamcrest Core (`/lib`)


* **Entornos recomendados:** Eclipse IDE, IntelliJ IDEA, Apache NetBeans o VS Code



---

## 🚀 Cómo Empezar

### Requisitos Previos

* Tener instalado el **Java Development Kit (JDK)** versión 8 o superior.
* Tener instalado **Apache Maven** (opcional si usas un IDE moderno).

### Clonar y Ejecutar

1. **Clonar el repositorio:**
```bash
git clone https://github.com/tu-usuario/Learning_Java.git
cd Learning_Java

```


2. **Compilar el proyecto con Maven:**
```bash
mvn clean compile

```


3. **Ejecutar cualquier clase con método `main`:**
* Desde tu IDE: Haz clic derecho en el archivo deseado y selecciona **Run As -> Java Application**.
* Desde consola:
```bash
mvn exec:java -Dexec.mainClass="procesadorTexto.ProcesadorTexto"

```





---

## 📌 Autor

Proyecto organizado con fines educativos y de consulta para el aprendizaje progresivo del ecosistema Java.
