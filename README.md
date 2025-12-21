let jugador = {
  x: 100,
  y: 100,
  ancho: 50,
  alto: 50,
  velocidadX: 0,
  velocidadY: 0,
  vida: 100
};

let enemigo = {
  x: 600,
  y: 100,
  ancho: 50,
  alto: 50,
  velocidadX: 0,
  velocidadY: 0,
  vida: 100
};

let balas = [];

function dibujar() {
  ctx.clearRect(0, 0, canvas.width, canvas.height);
  ctx.fillStyle = "# FolderMover
Un programa muy básico de Python. Se encarga de crear dos carpetas de nombres distintos, y luego mover otras dos carpetas adentro de estas. Esto generará dos carpetas que adentro cada una tiene otra carpeta del mismo nombre. Esto sirve para generar los instaladores de mis juegos de Unity.
