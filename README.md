```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ZORO TRADER - Stock Market & Analysis Educator</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Google Fonts: Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&display=swap" rel="stylesheet">
  <!-- FontAwesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            darkBg: '#090d16',
            cardBg: '#0e1526',
            brandBlue: '#0088cc',
            brandBlueHover: '#0077b5',
            glowYellow: '#ffcc00',
            subtitleBlue: '#4b83fb',
          }
        }
      }
    }
  </script>

  <style>
    /* Dark grid pattern background */
    body {
      background-color: #080c14;
      background-image: 
        linear-gradient(to right, rgba(255, 255, 255, 0.03) 1px, transparent 1px),
        linear-gradient(to bottom, rgba(255, 255, 255, 0.03) 1px, transparent 1px);
      background-size: 32px 32px;
      color: #ffffff;
      font-family: 'Inter', sans-serif;
    }

    /* Avatar Glow Effect */
    .avatar-glow {
      box-shadow: 0 0 25px 5px rgba(255, 204, 0, 0.45);
    }

    /* Button Glow Effect */
    .btn-glow {
      box-shadow: 0 0 20px 2px rgba(0, 136, 204, 0.5);
    }

    .btn-glow:hover {
      box-shadow: 0 0 30px 5px rgba(0, 136, 204, 0.7);
    }
  </style>
</head>
<body class="min-h-screen flex flex-col items-center justify-center p-4 sm:p-6 md:p-8 select-none">

  <!-- Main Container -->
  <main class="w-full max-w-xl mx-auto flex flex-col items-center text-center py-6 px-2">

    <!-- Top Badge Pill -->
    <div class="mb-8 px-4 py-1.5 rounded-full border border-gray-700/60 bg-[#111827]/80 backdrop-blur-md shadow-inner text-[10px] sm:text-xs font-semibold tracking-wider text-gray-300 uppercase">
      RESEARCH & MARKET EDUCATION • TRADING COMMUNITY
    </div>

    <!-- Profile Picture with Glow -->
    <div class="relative mb-3">
      <div class="w-28 h-28 sm:w-32 sm:h-32 rounded-full p-[3px] bg-gradient-to-r from-yellow-400 via-amber-300 to-yellow-500 avatar-glow">
        <img 
          src="https://i.ibb.co/v6MgRZH4/IMG-20261026-180311-312.jpg" 
          alt="ZORO TRADER Logo" 
          class="w-full h-full object-cover rounded-full bg-black"
          onerror="this.onerror=null; this.src='https://placehold.co/150x150/1e293b/ffffff?text=ZORO+TRADER'"
        />
      </div>
    </div>

    <!-- Yellow Badge under profile -->
    <div class="mb-8">
      <span class="inline-flex items-center px-3 py-1 rounded-full text-xs font-bold bg-[#ffc800] text-black shadow-lg uppercase tracking-wide">
        ✓ MARKET EDUCATOR
      </span>
    </div>

    <!-- Subtitle Category -->
    <p class="text-xs sm:text-sm font-bold text-subtitleBlue tracking-widest uppercase mb-2">
      STOCK MARKET & ANALYSIS EDUCATOR
    </p>

    <!-- Main Heading -->
    <h1 class="text-2xl sm:text-3xl md:text-4xl font-extrabold text-white tracking-tight leading-snug mb-2">
      Learn Stock Market & Analysis with
    </h1>

    <!-- Highlighted Title -->
    <h2 class="text-3xl sm:text-4xl md:text-5xl font-black text-[#ffcc00] tracking-wide mb-6 drop-shadow-md">
      ZORO TRADER
    </h2>

    <!-- Description -->
    <p class="text-gray-400 text-xs sm:text-sm md:text-base font-normal max-w-md mb-8">
      Daily Market Analysis • Nifty & Bank Nifty • Educational Insights
    </p>

    <!-- Main CTA Telegram Button -->
    <a 
      href="https://t.me/+gM70YcQjR7xkODI1" 
      target="_blank" 
      rel="noopener noreferrer"
      class="w-full max-w-md py-4 px-6 rounded-2xl bg-gradient-to-r from-[#0088cc] via-[#0099e6] to-[#0088cc] text-white font-bold text-base sm:text-lg flex items-center justify-center gap-3 transition-all duration-300 transform hover:-translate-y-0.5 active:translate-y-0 btn-glow mb-3 cursor-pointer"
    >
      <i class="fa-brands fa-telegram text-2xl sm:text-3xl"></i>
      <span>Join Telegram Community — Free</span>
    </a>

    <!-- Sub-text below CTA -->
    <div class="flex items-center justify-center gap-1.5 text-xs text-gray-400 mb-8 font-medium">
      <span>🔒</span>
      <span>Instant Free Access • 100% Educational Content</span>
    </div>

    <!-- Social Proof Pill -->
    <div class="w-full max-w-md bg-[#0d1424]/90 border border-gray-800 rounded-full py-2.5 px-4 flex items-center justify-center gap-3 mb-8 shadow-md">
      <!-- Avatar Stack -->
      <div class="flex -space-x-2 overflow-hidden">
        <div class="inline-block h-6 w-6 rounded-full ring-2 ring-[#0d1424] bg-blue-600 flex items-center justify-center text-[9px] font-bold text-white">ZT</div>
        <div class="inline-block h-6 w-6 rounded-full ring-2 ring-[#0d1424] bg-amber-600 flex items-center justify-center text-[9px] font-bold text-white">RK</div>
        <div class="inline-block h-6 w-6 rounded-full ring-2 ring-[#0d1424] bg-emerald-600 flex items-center justify-center text-[9px] font-bold text-white">AK</div>
        <div class="inline-block h-6 w-6 rounded-full ring-2 ring-[#0d1424] bg-purple-600 flex items-center justify-center text-[9px] font-bold text-white">VS</div>
      </div>
      <span class="text-xs sm:text-sm font-semibold text-gray-200">
        Join our growing <span class="text-white font-bold">50,000+</span> trading community
      </span>
    </div>

    <!-- Feature Cards Row -->
    <div class="w-full max-w-md grid grid-cols-1 sm:grid-cols-2 gap-3 mb-3">
      <!-- Feature 1 -->
      <div class="bg-[#0b101d] border border-gray-800/80 rounded-xl py-3 px-4 flex items-center justify-center gap-2 text-xs sm:text-sm font-semibold text-gray-200 shadow-sm">
        <span class="text-yellow-400">⚡</span>
        <span>Daily Market Updates</span>
      </div>
      <!-- Feature 2 -->
      <div class="bg-[#0b101d] border border-gray-800/80 rounded-xl py-3 px-4 flex items-center justify-center gap-2 text-xs sm:text-sm font-semibold text-gray-200 shadow-sm">
        <span class="text-red-400">🎯</span>
        <span>Nifty & BankNifty Setup</span>
      </div>
    </div>

    <!-- Wide Made For India Pill -->
    <div class="w-full max-w-md bg-[#0b101d] border border-gray-800/80 rounded-xl py-3 px-4 flex items-center justify-center gap-2 text-xs sm:text-sm font-semibold text-gray-200 mb-12 shadow-sm">
      <span>🇮🇳</span>
      <span>Made for Indian Traders & Investors</span>
    </div>

    <!-- Divider Line -->
    <div class="w-full max-w-md border-t border-gray-800/50 mb-8"></div>

    <!-- Disclaimer Section -->
    <footer class="w-full max-w-md text-center text-[10px] sm:text-xs text-gray-500 leading-relaxed space-y-4">
      <p>
        <strong class="font-semibold text-gray-400">Disclaimer:</strong> Investment in securities market are subject to market risks. Read all the related documents carefully before investing. Content shared on this platform is strictly for educational, informational, and research purposes only. We do not provide any buy/sell tips, direct stock recommendations, or guaranteed returns.
      </p>
      <p class="font-medium tracking-wide text-gray-400">
        © 2026 ZORO TRADER • ALL RIGHTS RESERVED
      </p>
    </footer>

  </main>

</body>
</html>
```
