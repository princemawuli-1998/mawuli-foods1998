<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Food Order Menu</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      background-color: #f8f8f8;
      color: #333;
    }
    h2 {
      text-align: center;
      color: #c0392b;
    }
    h3 {
      color: #2c3e50;
      margin-top: 20px;
    }
    form {
      background: #fff;
      padding: 20px;
      border-radius: 8px;
      max-width: 500px;
      margin: auto;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    label {
      display: block;
      margin: 5px 0;
    }
    input[type="text"], input[type="tel"] {
      width: 100%;
      padding: 8px;
      margin: 5px 0 15px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      display: block;
      width: 100%;
      padding: 10px;
      background: #27ae60;
      color: white;
      font-size: 16px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background: #219150;
    }
  </style>
</head>
<body>
  <h2>🍴 Food Order Menu</h2>
  <form action="https://formspree.io/f/xgvnebdg" method="POST">
    
    <h3>Food</h3>
    <label><input type="checkbox" name="Food" value="Jollof"> Jollof</label>
    <label><input type="checkbox" name="Food" value="Waakye"> Waakye</label>
    <label><input type="checkbox" name="Food" value="Banku"> Banku</label>
    <label><input type="checkbox" name="Food" value="Yam"> Yam</label>

    <h3>Stew</h3>
    <label><input type="checkbox" name="Stew" value="Kotomire Stew"> Kotomire Stew</label>
    <label><input type="checkbox" name="Stew" value="Chicken Stew"> Chicken Stew</label>
    <label><input type="checkbox" name="Stew" value="Beans Stew"> Beans Stew</label>
    <label><input type="checkbox" name="Stew" value="Beef Stew"> Beef Stew</label>
    <label><input type="checkbox" name="Stew" value="Pepper Sauce"> Pepper Sauce</label>
    <label><input type="checkbox" name="Stew" value="Egg Stew"> Egg Stew</label>

    <h3>Soup</h3>
    <label><input type="checkbox" name="Soup" value="Groundnut Soup"> Groundnut Soup</label>
    <label><input type="checkbox" name="Soup" value="Okro Stew"> Okro Stew</label>
    <label><input type="checkbox" name="Soup" value="Light Soup"> Light Soup</label>

    <h3>Drinks</h3>
    <label><input type="checkbox" name="Drinks" value="Ice Kenkey"> Ice Kenkey</label>
    <label><input type="checkbox" name="Drinks" value="Sobolo"> Sobolo</label>

    <h3>Pastries</h3>
    <label><input type="checkbox" name="Pastries" value="Bofrot"> Bofrot</label>
    <label><input type="checkbox" name="Pastries" value="Meat Pie"> Meat Pie</label>
    <label><input type="checkbox" name="Pastries" value="Bread"> Bread</label>

    <h3>Your Details</h3>
    <label>Name:</label>
    <input type="text" name="Customer Name" required>
    
    <label>Phone:</label>
    <input type="tel" name="Customer Phone" required>

    <button type="submit">📩 Place Order</button>
  </form>
</body>
</html>
