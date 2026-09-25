Escenario A.

<head>
  <script src="script1.js"></script>
  <script src="script2.js"></script>
  <script src="script3.js"></script>
</head>
<body>
  <h1 id="titulo">Hola, Mundo</h1>
</body>

- En el escenario A se ejecutan primero los 3 scripts y la página aparece después,
a los 650 ms. Mientras tanto, la pantalla está en blanco. Entonces, los scripts fallan porque el <h1> no existe, de ahí nacen los 3 errores y  no cambia el título.