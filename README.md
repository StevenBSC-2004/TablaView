# TablaView
![image](https://github.com/user-attachments/assets/dcaef2a5-65e4-44a7-9fa7-8b44ccacd4e6)
![image](https://github.com/user-attachments/assets/f228d5d5-ee83-41c2-969e-b788a8bb6b36)
Constructor InterfazGrafica:

Inicia la conexión a la base de datos y crea la interfaz gráfica.

Método connectDB:

Establece la conexión a la base de datos PostgreSQL con JDBC.

Método createGUI:

Configura la ventana principal, añade un combo box para seleccionar el año y una tabla para mostrar datos.

Método populateComboBox:

Llena el combo box con los años disponibles en la base de datos.

Método updateTableInBackground:

Ejecuta una consulta SQL en segundo plano para obtener y mostrar los datos de los constructores del año seleccionado.

Método main:

Inicia la aplicación y asegura que la creación de la interfaz gráfica se realice en el hilo de eventos de Swing.
