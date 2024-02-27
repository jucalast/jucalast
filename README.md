### Olá! Eu sou [seu nome] 👋

<span id="typing-animation"></span>

<script>
// Array de palavras
const words = ["Eu", "sou", "o", "jucalast"];
let i = 0;
let timer;

// Função para adicionar uma palavra à animação
function typeWriter() {
  if (i < words.length) {
    document.getElementById("typing-animation").innerHTML += words[i] + " ";
    i++;
    timer = setTimeout(typeWriter, 500); // Velocidade da escrita (em milissegundos)
  }
}

// Inicia a animação
typeWriter();
</script>


