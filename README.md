# Project Responsive Web Design using Bootstrap
# Date: 19.5.2025
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Amazon Fashion</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-white text-gray-800 font-sans">

  <!-- Header -->
  <header class="flex justify-between items-center px-6 py-4 shadow-md bg-yellow-400">
    <div class="text-2xl font-bold text-gray-800">amazon<span class="text-blue-700">.fashion</span></div>
    <nav class="space-x-6 hidden md:flex text-gray-800">
      <a href="#" class="hover:text-blue-700">Men</a>
      <a href="#" class="hover:text-blue-700">Women</a>
      <a href="#" class="hover:text-blue-700">Kids</a>
      <a href="#" class="hover:text-blue-700">Accessories</a>
    </nav>
    <div class="space-x-4">
      <button class="text-sm text-gray-700 hover:text-gray-900">Sign in</button>
      <button class="bg-blue-700 text-white px-4 py-2 rounded text-sm hover:bg-blue-800">Cart</button>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="text-center py-16 bg-gray-100">
    <h1 class="text-4xl font-bold mb-4">Shop the Latest Fashion</h1>
    <p class="text-lg text-gray-600 mb-6 max-w-2xl mx-auto">Discover trendy clothes for every season, all with the reliability and delivery speed of Amazon.</p>
    <div class="flex flex-wrap justify-center gap-4">
      <a href="#" class="bg-blue-700 text-white px-6 py-2 rounded hover:bg-blue-800">Men</a>
      <a href="#" class="bg-blue-700 text-white px-6 py-2 rounded hover:bg-blue-800">Women</a>
      <a href="#" class="bg-blue-700 text-white px-6 py-2 rounded hover:bg-blue-800">Kids</a>
    </div>
  </section>

  <!-- Product Grid -->
  <section class="px-6 py-12">
    <h2 class="text-2xl font-semibold mb-6 text-center">Featured Clothing</h2>
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">

      <!-- Men's Shirt -->
      <div class="border rounded-lg overflow-hidden shadow hover:shadow-lg transition">
        <img src="https://m.media-amazon.com/images/I/81k1k0URwqL._AC_UY1100_.jpg" alt="Men's Shirt" class="w-full h-60 object-cover"/>
        <div class="p-4">
          <h3 class="font-semibold text-lg">Classic Men's Shirt</h3>
          <p class="text-sm text-gray-600">₹600</p>
        </div>
      </div>

      <!-- Women's Dress -->
      <div class="border rounded-lg overflow-hidden shadow hover:shadow-lg transition">
        <img src="https://m.media-amazon.com/images/I/71UK4Zi120L._AC_UY1100_.jpg" alt="Women's Dress" class="w-full h-60 object-cover"/>
        <div class="p-4">
          <h3 class="font-semibold text-lg">Summer Floral Dress</h3>
          <p class="text-sm text-gray-600">₹500</p>
        </div>
      </div>

      <!-- Stylish Jacket -->
      <div class="border rounded-lg overflow-hidden shadow hover:shadow-lg transition">
        <img src="https://m.media-amazon.com/images/I/81ar0DzbS+L._AC_UY1100_.jpg" alt="Jacket" class="w-full h-60 object-cover"/>
        <div class="p-4">
          <h3 class="font-semibold text-lg">Urban Denim Jacket</h3>
          <p class="text-sm text-gray-600">₹2500</p>
        </div>
      </div>

      <!-- Kids Outfit -->
      <div class="border rounded-lg overflow-hidden shadow hover:shadow-lg transition">
        <img src="https://m.media-amazon.com/images/I/A1ShS6WfojL._AC_UY1100_.jpg" alt="Kids Clothing" class="w-full h-60 object-cover"/>
        <div class="p-4">
          <h3 class="font-semibold text-lg">Kids’ Cotton Set</h3>
          <p class="text-sm text-gray-600">₹300</p>
        </div>
      </div>

    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-200 text-center py-6 text-sm text-gray-600">
    © 2025 Amazon Fashion (Clone). 
  </footer>

</body>
</html>
```
# OUTPUT:

![image](https://github.com/user-attachments/assets/e44b5c65-a329-4058-8316-d82c72a4c582)

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
