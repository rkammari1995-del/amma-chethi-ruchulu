# amma-chethi-ruchulu
Official website catalog and ordering page for traditional sweets and spice powders.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Aromas & Sweets | Traditional Podis, Sweets & Snacks</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
</head>
<body class="bg-amber-50 text-stone-800 antialiased">

  <!-- Notification Bar -->
  <div class="bg-amber-800 text-amber-100 text-xs sm:text-sm text-center py-2 px-4">
    Free Shipping on all orders above ₹499 | Made fresh to order with pure ingredients
  </div>

  <!-- Navbar -->
  <header class="sticky top-0 bg-white/95 backdrop-blur shadow-sm z-40 border-b border-amber-100">
    <div class="max-w-6xl mx-auto px-4 h-16 flex items-center justify-between">
      <a href="#" class="text-2xl font-bold tracking-tight text-amber-900 flex items-center gap-2">
        <i class="fa-solid fa-mortar-pestle text-amber-700"></i>
        SwarnaFlavors
      </a>
      <nav class="hidden md:flex gap-8 font-medium text-stone-600 text-sm">
        <a href="#podis" class="hover:text-amber-800 transition">Authentic Podis</a>
        <a href="#sweets" class="hover:text-amber-800 transition">Ghee Sweets</a>
        <a href="#snacks" class="hover:text-amber-800 transition">Crispy Snacks</a>
        <a href="#combos" class="hover:text-amber-800 transition">Gift Boxes</a>
      </nav>
      <div class="flex items-center gap-4">
        <button id="cartBtn" class="relative p-2 text-stone-700 hover:text-amber-800">
          <i class="fa-solid fa-bag-shopping text-xl"></i>
          <span id="cartCount" class="absolute -top-1 -right-1 bg-amber-700 text-white text-xs rounded-full w-5 h-5 flex items-center justify-center font-bold">0</span>
        </button>
      </div>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="relative bg-gradient-to-r from-amber-900 to-amber-800 text-white py-16 px-4">
    <div class="max-w-6xl mx-auto flex flex-col md:flex-row items-center justify-between gap-8">
      <div class="md:w-1/2 space-y-4">
        <span class="inline-block bg-amber-700/60 text-amber-200 px-3 py-1 rounded-full text-xs uppercase tracking-wider font-semibold">100% Homemade Taste</span>
        <h1 class="text-4xl sm:text-5xl font-extrabold leading-tight">Freshly Ground Podis & Pure Desi Ghee Sweets</h1>
        <p class="text-amber-100 text-base">Traditional recipes handcrafted in small batches. No artificial colors, preservatives, or palm oil.</p>
        <div class="pt-2 flex flex-wrap gap-3">
          <a href="#products" class="bg-amber-500 hover:bg-amber-600 text-stone-900 font-semibold px-6 py-3 rounded-lg shadow-md transition">Explore Catalog</a>
          <a href="#combos" class="bg-transparent border border-amber-300 text-white hover:bg-white/10 px-6 py-3 rounded-lg transition">View Gift Boxes</a>
        </div>
      </div>
      <div class="md:w-1/2 flex justify-center">
        <div class="w-full max-w-sm rounded-2xl overflow-hidden shadow-2xl bg-amber-950/40 p-4 border border-amber-700/50 text-center">
          <div class="h-64 bg-amber-100/10 rounded-xl flex items-center justify-center text-amber-200">
            <i class="fa-solid fa-bowl-food text-6xl"></i>
          </div>
          <p class="mt-3 text-xs text-amber-200 font-medium">Small-batch roasted spices & hand-rolled confections</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Trust Badges -->
  <section class="border-b border-amber-100 bg-white py-6">
    <div class="max-w-6xl mx-auto px-4 grid grid-cols-2 md:grid-cols-4 gap-6 text-center">
      <div class="flex flex-col items-center">
        <i class="fa-solid fa-leaf text-2xl text-emerald-600 mb-2"></i>
        <h4 class="font-bold text-sm">Natural Ingredients</h4>
        <p class="text-xs text-stone-500">Zero artificial flavors</p>
      </div>
      <div class="flex flex-col items-center">
        <i class="fa-solid fa-fire-burner text-2xl text-amber-600 mb-2"></i>
        <h4 class="font-bold text-sm">Made to Order</h4>
        <p class="text-xs text-stone-500">Shipped within 24-48 hrs</p>
      </div>
      <div class="flex flex-col items-center">
        <i class="fa-solid fa-shield-halved text-2xl text-amber-700 mb-2"></i>
        <h4 class="font-bold text-sm">FSSAI Certified</h4>
        <p class="text-xs text-stone-500">Clean & hygienic facility</p>
      </div>
      <div class="flex flex-col items-center">
        <i class="fa-solid fa-box text-2xl text-stone-700 mb-2"></i>
        <h4 class="font-bold text-sm">Aroma-Lock Packing</h4>
        <p class="text-xs text-stone-500">3-layer moisture-proof pouches</p>
      </div>
    </div>
  </section>

  <!-- Products Section -->
  <main id="products" class="max-w-6xl mx-auto px-4 py-12">
    <div class="flex flex-col sm:flex-row sm:items-end justify-between mb-8 gap-4">
      <div>
        <h2 class="text-2xl font-bold text-stone-900">Featured Specialties</h2>
        <p class="text-stone-600 text-sm">Select items to build your box</p>
      </div>
      <!-- Category Chips -->
      <div class="flex gap-2 overflow-x-auto pb-1 text-sm font-medium">
        <button class="px-4 py-1.5 rounded-full bg-amber-800 text-white">All</button>
        <button class="px-4 py-1.5 rounded-full bg-white border border-stone-200 text-stone-700 hover:border-amber-700">Podis</button>
        <button class="px-4 py-1.5 rounded-full bg-white border border-stone-200 text-stone-700 hover:border-amber-700">Sweets</button>
        <button class="px-4 py-1.5 rounded-full bg-white border border-stone-200 text-stone-700 hover:border-amber-700">Savory</button>
      </div>
    </div>

    <!-- Product Grid -->
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">

      <!-- Item 1: Podi -->
      <div class="bg-white rounded-xl border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
        <div class="h-44 bg-amber-100/50 flex items-center justify-center text-amber-700">
          <i class="fa-solid fa-jar text-5xl"></i>
        </div>
        <div class="p-4 flex-1 flex flex-col justify-between">
          <div>
            <span class="text-xs font-semibold text-amber-700 bg-amber-50 px-2 py-0.5 rounded">Podi</span>
            <h3 class="font-bold text-base text-stone-900 mt-1">Gunpowder (Karam Podi)</h3>
            <p class="text-xs text-stone-500 mt-1">Roasted lentils, red chillies, and garlic cloves. Best with hot rice & ghee.</p>
          </div>
          <div class="mt-4 pt-3 border-t border-stone-100 flex items-center justify-between">
            <span class="text-stone-900 font-bold">₹160 <span class="text-xs font-normal text-stone-500">/ 250g</span></span>
            <button onclick="addToCart('Gunpowder (Karam Podi)', 160)" class="bg-amber-800 hover:bg-amber-900 text-white text-xs px-3 py-2 rounded font-medium transition">Add to Cart</button>
          </div>
        </div>
      </div>

      <!-- Item 2: Sweet -->
      <div class="bg-white rounded-xl border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
        <div class="h-44 bg-amber-100/50 flex items-center justify-center text-amber-700">
          <i class="fa-solid fa-cookie-bite text-5xl"></i>
        </div>
        <div class="p-4 flex-1 flex flex-col justify-between">
          <div>
            <span class="text-xs font-semibold text-amber-700 bg-amber-50 px-2 py-0.5 rounded">Sweet</span>
            <h3 class="font-bold text-base text-stone-900 mt-1">Pure Ghee Besan Laddu</h3>
            <p class="text-xs text-stone-500 mt-1">Slow-roasted gram flour, green cardamom, and golden dry fruits.</p>
          </div>
          <div class="mt-4 pt-3 border-t border-stone-100 flex items-center justify-between">
            <span class="text-stone-900 font-bold">₹280 <span class="text-xs font-normal text-stone-500">/ 400g</span></span>
            <button onclick="addToCart('Pure Ghee Besan Laddu', 280)" class="bg-amber-800 hover:bg-amber-900 text-white text-xs px-3 py-2 rounded font-medium transition">Add to Cart</button>
          </div>
        </div>
      </div>

      <!-- Item 3: Snack -->
      <div class="bg-white rounded-xl border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
        <div class="h-44 bg-amber-100/50 flex items-center justify-center text-amber-700">
          <i class="fa-solid fa-wheat-awn text-5xl"></i>
        </div>
        <div class="p-4 flex-1 flex flex-col justify-between">
          <div>
            <span class="text-xs font-semibold text-amber-700 bg-amber-50 px-2 py-0.5 rounded">Savory</span>
            <h3 class="font-bold text-base text-stone-900 mt-1">Butter Murukku / Chakli</h3>
            <p class="text-xs text-stone-500 mt-1">Melt-in-mouth spiral crunch seasoned with cumin and white butter.</p>
          </div>
          <div class="mt-4 pt-3 border-t border-stone-100 flex items-center justify-between">
            <span class="text-stone-900 font-bold">₹140 <span class="text-xs font-normal text-stone-500">/ 250g</span></span>
            <button onclick="addToCart('Butter Murukku', 140)" class="bg-amber-800 hover:bg-amber-900 text-white text-xs px-3 py-2 rounded font-medium transition">Add to Cart</button>
          </div>
        </div>
      </div>

      <!-- Item 4: Podi -->
      <div class="bg-white rounded-xl border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
        <div class="h-44 bg-amber-100/50 flex items-center justify-center text-amber-700">
          <i class="fa-solid fa-mortar-pestle text-5xl"></i>
        </div>
        <div class="p-4 flex-1 flex flex-col justify-between">
          <div>
            <span class="text-xs font-semibold text-amber-700 bg-amber-50 px-2 py-0.5 rounded">Podi</span>
            <h3 class="font-bold text-base text-stone-900 mt-1">Curry Leaf (Karivepaku) Podi</h3>
            <p class="text-xs text-stone-500 mt-1">Sun-dried country curry leaves, roasted black gram, and hing.</p>
          </div>
          <div class="mt-4 pt-3 border-t border-stone-100 flex items-center justify-between">
            <span class="text-stone-900 font-bold">₹175 <span class="text-xs font-normal text-stone-500">/ 250g</span></span>
            <button onclick="addToCart('Curry Leaf Podi', 175)" class="bg-amber-800 hover:bg-amber-900 text-white text-xs px-3 py-2 rounded font-medium transition">Add to Cart</button>
          </div>
        </div>
      </div>

    </div>
  </main>

  <!-- Sliding Cart Drawer -->
  <div id="cartModal" class="fixed inset-0 bg-stone-900/60 z-50 hidden flex justify-end">
    <div class="bg-white w-full max-w-md h-full flex flex-col p-6 shadow-2xl">
      <div class="flex items-center justify-between pb-4 border-b border-stone-200">
        <h3 class="font-bold text-lg text-stone-900">Your Basket</h3>
        <button id="closeCart" class="text-stone-400 hover:text-stone-600 text-xl font-bold">&times;</button>
      </div>

      <div id="cartItems" class="flex-1 overflow-y-auto py-4 space-y-3">
        <p class="text-stone-400 text-sm text-center py-8">Your cart is empty.</p>
      </div>

      <div class="pt-4 border-t border-stone-200 space-y-3">
        <div class="flex justify-between font-bold text-stone-800 text-base">
          <span>Subtotal:</span>
          <span id="cartTotal">₹0</span>
        </div>
        <button class="w-full bg-amber-800 hover:bg-amber-900 text-white py-3 rounded-lg font-semibold transition">
          Proceed to Checkout
        </button>
      </div>
    </div>
  </div>

  <script>
    let cart = [];
    const cartBtn = document.getElementById('cartBtn');
    const closeCart = document.getElementById('closeCart');
    const cartModal = document.getElementById('cartModal');
    const cartItems = document.getElementById('cartItems');
    const cartTotal = document.getElementById('cartTotal');
    const cartCount = document.getElementById('cartCount');

    cartBtn.onclick = () => cartModal.classList.remove('hidden');
    closeCart.onclick = () => cartModal.classList.add('hidden');

    function addToCart(title, price) {
      cart.push({ title, price });
      updateCart();
      cartModal.classList.remove('hidden');
    }

    function updateCart() {
      cartCount.innerText = cart.length;
      if (cart.length === 0) {
        cartItems.innerHTML = '<p class="text-stone-400 text-sm text-center py-8">Your cart is empty.</p>';
        cartTotal.innerText = '₹0';
        return;
      }

      cartItems.innerHTML = '';
      let sum = 0;
      cart.forEach((item, index) => {
        sum += item.price;
        const div = document.createElement('div');
        div.className = 'flex justify-between items-center text-sm p-2 bg-amber-50/50 rounded border border-amber-100';
        div.innerHTML = `
          <div>
            <p class="font-medium text-stone-800">${item.title}</p>
            <p class="text-stone-500 text-xs">₹${item.price}</p>
          </div>
          <button onclick="removeItem(${index})" class="text-red-500 hover:text-red-700 text-xs">Remove</button>
        `;
        cartItems.appendChild(div);
      });
      cartTotal.innerText = '₹' + sum;
    }

    function removeItem(index) {
      cart.splice(index, 1);
      updateCart();
    }
  </script>
</body>
</html>
