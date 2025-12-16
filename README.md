<!doctype html>
<html lang="es">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="css/HojaDeVida.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.13.1/font/bootstrap-icons.min.css">
    <style>
      *{
  margin: 0;
  padding: 0;
}
body{
    background-color: #E6E6FA;
    margin: 5%;
}
.texto1{
    text-align: center;
    display: inline-block;
    vertical-align: middle;
    margin-left: 28%;
}
.container{
  background-color: #D8BFD8;
  box-shadow: 0px 0px 10px #000000;
  width: 80%;
  margin: 0 auto;
  position: relative;
}
.conteiner_e{
  display: flex;
  width: 100%;
}
.contactos{
  display: inline-block;
  vertical-align: top;
  background-color: #9966CC;
  padding: 5%;
  width: 28%;
}
.sobre_mi{
  display: inline-block;
  padding: 5%;
  margin-top: 0%;
  text-align: justify;
  background-color: #800080;
}

    </style>
  </head>
  <body>
    <main class="container">
      <div class="row">
        <div class="col-3 d-flex justify-content-center" background-color: #E6E6FA;>
          <img src="imagenes/foto mia.jpeg" width="200">
          <div class="foto">
            <h1 class="texto1"> SARA XIOMARA CHACÓN BARRERA</h1>
          </div>

        </div>

      </div>
      <div class="conteiner_e"> 
        <div class="contactos">
          <h2><i class="bi bi-geo-fill"></i>CONTACTO</h2>
          <hr>
          <br>
          <P><i class="bi bi-telephone-fill"></i>(+57)3213757715 <br><br><i class="bi bi-envelope-at-fill"></i>saritaxiomara10@gmail.com <br><br><i class="bi bi-geo-alt-fill"></i>BOGOTA COLOMBIA</P>
          <br>
          <br>
          <h2><i class="bi bi-translate"></i>IDIOMAS</h2>
          <hr>
          <br>
          <P>ESPAÑOL: lengua materna <br><br>INGLES: principiante A1</P>
          <br>
          <br>
          <h2><i class="bi bi-pen-fill"></i>HABILIDADES</h2>
          <hr>
          <br>
          <P>Trabajo en equipo <br><br> Creatica</P>
        </div>
        <div class="sobre_mi">
          <h2><i class="bi bi-person-badge-fill"></i>SOBRE MÍ</h2>
          <hr>
          <br>
          <P>Soy estudiante de Desarrollo de Medios Gráficos Visuales e el SENA, con formación en Técnico en Asistencia Administrativa obtenida durante mi etapa de bachillerato. Mi enfoque está orientado a la creatividad y el diseño visual, combinando mis conocimientos en administración para gestionar proyectos de forma eficiente.</P>
          <br>
          <br>
         <h2><i class="bi bi-backpack3-fill"></i>FORMACION ACADEMICA</h2>
         <hr>
         <br>
         <h3>SENA</h3>
         <P>Tecnólogo en Desarrollo de medios gráficos visuales( en curso)</P>
         <br>
         <h3>BACHILLERATO</h3>
         <p>2023</p>
         <br><br>
         <h2><i class="bi bi-briefcase-fill"></i>EXPERIENCIA LABORAL</h2>
         <hr>
         <br>
         <h3>ASISTENCIA ADMINISTRATICA EN CORFEDES S.A.S</h3>
         <br>
         <P>-Coordinación y organización de las llamadas realizadas a los estudiantes, gestionando la programación y seguimiento de las mismas.<br>-Apoyo en la organización administrativa y de comunicaciones internas de la empresa.</P>
        </div>
      </div>
    </main>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js" integrity="sha384-FKyoEForCGlyvwx9Hj09JcYn3nv7wiPVlz7YYwJrWVcXK/BmnVDxM+D2scQbITxI" crossorigin="anonymous"></script>
  </body>
</html>
