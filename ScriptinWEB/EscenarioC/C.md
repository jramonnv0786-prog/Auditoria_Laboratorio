Escenario C

<head>
  <script async src="script1.js"></script>
  <script async src="script2.js"></script>
  <script async src="script3.js"></script>
</head>

- Async no bloquea la página, que se pinta pronto.
- No garantiza el orden de ejecución ni que el DOM esté listo.
- En local funciona porque el HTML es pequeño, con una conexión lenta un script podría llegar antes que el H1 y fallar. 