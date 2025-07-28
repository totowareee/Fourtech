primero como ya se sabe tienen que poner los archivos en la carpeta htdocs, luego en el xaamp iniciar MySQL y Apache para que
funcione la pagina, previo a esto le daremos en la parte de MySQL en xaamp a Admin y crearemos una database llamada fourtech
e iremos a la pestaña MySQL e ingresaremos la siguiente consulta: 
CREATE TABLE postulaciones (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nombre VARCHAR(100),
    cedula VARCHAR(20),
    edad INT,
    email VARCHAR(100),
    telefono VARCHAR(20),
    situacion VARCHAR(50),
    cantidad_menores INT,
    prioridad TEXT,
    fecha DATETIME
);
