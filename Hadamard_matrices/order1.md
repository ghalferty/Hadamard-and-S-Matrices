## Order 1 Hadamard Matrix

<pre id="order1-container"></pre>

<script>
  fetch('Hadamard_matrices/order1.txt')
    .then(response => response.text())
    .then(data => {
      document.getElementById('order1-container').textContent = data;
    })
    .catch(error => {
      document.getElementById('order1-container').textContent = 'Error loading matrix.';
      console.error(error);
    });
</script>
