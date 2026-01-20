# Explicación

Ecosistema Tecnológico del Proyecto
1. Entorno de Desarrollo y Control de Versiones
IDE / Editor de Texto: Se utilizó Visual Studio Code (VS Code) como entorno principal de desarrollo, aprovechando su terminal integrada y la extensión de lenguaje Haskell para la depuración y sintaxis.

Gestión de Repositorios: Se empleó GitHub para el alojamiento del código fuente, permitiendo un control de versiones y asegurando la integridad de los módulos main.hs y Processing.hs.

2. Lenguaje y Compilador
Lenguaje de Programación: Haskell, seleccionado por su paradigma funcional puro que facilita el procesamiento de datos sin efectos secundarios.

Compilador e Intérprete: GHC (Glasgow Haskell Compiler) y su entorno interactivo GHCi, utilizados para cargar módulos, realizar pruebas de funciones individuales y ejecutar el controlador principal.

3. Librerías y Módulos Estándar
Processing: Módulo personalizado creado para encapsular la lógica de las funciones computeStats y transformText.

System.IO: Para la administración de entrada y salida, permitiendo la lectura del archivo CSV y la escritura del reporte results.txt.

Text.Read (readMaybe): Implementada para la validación segura de datos numéricos, evitando errores de ejecución durante la conversión de tipos.

Data.Char y Data.List: Utilizadas para la manipulación de cadenas (mayúsculas/espacios) y el procesamiento de listas (ordenamiento y plegado).

4. Asistentes de Inteligencia Artificial
Gemini (IA de Google): Utilizado como socio de pensamiento y asistente de codificación para la optimización de algoritmos, explicación técnica de conceptos funcionales (como currying y folding), y para la estructuración de la documentación y material de presentación.
