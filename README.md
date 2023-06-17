<h1 id="typing-effect"></h1>

<script>
  const text = "Hello! I'm Ever Frank (NesoDev) 👋";
  let index = 0;

  function typeEffect() {
    const typingElement = document.getElementById("typing-effect");
    if (index < text.length) {
      typingElement.innerHTML += text.charAt(index);
      index++;
      setTimeout(typeEffect, 100);
    }
  }

  typeEffect();
</script>

<p align="center">
  <img src="https://i.pinimg.com/originals/17/28/5f/17285fc448d970cdd53b1b3ba11d7e66.gif" alt="GIF" width="300">
</p>
