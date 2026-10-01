<!DOCTYPE html>
<html lang="en" class="dark">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, viewport-fit=cover">
  <title>STG Miner Web3 Ecosystem</title>

  <!-- Telegram WebApp SDK -->
  <script src="https://telegram.org/js/telegram-web-app.js"></script>
  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Lucide Icons -->
  <script src="https://unpkg.com/lucide@latest"></script>
  <!-- Canvas Confetti -->
  <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.9.3/dist/confetti.browser.min.js"></script>

  <!-- Google Fonts: Plus Jakarta Sans & JetBrains Mono -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;700;800&family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          fontFamily: {
            sans: ['"Plus Jakarta Sans"', 'sans-serif'],
            mono: ['"JetBrains Mono"', 'monospace'],
          },
          colors: {
            brand: '#72e6a2',
          }
        }
      }
    }
  </script>

  <style>
    body {
      background-color: #05080e;
      color: #f1f5f9;
      font-family: 'Plus Jakarta Sans', sans-serif;
      user-select: none;
      -webkit-user-select: none;
    }
    @keyframes spin-slow {
      to { transform: rotate(360deg); }
    }
    @keyframes reverse-spin-slow {
      to { transform: rotate(-360deg); }
    }
    .animate-spin-slow { animation: spin-slow 20s linear infinite; }
    .animate-reverse-spin-slow { animation: reverse-spin-slow 24s linear infinite; }
    .floater-num {
      position: fixed;
      pointer-events: none;
      font-family: 'JetBrains Mono', monospace;
      font-weight: 900;
      color: #6ee7b7;
      text-shadow: 0 2px 4px rgba(0,0,0,0.8);
      animation: floatUp 0.8s ease-out forwards;
      z-index: 9999;
    }
    @keyframes floatUp {
      0% { opacity: 1; transform: translate(-50%, 0); }
      100% { opacity: 0; transform: translate(-50%, -45px); }
    }
  </style>
</head>
<body class="bg-[#05080e] min-h-screen flex flex-col items-center justify-start pb-20">

  <!-- Mobile Frame Container (Preview Equivalent) -->
  <div class="w-full max-w-md bg-[#070b12] text-slate-100 min-h-screen flex flex-col relative shadow-2xl border-x border-slate-900/60">

    <!-- Top Header -->
    <header class="px-4 py-3 bg-[#070b12]/90 backdrop-blur-md border-b border-slate-800/80 sticky top-0 z-40 flex items-center justify-between">
      <div class="flex items-center gap-2.5">
        <div class="w-9 h-9 rounded-xl bg-gradient-to-tr from-emerald-500/20 to-teal-500/10 border border-emerald-500/30 flex items-center justify-center font-mono font-black text-sm text-emerald-400 shadow-md shadow-emerald-500/10">
          STG
        </div>
        <div>
          <h1 class="text-sm font-extrabold text-white tracking-wide flex items-center gap-1.5">
            <span>STG MINER</span>
            <span class="text-[9px] bg-emerald-500/10 text-emerald-400 border border-emerald-500/20 px-1.5 py-0.2 rounded font-mono">ERA 1</span>
          </h1>
          <div class="text-[10px] text-slate-400 font-mono flex items-center gap-1.5">
            <span class="text-emerald-400">10.0 GH/s</span>
            <span>·</span>
            <span>@stgairdrop</span>
          </div>
        </div>
      </div>

      <div class="flex items-center gap-1.5">
        <button onclick="openHistoryModal()" class="h-8 px-2.5 rounded-lg bg-slate-900 border border-slate-800 text-slate-300 hover:text-white text-xs font-mono flex items-center gap-1.5 transition-colors cursor-pointer">
          <i data-lucide="history" class="w-3.5 h-3.5 text-emerald-400"></i>
          <span>History</span>
        </button>
        <button id="soundBtn" onclick="toggleAudio()" class="w-8 h-8 rounded-lg bg-slate-900 border border-slate-800 text-slate-300 hover:text-white flex items-center justify-center transition-colors cursor-pointer">
          <i data-lucide="volume-2" class="w-4 h-4 text-slate-400"></i>
        </button>
        <button onclick="switchTab('profile')" class="w-8 h-8 rounded-lg bg-slate-900 border border-slate-800 text-slate-300 hover:text-white flex items-center justify-center transition-colors cursor-pointer">
          <i data-lucide="user" class="w-4 h-4 text-emerald-400"></i>
        </button>
      </div>
    </header>

    <!-- Main Content Area -->
    <main class="flex-1 px-4 pt-3 overflow-y-auto">

      <!-- ================= 1. MINE TAB ================= -->
      <section id="tab-mine-page" class="space-y-4 pb-4">
        
        <!-- 1. HARVEST TOP CONSOLE -->
        <div class="text-center rounded-3xl bg-gradient-to-b from-[#0b1424] via-[#080f1a] to-[#060a12] border border-slate-800/90 p-5 shadow-2xl relative overflow-hidden">
          <div id="ambientGlow" class="absolute inset-0 bg-gradient-to-b from-emerald-500/15 via-teal-500/5 to-transparent opacity-80 pointer-events-none transition-opacity"></div>

          <!-- Holding Balance Header -->
          <div class="relative z-10 mb-2">
            <div class="text-[11px] font-mono tracking-widest text-slate-400 uppercase flex items-center justify-center gap-1.5">
              <span class="w-1.5 h-1.5 rounded-full bg-emerald-400 animate-pulse"></span>
              <span>HOLDING BALANCE</span>
            </div>
            <div class="mt-1 flex items-baseline justify-center gap-1.5">
              <span id="holdingBalance" class="font-mono text-3xl sm:text-4xl font-extrabold tracking-tight text-white drop-shadow-md">0.000000</span>
              <span class="text-sm font-mono font-bold text-emerald-400">STG</span>
            </div>
            <div class="text-xs font-mono text-slate-400 mt-0.5">
              ≈ $<span id="holdingUsd">0.000</span> USD
            </div>
          </div>

          <!-- Tactile 3D Harvest Coin Circle -->
          <div class="relative my-6 flex items-center justify-center" id="coinContainer">
            <div id="ringOuter" class="absolute w-52 h-52 rounded-full border border-dashed border-emerald-400/50 animate-spin-slow"></div>
            <div class="absolute w-60 h-60 rounded-full border border-slate-800/50 animate-reverse-spin-slow"></div>
            <div id="radialGlow" class="absolute w-44 h-44 rounded-full blur-2xl bg-emerald-400/25"></div>

            <!-- SVG Progress Ring -->
            <svg id="svgProgressRing" class="absolute w-48 h-48 -rotate-90 pointer-events-none hidden" viewBox="0 0 100 100">
              <circle cx="50" cy="50" r="46" fill="none" stroke="currentColor" stroke-width="2" class="text-slate-800/80"/>
              <circle id="svgCircleBar" cx="50" cy="50" r="46" fill="none" stroke="currentColor" stroke-width="3.5" stroke-dasharray="289" stroke-dashoffset="289" stroke-linecap="round" class="text-emerald-400 drop-shadow-[0_0_8px_rgba(52,211,153,0.8)]"/>
            </svg>

            <!-- 3D Coin Button -->
            <div onclick="handleCoinTap(event)" class="relative z-10 w-40 h-40 rounded-full cursor-pointer select-none transition-transform active:scale-95 flex items-center justify-center shadow-2xl shadow-emerald-500/20 ring-2 ring-emerald-500/40" style="background: radial-gradient(circle at 35% 30%, #ffffff 0%, #cbd5e1 25%, #475569 60%, #0f172a 100%);">
              <div class="w-34 h-34 rounded-full border-2 border-slate-400/40 flex flex-col items-center justify-center bg-gradient-to-b from-slate-200/25 via-slate-700/30 to-slate-950/70 shadow-inner">
                <span class="font-mono text-3xl font-black tracking-widest text-[#070b12] drop-shadow-sm">STG</span>
                <span class="text-[10px] font-mono font-bold tracking-wider text-slate-800 uppercase mt-0.5">MINER</span>
                <span class="text-[9px] font-mono text-emerald-800 font-bold mt-0.5">10 STG/H</span>
              </div>
            </div>
          </div>

          <!-- Overclock Energy Bar -->
          <div class="mb-4 max-w-xs mx-auto">
            <div class="flex items-center justify-between text-[11px] font-mono text-slate-400 mb-1.5">
              <span class="flex items-center gap-1">
                <i data-lucide="flame" class="w-3.5 h-3.5 text-slate-500"></i>
                <span>Overclock Energy (Tap Coin)</span>
              </span>
              <span id="energyText" class="font-bold text-slate-300">15%</span>
            </div>
            <div class="h-2 w-full bg-slate-800 rounded-full overflow-hidden p-[1px]">
              <div id="energyBar" class="h-full rounded-full bg-gradient-to-r from-emerald-500 to-teal-400 transition-all duration-300" style="width: 15%"></div>
            </div>
            <button id="turboBtn" onclick="activateTurbo()" class="hidden mt-2.5 w-full py-2 rounded-xl bg-gradient-to-r from-amber-500 to-orange-500 text-slate-950 font-mono font-bold text-xs tracking-wider uppercase flex items-center justify-center gap-1.5 shadow-lg shadow-amber-500/20 active:scale-98 cursor-pointer">
              <i data-lucide="zap" class="w-3.5 h-3.5 fill-slate-950"></i>
              <span>Ignite Turbo Overclock (+50% Speed)</span>
            </button>
            <div id="turboActiveBanner" class="hidden mt-2 py-1.5 px-3 rounded-lg bg-amber-950/60 border border-amber-600/40 text-amber-300 font-mono text-xs flex items-center justify-center gap-1.5 animate-pulse">
              <i data-lucide="flame" class="w-3.5 h-3.5 text-amber-400"></i>
              <span id="turboCountdown">OVERCLOCK ACTIVE: 30s left</span>
            </div>
          </div>

          <!-- Status Message -->
          <div id="statusMsg" class="text-xs font-mono mb-4 text-slate-300 flex items-center justify-center gap-2">
            Node Standby — Tap Start Mining below
          </div>

          <!-- Main Action Button -->
          <div id="actionArea">
            <button id="primaryMineBtn" onclick="toggleMining()" class="w-full py-4 rounded-2xl bg-white hover:bg-slate-100 text-[#070b12] font-mono font-extrabold text-sm tracking-wider uppercase flex items-center justify-center gap-2 shadow-xl shadow-white/10 active:scale-98 transition-transform cursor-pointer">
              <i data-lucide="zap" class="w-4 h-4 fill-[#070b12]"></i>
              <span>START MINING (10 STG / H)</span>
            </button>
          </div>
        </div>

        <!-- 2. GENESIS 1% BLOCK INDICATOR -->
        <div class="rounded-2xl bg-gradient-to-br from-[#0c1422] to-[#070c16] border border-slate-800 p-4 shadow-md">
          <div class="flex items-center justify-between">
            <div class="flex items-center gap-2">
              <span class="w-2.5 h-2.5 rounded-full bg-emerald-400 animate-ping"></span>
              <div>
                <h3 class="text-xs font-bold text-white uppercase font-mono tracking-wider">Genesis Block Processing</h3>
                <p class="text-[11px] text-slate-400 font-mono">Brand New Ecosystem Launch · Genesis Era 1</p>
              </div>
            </div>
            <span class="text-xs font-mono font-extrabold text-emerald-400 bg-emerald-950/80 border border-emerald-700/60 px-2.5 py-0.5 rounded-full">
              1% PROCESSED
            </span>
          </div>
          <div class="mt-3">
            <div class="h-2 w-full bg-slate-900 rounded-full overflow-hidden p-[1px] border border-slate-800">
              <div class="h-full bg-emerald-400 rounded-full" style="width: 1%"></div>
            </div>
            <div class="flex items-center justify-between text-[10px] font-mono text-slate-500 mt-1.5">
              <span>Stage 1: Launch Phase (10 STG/H)</span>
              <span>Next Halving: 10,000 Miners</span>
            </div>
          </div>
        </div>

        <!-- 3. MINING SPEED & ESTIMATED VALUE -->
        <div class="grid grid-cols-2 gap-2.5 font-mono">
          <div class="bg-[#0b121e] rounded-2xl p-3.5 border border-slate-800">
            <span class="text-[10px] text-slate-400 uppercase tracking-wider block">MINING SPEED</span>
            <div class="flex items-baseline gap-1 mt-0.5">
              <span id="ratePerHourText" class="text-xl font-bold text-emerald-400">10.00</span>
              <span class="text-xs text-slate-400">STG/H</span>
            </div>
            <span class="text-[10px] text-slate-500 mt-0.5 block">10.0 GH/s Hashrate</span>
          </div>

          <div class="bg-[#0b121e] rounded-2xl p-3.5 border border-slate-800">
            <span class="text-[10px] text-slate-400 uppercase tracking-wider block">EST. VALUE / HOUR</span>
            <div class="flex items-baseline gap-1 mt-0.5">
              <span class="text-xl font-bold text-white">$0.125</span>
              <span class="text-xs text-slate-400">USD</span>
            </div>
            <span class="text-[10px] text-slate-500 mt-0.5 block">$0.0125 / STG</span>
          </div>
        </div>

        <!-- 4. ASSETS SUMMARY -->
        <div class="grid grid-cols-2 gap-2.5 font-mono">
          <div class="bg-[#0b121e] border border-slate-800 rounded-2xl p-3.5">
            <span class="text-[10px] text-slate-400 uppercase tracking-wider block">HOLDING BALANCE</span>
            <strong id="holdingSub" class="text-sm font-bold text-white mt-1 block truncate">0.000000 STG</strong>
            <span class="text-[10px] text-slate-500">Tier 1 Genesis</span>
          </div>

          <div class="bg-[#0b121e] border border-slate-800 rounded-2xl p-3.5">
            <span class="text-[10px] text-slate-400 uppercase tracking-wider block">TOTAL MINED</span>
            <strong id="totalMinedSub" class="text-sm font-bold text-emerald-400 mt-1 block truncate">0.000000 STG</strong>
            <span class="text-[10px] text-slate-500">Genesis Node</span>
          </div>
        </div>

        <!-- 5. BALANCE HISTORY BUTTON -->
        <button onclick="openHistoryModal()" class="w-full py-3 px-4 rounded-2xl bg-slate-900/90 hover:bg-slate-800/90 border border-slate-800 text-xs font-mono font-medium text-slate-300 hover:text-white flex items-center justify-between transition-all active:scale-98 cursor-pointer shadow-md">
          <div class="flex items-center gap-2">
            <i data-lucide="history" class="w-3.5 h-3.5 text-emerald-400"></i>
            <span>Balance Credit History (ব্যালেন্স হিস্ট্রি)</span>
          </div>
          <span id="historyRecordBadge" class="text-[10px] text-emerald-400 font-bold font-mono">1 Records →</span>
        </button>
      </section>

      <!-- ================= 2. RIGS TAB ================= -->
      <section id="tab-rigs-page" class="space-y-3 pb-4 hidden">
        <div>
          <h2 class="text-sm font-bold text-white tracking-wide">Hardware Upgrades</h2>
          <p class="text-xs text-slate-400 mt-0.5 font-mono">Upgrade your cloud computing hashrate array</p>
        </div>

        <div class="rounded-2xl bg-[#090f19] border border-emerald-500/40 p-4 flex items-center justify-between shadow-lg">
          <div>
            <div class="flex items-center gap-2">
              <h3 class="text-sm font-bold text-white">Nano Mobile Node</h3>
              <span class="text-[9px] bg-emerald-500/20 text-emerald-400 border border-emerald-500/40 px-1.5 py-0.5 rounded font-mono">ACTIVE</span>
            </div>
            <p class="text-xs font-mono text-emerald-400 mt-1">10.00 STG/H · Default Genesis</p>
          </div>
          <span class="font-mono text-xs font-bold text-emerald-400">EQUIPPED</span>
        </div>

        <div class="rounded-2xl bg-[#090f19] border border-slate-800 p-4 flex items-center justify-between">
          <div>
            <h3 class="text-sm font-bold text-white">ASIC Blade Cluster</h3>
            <p class="text-xs font-mono text-emerald-400 mt-1">+25.00 STG/H</p>
            <span class="text-[11px] font-mono text-slate-400">Cost: 15.0 STG</span>
          </div>
          <button onclick="upgradeRig(2, 15, 25)" class="py-2 px-3.5 rounded-xl bg-emerald-400 hover:bg-emerald-300 text-slate-950 font-mono text-xs font-bold transition-all active:scale-95 cursor-pointer">
            Upgrade
          </button>
        </div>

        <div class="rounded-2xl bg-[#090f19] border border-slate-800 p-4 flex items-center justify-between">
          <div>
            <h3 class="text-sm font-bold text-white">Cryo-Cooled GPU Rack</h3>
            <p class="text-xs font-mono text-emerald-400 mt-1">+50.00 STG/H</p>
            <span class="text-[11px] font-mono text-slate-400">Cost: 50.0 STG</span>
          </div>
          <button onclick="upgradeRig(3, 50, 50)" class="py-2 px-3.5 rounded-xl bg-emerald-400 hover:bg-emerald-300 text-slate-950 font-mono text-xs font-bold transition-all active:scale-95 cursor-pointer">
            Upgrade
          </button>
        </div>
      </section>

      <!-- ================= 3. TASKS TAB ================= -->
      <section id="tab-quests-page" class="space-y-4 pb-4 hidden">
        <!-- 7-Day Streak Card -->
        <div class="rounded-2xl bg-gradient-to-br from-[#0e1726] to-[#080d16] border border-slate-800 p-4 shadow-lg">
          <div class="flex items-center justify-between mb-3">
            <div class="flex items-center gap-2">
              <i data-lucide="calendar" class="w-4 h-4 text-emerald-400"></i>
              <div>
                <h2 class="text-sm font-bold text-white">Daily Mining Streak</h2>
                <p class="text-[11px] text-slate-400">Check in every 24h to earn free STG</p>
              </div>
            </div>
            <div class="text-right font-mono">
              <span class="text-[10px] text-slate-400 block">Streak</span>
              <span id="streakDaysCount" class="text-xs font-bold text-emerald-400">0 Days</span>
            </div>
          </div>

          <button id="streakClaimBtn" onclick="claimDailyStreak()" class="w-full py-2.5 rounded-xl font-mono text-xs font-bold uppercase tracking-wider flex items-center justify-center gap-1.5 transition-all bg-emerald-400 hover:bg-emerald-300 text-slate-950 shadow-md shadow-emerald-500/20 active:scale-98 cursor-pointer">
            <i data-lucide="sparkles" class="w-3.5 h-3.5 fill-slate-950"></i>
            <span>Claim Daily Bonus (+0.50 STG)</span>
          </button>
        </div>

        <div>
          <h3 class="text-sm font-bold text-white tracking-wide">Official STG Missions</h3>
          <p class="text-xs text-slate-400 mt-0.5">Complete verified tasks to receive instant token rewards</p>
        </div>

        <div class="space-y-3">
          <div class="rounded-2xl bg-[#090f19] border border-slate-800/90 p-4 flex items-center justify-between gap-3 shadow-md">
            <div class="flex items-center gap-3">
              <div class="w-11 h-11 rounded-xl bg-slate-800/80 border border-slate-700/60 flex items-center justify-center shrink-0">
                <i data-lucide="send" class="w-4 h-4 text-sky-400"></i>
              </div>
              <div>
                <h4 class="text-xs font-bold text-white">Join STG Official Channel</h4>
                <div class="flex items-center gap-2 mt-0.5 font-mono">
                  <span class="text-xs font-bold text-emerald-400">+1.00 STG</span>
                  <span class="text-[10px] text-slate-500">·</span>
                  <span class="text-[10px] text-slate-400">t.me/stgairdrop</span>
                </div>
              </div>
            </div>
            <button id="taskBtn1" onclick="handleTask(1, 1.0, 'https://t.me/stgairdrop')" class="py-2 px-4 rounded-xl bg-emerald-400 hover:bg-emerald-300 text-slate-950 font-mono text-xs font-bold transition-all active:scale-95 shadow-md shadow-emerald-500/20 cursor-pointer">
              Start
            </button>
          </div>

          <div class="rounded-2xl bg-[#090f19] border border-slate-800/90 p-4 flex items-center justify-between gap-3 shadow-md">
            <div class="flex items-center gap-3">
              <div class="w-11 h-11 rounded-xl bg-slate-800/80 border border-slate-700/60 flex items-center justify-center shrink-0">
                <i data-lucide="twitter" class="w-4 h-4 text-blue-400"></i>
              </div>
              <div>
                <h4 class="text-xs font-bold text-white">Follow @stgsajib on X</h4>
                <div class="flex items-center gap-2 mt-0.5 font-mono">
                  <span class="text-xs font-bold text-emerald-400">+0.50 STG</span>
                  <span class="text-[10px] text-slate-500">·</span>
                  <span class="text-[10px] text-slate-400">Founder Account</span>
                </div>
              </div>
            </div>
            <button id="taskBtn2" onclick="handleTask(2, 0.5, 'https://x.com/stgsajib')" class="py-2 px-4 rounded-xl bg-emerald-400 hover:bg-emerald-300 text-slate-950 font-mono text-xs font-bold transition-all active:scale-95 shadow-md shadow-emerald-500/20 cursor-pointer">
              Start
            </button>
          </div>
        </div>
      </section>

      <!-- ================= 4. SQUAD TAB (UNDER MAINTENANCE) ================= -->
      <section id="tab-squad-page" class="space-y-4 pb-4 hidden">
        <div class="rounded-3xl bg-gradient-to-b from-[#141924] to-[#090d14] border border-amber-500/30 p-6 text-center shadow-xl">
          <div class="inline-flex items-center gap-1.5 px-3 py-1 rounded-full bg-amber-500/10 border border-amber-500/30 text-amber-400 text-xs font-mono font-bold mb-3">
            <i data-lucide="lock" class="w-3 h-3"></i>
            <span>UNDER MAINTENANCE</span>
          </div>
          <h2 class="text-base font-extrabold text-white">Squad Network is Locked</h2>
          <p class="text-xs text-slate-300 mt-2 leading-relaxed">
            The referral and squad hash system is currently undergoing infrastructure upgrades.<br>
            <strong class="text-amber-400 font-mono">মেইনটেন্যান্স চলছে — খুব শীঘ্রই চালু হবে।</strong>
          </p>
          <div class="mt-4 pt-4 border-t border-slate-800 text-[11px] font-mono text-slate-400">
            For updates join: <span class="text-emerald-400">@stgairdrop</span>
          </div>
          <button onclick="openChannel()" class="mt-3 w-full py-2.5 rounded-xl bg-sky-500 hover:bg-sky-400 text-white font-mono text-xs font-bold transition-all active:scale-95 cursor-pointer">
            Check Official Channel
          </button>
        </div>
      </section>

      <!-- ================= 5. PROFILE TAB ================= -->
      <section id="tab-profile-page" class="space-y-4 pb-4 hidden">
        <!-- User Info Card -->
        <div class="rounded-3xl bg-gradient-to-br from-[#0d1627] via-[#09111e] to-[#070b13] border border-slate-800 p-5 shadow-xl relative overflow-hidden">
          <div class="flex items-center gap-4">
            <div class="relative w-16 h-16 rounded-2xl bg-gradient-to-tr from-emerald-500 to-teal-400 p-0.5 shadow-lg shadow-emerald-500/20 shrink-0">
              <div class="w-full h-full rounded-[14px] bg-[#0a101b] flex items-center justify-center text-3xl">
                <i data-lucide="user" class="w-7 h-7 text-emerald-400"></i>
              </div>
            </div>
            <div class="flex-1 min-w-0">
              <h2 id="profUserTitle" class="text-base font-bold text-white truncate">STG Miner User</h2>
              <div class="flex items-center gap-1.5 mt-0.5">
                <span class="text-xs font-mono text-emerald-400 font-bold">@stgairdrop</span>
                <span class="text-slate-600">·</span>
                <span id="profIdText" class="text-xs font-mono text-slate-400">ID: 7129845</span>
              </div>
              <div class="text-[11px] font-mono text-slate-400 mt-1">
                <span class="text-emerald-400 font-bold">Tier 1 Miner</span> · 10.0 GH/s
              </div>
            </div>
          </div>

          <div class="grid grid-cols-2 gap-2.5 mt-4 pt-3.5 border-t border-slate-800/80 font-mono">
            <div class="bg-[#0b121e]/90 rounded-2xl p-3 border border-slate-800">
              <span class="text-[10px] text-slate-400 uppercase tracking-wider block">HOLDING BALANCE</span>
              <div id="profBalanceVal" class="text-lg font-extrabold text-white mt-0.5 truncate">0.0000 <span class="text-xs text-emerald-400">STG</span></div>
              <span id="profUsdVal" class="text-[10px] text-slate-500">≈ $0.000 USD</span>
            </div>

            <div class="bg-[#0b121e]/90 rounded-2xl p-3 border border-slate-800">
              <span class="text-[10px] text-slate-400 uppercase tracking-wider block">TOTAL MINED</span>
              <div id="profTotalMinedVal" class="text-lg font-extrabold text-emerald-400 mt-0.5 truncate">0.0000 <span class="text-xs">STG</span></div>
              <span class="text-[10px] text-slate-500">Genesis Node</span>
            </div>
          </div>
        </div>

        <!-- WALLET ADDRESS PASTE & SAVE -->
        <div class="rounded-3xl bg-[#090f19] border border-slate-800 p-4 shadow-md">
          <div class="flex items-center justify-between mb-1.5 font-mono">
            <div class="flex items-center gap-1.5">
              <i data-lucide="shield" class="w-4 h-4 text-emerald-400"></i>
              <span class="text-xs font-bold text-white">Withdrawal Wallet Address</span>
            </div>
            <span id="walletSavedBadge" class="hidden text-[10px] text-emerald-400 flex items-center gap-1 font-bold">
              <i data-lucide="check" class="w-3 h-3"></i> Saved
            </span>
          </div>

          <p class="text-[11px] text-slate-400 mb-3 leading-relaxed">
            Paste your TON or crypto wallet address to keep on file for token distribution.
          </p>

          <div class="space-y-2">
            <div class="relative">
              <input type="text" id="walletInput" placeholder="Paste TON Address (EQ... / UQ...)" class="w-full bg-slate-950 border border-slate-800 rounded-xl px-3 py-2.5 text-xs font-mono text-white placeholder-slate-600 focus:outline-none focus:border-emerald-500 pr-16">
              <button onclick="pasteClipboard()" class="absolute right-1.5 top-1/2 -translate-y-1/2 px-2.5 py-1 bg-slate-800 hover:bg-slate-700 text-slate-300 rounded-lg text-[10px] font-mono cursor-pointer">
                Paste
              </button>
            </div>
            <button onclick="saveWalletAddress()" class="w-full py-2.5 bg-emerald-400 hover:bg-emerald-300 text-slate-950 font-mono text-xs font-bold rounded-xl flex items-center justify-center gap-1.5 shadow-md shadow-emerald-500/20 active:scale-98 transition-all cursor-pointer">
              <i data-lucide="save" class="w-3.5 h-3.5"></i>
              <span>Save Wallet Address</span>
            </button>
          </div>
        </div>

        <!-- HISTORY SHORTCUT -->
        <div onclick="openHistoryModal()" class="rounded-2xl bg-[#090f19] border border-slate-800 p-3.5 flex items-center justify-between cursor-pointer hover:border-slate-700 transition-colors">
          <div class="flex items-center gap-2">
            <i data-lucide="history" class="w-4 h-4 text-emerald-400"></i>
            <span class="text-xs font-mono font-bold text-slate-200">Balance Credit History (লেজার)</span>
          </div>
          <span class="text-xs font-mono text-emerald-400">Open →</span>
        </div>

        <!-- CHANNEL LINK -->
        <button onclick="openChannel()" class="w-full py-3 rounded-2xl bg-[#090f19] border border-sky-500/30 text-sky-400 font-mono text-xs font-bold flex items-center justify-center gap-2 hover:bg-sky-500/10 transition-colors cursor-pointer">
          <i data-lucide="send" class="w-4 h-4"></i>
          <span>Official Announcements: t.me/stgairdrop</span>
        </button>
      </section>

    </main>

    <!-- Fixed Bottom Navigation (5 Tabs) -->
    <nav class="fixed bottom-0 left-0 right-0 z-40 bg-[#070b12]/95 backdrop-blur-md border-t border-slate-800/80">
      <div class="grid grid-cols-5 h-16 max-w-md mx-auto">
        <button onclick="switchTab('mine')" id="nav-btn-mine" class="flex flex-col items-center justify-center min-h-[48px] py-1 transition-all text-emerald-400 font-semibold cursor-pointer">
          <i data-lucide="pickaxe" class="w-5 h-5"></i>
          <span class="text-[10px] tracking-tight mt-1">Mine</span>
        </button>
        <button onclick="switchTab('rigs')" id="nav-btn-rigs" class="flex flex-col items-center justify-center min-h-[48px] py-1 transition-all text-slate-400 hover:text-slate-200 cursor-pointer">
          <i data-lucide="cpu" class="w-5 h-5"></i>
          <span class="text-[10px] tracking-tight mt-1">Rigs</span>
        </button>
        <button onclick="switchTab('quests')" id="nav-btn-quests" class="flex flex-col items-center justify-center min-h-[48px] py-1 transition-all text-slate-400 hover:text-slate-200 cursor-pointer">
          <i data-lucide="check-square" class="w-5 h-5"></i>
          <span class="text-[10px] tracking-tight mt-1">Tasks</span>
        </button>
        <button onclick="switchTab('squad')" id="nav-btn-squad" class="flex flex-col items-center justify-center min-h-[48px] py-1 transition-all text-slate-400 hover:text-slate-200 relative cursor-pointer">
          <div class="relative">
            <i data-lucide="users" class="w-5 h-5"></i>
            <span class="absolute -top-1.5 -right-2 text-[8px] bg-amber-500/20 text-amber-400 border border-amber-500/40 rounded px-0.5 font-mono">🔒</span>
          </div>
          <span class="text-[10px] tracking-tight mt-1">Squad</span>
        </button>
        <button onclick="switchTab('profile')" id="nav-btn-profile" class="flex flex-col items-center justify-center min-h-[48px] py-1 transition-all text-slate-400 hover:text-slate-200 cursor-pointer">
          <i data-lucide="user" class="w-5 h-5"></i>
          <span class="text-[10px] tracking-tight mt-1">Profile</span>
        </button>
      </div>
    </nav>

  </div>

  <!-- History Modal -->
  <div id="historyModal" class="hidden fixed inset-0 z-50 flex items-center justify-center p-4 bg-black/75 backdrop-blur-sm">
    <div class="relative w-full max-w-sm rounded-3xl bg-[#0b121e] border border-slate-800 shadow-2xl p-5 max-h-[85vh] flex flex-col">
      <div class="flex items-center justify-between pb-3 border-b border-slate-800">
        <div class="flex items-center gap-2">
          <i data-lucide="history" class="w-4 h-4 text-emerald-400"></i>
          <h3 class="text-sm font-bold text-white font-mono">Balance Credit History</h3>
        </div>
        <button onclick="closeHistoryModal()" class="w-7 h-7 rounded-full bg-slate-900 border border-slate-800 text-slate-400 flex items-center justify-center cursor-pointer">✕</button>
      </div>
      <div id="historyList" class="flex-1 overflow-y-auto space-y-2 py-3 pr-1"></div>
    </div>
  </div>

  <script>
    const STORAGE_KEY = 'STG_STANDALONE_V3';
    const TOKEN_PRICE = 0.0125;
    const CYCLE_DURATION = 60 * 60 * 1000; // 1 hour

    let state = {
      balance: 0.0,
      totalMined: 0.0,
      ratePerHour: 10.0,
      active: false,
      ready: false,
      startTime: 0,
      energy: 15,
      boostUntil: 0,
      streak: 0,
      lastCheckIn: null,
      walletAddress: '',
      tasks: {},
      verifying: {},
      claimable: {},
      txs: [
        { id: 1, title: 'Welcome Genesis Bonus', amount: 0.5, time: new Date().toLocaleTimeString() }
      ]
    };

    let audioEnabled = true;
    let audioCtx = null;

    function playSound(type) {
      if (!audioEnabled) return;
      try {
        if (!audioCtx) audioCtx = new (window.AudioContext || window.webkitAudioContext)();
        if (audioCtx.state === 'suspended') audioCtx.resume();
        const now = audioCtx.currentTime;
        const osc = audioCtx.createOscillator();
        const gain = audioCtx.createGain();

        if (type === 'tap') {
          osc.frequency.setValueAtTime(650, now);
          osc.frequency.exponentialRampToValueAtTime(300, now + 0.04);
          gain.gain.setValueAtTime(0.1, now);
          gain.gain.exponentialRampToValueAtTime(0.001, now + 0.04);
          osc.connect(gain); gain.connect(audioCtx.destination);
          osc.start(now); osc.stop(now + 0.04);
        } else if (type === 'claim') {
          [523, 659, 783, 1046].forEach((f, i) => {
            const o = audioCtx.createOscillator();
            const g = audioCtx.createGain();
            const t = now + i * 0.06;
            o.frequency.setValueAtTime(f, t);
            g.gain.setValueAtTime(0.12, t);
            g.gain.exponentialRampToValueAtTime(0.001, t + 0.25);
            o.connect(g); g.connect(audioCtx.destination);
            o.start(t); o.stop(t + 0.25);
          });
        }
      } catch (e) {}
    }

    function toggleAudio() {
      audioEnabled = !audioEnabled;
      const btn = document.getElementById('soundBtn');
      btn.innerHTML = audioEnabled ? '<i data-lucide="volume-2" class="w-4 h-4 text-emerald-400"></i>' : '<i data-lucide="volume-x" class="w-4 h-4 text-slate-500"></i>';
      lucide.createIcons();
    }

    function saveState() {
      try { localStorage.setItem(STORAGE_KEY, JSON.stringify(state)); } catch (e) {}
    }

    function loadState() {
      try {
        const saved = localStorage.getItem(STORAGE_KEY);
        if (saved) state = Object.assign(state, JSON.parse(saved));
      } catch (e) {}
    }

    function fmt(n, d = 6) { return Number(n || 0).toFixed(d); }

    function updateUI() {
      const now = Date.now();
      const isBoost = state.boostUntil > now;
      const effectiveRate = state.ratePerHour * (isBoost ? 1.5 : 1.0);

      document.getElementById('holdingBalance').innerText = fmt(state.balance);
      document.getElementById('holdingUsd').innerText = (state.balance * TOKEN_PRICE).toFixed(3);
      document.getElementById('holdingSub').innerText = fmt(state.balance) + ' STG';
      document.getElementById('totalMinedSub').innerText = fmt(state.totalMined, 4) + ' STG';
      document.getElementById('ratePerHourText').innerText = effectiveRate.toFixed(2);
      document.getElementById('energyText').innerText = state.energy + '%';
      document.getElementById('energyBar').style.width = state.energy + '%';
      document.getElementById('streakDaysCount').innerText = state.streak + ' Days';
      document.getElementById('historyRecordBadge').innerText = (state.txs ? state.txs.length : 0) + ' Records →';

      // Profile tab
      document.getElementById('profBalanceVal').innerHTML = fmt(state.balance, 4) + ' <span class="text-xs text-emerald-400">STG</span>';
      document.getElementById('profUsdVal').innerText = '≈ $' + (state.balance * TOKEN_PRICE).toFixed(3) + ' USD';
      document.getElementById('profTotalMinedVal').innerHTML = fmt(state.totalMined, 4) + ' <span class="text-xs">STG</span>';

      if (state.walletAddress) {
        document.getElementById('walletSavedBadge').classList.remove('hidden');
      }

      // Turbo Overclock display
      const turboBtn = document.getElementById('turboBtn');
      const turboBanner = document.getElementById('turboActiveBanner');
      if (state.energy >= 100 && !isBoost) {
        turboBtn.classList.remove('hidden');
      } else {
        turboBtn.classList.add('hidden');
      }

      if (isBoost) {
        turboBanner.classList.remove('hidden');
        document.getElementById('turboCountdown').innerText = `OVERCLOCK ACTIVE: ${Math.ceil((state.boostUntil - now) / 1000)}s left`;
      } else {
        turboBanner.classList.add('hidden');
      }

      // Mining Button & Status
      const actionArea = document.getElementById('actionArea');
      const statusMsg = document.getElementById('statusMsg');
      const svgRing = document.getElementById('svgProgressRing');
      const svgCircleBar = document.getElementById('svgCircleBar');

      if (state.active) {
        const elapsed = now - state.startTime;
        const remain = Math.max(0, CYCLE_DURATION - elapsed);

        if (remain <= 0) {
          state.active = false;
          state.ready = true;
          saveState();
        } else {
          svgRing.classList.remove('hidden');
          const pct = Math.min(100, (elapsed / CYCLE_DURATION) * 100);
          svgCircleBar.style.strokeDashoffset = 289 - (289 * pct) / 100;

          const sec = Math.ceil(remain / 1000);
          const m = Math.floor(sec / 60);
          const s = sec % 60;
          actionArea.innerHTML = `
            <div class="h-12 w-full rounded-2xl bg-slate-800/90 border border-slate-700 text-slate-200 font-mono font-bold text-sm flex items-center justify-center gap-2 shadow-inner">
              <i data-lucide="clock" class="w-4 h-4 text-emerald-400"></i>
              <span>CYCLE REMAINING: ${String(m).padStart(2,'0')}:${String(s).padStart(2,'0')}</span>
            </div>
          `;
          statusMsg.innerHTML = '<span class="w-2 h-2 rounded-full bg-emerald-400 animate-ping"></span><span>Mining Active at 10.0 STG/H</span>';
          lucide.createIcons();
          return;
        }
      }

      svgRing.classList.add('hidden');

      if (state.ready) {
        actionArea.innerHTML = `
          <button onclick="claimMining()" class="w-full py-4 rounded-2xl bg-gradient-to-r from-emerald-400 to-teal-400 hover:from-emerald-300 text-slate-950 font-mono font-extrabold text-sm tracking-wider uppercase flex items-center justify-center gap-2 shadow-xl shadow-emerald-500/30 active:scale-98 cursor-pointer">
            <i data-lucide="sparkles" class="w-4 h-4 fill-slate-950"></i>
            <span>CLAIM MINED STG (+10.0000 STG)</span>
          </button>
        `;
        statusMsg.innerHTML = '<span class="w-2 h-2 rounded-full bg-emerald-400"></span><span class="text-emerald-400 font-bold">Cycle Complete — Ready to Claim STG!</span>';
        lucide.createIcons();
        return;
      }

      actionArea.innerHTML = `
        <button onclick="startMining()" class="w-full py-4 rounded-2xl bg-white hover:bg-slate-100 text-[#070b12] font-mono font-extrabold text-sm tracking-wider uppercase flex items-center justify-center gap-2 shadow-xl shadow-white/10 active:scale-98 cursor-pointer">
          <i data-lucide="zap" class="w-4 h-4 fill-[#070b12]"></i>
          <span>START MINING (10 STG / H)</span>
        </button>
      `;
      statusMsg.innerText = 'Node Standby — Tap Start Mining below';
      lucide.createIcons();

      // Tasks state sync
      [1, 2].forEach(id => {
        const btn = document.getElementById('taskBtn' + id);
        if (!btn) return;
        if (state.tasks[id]) {
          btn.className = 'py-2 px-3.5 rounded-xl bg-emerald-950/70 border border-emerald-800/50 text-emerald-400 font-mono text-xs font-bold';
          btn.innerText = '✓ Done';
          btn.onclick = null;
        } else if (state.claimable[id]) {
          btn.className = 'py-2 px-3.5 rounded-xl bg-gradient-to-r from-emerald-400 to-teal-400 text-slate-950 font-mono text-xs font-black animate-pulse cursor-pointer';
          btn.innerText = 'Claim +' + (id === 1 ? '1.0' : '0.5');
        } else if (state.verifying[id]) {
          btn.className = 'py-2 px-3 rounded-xl bg-slate-800 border border-slate-700 text-slate-300 font-mono text-xs';
          btn.innerText = 'Checking...';
        } else {
          btn.className = 'py-2 px-4 rounded-xl bg-emerald-400 hover:bg-emerald-300 text-slate-950 font-mono text-xs font-bold active:scale-95 cursor-pointer';
          btn.innerText = 'Start';
        }
      });
    }

    function toggleMining() { startMining(); }

    function startMining() {
      state.startTime = Date.now();
      state.active = true;
      state.ready = false;
      playSound('tap');
      saveState();
      updateUI();
    }

    function claimMining() {
      const reward = 10.0;
      state.balance += reward;
      state.totalMined += reward;
      state.active = false;
      state.ready = false;
      state.startTime = 0;

      state.txs.unshift({
        id: Date.now(),
        title: 'Mining Cycle Output',
        amount: reward,
        time: new Date().toLocaleTimeString()
      });

      playSound('claim');
      if (window.confetti) confetti({ particleCount: 50, spread: 60, origin: { y: 0.6 } });
      saveState();
      updateUI();
    }

    function handleCoinTap(e) {
      playSound('tap');
      state.balance += 0.001;
      state.totalMined += 0.001;
      state.energy = Math.min(100, state.energy + 2);

      const floater = document.createElement('div');
      floater.className = 'floater-num';
      floater.innerText = '+0.001';
      floater.style.left = (e.clientX || 180) + 'px';
      floater.style.top = (e.clientY || 260) + 'px';
      document.body.appendChild(floater);
      setTimeout(() => floater.remove(), 800);

      saveState();
      updateUI();
    }

    function activateTurbo() {
      state.energy = 0;
      state.boostUntil = Date.now() + 30 * 1000;
      playSound('claim');
      saveState();
      updateUI();
    }

    function handleTask(id, reward, url) {
      if (state.tasks[id]) return;

      if (state.claimable[id]) {
        state.balance += reward;
        state.totalMined += reward;
        state.tasks[id] = true;
        delete state.claimable[id];
        delete state.verifying[id];

        state.txs.unshift({
          id: Date.now(),
          title: id === 1 ? 'Join Channel Reward' : 'Follow on X Reward',
          amount: reward,
          time: new Date().toLocaleTimeString()
        });

        playSound('claim');
        if (window.confetti) confetti({ particleCount: 40 });
        saveState();
        updateUI();
        return;
      }

      if (!state.verifying[id]) {
        state.verifying[id] = true;
        updateUI();

        try {
          if (window.Telegram && window.Telegram.WebApp && window.Telegram.WebApp.openTelegramLink && url.includes('t.me')) {
            window.Telegram.WebApp.openTelegramLink(url);
          } else {
            window.open(url, '_blank');
          }
        } catch (e) {
          window.open(url, '_blank');
        }

        setTimeout(() => {
          delete state.verifying[id];
          state.claimable[id] = true;
          saveState();
          updateUI();
        }, 3500);
      }
    }

    function claimDailyStreak() {
      const today = new Date().toDateString();
      if (state.lastCheckIn === today) {
        alert('Checked in today already! Come back in 24 hours.');
        return;
      }
      state.streak++;
      state.lastCheckIn = today;
      state.balance += 0.5;
      state.totalMined += 0.5;

      state.txs.unshift({
        id: Date.now(),
        title: `Day ${state.streak} Daily Check-in`,
        amount: 0.5,
        time: new Date().toLocaleTimeString()
      });

      playSound('claim');
      if (window.confetti) confetti({ particleCount: 40 });
      saveState();
      updateUI();
    }

    function upgradeRig(level, cost, newRate) {
      if (state.balance < cost) {
        alert(`Insufficient STG balance! You need ${cost} STG.`);
        return;
      }
      state.balance -= cost;
      state.ratePerHour = newRate;
      playSound('claim');
      alert(`Hardware successfully upgraded to ${newRate} STG/H!`);
      saveState();
      updateUI();
    }

    function saveWalletAddress() {
      const val = document.getElementById('walletInput').value.trim();
      if (!val) return;
      state.walletAddress = val;
      saveState();
      updateUI();
      alert('Wallet address saved successfully!');
    }

    async function pasteClipboard() {
      try {
        if (navigator.clipboard && navigator.clipboard.readText) {
          const t = await navigator.clipboard.readText();
          if (t) document.getElementById('walletInput').value = t.trim();
        }
      } catch (e) {}
    }

    function openHistoryModal() {
      const list = document.getElementById('historyList');
      list.innerHTML = '';
      (state.txs || []).forEach(tx => {
        const item = document.createElement('div');
        item.className = 'p-2.5 rounded-xl bg-slate-950/70 border border-slate-800/80 flex items-center justify-between font-mono text-xs';
        item.innerHTML = `
          <div>
            <span class="font-bold text-slate-200 block truncate max-w-[180px]">${tx.title}</span>
            <span class="text-[10px] text-slate-500">${tx.time}</span>
          </div>
          <span class="font-bold text-emerald-400">+${fmt(tx.amount, 4)} STG</span>
        `;
        list.appendChild(item);
      });
      document.getElementById('historyModal').classList.remove('hidden');
    }

    function closeHistoryModal() {
      document.getElementById('historyModal').classList.add('hidden');
    }

    function switchTab(tab) {
      ['mine', 'rigs', 'quests', 'squad', 'profile'].forEach(t => {
        const page = document.getElementById('tab-' + t + '-page');
        const btn = document.getElementById('nav-btn-' + t);
        if (page) page.classList.toggle('hidden', t !== tab);
        if (btn) {
          if (t === tab) {
            btn.className = 'flex flex-col items-center justify-center min-h-[48px] py-1 transition-all text-emerald-400 font-semibold cursor-pointer';
          } else {
            btn.className = 'flex flex-col items-center justify-center min-h-[48px] py-1 transition-all text-slate-400 hover:text-slate-200 cursor-pointer';
          }
        }
      });
      window.scrollTo({ top: 0, behavior: 'smooth' });
    }

    function openChannel() {
      const url = 'https://t.me/stgairdrop';
      if (window.Telegram && window.Telegram.WebApp && window.Telegram.WebApp.openTelegramLink) {
        window.Telegram.WebApp.openTelegramLink(url);
      } else {
        window.open(url, '_blank');
      }
    }

    window.addEventListener('DOMContentLoaded', () => {
      loadState();
      lucide.createIcons();

      if (state.walletAddress) {
        document.getElementById('walletInput').value = state.walletAddress;
      }

      if (window.Telegram && window.Telegram.WebApp) {
        const tg = window.Telegram.WebApp;
        try {
          tg.ready();
          tg.expand();
          if (tg.initDataUnsafe && tg.initDataUnsafe.user) {
            const u = tg.initDataUnsafe.user;
            document.getElementById('profUserTitle').innerText = (u.first_name || 'STG User') + (u.last_name ? ' ' + u.last_name : '');
            document.getElementById('profIdText').innerText = 'ID: ' + u.id;
          }
        } catch (e) {}
      }

      updateUI();
      setInterval(updateUI, 500);
    });
  </script>
</body>
</html>
