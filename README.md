<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SmartBiz Emerald | Enterprise Architecture</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');
        
        body {
            font-family: 'Inter', sans-serif;
            background-color: #064e3b; /* Deep Emerald */
            color: #ecfdf5;
            overflow-x: hidden;
            scroll-behavior: smooth;
        }

        .emerald-glass {
            background: rgba(6, 78, 59, 0.7);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(16, 185, 129, 0.2);
            box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.37);
        }

        .nav-link {
            transition: all 0.3s ease;
            position: relative;
        }

        .nav-link:hover {
            color: #10b981;
        }

        .hero-gradient {
            background: radial-gradient(circle at top right, #065f46, #064e3b);
        }

        .status-pulse {
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0% { opacity: 1; }
            50% { opacity: 0.5; }
            100% { opacity: 1; }
        }

        .card-hover:hover {
            transform: translateY(-5px);
            border-color: rgba(16, 185, 129, 0.5);
            background: rgba(6, 78, 59, 0.9);
        }
    </style>
</head>
<body class="min-h-screen">

    <!-- Navigation -->
    <nav class="fixed w-full z-50 emerald-glass border-b border-emerald-800/50">
        <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
            <div class="flex items-center space-x-2">
                <i data-lucide="gem" class="text-emerald-400 w-8 h-8"></i>
                <span class="text-2xl font-bold tracking-tighter text-white">SMARTBIZ <span class="text-emerald-500 underline decoration-2">EMERALD</span></span>
            </div>
            
            <div class="hidden md:flex space-x-10 text-sm font-medium uppercase tracking-widest text-emerald-100">
                <a href="#home" class="nav-link">Architecture</a>
                <a href="#systems" class="nav-link">Systems</a>
                <a href="#contact" class="bg-emerald-600 hover:bg-emerald-500 text-white px-5 py-2 rounded-full transition-colors">Contact CEO</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="pt-48 pb-32 px-6 hero-gradient">
        <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-12 items-center">
            <div>
                <div class="inline-flex items-center space-x-2 bg-emerald-900/50 border border-emerald-700 rounded-full px-4 py-1 mb-6">
                    <span class="w-2 h-2 bg-emerald-400 rounded-full status-pulse"></span>
                    <span class="text-xs font-bold text-emerald-300 uppercase tracking-tighter">System Status: Optimal</span>
                </div>
                <h1 class="text-6xl md:text-7xl font-bold mb-6 leading-tight text-white">Enterprise <br><span class="text-emerald-400">Precision.</span></h1>
                <p class="text-emerald-100 text-lg mb-8 max-w-lg leading-relaxed">
                    Deploying the 2026 Enterprise Web Architecture. I specialize in high-availability systems and automated logic layers for modern business.
                </p>
                <div class="flex space-x-4">
                    <a href="#systems" class="bg-emerald-500 hover:bg-emerald-400 text-emerald-950 font-bold px-8 py-4 rounded-lg transition-all transform hover:-translate-y-1 inline-block">Explore Systems</a>
                    <a href="#contact" class="border border-emerald-500 text-emerald-400 font-bold px-8 py-4 rounded-lg hover:bg-emerald-500/10 transition-all inline-block text-center">Inquire Now</a>
                </div>
            </div>
            <div class="relative hidden md:block">
                <div class="emerald-glass rounded-3xl p-10 transform rotate-2 hover:rotate-0 transition-transform duration-500 border border-emerald-500/30">
                    <div class="flex items-center justify-between mb-8">
                        <h3 class="font-bold text-xl uppercase tracking-widest text-emerald-400">System Load</h3>
                        <i data-lucide="activity" class="text-emerald-400"></i>
                    </div>
                    <div class="space-y-8">
                        <div>
                            <div class="flex justify-between text-xs mb-2 uppercase font-bold text-emerald-200"><span>Architecture Hub</span><span>88%</span></div>
                            <div class="h-2 bg-emerald-900 rounded-full overflow-hidden">
                                <div class="h-full bg-emerald-400 w-[88%] shadow-[0_0_10px_#10b981]"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between text-xs mb-2 uppercase font-bold text-emerald-200"><span>Logic Processing</span><span>64%</span></div>
                            <div class="h-2 bg-emerald-900 rounded-full overflow-hidden">
                                <div class="h-full bg-emerald-500 w-[64%] shadow-[0_0_10px_#10b981]"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between text-xs mb-2 uppercase font-bold text-emerald-200"><span>Data Integrity</span><span>100%</span></div>
                            <div class="h-2 bg-emerald-900 rounded-full overflow-hidden">
                                <div class="h-full bg-emerald-300 w-full shadow-[0_0_10px_#10b981]"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="systems" class="py-32 bg-emerald-950 px-6">
        <div class="max-w-7xl mx-auto text-center mb-20">
            <h2 class="text-4xl font-bold mb-4 text-white">Core Systems</h2>
            <div class="h-1 w-20 bg-emerald-500 mx-auto rounded-full"></div>
            <p class="text-emerald-400 mt-6 max-w-xl mx-auto uppercase tracking-widest text-sm font-bold">Modular architecture designed for infinite scalability.</p>
        </div>
        <div class="max-w-7xl mx-auto grid md:grid-cols-3 gap-8">
            <div class="emerald-glass p-10 rounded-3xl border border-emerald-800/50 card-hover transition-all duration-300">
                <div class="w-14 h-14 bg-emerald-900/50 rounded-2xl flex items-center justify-center mb-6 border border-emerald-700">
                    <i data-lucide="shield-check" class="w-8 h-8 text-emerald-400"></i>
                </div>
                <h3 class="text-xl font-bold mb-4 text-white">Secure Logic</h3>
                <p class="text-emerald-200/70 text-sm leading-relaxed">End-to-end encrypted data pathways with zero-latency overhead. Built for high-trust environments.</p>
            </div>
            <div class="emerald-glass p-10 rounded-3xl border border-emerald-800/50 card-hover transition-all duration-300">
                <div class="w-14 h-14 bg-emerald-900/50 rounded-2xl flex items-center justify-center mb-6 border border-emerald-700">
                    <i data-lucide="cpu" class="w-8 h-8 text-emerald-400"></i>
                </div>
                <h3 class="text-xl font-bold mb-4 text-white">Neural Processing</h3>
                <p class="text-emerald-200/70 text-sm leading-relaxed">AI-driven automated logic layers managing real-time enterprise demands and smart decision routing.</p>
            </div>
            <div class="emerald-glass p-10 rounded-3xl border border-emerald-800/50 card-hover transition-all duration-300">
                <div class="w-14 h-14 bg-emerald-900/50 rounded-2xl flex items-center justify-center mb-6 border border-emerald-700">
                    <i data-lucide="database" class="w-8 h-8 text-emerald-400"></i>
                </div>
                <h3 class="text-xl font-bold mb-4 text-white">Cloud Fabric</h3>
                <p class="text-emerald-200/70 text-sm leading-relaxed">Distributed ledger storage ensuring high-availability uptime and redundant data integrity.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-32 px-6 hero-gradient">
        <div class="max-w-3xl mx-auto emerald-glass p-12 md:p-16 rounded-[3rem] text-center border border-emerald-500/20">
            <h2 class="text-4xl font-bold mb-6 text-white tracking-tight">Connect with Leadership</h2>
            <p class="text-emerald-200 mb-12 text-lg">Send this architecture report directly to the CEO's dashboard for executive review.</p>
            <form class="space-y-6 text-left" onsubmit="event.preventDefault(); document.getElementById('submit-text').innerText = 'DATA TRANSMITTED ✓';">
                <div>
                    <label class="block text-[10px] font-bold uppercase tracking-[0.2em] text-emerald-400 mb-2 ml-1">Reporting Officer Name</label>
                    <input type="text" placeholder="John Doe" class="w-full bg-emerald-900/30 border border-emerald-700/50 rounded-xl p-4 focus:outline-none focus:border-emerald-400 text-white placeholder-emerald-800 font-medium">
                </div>
                <div>
                    <label class="block text-[10px] font-bold uppercase tracking-[0.2em] text-emerald-400 mb-2 ml-1">Executive Summary</label>
                    <textarea placeholder="Describe the system architecture requirements..." class="w-full bg-emerald-900/30 border border-emerald-700/50 rounded-xl p-4 h-40 focus:outline-none focus:border-emerald-400 text-white placeholder-emerald-800 font-medium resize-none"></textarea>
                </div>
                <button class="w-full bg-emerald-500 hover:bg-emerald-400 text-emerald-950 font-black py-5 rounded-xl transition-all shadow-xl shadow-emerald-500/20 uppercase tracking-widest text-sm" id="submit-btn">
                    <span id="submit-text">Transmit Data Protocol</span>
                </button>
            </form>
        </div>
    </section>

    <footer class="py-16 border-t border-emerald-800/30 bg-emerald-950 px-6 text-center">
        <div class="max-w-7xl mx-auto">
            <div class="flex items-center justify-center space-x-2 mb-6 opacity-50">
                <i data-lucide="gem" class="text-emerald-400 w-5 h-5"></i>
                <span class="text-lg font-bold tracking-tighter text-white">SMARTBIZ</span>
            </div>
            <p class="text-emerald-600 text-[10px] font-black uppercase tracking-[0.5em]">
                &copy; 2026 SmartBiz Emerald Architecture. All protocols active and monitored.
            </p>
        </div>
    </footer>

    <script>
        // Initialize Lucide Icons
        lucide.createIcons();
    </script>
</body>
</html>

