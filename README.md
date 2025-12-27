# .github

![ouritres.svg](https://github.com/OurITRes/.github/blob/main/ouritres.svg)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>our IT resources - Brand Identity</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap');
        body { font-family: 'Inter', sans-serif; }
    </style>
</head>
<body class="bg-gray-50 text-gray-800 p-8">
    <div class="max-w-6xl mx-auto">
        <header class="mb-12 text-center">
            <h1 class="text-4xl font-extrabold text-slate-800 mb-2">Brand Identity Ecosystem</h1>
            <p class="text-xl text-slate-500 italic">"Governing the Core. Automating the Services."</p>
        </header>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- 1. Master Brand -->
            <div class="bg-white rounded-xl shadow-lg p-8 flex flex-col items-center border-t-4 border-[#00E5FF]">
                <h2 class="text-lg font-bold text-[#2C3E50] mb-6 uppercase tracking-wider">Master Brand</h2>
                <!-- SVG Logo -->
                <div class="w-48 h-48 mb-6 relative">
                    <svg viewBox="0 0 200 200" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <!-- Left Bracket (Dark Gray) -->
                        <path d="M70 40 L30 100 L70 160" stroke="#2C3E50" stroke-width="20" stroke-linecap="round" stroke-linejoin="round"/>
                        <!-- Right Bracket (Cyan) -->
                        <path d="M130 40 L170 100 L130 160" stroke="#00E5FF" stroke-width="20" stroke-linecap="round" stroke-linejoin="round"/>
                        <!-- Center O (Negative space implied by curvature or explicit shape) -->
                        <!-- Adding a subtle tech 'core' diamond in the middle to emphasize the O space -->
                        <circle cx="100" cy="100" r="15" fill="#2C3E50" opacity="0.1"/>
                    </svg>
                </div>
                <div class="text-center">
                    <h3 class="text-3xl font-extrabold text-[#2C3E50] leading-none">
                        our<span class="text-[#00E5FF]">IT</span>
                    </h3>
                    <p class="text-sm font-semibold text-[#2C3E50] tracking-widest mt-1">RESOURCES</p>
                </div>
                <div class="mt-8 w-full">
                    <div class="flex items-center justify-between text-xs text-gray-400 mb-2">
                        <span>HEX</span>
                        <span>#2C3E50 / #00E5FF</span>
                    </div>
                    <div class="flex h-4 w-full rounded overflow-hidden">
                        <div class="w-1/2 bg-[#2C3E50]"></div>
                        <div class="w-1/2 bg-[#00E5FF]"></div>
                    </div>
                </div>
            </div>
            <!-- 2. SITARCA -->
            <div class="bg-white rounded-xl shadow-lg p-8 flex flex-col items-center border-t-4 border-[#4169E1]">
                <h2 class="text-lg font-bold text-[#4169E1] mb-6 uppercase tracking-wider">Module SITARCA</h2>
                <!-- SVG Logo -->
                <div class="w-48 h-48 mb-6">
                    <svg viewBox="0 0 200 200" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <defs>
                            <filter id="glow-blue" x="-20%" y="-20%" width="140%" height="140%">
                                <feGaussianBlur stdDeviation="2" result="blur"/>
                                <feComposite in="SourceGraphic" in2="blur" operator="over"/>
                            </filter>
                        </defs>
                        <!-- Brackets (Royal Blue) -->
                        <path d="M70 40 L30 100 L70 160" stroke="#4169E1" stroke-width="16" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M130 40 L170 100 L130 160" stroke="#4169E1" stroke-width="16" stroke-linecap="round" stroke-linejoin="round"/>
                        <!-- Neural Network Nodes (Interior) -->
                        <circle cx="100" cy="100" r="8" fill="#4169E1" />
                        <circle cx="100" cy="70" r="5" fill="#4169E1" opacity="0.7"/>
                        <circle cx="100" cy="130" r="5" fill="#4169E1" opacity="0.7"/>
                        <circle cx="75" cy="100" r="5" fill="#4169E1" opacity="0.7"/>
                        <circle cx="125" cy="100" r="5" fill="#4169E1" opacity="0.7"/>
                        <!-- Connections -->
                        <line x1="100" y1="70" x2="100" y2="130" stroke="#4169E1" stroke-width="2" opacity="0.5"/>
                        <line x1="75" y1="100" x2="125" y2="100" stroke="#4169E1" stroke-width="2" opacity="0.5"/>
                        <line x1="100" y1="100" x2="130" y2="70" stroke="#4169E1" stroke-width="1" opacity="0.3"/>
                        <line x1="100" y1="100" x2="70" y2="130" stroke="#4169E1" stroke-width="1" opacity="0.3"/>
                    </svg>
                </div>
                <div class="text-center">
                    <h3 class="text-2xl font-bold text-[#4169E1] tracking-wider">SITARCA</h3>
                    <p class="text-[0.6rem] text-gray-400 mt-2 max-w-[150px] leading-tight">
                        Synchronized Intelligence, Tiered Automated Remediation & Conformity Alignment
                    </p>
                </div>
                 <div class="mt-8 w-full">
                    <div class="flex items-center justify-between text-xs text-gray-400 mb-2">
                        <span>HEX</span>
                        <span>#4169E1</span>
                    </div>
                    <div class="h-4 w-full bg-[#4169E1] rounded"></div>
                </div>
            </div>
            <!-- 3. SAGAPI -->
            <div class="bg-white rounded-xl shadow-lg p-8 flex flex-col items-center border-t-4 border-[#FF8C00]">
                <h2 class="text-lg font-bold text-[#FF8C00] mb-6 uppercase tracking-wider">Module SAGAPI</h2>
                <!-- SVG Logo -->
                <div class="w-48 h-48 mb-6">
                    <svg viewBox="0 0 200 200" fill="none" xmlns="http://www.w3.org/2000/svg">
                         <!-- Brackets (Orange) -->
                        <path d="M70 40 L30 100 L70 160" stroke="#FF8C00" stroke-width="16" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M130 40 L170 100 L130 160" stroke="#FF8C00" stroke-width="16" stroke-linecap="round" stroke-linejoin="round"/>
                        <!-- Kinetic API Lines -->
                        <path d="M40 85 L160 85" stroke="#FF8C00" stroke-width="4" stroke-linecap="round" opacity="0.8"/>
                        <path d="M20 100 L180 100" stroke="#FF8C00" stroke-width="6" stroke-linecap="round"/>
                        <path d="M40 115 L160 115" stroke="#FF8C00" stroke-width="4" stroke-linecap="round" opacity="0.8"/>
                        <!-- Flow indicators -->
                         <circle cx="160" cy="85" r="3" fill="#FF8C00" />
                         <circle cx="40" cy="115" r="3" fill="#FF8C00" />
                    </svg>
                </div>
                <div class="text-center">
                    <h3 class="text-2xl font-bold text-[#FF8C00] tracking-wider">SAGAPI</h3>
                    <p class="text-[0.6rem] text-gray-400 mt-2 max-w-[150px] leading-tight">
                        Service Account Governance & Automation Programmable Interface
                    </p>
                </div>
                <div class="mt-8 w-full">
                    <div class="flex items-center justify-between text-xs text-gray-400 mb-2">
                        <span>HEX</span>
                        <span>#FF8C00</span>
                    </div>
                    <div class="h-4 w-full bg-[#FF8C00] rounded"></div>
                </div>
            </div>
        </div>
        <footer class="mt-12 text-center text-gray-400 text-sm">
            <p>Generated Vector Assets (SVG) - Ready for Export</p>
        </footer>
    </div>
</body>
</html>
