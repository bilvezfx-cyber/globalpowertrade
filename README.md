# globalpowertrade
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>QuantumArb | Crypto Arbitrage MLM Platform</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0f172a;
            color: #e2e8f0;
        }
        .gradient-bg {
            background: linear-gradient(135deg, #1e3a8a 0%, #6b21a8 100%);
        }
        .card-gradient {
            background: linear-gradient(to bottom right, #1e293b, #0f172a);
        }
        .btn-primary {
            background: linear-gradient(to right, #2563eb, #7c3aed);
        }
        .modal {
            transition: opacity 0.3s ease, visibility 0.3s ease;
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav class="bg-gray-900 border-b border-gray-800 px-4 py-3 sticky top-0 z-50">
        <div class="max-w-7xl mx-auto flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <img src="https://placehold.co/40x40" alt="QuantumArb logo - abstract crypto symbol with hexagon pattern in blue and purple" class="h-10 w-10">
                <span class="text-xl font-bold bg-gradient-to-r from-blue-500 to-purple-600 bg-clip-text text-transparent">QuantumArb</span>
            </div>
            <div class="hidden md:flex items-center space-x-8">
                <a href="#features" class="text-gray-300 hover:text-white transition">Features</a>
                <a href="#how-it-works" class="text-gray-300 hover:text-white transition">How It Works</a>
                <a href="#mlm" class="text-gray-300 hover:text-white transition">MLM Program</a>
                <a href="#earnings" class="text-gray-300 hover:text-white transition">Earnings</a>
                <a href="#bot" class="text-gray-300 hover:text-white transition">Bot Features</a>
            </div>
            <div class="flex items-center space-x-4">
                <button id="login-btn" class="px-4 py-2 rounded-lg text-sm font-medium text-white bg-gray-800 hover:bg-gray-700 transition">Login</button>
                <button id="register-btn" class="px-4 py-2 rounded-lg text-sm font-medium text-white btn-primary hover:opacity-90 transition">Register</button>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="gradient-bg py-20 px-4">
        <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-12 items-center">
            <div>
                <h1 class="text-4xl md:text-5xl font-bold text-white leading-tight mb-6">
                    Profit From Crypto Price Differences With Our AI-Powered Arbitrage Bot
                </h1>
                <p class="text-lg text-gray-300 mb-8">
                    Our advanced algorithm scans multiple exchanges simultaneously to find and execute profitable trades in milliseconds. Join our MLM program and earn from both trading profits and referrals.
                </p>
                <div class="flex flex-wrap gap-4">
                    <button id="cta-btn" class="px-8 py-3 rounded-lg font-medium text-white btn-primary hover:opacity-90 transition">
                        Start Earning Today
                    </button>
                    <button class="px-8 py-3 rounded-lg font-medium text-white bg-gray-800 hover:bg-gray-700 transition">
                        Watch Demo
                    </button>
                </div>
            </div>
            <div>
                <img src="https://placehold.co/800x500" alt="3D rendering of a futuristic crypto trading dashboard showing multiple exchange comparisons and profit calculations" class="rounded-xl shadow-2xl">
            </div>
        </div>
    </section>

    <!-- Bot Features Section -->
    <section class="py-20 px-4" id="bot">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-white mb-4">Bot Features</h2>
                <p class="text-lg text-gray-400 max-w-3xl mx-auto">
                    Unlock the full potential of crypto trading with our advanced bot.
                </p>
            </div>
            <div class="grid md:grid-cols-2 gap-12">
                <div class="card-gradient p-6 rounded-xl border border-gray-800">
                    <h3 class="text-xl font-semibold text-white mb-3">Automated Trading</h3>
                    <p class="text-gray-400">
                        Our bot operates 24/7, executing trades automatically based on market conditions and your preferences.
                    </p>
                </div>
                <div class="card-gradient p-6 rounded-xl border border-gray-800">
                    <h3 class="text-xl font-semibold text-white mb-3">Real-Time Analytics</h3>
                    <p class="text-gray-400">
                        Get insights into market trends and performance metrics to make informed decisions.
                    </p>
                </div>
                <div class="card-gradient p-6 rounded-xl border border-gray-800">
                    <h3 class="text-xl font-semibold text-white mb-3">Risk Management</h3>
                    <p class="text-gray-400">
                        The bot includes built-in risk management features to protect your investments.
                    </p>
                </div>
                <div class="card-gradient p-6 rounded-xl border border-gray-800">
                    <h3 class="text-xl font-semibold text-white mb-3">Bot Fee</h3>
                    <p class="text-gray-400">
                        A one-time fee of <span class="text-green-400 font-bold">$100</span> is required to activate the trading bot.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="py-20 px-4" id="features">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-white mb-4">Why QuantumArb Works</h2>
                <p class="text-lg text-gray-400 max-w-3xl mx-auto">
                    Our proprietary technology gives you an edge in the volatile crypto markets
                </p>
            </div>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="card-gradient p-6 rounded-xl border border-gray-800 hover:border-blue-500 transition">
                    <div class="w-14 h-14 bg-blue-900 rounded-lg flex items-center justify-center mb-4">
                        <img src="https://placehold.co/30x30" alt="Lightning bolt icon representing speed" class="h-6 w-6">
                    </div>
                    <h3 class="text-xl font-semibold text-white mb-3">Lightning Fast Execution</h3>
                    <p class="text-gray-400">
                        Our servers located in exchange data centers execute trades in under 50ms to capture fleeting arbitrage opportunities.
                    </p>
                </div>
                <div class="card-gradient p-6 rounded-xl border border-gray-800 hover:border-purple-500 transition">
                    <div class="w-14 h-14 bg-purple-900 rounded-lg flex items-center justify-center mb-4">
                        <img src="https://placehold.co/30x30" alt="AI brain icon representing artificial intelligence" class="h-6 w-6">
                    </div>
                    <h3 class="text-xl font-semibold text-white mb-3">AI-Powered Analysis</h3>
                    <p class="text-gray-400">
                        Machine learning models predict price movements and optimize trading strategies in real-time.
                    </p>
                </div>
                <div class="card-gradient p-6 rounded-xl border border-gray-800 hover:border-blue-500 transition">
                    <div class="w-14 h-14 bg-blue-900 rounded-lg flex items-center justify-center mb-4">
                        <img src="https://placehold.co/30x30" alt="Shield icon representing security" class="h-6 w-6">
                    </div>
                    <h3 class="text-xl font-semibold text-white mb-3">Risk Management</h3>
                    <p class="text-gray-400">
                        Smart algorithms automatically hedge positions and limit exposure across exchanges.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- How It Works -->
    <section class="py-20 px-4 bg-gray-900" id="how-it-works">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-white mb-4">How QuantumArb Works</h2>
                <p class="text-lg text-gray-400 max-w-3xl mx-auto">
                    Our three-step process for consistent arbitrage profits
                </p>
            </div>
            <div class="grid md:grid-cols-3 gap-12">
                <div class="relative">
                    <div class="absolute -left-2 top-0 h-full w-0.5 bg-gradient-to-b from-blue-500 to-purple-600 md:block hidden"></div>
                    <div class="flex flex-col items-center text-center">
                        <div class="w-16 h-16 rounded-full bg-blue-900 flex items-center justify-center mb-6 border-2 border-blue-500">
                            <span class="text-white font-bold text-xl">1</span>
                        </div>
                        <h3 class="text-xl font-semibold text-white mb-3">Exchange Scanning</h3>
                        <p class="text-gray-400">
                            Our bots continuously monitor 50+ exchanges for price discrepancies across trading pairs.
                        </p>
                    </div>
                </div>
                <div class="relative">
                    <div class="absolute -left-2 top-0 h-full w-0.5 bg-gradient-to-b from-blue-500 to-purple-600 md:block hidden"></div>
                    <div class="flex flex-col items-center text-center">
                        <div class="w-16 h-16 rounded-full bg-purple-900 flex items-center justify-center mb-6 border-2 border-purple-500">
                            <span class="text-white font-bold text-xl">2</span>
                        </div>
                        <h3 class="text-xl font-semibold text-white mb-3">Opportunity Execution</h3>
                        <p class="text-gray-400">
                            When profitable opportunities are found, trades are instantly executed across exchanges.
                        </p>
                    </div>
                </div>
                <div class="relative">
                    <div class="flex flex-col items-center text-center">
                        <div class="w-16 h-16 rounded-full bg-indigo-900 flex items-center justify-center mb-6 border-2 border-indigo-500">
                            <span class="text-white font-bold text-xl">3</span>
                        </div>
                        <h3 class="text-xl font-semibold text-white mb-3">Profit Distribution</h3>
                        <p class="text-gray-400">
                            Profits are calculated, with 70% going to you and 30% allocated to the MLM pool.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- MLM Program -->
    <section class="py-20 px-4" id="mlm">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-white mb-4">Multi-Level Marketing Program</h2>
                <p class="text-lg text-gray-400 max-w-3xl mx-auto">
                    Earn from both your trading profits and your network's activity
                </p>
            </div>
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div>
                    <div class="bg-gray-900 p-6 rounded-xl mb-8 border border-gray-800">
                        <h3 class="text-xl font-semibold text-white mb-4">Compensation Plan</h3>
                        <div class="space-y-4">
                            <div class="flex justify-between">
                                <span class="text-gray-400">Direct Referral</span>
                                <span class="text-purple-400 font-medium">10%</span>
                            </div>
                            <div class="flex justify-between">
                                <span class="text-gray-400">Level 2 (Indirect)</span>
                                <span class="text-blue-400 font-medium">5%</span>
                            </div>
                            <div class="flex justify-between">
                                <span class="text-gray-400">Level 3</span>
                                <span class="text-blue-400 font-medium">3%</span>
                            </div>
                            <div class="flex justify-between">
                                <span class="text-gray-400">Level 4-6</span>
                                <span class="text-blue-400 font-medium">1%</span>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-400 mb-6">
                        Build your network and earn a percentage of your downline's trading profits. The more active your network, the more you earn.
                    </p>
                    <button id="referral-btn" class="px-8 py-3 rounded-lg font-medium text-white btn-primary hover:opacity-90 transition">
                        Get Your Referral Link
                    </button>
                </div>
                <div>
                    <img src="https://placehold.co/600x500" alt="Network visualization showing 6 levels of MLM structure with increasing numbers of nodes at each level" class="rounded-xl">
                </div>
            </div>
        </div>
    </section>

    <!-- Earnings Dashboard Preview -->
    <section class="py-20 px-4 bg-gray-900" id="earnings">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-white mb-4">Real-Time Earnings Dashboard</h2>
                <p class="text-lg text-gray-400 max-w-3xl mx-auto">
                    Track your trading profits and referral earnings in one place
                </p>
            </div>
            <div class="card-gradient rounded-xl p-6 border border-gray-800">
                <div class="grid md:grid-cols-3 gap-6 mb-8">
                    <div class="bg-gray-800 p-4 rounded-lg hover:bg-gray-750 transition">
                        <p class="text-gray-400 text-sm">Today's Profit</p>
                        <p id="today-profit" class="text-2xl font-bold text-green-400">$1,284.62</p>
                    </div>
                    <div class="bg-gray-800 p-4 rounded-lg hover:bg-gray-750 transition">
                        <p class="text-gray-400 text-sm">Referral Earnings</p>
                        <p id="referral-earnings" class="text-2xl font-bold text-purple-400">$862.35</p>
                    </div>
                    <div class="bg-gray-800 p-4 rounded-lg hover:bg-gray-750 transition">
                        <p class="text-gray-400 text-sm">Total Network</p>
                        <p id="network-size" class="text-2xl font-bold text-blue-400">1,248 members</p>
                    </div>
                </div>
                <div class="h-64 bg-gray-800 rounded-lg flex items-center justify-center">
                    <img src="https://placehold.co/800x300" alt="Line chart showing 30-day profit trend with increasing exponential growth curve" class="h-full w-full object-cover rounded-lg">
                </div>
            </div>
        </div>
    </section>

    <!-- Registration CTA -->
    <section class="gradient-bg py-20 px-4">
        <div class="max-w-4xl mx-auto text-center">
            <h2 class="text-3xl md:text-4xl font-bold text-white mb-6">Start Earning With Crypto Arbitrage Today</h2>
            <p class="text-lg text-gray-300 mb-8">
                Join thousands of members already profiting from our platform. No trading experience required - our bots do all the work.
            </p>
            <button id="final-cta" class="px-8 py-3 rounded-lg font-medium text-white btn-primary hover:opacity-90 transition text-lg">
                Create Free Account
            </button>
            <p class="text-gray-400 text-sm mt-4">
                $50 minimum deposit required to activate trading bot
            </p>
        </div>
    </section>

    <!-- Features -->
    <section class="py-20 px-4">
        <div class="max-w-7xl mx-auto">
            <div class="grid md:grid-cols-2 gap-12">
                <div>
                    <h2 class="text-3xl font-bold text-white mb-6">Secure & Trusted Platform</h2>
                    <div class="space-y-6">
                        <div class="flex items-start gap-4">
                            <div class="flex-shrink-0 mt-1">
                                <img src="https://placehold.co/24x24" alt="Checkmark icon indicating security feature" class="h-6 w-6">
                            </div>
                            <div>
                                <h3 class="text-lg font-semibold text-white mb-1">Non-Custodial Trading</h3>
                                <p class="text-gray-400">
                                    Your funds stay in your exchange accounts. We never take custody of user funds.
                                </p>
                            </div>
                        </div>
                        <div class="flex items-start gap-4">
                            <div class="flex-shrink-0 mt-1">
                                <img src="https
