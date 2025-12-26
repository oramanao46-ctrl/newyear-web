<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<title>Happy New Year 2026 🎆</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
html, body {
  margin: 0;
  padding: 0;
  background: black;
  overflow: hidden;
  height: 100%;
  font-family: Arial, sans-serif;
}
h1 {
  position: absolute;
  top: 40%;
  width: 100%;
  text-align: center;
  color: gold;
  font-size: 3rem;
  animation: zoom 3s ease-in-out;
}
@keyframes zoom {
  from { opacity: 0; transform: scale(0.5); }
  to { opacity: 1; transform: scale(1); }
}
</style>
</head>
<body>

<h1>🎉 Happy New Year 2026 🎉</h1>

<script src="https://cdn.jsdelivr.net/npm/fireworks-js@2.10.2/dist/fireworks.js"></script>
<script>
const fireworks = new Fireworks(document.body, {
  rocketsPoint: 50,
  hue: { min: 0, max: 360 },
  delay: { min: 15, max: 30 },
  speed: 2,
  acceleration: 1.05,
  friction: 0.95,
  gravity: 1.5,
  particles: 80,
  trace: 3,
  explosion: 5
})
fireworks.start()
</script>

</body>
</html>
