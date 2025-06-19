<!DOCTYPE html>

<html>
<head>
  <meta http-equiv="CONTENT-TYPE" content="text/html; charset=UTF-8">
   <link rel="stylesheet" href="agua2.css">
 
</head>
<body>
  <h1>
    La importancia del agua
  </h1>
  <img src="/storage/emulated/0/Pictures/1.jpg" alt="Descripción de la imagen" class="tarjeta">
  <h2> Importancia: 
    <p>• Vital para los seres vivos: Todos los organismos necesitan agua para sobrevivir.
    <p>• Uso humano: Se usa para beber, cocinar, lavar, limpiar y cultivar alimentos.
      <p>•Regulación del clima: Ayuda a mantener la temperatura del planeta.
        <p>• Higiene y salud: Es indispensable para la limpieza y para prevenir enfermedades.
        <p>• Ecosistemas: Ríos, lagos y océanos son hábitats de muchas especies.</h2>
  <h2> ¿Por qué la debemos cuidar? 
    <p>El agua dulce es limitada solo un pequeño porcentaje del agua del planeta es apta para el consumo humano, muchas fuentes de agua están contaminadas por basura, químicos o desechos industriales. Afecta los patrones de lluvia y puede causar sequías o inundaciones no todas las personas en el mundo tienen acceso a agua potable.</h2>
  

</body>
</html>
body{background-color: lightblue;
 }
@keyframes rotar{ 
  from{ transform: rotate(0deg);}
  to { transform: rotate(200deg);}
}
  .tarjeta {
    width: 180px;
  height: 180px;
  background-color: deepskyblue;
  border-top-right-radius: 20%;
  border-bottom-left-radius:20%;
  border-top-left-radius: 20%;
  border-bottom-right-radius:20%;
  margin:70px;
  border:dotted deepskyblue 10px; }

.tarjeta:hover{
  animation:rotar 10s linear infinite;
}

h1 {
  text-align: center;
  font-family: BellMT;
}
h2 {
  text-align: center;
}
