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
  <!-- iframe where the form will submit, and the response will be loaded -->
  <iframe name="form_output" style="width: 0; height: 0; border: 0; visibility: hidden;" onload="formSubmitted()"></iframe>

  <!-- Form container for easier manipulation -->
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
  <!-- Message displayed after form submission -->
  <div id="thank-you-message" style="display: none; max-width: 600px; margin: 20px auto; font-size: 18px;">
    Thank you for your submission. We will get back to you soon!
  </div>
</div>

<script>
  function formSubmitted() {
    // Check if the iframe body is empty; if not, assume content was loaded
    var iframe = document.getElementsByName('form_output')[0];
    if (iframe.contentDocument && iframe.contentDocument.body.innerHTML.trim() !== "") {
      // Hide the form
      document.getElementById('form-container').style.display = 'none';
      // Show the thank-you message
      document.getElementById('thank-you-message').style.display = 'block';
    }
  }
</script>





## Our Technology

The **Nitrogen Company** excels in plasma reactor technology, revolutionizing agrochemical synthesis, ESAF, and CO2 splitting:

## Agrochemicals Synthesis

Efficiently produces high quality agrochemicals with high purity and reduced environmental impact.

## Fuels

Enables energy-efficient, scalable, and sustainable production of sustainable fuels. 

## CO2 Splitting

Converts carbon dioxide into valuable products using renewable energy. 
