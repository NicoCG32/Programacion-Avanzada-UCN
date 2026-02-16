# Programación Avanzada - UCN

Recopilación de pruebas y material de apoyo para **Programación Orientada a Objetos (POO)** y **Técnicas y Metodologías de Programación Avanzada** de la Universidad Católica del Norte. Incluye enunciados de pruebas (PRUEBA), evaluaciones de recuperación (RECA) y soluciones implementadas en Java.

---

## Pruebas Resueltas

Se han implementado soluciones completas para las siguientes pruebas:

### Programación Orientada a Objetos
  
  **Prueba 1**
  
  - ✅ [Prueba 1 - 2025 S1](Prog.%20Orientada%20a%20Objetos/PRUEBA%201/2025%20S1/Solución/) **Completa** - Ruteo con salida y diagrama de objetos + Programa con multiplicidad 1...N
  - ⚠️ [Prueba 1 - 2023 S2](Prog.%20Orientada%20a%20Objetos/PRUEBA%201/2023%20S2/Solución/) **Implementada** - Ruteo de línea a línea + Programa con multiplicidad N...N

  **Prueba 2**

  - ✅ [Prueba 2 - 2024 S1](Prog.%20Orientada%20a%20Objetos/PRUEBA%202/2024%20S1/Solución/) **Completa** - Ruteo GUI dinámico + Programa con Visitor
  - ✅ [Prueba 2 - 2024 S2](Prog.%20Orientada%20a%20Objetos/PRUEBA%202/2024%20S2/Solución/) **Completa** - Ruteo GUI dinámico + Programa Strategy y Visitor

### Técnicas y Metodologías de Programación Avanzada

  **Prueba 1**
  
  - ✅ [Prueba 1 - 2025 S1](Técnicas%20y%20Metodologías%20de%20Prog.%20Avanz/PRUEBA%201/2025%20S1/Solución/) **Completa** - Recursión + Divide y Conquista + Árbol Binario de Búsqueda

  **Prueba 2**
  
  - ✅ [Prueba 2 - 2024 S2](Técnicas%20y%20Metodologías%20de%20Prog.%20Avanz/PRUEBA%202/2024%20S2/Solución/) **Completa** - Backtracking + Árbol Binario de Búsqueda + Concurrencia con sincronización

**Otras evaluaciones**: Se encuentran en estado **Por Implementar** pero cuentan con enunciados en PDF, carpeta `Solución` con estructura base, README con instrucciones para cargar en Eclipse, y carpeta `src/` lista para agregar código.

---

## Estructura y Navegación

### Organización del Repositorio

```
Programación-Avanzada-UCN/
├── Prog. Orientada a Objetos/
│   ├── PRUEBA 1/
│   ├── PRUEBA 2/
│   └── RECA/
├── Técnicas y Metodologías de Prog. Avanz/
│   ├── PRUEBA 1/
│   ├── PRUEBA 2/
│   └── RECA/
└── Prog. Avanzada/
    ├── PRUEBA 1/
    ├── PRUEBA 2/
    └── RECA/
```

### Contenido de Cada Evaluación

- **PRUEBA.pdf** o **Prueba - Parte 1/2.pdf**: Enunciado de la evaluación
- **Archivos.txt**: Los txt a cargar (si aplica)
- **Solución/**: Carpeta con la implementación
  - **src/**: Código fuente Java
  - **README.md**: Especificaciones de la prueba y cómo cargar en Eclipse
  - **referencia/**: Soluciones de referencia (cuando aplica)
  - **EXPLICACION.md**: Documentación detallada de algoritmos (cuando aplica)

---

## Notas

Las soluciones están en desarrollo y se actualizan constantemente.

---

## Temas de Estudio (Material de Referencia)

### Programación Orientada a Objetos

#### Herramientas y Entorno
- Introducción a Java
- Eclipse IDE (Instalación y configuración)

#### Nivelación
- Tipos de datos y variables
- Lectura de archivos (Scanner & File)
- Ejecución de programas en Java (Compilación != Ejecución)
- **Manejo de excepciones (Try/Catch)**:
  - Excepciones en Java
  - Try-catch-finally para manejo de errores
- Referencias en Java

#### Conceptos Fundamentales POO
- **Abstracción**: Representar entidades del mundo real mediante código
- **Objetos**: Instancias de clases que encapsulan estado y comportamiento
- **Encapsulamiento**: Controlar el acceso a datos mediante visibilidad (public, private, protected)
- **Mensajes**: Comunicación entre objetos mediante llamadas a métodos

#### Clases y Métodos
- Constructores y rutina constructora
- Métodos y su propósito en la programación
- Sobrecarga de métodos (métodos con mismo nombre, diferentes parámetros)
- Sobreescritura de métodos (redefinición en clases heredadas)
- Getters y Setters (accesores y mutadores)
- Concepto de `this` (referencia al objeto actual)
- Comparación y prueba de objetos
- `toString()` y representación en texto

#### Colecciones y Genéricos
- **Arreglos**: Estructuras de datos estáticas
- **ArrayList y LinkedList**: Listas dinámicas y sus características
- **Genéricos**: Parametrización de tipos para mayor seguridad
- **Interface List**: Contrato que implementan las colecciones
- **Iteradores**: Recorrido seguro de colecciones

#### Composición y Relaciones
- Atributos de tipo objeto (composición)
- Composición vs Agregación (relaciones entre clases)
- Multiplicidad (1:1, 1:N, N:N)
- Construcción de instancias complejas
- **Modelo del Dominio**: Análisis de problemas reales
- **Diagramas de clases**: Visualización de relaciones

#### Herencia y Polimorfismo
- **Herencia**: Generalización y especialización de clases
- **Jerarquías de clases**: Estructuración mediante relaciones parent-child
- **Casting de objetos**: Conversión de tipos en jerarquías
- **Visibilidad en herencia**: Acceso a miembros heredados
- **Polimorfismo**: Métodos con comportamiento variable según el tipo real
- **Clases Abstractas**: Plantillas para jerarquías (no pueden instanciarse)
- **Métodos Abstractos**: Establecen contrato que subclases deben cumplir

#### Interfaces y Contratos
- **Interfaces**: Especificación pura de métodos sin implementación
- **Implementación de interfaces**: Cumplir con contratos definidos
- Múltiple implementación (una clase puede implementar varias interfaces)
- Documentación de contratos

#### Ingeniería de Software
- **Ciclo de vida del software**: Fases de desarrollo
- **Calidad del software**: Métricas y prácticas
- **Depuración**: Técnicas de debugging en Eclipse
- **Testing y Validación**:
  - Diseño de casos de prueba
  - Validación de entrada
  - Pruebas unitarias y de integración
- **Manejo de Excepciones mejorado**:
  - Tratamiento y propagación de excepciones
  - Excepciones en arquitectura

#### Arquitectura de Software
- **Diagramas de clases mejorado**: Visualización de relaciones con interfaces y herencia
- **Arquitectura de Aplicaciones**:
  - Patrón de 3 capas: Presentation, Business, Data
  - Estructura `App → Sistema (Interface) → SistemaImpl (Implementación)`
  - Modularización mediante paquetes
  - Organización del código
  - Separación de responsabilidades

- **SOLID - Principios de Diseño**:
  - **Single Responsibility Principle (SRP)**: Una clase, una responsabilidad
  - **Open/Closed Principle (OCP)**: Abierto para extensión, cerrado para modificación
  - **Liskov Substitution Principle (LSP)**: Subclases deben ser sustituibles por su clase base
  - **Interface Segregation Principle (ISP)**: Interfaces pequeñas y específicas
  - **Dependency Inversion Principle (DIP)**: Depender de abstracciones, no de implementaciones concretas

#### Patrones de Diseño
- **Patrones Creacionales** (cómo crear objetos):
  - **Singleton**: Garantizar una única instancia en toda la aplicación
  - **Factory**: Crear objetos sin especificar clases concretas
  
- **Patrones de Comportamiento** (cómo se comportan los objetos):
  - **Strategy**: Encapsular algoritmos intercambiables
  - **Observer**: Notificar cambios a múltiples observadores *(Generalmente no se ve)*
  - **Visitor**: Operar sobre estructuras complejas
  
- **Patrones Estructurales** (cómo se organizan los objetos):
  - **Decorator**: Añadir funcionalidad dinámicamente *(Generalmente no se ve)*
  - **Adapter**: Compatibilidad entre interfaces *(Generalmente no se ve)*

#### Interfaz Gráfica (Javax Swing)
- Creación de ventanas y componentes
- Botones y controles interactivos
- Eventos y listeners
- Layouts (FlowLayout, BorderLayout, GridLayout)
- Paneles y contenedores
- Imágenes y Graphics
- Aplicaciones Swing completas

---

### Técnicas y Metodologías de Programación Avanzada

#### Recursión
- **Concepto**: Funciones que se llaman a sí mismas
- **Base recursiva**: Condición de parada (ej: n <= 1)
- **Caso recursivo**: Llamada con parámetros modificados
- **Ejemplos clásicos**:
  - Factorial: n! = n * (n-1)!
  - Fibonacci: fib(n) = fib(n-1) + fib(n-2)
  - Búsqueda binaria recursiva
- **Análisis**: Ventajas (elegancia) y desventajas (memoria y velocidad)

#### Divide y Conquista
- **Estrategia**: Dividir el problema en subproblemas más pequeños
- **Combinar**: Resolver recursivamente y combinar resultados
- **Ejemplos**:
  - Búsqueda del máximo/mínimo
  - Mergesort: Divide en mitades, ordena recursivamente, fusiona
  - Quicksort: Particiona, ordena recursivamente
- **Complejidad**: Análisis de eficiencia O(n log n)

#### Árboles
- **Conceptos**:
  - Nodos: Puntos con datos
  - Aristas: Conexiones entre nodos
  - Raíz: Nodo superior
  - Hojas: Nodos sin hijos
  - Altura y profundidad
  
- **Tipos de árboles**:
  - **Árbol Binario**: Cada nodo tiene máximo 2 hijos
  - **Árbol Binario de Búsqueda (ABB)**: Orden izquierda < padre < derecha
  - **Árbol Balanceado**: Minimiza altura para búsqueda óptima
  - **Árbol Completamente Lleno**: Maximiza nodos por nivel
  
- **Recorridos**:
  - **BFS (Breadth-First)**: Por niveles
  - **DFS (Depth-First)**:
    - Pre-orden: Visitar primero, luego hijos
    - In-orden: Hijo izquierdo, nodo, hijo derecho
    - Post-orden: Hijos primero, luego nodo
  
- **Operaciones**:
  - Inserción manteniendo orden
  - Búsqueda eficiente
  - Eliminación compleja
  - **Heapsort**: Ordenamiento mediante heap

#### Backtracking
- **Concepto**: Exploración de soluciones con retroceso cuando falla
- **Patrón**: Explorar → Aceptar/Rechazar → Retroceder
- **Problemas clásicos**:
  - **8 Reinas**: Colocar reinas sin atacarse
  - **Problema del Caballo**: Recorrer tablero de ajedrez
  - **Laberintos**: Encontrar salida
  - **Combinaciones/Permutaciones**: Generar todas las disposiciones
- **Ventaja**: Encuentra todas las soluciones posibles

#### Concurrencia y Paralelismo
- **Programación secuencial**: Instrucciones una tras otra
- **Programación paralela**: Múltiples procesadores simultáneamente
- **Programación concurrente**: Múltiples hilos en un procesador
- **Hilos (Threads) en Java**:
  - **Creación de hilos - Forma 1: Extender Thread**
    - Heredar de la clase Thread y sobrescribir el método `run()`
    - Desventaja: No puede heredar de otra clase (Java no permite herencia múltiple)
  
  - **Creación de hilos - Forma 2: Implementar Runnable** (preferido)
    - Implementar la interfaz Runnable y pasarla a un nuevo Thread
    - Ventaja: Permite heredar de otras clases además de usar Runnable
  
  - **Ciclo de vida de threads**: New → Runnable → Running → Waiting → Terminated
  
  - **Atributos base de un Thread**:
    - **ID**: Identificador único del hilo (asignado automáticamente)
    - **Nombre**: Identificador legible (ej: "Thread-0", "main")
    - **Prioridad**: Valor de 1 a 10 que indica importancia relativa
    - **Estado**: Estado actual (New, Runnable, Running, Waiting, Terminated)
    - **Grupo**: ThreadGroup al que pertenece el hilo
  
  - **Métodos fundamentales**:
    - `start()`: Inicia la ejecución del hilo (llama a run() en nuevo thread)
    - `run()`: Define el código que ejecutará el hilo
    - `join()`: Espera a que el hilo termine antes de continuar
  - **Métodos comunes y útiles**:
    - `sleep(long millis)`: Pausa el hilo durante milisegundos
    - `interrupt()`: Interrumpe la ejecución del hilo
    - `isAlive()`: Verifica si el hilo está en ejecución
    - `getName()`, `setName()`: Obtener/establecer nombre del hilo
    - `getPriority()`, `setPriority()`: Obtener/establecer prioridad (1-10)
    - `yield()`: Cede el control a otros hilos
  - **Sincronización**:
    - `synchronized`: Bloquear acceso a secciones críticas
    - Locks y ReentrantLock
    - `volatile`: Variables compartidas thread-safe
- **Problemas comunes**:
  - Condiciones de carrera
  - Deadlocks
  - Race conditions
- **Soluciones**: Sincronización crítica, estructuras thread-safe

--- 

# Glosario NicoPablo

## 1. Clase vs Objeto

La **clase** es el molde o plano que define la estructura y el comportamiento de un conjunto de objetos. En ella se especifican:

- Los **atributos** (estado).
- Los **métodos** (comportamiento).
- Las reglas internas que regulan su funcionamiento.

Puede entenderse como la receta y el cortador de galletas.

El **objeto**, en cambio, es una **instancia concreta** creada a partir de una clase.  
Es la galleta real, con valores propios en sus atributos.

Conceptualmente:

- La clase define la estructura.
- El objeto contiene el estado.
- La clase existe en el código.
- El objeto existe en memoria durante la ejecución.

---

## 2. Abstracción

La **abstracción** consiste en interpretar y modelar un problema del mundo real, identificando los elementos esenciales y omitiendo los irrelevantes.

Antes de programar, se debe decidir:

- Qué entidades forman parte del problema.
- Qué clases se necesitan.
- Qué atributos son relevantes.
- Qué comportamientos deben modelarse.

Por ejemplo, si un amigo te pide guardar ropa, puedes pensar en un clóset, una habitación o una caja; tú defines la forma y las propiedades específicas.

Abstraer implica:

- Simplificar la realidad.
- Enfocarse en lo necesario para resolver el problema.
- Construir un modelo coherente y funcional.

Una mala abstracción conduce a un diseño deficiente.

---

## 3. Encapsulamiento

El **encapsulamiento** consiste en controlar la visibilidad y el acceso a los atributos y métodos de una clase.

Su objetivo es:

- Proteger el estado interno.
- Evitar accesos indebidos.
- Exponer únicamente lo necesario.

No todos los atributos deben ser públicos.  
No todas las operaciones deben ser accesibles desde cualquier parte del sistema.

Aplicado a la arquitectura:

- La `App` realiza solicitudes.
- El `Sistema` (interface) define los métodos disponibles.
- El `SistemaImpl` implementa la lógica interna.

La App no conoce cómo se ejecutan las operaciones; solo conoce qué puede solicitar.

Esto permite mantener el control sobre la lógica interna y reducir el acoplamiento entre componentes.

---

## 4. Herencia

La **herencia** permite que una clase derive de otra, reutilizando atributos y métodos comunes.

Se utiliza cuando varias clases comparten características similares.

En lugar de duplicar código:

- Se define una clase base con los elementos comunes.
- Las subclases heredan esos elementos.

Si la clase base no debe instanciarse directamente, se declara como `abstract`.

Esto implica que:

- No se pueden crear objetos de la clase base.
- Solo se pueden crear instancias de las subclases concretas.
- Todas comparten la estructura y comportamiento común definido en la clase base.

La herencia representa una relación del tipo:

> “Es un tipo de…”

Debe utilizarse únicamente cuando esa relación conceptual es válida.

---

## 5. Polimorfismo

El **polimorfismo** permite que un mismo nombre de método represente comportamientos distintos según el contexto.

### 🔹 Polimorfismo en métodos (Sobrecarga)

Consiste en definir varios métodos con el mismo nombre pero con diferentes listas de parámetros.

El compilador determina cuál método ejecutar según los argumentos proporcionados.

Este tipo de polimorfismo se resuelve en tiempo de compilación.

---

### 🔹 Polimorfismo en clases (Sobreescritura)

Ocurre cuando una subclase redefine un método heredado de la clase base, proporcionando una implementación específica.

Por ejemplo, todos los peleadores tienen un método `golpear()`, pero:

- El boxeador golpea a puño cerrado.
- El karateka a mano abierta.
- etc.

El nombre del método es el mismo, pero el comportamiento depende del tipo real del objeto en tiempo de ejecución.

Este es el polimorfismo más relevante en Programación Orientada a Objetos.

---

## 6. Interfaces

Una **interfaz** define un conjunto de métodos que una clase debe implementar, sin especificar cómo deben hacerlo.

Puede compararse con el panel de controles de un auto: los botones y palancas disponibles para el conductor.

El conductor:

- No necesita conocer el funcionamiento interno (tuercas, motores, electrónica).
- Solo utiliza los controles disponibles.

En programación:

- La interfaz define qué métodos están disponibles.
- La implementación concreta define cómo funcionan.

El mejor ejemplo es la implementación List, esta tiene muchas implementaciones pero las más utilizadas son ArrayList y LinkedList, es probable que tú hayas utilizado alguna de estas, ocupas sus métodos (métodos de la interfaz List), no sabes cómo funcionan internamente, pero sabes que cumplen una función, porque ello está definido en su contrato.

Tú mismo podrías crear tu clase Lista y que implemente la interfaz List, para definir sus mecanismos con tu propia lógica

---

### 🔹 El Contrato

Las interfaces deben incluir un mensaje claro que indique qué hacen los métodos definidos.  
Ese mensaje constituye el **CONTRATO**.

El contrato especifica:

- Qué hace el método.
- Qué parámetros recibe.
- Qué valor retorna.
- Qué excepciones puede lanzar.

Existe un estándar de documentación llamado **Javadoc**, que utiliza etiquetas como:

- `@param` : Qué parámetros recibe el método.
- `@throws` : Qué excepciones lanza el método.
- `@return` : Qué devuelve el método.
- `@author` : Quién es el autor de la interfaz.

El contrato puede visualizarse desde el cliente posicionando el mouse sobre la interfaz o sobre `interfaz.metodo`.

El cliente conoce qué hace el método, pero no cómo lo hace.

## 7. Principios SOLID

Los principios **SOLID** proporcionan lineamientos para diseñar software mantenible y escalable.

Su correcta aplicación permite:

- Evitar clases excesivamente grandes.
- Reducir dependencias innecesarias.
- Facilitar modificaciones futuras.
- Mejorar la legibilidad del código.

No es imprescindible memorizar cada principio, sino comprender su finalidad: organizar responsabilidades y minimizar el acoplamiento.

## 8. Arquitectura

### Arquitectura App / Sistema / SistemaImpl

#### 🔹 App

Es el cliente.

Por cliente se entiende una entidad que solicita servicios y recibe resultados, pero no implementa la lógica interna. Por eso se denomina "cliente" porque pide cosas concretas sin la necesidad de entender cómo se le dan.

Desde la App:

- Se realizan solicitudes (pedir promedios, mayores, menores, etc.).
- Se muestran resultados por pantalla.
- Se gestiona la interacción con el usuario (Scanner, prints).

La App no contiene lógica de implementación, porque el cliente no hace cosas, sólo las pide y las recibe.

---

#### 🔹 Sistema (interface)

Define qué puede solicitar el cliente.

Actúa como el panel de botones disponible para la App o el cliente.

Generalmente retorna `String` para que la App los imprima.

La App (el cliente) sólo puede ver la interfaz (los botones con sus etiquetas y contratos), no la implementación concreta de estos botones.

---

#### 🔹 SistemaImpl

Implementa la lógica real de cada método definido en `Sistema`.

Aquí se encuentran:

- Métodos privados.
- Algoritmos internos.
- Reglas de negocio.

Puede haber distintas implementaciones de `Sistema` según la lógica requerida.

Este diseño permite cambiar la implementación sin modificar la App.

---

Hay otros tipos de Arquitectura pero no se contemplan en el curso.

## 9. Patrones de Diseño

### 🔹 Factory


El patrón **Factory** delega la responsabilidad de creación de objetos a una clase especializada, en lugar de realizar la creación directamente en `Sistema`.

Factory se puede implementar como clase o como interfaz, dependiendo de las necesidades del problema. Sin embargo, es recomendable implementarlo como interfaz para definir correctamente su contrato. En ese caso, el Factory se define como un atributo de `SistemaImpl`, que le delega la tarea de crear las instancias.

Esto permite:
- Centralizar la lógica de creación.
- Reducir dependencias directas.
- Facilitar cambios futuros en la construcción de objetos.

---

### 🔹 Singleton


El patrón **Singleton** se utiliza cuando una clase debe tener una única instancia durante la ejecución del programa.

Singleton se implementa como clase.

Por ejemplo, el Factory crea instancias particulares, pero ¿necesitas un Factory para crear todas las instancias o cada instancia requiere su propio Factory? Así es, lo último no tiene sentido; una sola fábrica debe crear todas las instancias.

Para este tipo de situaciones se utiliza Singleton, que permite aislar una única instancia.

Generalmente se usa para `SistemaImpl`, ya que rara vez se requiere de más de una implementación del `Sistema`.

---

### 🔹 Visitor


Se utiliza **Visitor** cuando se requiere aplicar operaciones distintas según el tipo concreto de objeto dentro de una jerarquía de clases.

Visitor se implementa como interfaz, pues define los "botones" (métodos) del visitor, y sus implementaciones concretas se realizan como clases.

Por ejemplo, distinguir entre Auto, Camioneta y SUV para aplicar lógica distinta a cada uno.

Es útil cuando el problema exige **diferenciar** el comportamiento **según el tipo de instancia**.

---

### 🔹 Strategy


Se utiliza **Strategy** cuando se necesita **cambiar el comportamiento de una instancia** específica en tiempo de ejecución.

Strategy se implementa como interfaz, ya que define los "botones" (métodos) de la instancia. Esta instancia cambia su comportamiento según la estrategia implementada por una clase concreta.

Por ejemplo, asignar un modo de manejo distinto a un vehículo.

Permite que **un mismo objeto cambie su algoritmo o forma de operar** sin modificar su clase.

---

### 🔹 Diferencia entre Visitor y Strategy

- Si el comportamiento cambia para la **misma instancia**, se utiliza **Strategy**.
- Si la lógica cambia según el **tipo concreto de clase**, se utiliza **Visitor**.
- Si el problema requiere ambas condiciones, es posible combinar ambos patrones.

---

## Secuencia Conceptual Correcta

El orden conceptual adecuado para comprender POO es:

1. Abstraer el problema.
2. Modelar con clases.
3. Aplicar encapsulamiento.
4. Utilizar herencia cuando corresponda.
5. Implementar polimorfismo.
6. Definir y desacoplar mediante interfaces.
7. Organizar el diseño con principios SOLID.
8. Optimizar la estructura con patrones de diseño.
9. Implementar interfaces y estructura del código.

Este enfoque permite pasar de programar por ensayo y error a diseñar soluciones de manera estructurada y profesional.