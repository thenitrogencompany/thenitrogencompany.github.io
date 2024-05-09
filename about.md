---
layout: page
title: About
permalink: /about/
---

# About

Our origins at Stanford University have equipped us with cutting-edge expertise in plasma physics, laying the foundation for our core technology: large-scale plasma reactors.

Our mission is straightforward: to revolutionize chemical manufacturing by making it cleaner and more efficient. Our plasma reactors utilize advanced techniques to enhance process efficiency and reduce the environmental footprint of chemical production.

## Contact
<div style="text-align: center;">
  <!-- iframe for form submission, hidden from view -->
  <iframe name="form_output" style="width: 0; height: 0; border: 0; visibility: hidden;"></iframe>

  <!-- Form container -->
  <div id="form-container">
    <form action="https://formspree.io/f/xwkgzpey" method="POST" target="form_output" style="display: inline-block; text-align: left; width: 100%; max-width: 600px;">
      <label for="email">Your email:</label>
      <br>
      <input type="email" id="email" name="email" required style="width: 100%;">
      <br>
      <label for="message">Your message:</label>
      <br>
      <textarea id="message" name="message" required style="width: 100%; height: 150px;"></textarea>
      <br>
      <button type="submit" style="width: 100%;">Send</button>
    </form>
  </div>
  <!-- Thank-you message container -->
  <div id="thank-you-message" style="display: none; max-width: 600px; margin: 20px auto; font-size: 18px;">
    Thank you for your submission. We will get back to you soon!
  </div>
</div>

<script>
document.getElementById('form-container').addEventListener('submit', function(event) {
  event.preventDefault(); // Stop the form from submitting normally
  var form = event.target;

  // Optionally, add any validation or checks before submitting the form

  // Form submission via the iframe
  form.submit();

  // Hide the form and show the thank-you message
  document.getElementById('form-container').style.display = 'none';
  document.getElementById('thank-you-message').style.display = 'block';
});
</script>






## Our Technology

The **Nitrogen Company** excels in plasma reactor technology, revolutionizing agrochemical synthesis, ESAF, and CO2 splitting:

## Agrochemicals Synthesis

Efficiently produces high quality agrochemicals with high purity and reduced environmental impact.

## Fuels

Enables energy-efficient, scalable, and sustainable production of sustainable fuels. 

## CO2 Splitting

Converts carbon dioxide into valuable products using renewable energy. 
