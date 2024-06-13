![Imagen de WhatsApp 2024-06-12 a las 22 56 21_803b6926](https://github.com/MORANHOLGUIN/Dise-a-el-siguiente-formulario-en-JavaFx/assets/168208095/fc5c517d-18b9-4388-b590-b999d4c24bb4)

Clase Principal (Main) y Herencia de Application:

La clase Main extiende Application, lo que la convierte en una aplicación JavaFX.
El método start se sobrescribe para definir el comportamiento de la aplicación cuando se inicia.

Stage y Scene:

Se crea un Stage (primaryStage) que representa la ventana principal de la aplicación.
Se crea una Scene que contiene todos los elementos de la GUI y se añade al Stage.

Layouts:

GridPane: Se utiliza para organizar los controles en una cuadrícula con filas y columnas. Se configuran espacios (Hgap y Vgap) y márgenes (Padding).
HBox: Se usa para organizar los elementos en una fila horizontal. Aquí se usa para ProgressIndicator, ProgressBar y Slider.
VBox: Se usa para organizar los elementos en una columna vertical. Aquí se usa para contener todo el GridPane y las HBox.

Controles de JavaFX:

Label: Para mostrar texto estático.
Button: Para crear un botón interactivo.
CheckBox: Para crear una casilla de verificación.
Hyperlink: Para crear un enlace de hipertexto.
ToggleButton: Para crear un botón conmutador.
RadioButton: Para crear un botón de opción.
TextField: Para introducir una sola línea de texto.
PasswordField: Para introducir texto enmascarado, como contraseñas.
TextArea: Para introducir y mostrar texto en múltiples líneas con ajuste de texto.
ProgressIndicator: Para mostrar un indicador de progreso circular.
ProgressBar: Para mostrar una barra de progreso lineal.
Slider: Para permitir la selección de un valor de un rango.

Configuraciones Adicionales:

Espaciado y Alineación: Se configura el espaciado entre los elementos y su alineación dentro de los HBox.
Prompt Text: Se establece el texto de ayuda para el
