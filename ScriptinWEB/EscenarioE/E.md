Escenario E

<head>
  <script type="module" src="script1.js"></script>
  <script type="module" src="script2.js"></script>
  <script type="module" src="script3.js"></script>
</head>

El escenario E funciona igual que defer, pero además cada módulo tiene su propio
ámbito de variables y funciona en modo estricto. Necesita un servidor local.
Esta opción es la recomendada para el JavaScript moderno.