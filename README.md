Probabilidad, Estadística y Procesos Cuánticos

Repositorio de actividades para la materia "Probabilidad, Estadística y Procesos Estocásticos" dictada por el profesor Andrés.

Este espacio tiene como objetivo explorar la convergencia entre los conceptos estadísticos abordados en clase y la Computación Cuántica. Aquí encontrará una serie de notebooks diseñados para validar la teoría probabilística mediante simulaciones cuánticas.
Nuestra Metodología: "Andamiaje Cuántico"

Para que el estudio no sea simplemente una lista de fórmulas, aplicamos una metodología de andamiaje (scaffolding) en cada módulo. La estructura de cada actividad sigue estos tres pasos lógicos:

    Fundamentos Clásicos: Partimos de la teoría vista en la cátedra (ej. Variables Aleatorias de Bernoulli, Correlación, Procesos de Markov).

    El Salto Cuántico: Conectamos ese concepto con un fenómeno físico-cuántico (ej. Qubits, Entrelazamiento, Decoherencia). Demostramos por qué el concepto estadístico es la herramienta necesaria para describir esa realidad cuántica.

    Actividad Práctica (Laboratorio): Cerramos con una consigna de programación en Google Colab. Los alumnos deben escribir código (usando Qiskit y numpy) para simular el fenómeno y validar los resultados teóricos mediante estadística frecuencial.

Roadmap del Curso

    Módulo 1: Azar y Medición

        Conceptos: Variables Aleatorias y Distribuciones.

        Conexión Cuántica: La Regla de Born y la medición de qubits.

        Tarea: Simulación de Monte Carlo para validar la frecuencia de resultados de un qubit.

    Módulo 2: Detectives de Entrelazamiento

        Conceptos: Covarianza y Correlación.

        Conexión Cuántica: Estados de Bell y correlaciones no locales.

        Tarea: Cálculo de covarianza en sistemas entrelazados.

    Módulo 3: La Batalla contra el Ruido

        Conceptos: Procesos Estocásticos y Estacionariedad.

        Conexión Cuántica: Decoherencia y Canales de Depolarización.

        Tarea: Simulación de un proceso de Markov que modela la pérdida de pureza de un sistema cuántico.

    Módulo 4: Inferencia Estadística

        Conceptos: Estimación y Máxima Verosimilitud (MLE).

        Conexión Cuántica: Tomografía de Estados Cuánticos.

        Tarea: Reconstrucción de un estado secreto a partir de datos ruidosos.

Instrucciones de Uso

Todos los notebooks están preparados para ser ejecutados directamente en Google Colab.

    Entra en cualquier carpeta de módulo.

    Abre el notebook .ipynb correspondiente.

    Haz clic en el botón "Open in Colab".

    Ejecuta las celdas de código.

Nota: Para correr los ejemplos localmente, asegúrate de tener instaladas las librerías necesarias ejecutando pip install qiskit qiskit-aer numpy matplotlib.
Contribución

Este repositorio es un espacio vivo. Si eres alumno de la materia, te invito a clonar este proyecto, experimentar con los parámetros de los circuitos y proponer nuevas conexiones entre los temas de la cátedra y el mundo cuántico.
