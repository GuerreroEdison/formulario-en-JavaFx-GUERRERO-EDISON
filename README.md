# formulario-en-JavaFx-GUERRERO-EDISON

![formulario en JavaFx](https://github.com/GuerreroEdison/formulario-en-JavaFx-GUERRERO-EDISON/assets/172848826/70504922-32e9-4363-9c59-71741ea7a439)

## Funcionamiento General

- *Inicialización de la Aplicación:*

- La aplicación comienza ejecutando el método main, que lanza la aplicación JavaFX.
    
- En el método start, se carga la estructura de la interfaz gráfica desde allControls.fxml utilizando FXMLLoader.

- *Interfaz Gráfica:*
  
- La interfaz gráfica se compone de una serie de controles (Button, CheckBox, TextField, etc.) organizados verticalmente en un VBox.
  
- Cada control tiene etiquetas descriptivas (Label) asociadas para identificar su propósito.
  
- Los controles están configurados con valores iniciales y propiedades específicas según el diseño definido en el archivo FXML.

- *Controlador y Eventos:*
  
- La clase AllControlsController actúa como el controlador para la interfaz gráfica, aunque actualmente no contiene lógica adicional.
  
- Se puede extender para manejar eventos de usuario (por ejemplo, clics de botón, cambios en checkbox, etc.) o para realizar operaciones lógicas más complejas según sea necesario.
  
