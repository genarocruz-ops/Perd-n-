<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Para ti 💖</title>
<style>
body {
  background: linear-gradient(135deg, #ff9a9e, #fad0c4);
  font-family: Arial;
  text-align: center;
  color: white;
  padding: 40px;
}
button {
  padding: 10px 20px;
  border-radius: 10px;
  border: none;
  margin: 10px;
  font-size: 16px;
}
</style>
</head>

<body>

<h1>Hola mi hermosa 🥺💖</h1>
<p>Este mensaje es para ti...</p>

<button onclick="mensaje()">Presiona aquí</button>

<script>
function mensaje() {
  document.body.innerHTML = `
    <h2>Perdóname 😔</h2>
    <p>Me equivoqué y me duele haberte lastimado</p>
    <h3>Te amo muchísimo ❤️</h3>
  `;
}
</script>

</body>
</html>
