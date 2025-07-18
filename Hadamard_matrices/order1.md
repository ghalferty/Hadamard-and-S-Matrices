## Order 1 Hadamard Matrix

<div id="text-container"></div>

<script>
  fetch('order1.txt')
    .then(response => response.text())
    .then(data => {
      document.getElementById('text-container').innerText = data;
    });
</script>
