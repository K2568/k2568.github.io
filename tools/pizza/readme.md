## Pizza calculator
### Pizza sizes:
<input id="input_sizes" type="text" inputmode="decimal" placeholder="10 11 12">

<p id="output_size"><strong>Equivalent diameter:</strong> 0.00</p>
<p id="error"></p>

<script>
const input = document.getElementById("input_sizes");
const result = document.getElementById("output_size");
const error = document.getElementById("error");

input.addEventListener("input", () => {
  const text = input.value.trim();

  const values = text.split(/\s+/).map(Number);

  error.textContent = "";

  const equivalent = Math.sqrt(
    values.reduce((total, value) => total + value ** 2, 0)
  );

  result.innerHTML =
    `<strong>Equivalent diameter:</strong> ${equivalent.toFixed(2)}`;
});
</script>