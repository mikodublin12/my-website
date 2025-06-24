/![eggp](https://github.com/user-attachments/assets/26b8ce50-5d9d-4aed-93d1-6fb2ca5ddc63)

<header>
  <img src="eggp.png" alt="Eggplantastik Logo" style="width: 100%; max-height: 350px; object-fit: none;" alt="Logo">

  <p>Talong-talo ang iba sa lasa!</p> 
  <link rel="icon" type="image/x-icon" href="favicon.png">
<head>
  <meta charset="UTF-8">
  <title>Eggplantastik</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #500b4c;
      color: white;
      padding: 10px 0;
    }

    header img {
      max-height: 100px;
      height: auto;
      width: auto;
    }
  </style>
</body>
  </header>
<style>
 body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: #f9f9f9;
      color: #333;
    }

    header {
      background-color: #1f0729;
      color: white;
      padding: 5px 0;
      text-align: center;
    }

  header img {
      max-height: 100px;
    }

    nav {
      text-align: center;
      margin-top:20px;
    }

    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #1f0729;
      font-weight: bold;
    }

    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 20px 0;
      margin-top: 40px;
    }

    .btn {
      display: inline-block;
      padding: 10px 20px;
      background-color: #6d0865;
      color: white;
      border: none;
      text-decoration: none;
      margin-top: 10px;
      cursor: pointer;
      border-radius: 5px;
    }

  #menuPopup {
      display: none;
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      background: white;
      color: black;
      padding: 20px 30px;
      border: 2px solid #6d0865;
      border-radius: 12px;
      box-shadow: 0 0 15px rgba(0, 0, 0, 0.3);
      z-index: 1000;
      max-width: 600px;
      width: 90%;
    
    }

    #menuPopup ul {
      list-style-type: circle;
      padding-left: 20px;
    }

    #menuPopup button {
      margin-top: 15px;
      background-color: #6d0865;
      color: white;
      border: none;
      padding: 8px 16px;
      cursor: pointer;
      border-radius: 5px;
    }
    
     
    
  </style>

  <nav>
    <a href="#about">About</a>
    <a href="#services">Products</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Us</h2>
    <p>
      Eggplantastik operates in the Food industry, offering plant-based sushi rolls inspired by Filipino flavors. The venture is a micro-business serving nutritious and eco-friendly meals using repurposed ingredients such as eggplant peels, ensuring both health impact and waste reduction.
    </p>
  </section>

  <section id="services">
    <h2>Our Products</h2>
    <a href="#" class="btn" onclick="showMenu()">Open Offers</a>
  
  </section>

  <div id="menuPopup">
    <h3>Our Sushi Menu</h3>
 
<div class="menu-item">
      <h3>Sushinoy Classic</h3>
      <p>Eggplant peel wrap, plain rice, cheese, cucumber, tomato, and ham.</p>
      <button class="order-button">Order</button>
    </div>

    <div class="menu-item">
      <h3>Tinapa Rice</h3>
      <p>Featuring smoky flaked tinapa (smoked fish), this bold and savory option brings a taste of traditional Filipino breakfast to your sushi roll.</p>
      <button class="order-button">Order</button>
    </div>

    <div class="menu-item">
      <h3>Fried Rice with Torta (Tortang Talong)</h3>
      <p>A hearty fusion of fried rice and eggplant omelet, this variant adds a distinct, flavorful twist for those looking for something more filling.</p>
      <button class="order-button">Order</button>
    </div>
      

    <button onclick="closeMenu()">Close</button>

  </div>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>You can reach us at:</p>
    <p>Email: Eggplantastik@gmail.com</p>
    <p>Phone: 0912-345-6789</p>
    <p>Facebook: Eggplantastikent</p>
  </section>

  <footer>
    <p>&copy; 2025 Eggplantastik. All rights reserved.</p>
  </footer>

  <script>
    function showMenu() {
      document.getElementById('menuPopup').style.display = 'block';
    }

    function closeMenu() {
      document.getElementById('menuPopup').style.display = 'none';
    }
   </script>
</body>
</html>
