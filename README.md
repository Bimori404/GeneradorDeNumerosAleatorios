# Generador De Numeros Aleatorios
Esta aplicación Java proporciona una interfaz gráfica de usuario (GUI) para generar números aleatorios utilizando varios métodos. Le permite ingresar parámetros y ver los números aleatorios generados en formato tabular. La aplicación utiliza Java Swing para sus componentes de interfaz de usuario.

### Introducción

La clase `Pantalla_General` es la clase principal de esta aplicación, que crea la ventana GUI y maneja las interacciones del usuario. Proporciona funcionalidad para generar números aleatorios utilizando diferentes algoritmos y muestra los resultados en tablas dentro de pestañas.

### Primeros Pasos

Para ejecutar esta aplicación Java, debe tener Java instalado en su sistema. Siga estos pasos para comenzar:

1. Clone o descargue el proyecto desde el repositorio.
2. Abra el proyecto en su entorno de desarrollo Java favorito (por ejemplo, Eclipse, IntelliJ IDEA o NetBeans).
3. Compile y ejecute el proyecto.

### Características

1. **Interfaz con Pestañas:** La aplicación tiene una interfaz con pestañas con múltiples pestañas, cada una representando un método diferente de generación de números aleatorios.
2. **Generación de Números Aleatorios:** Puede generar números aleatorios utilizando varios métodos, incluyendo multiplicación, módulo y más.
3. **Entrada de Parámetros:** La aplicación le permite ingresar los parámetros necesarios para cada método de generación de números aleatorios.
4. **Visualización:** Los números aleatorios generados se muestran en tablas dentro de las pestañas para facilitar su visualización.

### Uso

1. **Método de Multiplicación:**
   - Ingrese un valor de semilla (un número de cuatro dígitos) y el número de iteraciones.
   - Haga clic en el botón "Generar" para generar números aleatorios utilizando el método de multiplicación.

2. **Método de Multiplicación y Módulo:**
   - Ingrese dos valores de semilla (cada uno un número de cuatro dígitos), el número de iteraciones y una constante adicional.
   - Haga clic en el botón "Generar" para generar números aleatorios utilizando el método de multiplicación y módulo.

3. **Métodos de Algoritmo Personalizado:**
   - Ingrese los parámetros requeridos para cada algoritmo personalizado.
   - Haga clic en el botón "Generar" para generar números aleatorios utilizando el algoritmo especificado.

4. **Agregar y Restablecer:** Puede agregar valores de semilla adicionales para algoritmos personalizados y restablecer las tablas.

### Métodos

La clase `Pantalla_General` contiene varios métodos para generar números aleatorios y administrar la GUI. Aquí hay algunos métodos clave:

- `digitos(int numero)`: Comprueba si un número dado tiene cuatro dígitos.
- `borrar(DefaultTableModel modelo)`: Borra y configura un modelo de tabla con columnas específicas.
- `medio(int numero)`: Extrae los cuatro dígitos medios de un número.
- Manejadores de eventos para clics en botones (por ejemplo, `jButton1ActionPerformed`): Manejan la entrada del usuario, realizan cálculos y actualizan las tablas en consecuencia.
