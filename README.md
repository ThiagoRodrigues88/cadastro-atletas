<!DOCTYPE html>

<html class="light" lang="pt-br"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Cadastro Atletas - Ribas do Rio Pardo</title>
<!-- Fonts -->
<link href="https://fonts.googleapis.com" rel="preconnect"/>
<link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&amp;family=Plus+Jakarta+Sans:ital,wght@0,400;0,500;0,600;0,700;0,800;1,800&amp;display=swap" rel="stylesheet"/>
<!-- Icons -->
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<!-- Tailwind -->
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "on-tertiary-container": "#0e0200",
              "surface-container-high": "#e6e8f2",
              "primary-fixed-dim": "#adc7ff",
              "on-tertiary-fixed": "#341100",
              "surface-dim": "#d8d9e3",
              "surface-container-low": "#f2f3fd",
              "on-surface-variant": "#414754",
              "tertiary": "#34a853",
              "on-secondary": "#ffffff",
              "on-error": "#ffffff",
              "background": "#f9f9ff",
              "primary-fixed": "#d8e2ff",
              "secondary-fixed": "#d8e2ff",
              "on-tertiary": "#ffffff",
              "on-secondary-fixed-variant": "#2e4673",
              "on-primary-container": "#ffffff",
              "error-container": "#ffdad6",
              "on-surface": "#191c23",
              "surface-bright": "#f9f9ff",
              "surface-container-highest": "#e0e2ec",
              "inverse-on-surface": "#eff0fa",
              "secondary-container": "#b2c9fe",
              "primary-container": "#1a73e8",
              "surface": "#f9f9ff",
              "error": "#ba1a1a",
              "on-primary-fixed-variant": "#004493",
              "on-secondary-fixed": "#001a41",
              "surface-container": "#ecedf7",
              "on-background": "#191c23",
              "inverse-primary": "#adc7ff",
              "surface-container-lowest": "#ffffff",
              "surface-variant": "#e0e2ec",
              "primary": "#005bbf",
              "tertiary-container": "#34a853",
              "on-primary": "#ffffff",
              "secondary-fixed-dim": "#afc7fb",
              "on-primary-fixed": "#001a41",
              "on-error-container": "#93000a",
              "inverse-surface": "#2d3038",
              "tertiary-fixed-dim": "#ffb691",
              "on-secondary-container": "#3d5481",
              "surface-tint": "#005bc0",
              "secondary": "#475e8c",
              "on-tertiary-fixed-variant": "#783100",
              "tertiary-fixed": "#ffdbcb",
              "outline-variant": "#c1c6d6",
              "outline": "#727785"
            },
            fontFamily: {
              "headline": ["Plus Jakarta Sans"],
              "body": ["Inter"],
              "label": ["Inter"]
            },
            borderRadius: {"DEFAULT": "0.25rem", "lg": "0.5rem", "xl": "0.75rem", "2xl": "1rem", "3xl": "1.5rem", "full": "9999px"},
          },
        },
      }
    </script>
<style>
      .material-symbols-outlined {
        font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
      }
      .font-plus-jakarta { font-family: 'Plus Jakarta Sans', sans-serif; }
      .bg-mesh {
        background-color: #f9f9ff;
        background-image: radial-gradient(at 0% 0%, rgba(26, 115, 232, 0.05) 0px, transparent 50%), 
                          radial-gradient(at 100% 100%, rgba(52, 168, 83, 0.05) 0px, transparent 50%);
      }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
</head>
<body class="bg-surface font-body text-on-surface min-h-screen selection:bg-primary/20 bg-mesh">
<!-- TopAppBar -->
<header class="fixed top-0 w-full z-50 bg-white/80 dark:bg-slate-900/80 backdrop-blur-xl">
<div class="flex items-center justify-between px-6 h-16 w-full max-w-md mx-auto">
<div class="flex items-center gap-3">
<span class="material-symbols-outlined text-blue-600 dark:text-blue-400">menu</span>
<h1 class="font-plus-jakarta text-lg font-bold tracking-tight text-blue-600 dark:text-blue-400">Cadastro Atletas</h1>
</div>
<div class="w-10 h-10 rounded-full bg-surface-container flex items-center justify-center overflow-hidden">
<img alt="User Profile" class="w-full h-full object-cover" data-alt="professional portrait of a sports coordinator in a clean modern office setting with soft natural lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB2zgCYGwGOxUUkd70hRHrJDF2GJpJ67fDobQdXwWK4X25tKm1ekYulqVuj32GgHXVza-qdGs5aSwc7EnWMvr-LubS90Ev0rB5KLA6kORT3EvVChOv5-OHB9XJ8TXfMff8hA3BhjwTAZaBvPsL7NuRbg2TUJz0Yhza3eH21TZsVXqt3EZhbDZbLutoxQxH-d9s_GEZtwpuiJfE-47qsIxx4soIs0MDsJM8QW55N-M5NkAqc-BGP06h2rpJBzjYYb-YizpsV5kGrWZue"/>
</div>
</div>
</header>
<main class="pt-24 pb-32 px-6 max-w-md mx-auto min-h-screen">
<!-- Hero Section: Editorial Style -->
<section class="mb-12 text-center">
<div class="inline-flex items-center justify-center w-24 h-24 rounded-3xl bg-gradient-to-br from-primary to-primary-container shadow-2xl shadow-primary/30 mb-8 transform -rotate-3 bg-white shadow-lg"><img alt="Projeto Pedalando para o Futuro Logo" class="w-full h-full object-contain p-2" src="https://lh3.googleusercontent.com/aida/ADBb0uizoebY0MocKyot1xS2dLozEg1Lgx2K1judcSsnO2-k3Tz8O_iCeiptvII4ZxoYDqggJS9Y5hOwfV3Jnu_DjPHDr2So5PEuDBq548oYdg_JBKLEXqn7pMaIcG_pNmduSoKRtWVduwvxFMLRbFHp8kubdU1eg0WhFLQ9rcD7xrxheAiYx__MRNh5XmS4A8t-_8iGj7CzmV3GYf5Jz0zO07CmA1g9F01QR5-8cFZpT-OcZ8RTiPmZossn750rD_-SqMXWUCeeaT7rcQE"/></div>
<h2 class="font-plus-jakarta text-4xl font-extrabold tracking-tight text-on-surface leading-tight mb-3">
                📊 Cadastro Alunos/Atletas
            </h2>
<p class="text-on-surface-variant font-medium text-lg leading-relaxed max-w-[280px] mx-auto opacity-80">
                Projeto Esportivo — Ribas do Rio Pardo/MS
            </p>
</section>
<!-- Bento Grid Styled Buttons -->
<div class="grid grid-cols-1 gap-6">
<!-- ➕ Novo Cadastro (Large Accent Card) -->
<button class="group relative overflow-hidden bg-surface-container-lowest rounded-3xl p-8 text-left transition-all duration-300 active:scale-95 shadow-sm hover:shadow-xl hover:shadow-tertiary/10">
<div class="absolute top-0 right-0 w-32 h-32 bg-tertiary/5 rounded-full -mr-16 -mt-16 group-hover:scale-150 transition-transform duration-500"></div>
<div class="relative z-10">
<div class="w-14 h-14 rounded-2xl bg-tertiary/10 flex items-center justify-center mb-6 group-hover:bg-tertiary group-hover:text-white transition-colors duration-300">
<span class="material-symbols-outlined text-3xl text-tertiary group-hover:text-white">person_add</span>
</div>
<h3 class="font-plus-jakarta text-2xl font-bold text-on-surface mb-1">➕ Novo Cadastro</h3>
<p class="text-on-surface-variant text-sm">Registre um novo aluno no projeto</p>
</div>
<div class="absolute bottom-6 right-8 opacity-0 group-hover:opacity-100 transition-opacity">
<span class="material-symbols-outlined text-tertiary">arrow_forward_ios</span>
</div>
</button>
<div class="grid grid-cols-2 gap-4">
<!-- 📋 Alunos Cadastrados -->
<button class="group bg-surface-container-lowest rounded-3xl p-6 text-left transition-all duration-300 active:scale-95 shadow-sm border-b-4 border-primary/20 hover:border-primary">
<div class="w-12 h-12 rounded-xl bg-primary/10 flex items-center justify-center mb-4 group-hover:bg-primary transition-colors">
<span class="material-symbols-outlined text-2xl text-primary group-hover:text-white">format_list_bulleted</span>
</div>
<h3 class="font-plus-jakarta text-lg font-bold text-on-surface leading-snug">📋 Alunos Cadastrados</h3>
</button>
<!-- 📊 Estatísticas -->
<button class="group bg-surface-container-lowest rounded-3xl p-6 text-left transition-all duration-300 active:scale-95 shadow-sm border-b-4 border-surface-container-highest hover:border-on-surface-variant">
<div class="w-12 h-12 rounded-xl bg-surface-container-high flex items-center justify-center mb-4 group-hover:bg-on-surface-variant transition-colors">
<span class="material-symbols-outlined text-2xl text-on-surface-variant group-hover:text-white">insights</span>
</div>
<h3 class="font-plus-jakarta text-lg font-bold text-on-surface leading-snug">📊 Estatísticas</h3>
</button>
</div>
<!-- Quick Access / Info Section -->
<div class="mt-4 p-6 rounded-3xl bg-surface-container-low flex items-center gap-4">
<div class="w-10 h-10 rounded-full bg-white flex items-center justify-center text-primary shadow-sm">
<span class="material-symbols-outlined text-xl">info</span>
</div>
<p class="text-xs text-on-surface-variant font-medium uppercase tracking-wider">
                    Total de 128 atletas ativos em Ribas
                </p>
</div>
</div>
</main>
<!-- FAB: Help/Support (Asymmetric placement as per system) -->
<button class="fixed bottom-24 right-6 w-14 h-14 bg-gradient-to-br from-primary to-primary-container text-white rounded-xl shadow-[0_8px_24px_rgba(25,28,35,0.2)] flex items-center justify-center z-40 active:scale-90 transition-transform">
<span class="material-symbols-outlined">support_agent</span>
</button>
<!-- BottomNavBar -->
<nav class="fixed bottom-0 w-full rounded-t-3xl pb-safe z-50 bg-white/80 dark:bg-slate-900/80 backdrop-blur-2xl shadow-[0_-8px_24px_rgba(25,28,35,0.06)]">
<div class="flex justify-around items-center px-4 py-3 w-full max-w-md mx-auto">
<!-- Home (Active) -->
<a class="flex flex-col items-center justify-center bg-gradient-to-br from-blue-600 to-blue-500 text-white rounded-2xl px-5 py-2 scale-110 shadow-lg shadow-blue-500/30" href="#">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">home</span>
<span class="font-plus-jakarta text-[10px] font-bold uppercase tracking-widest mt-0.5">Home</span>
</a>
<!-- Atletas -->
<a class="flex flex-col items-center justify-center text-slate-400 dark:text-slate-500 px-4 py-2 hover:text-blue-500 dark:hover:text-blue-300 transition-all" href="#">
<span class="material-symbols-outlined">format_list_bulleted</span>
<span class="font-plus-jakarta text-[10px] font-bold uppercase tracking-widest mt-0.5">Atletas</span>
</a>
<!-- Status -->
<a class="flex flex-col items-center justify-center text-slate-400 dark:text-slate-500 px-4 py-2 hover:text-blue-500 dark:hover:text-blue-300 transition-all" href="#">
<span class="material-symbols-outlined">insights</span>
<span class="font-plus-jakarta text-[10px] font-bold uppercase tracking-widest mt-0.5">Status</span>
</a>
</div>
</nav>
<!-- Image for visual depth (absolute positioning, editorial background element) -->
<div class="fixed top-1/2 -right-20 -z-10 opacity-10 pointer-events-none transform -translate-y-1/2">
<img alt="Sport Background Decor" class="w-[400px]" data-alt="Dynamic abstract close-up of a professional soccer ball with water droplets flying off during a high-speed motion shot" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCeZQI6nqC5UgjXmIXptwBN1QR0NOrq2xEd4gBbYYvJi5KjMP_04Fko4QAJYCZKdPPU-rNkNQQAlam4PF2LmZiK8cTLBr3QpKOjXZN79GflzCvgklcIUmJQbRFgt6KppSQQGVVIIQjH4ZcAiaJMQ27lUNBOi2yQ4EMXcUIz_eddSCL_9GU4Mka2MJAik8_dT7ioqeDdrDLcgxB1ZKr8l-l6weTgvZJUus-QouSIBawRo7iguGQqv4GDYRlLEUgPcj-ucYGMgn5BiSz4"/>
</div>
</body></html>
