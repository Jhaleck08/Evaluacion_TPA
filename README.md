# Evaluacion_TPA
1.-  Para crear y subir un proyecto a un repositorio se tienen que utilizar estos comandos:
- git remote -v
- git remote add origin “La URL de tu repositorio”
- git add .
- git init
- git status
- git add .
- git commit -m “Mensaje para el commit”
- git push origin “Nombre de la rama”

2.- Para poder utilizar el código de un proyecto en un repositorio remoto se tienen que utilizar los siguientes comandos:
- git clone “URL del repositorio del que vas a utilizar”

3.- Cuando se ejecuta un código en Python en la cuál se crea un objeto de clase abstracta, se producirá un error, ya que se utiliza el método “abc” y para solucionarlo se debe crear una clase que herede de la clase abstracta e implemente los métodos abstractos definidos en ella.

4.- Cuando un método tiene el decorador @abstractmethod significa que se está marcando un método como abstracto dentro de una clase abstracta y su propósito es definir una interfaz común y que garantice que las clases derivadas implementen ciertos métodos necesarios para su funcionamiento.

5.- 3 eventos que pueden ejecutarse en una interfaz gráfica son:
- Evento de entrada de teclado
- Evento de cierre de ventana
- Evento de cambio de tamaño de ventana

6.- Para definir un ciclo de evento se podría decir que es un mecanismo que permite que una aplicación de GUI pueda interactuar con el usuario y responda a las interacciones y eventos generados, también es un concepto muy fundamental al desarrollar una GUI.

7.- Sí, es posible ignorar un objeto de la clase QDialog y poder seguir utilizando la ventana principal, además que si utilizas el método “show()” en vez de “exec()” esto permitirá que el diálogo sea visible mientras se sigue interactuando con la ventana principal.

8.- QLineEdit, QComboBox,QPushButton, QLabel y QDialog.

9.- Algunas alternativas de componentes si se quiere ingresar datos numéricos podrían ser:
- QLineEdit (QIntValidator, QDoubleValidator)
- QDoubleSpinBox
- QSpinBox

10.- Para poder utilizar una interfaz creada en QtDesigner en un código fuente en Python con PyQt6 se tiene que guardar el archivo de la interfaz en un formato compatible con PyQt6 como un archivo .ui, luego hay que utilizar la herramienta pyuic6 para poder compilar el archivo .ui en un archivo de código Python, para poder hacer eso se tiene que utilizar el siguiente comando: pyuic6 nombre_archivo.ui -o nombre_archivo.py, para seguir se tiene que importar el archivo generado en el código fuente de Python, luego se crea una instancia de la clase principal de la interfaz y utilizarla en la aplicación, para eso se puede importar el archivo con algún nombre que quieras colocarle en este caso se podría dar un ejemplo del comando from nombre_archivo.py import “Ejemplo”, y para finalizar se crea un bucle de eventos con “app.exec()”.
