# Programación Avanzada - UCN

Recopilación de pruebas y material de apoyo para **Programación Orientada a Objetos (POO)** y **Técnicas y Metodologías de Programación Avanzada** de la Universidad Católica del Norte. Incluye enunciados de pruebas (PRUEBA), evaluaciones de recuperación (RECA) y soluciones implementadas en Java.

---


## Pruebas Resueltas

Se han implementado soluciones completas para las siguientes pruebas:

- **Programación Orientada a Objetos**
  - ✅ [Prueba 1 - 2025 S1](Prog.%20Orientada%20a%20Objetos/PRUEBA%201/2025%20S1/Solución/) **Completa** - Ruteo con salida y diagrama de objetos + Programa con multiplicidad 1...N

- **Técnicas y Metodologías de Programación Avanzada**
  - ✅ [Prueba 1 - 2025 S1](Técnicas%20y%20Metodologías%20de%20Prog.%20Avanz/PRUEBA%201/2025%20S1/Solución/) **Completa**

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
- **README.md**: Descripción de la prueba y guía de ejecución
- **Solución/**: Carpeta con la implementación
  - **src/**: Código fuente Java
  - **README.md**: Especificaciones y cómo cargar en Eclipse
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