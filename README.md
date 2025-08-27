<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>株式会社 獄臨道</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8f9fa;
        }
        .text-hero-gradient {
            background: linear-gradient(135deg, #1f2937 0%, #374151 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .bg-hero-pattern {
            background-image: url('https://placehold.co/1920x1080/e5e7eb/6b7280?text=Financial+Building');
            background-size: cover;
            background-position: center;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Header -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <div class="flex items-center">
                <a href="#" class="text-2xl font-bold text-gray-900">株式会社 獄臨道</a>
            </div>
            <nav class="hidden md:flex items-center space-x-8 text-sm font-medium">
                <a href="#about" class="text-gray-600 hover:text-gray-900 transition duration-300">会社概要</a>
                <a href="#services" class="text-gray-600 hover:text-gray-900 transition duration-300">サービス</a>
                <a href="#voice" class="text-gray-600 hover:text-gray-900 transition duration-300">お客様の声</a>
                <a href="#contact" class="px-5 py-2 rounded-full bg-indigo-600 text-white hover:bg-indigo-700 transition duration-300 shadow-lg">お問い合わせ</a>
            </nav>
            <!-- Mobile Menu Button -->
            <button id="mobile-menu-button" class="md:hidden text-gray-600 hover:text-gray-900 focus:outline-none focus:text-gray-900 transition duration-300">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
            </button>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white shadow-md">
            <nav class="flex flex-col p-4 space-y-2 text-sm font-medium">
                <a href="#about" class="block py-2 px-4 text-gray-600 hover:bg-gray-100 rounded-lg">会社概要</a>
                <a href="#services" class="block py-2 px-4 text-gray-600 hover:bg-gray-100 rounded-lg">サービス</a>
                <a href="#voice" class="block py-2 px-4 text-gray-600 hover:bg-gray-100 rounded-lg">お客様の声</a>
                <a href="#contact" class="block py-2 px-4 text-white bg-indigo-600 rounded-lg hover:bg-indigo-700">お問い合わせ</a>
            </nav>
        </div>
    </header>

    <main>
        <!-- Hero Section -->
        <section class="bg-hero-pattern py-24 md:py-48 bg-gray-900 text-white">
            <div class="container mx-auto px-6 text-center">
                <h1 class="text-4xl md:text-6xl font-bold mb-4 leading-tight shadow-text">あなたの未来を、ともに築く。</h1>
                <p class="text-lg md:text-xl mb-8">お客様一人ひとりの目標に寄り添い、最適な金融ソリューションを提供します。</p>
                <a href="#contact" class="px-8 py-3 bg-indigo-600 text-white text-lg font-semibold rounded-full hover:bg-indigo-700 transition duration-300 shadow-xl">ご相談はこちら</a>
            </div>
        </section>

        <!-- About Section -->
        <section id="about" class="py-20 bg-white">
            <div class="container mx-auto px-6">
                <h2 class="text-3xl font-bold text-center mb-12 text-hero-gradient">会社概要</h2>
                <div class="flex flex-col md:flex-row items-center md:space-x-12">
                    <div class="md:w-1/2 mb-8 md:mb-0">
                        <img src="https://placehold.co/800x600/e5e7eb/6b7280?text=About+Us" alt="会社概要のイメージ" class="rounded-2xl shadow-lg">
                    </div>
                    <div class="md:w-1/2">
                        <p class="text-lg leading-relaxed mb-6">
                            株式会社獄臨道は、お客様の人生の節目において、最適な金融ソリューションを提供することを使命としています。
                            専門知識を持つスタッフが、お客様一人ひとりの状況を丁寧にヒアリングし、事業資金の融資から資産運用、
                            将来を見据えたコンサルティングまで、幅広いニーズに対応いたします。
                        </p>
                        <p class="text-lg leading-relaxed">
                            私たちは単なる金融サービス提供者ではなく、お客様の成功をともに喜ぶパートナーでありたいと願っています。
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Services Section -->
        <section id="services" class="py-20 bg-gray-50">
            <div class="container mx-auto px-6">
                <h2 class="text-3xl font-bold text-center mb-12 text-hero-gradient">サービス</h2>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <!-- Service 1: 融資 -->
                    <div class="bg-white p-8 rounded-2xl shadow-lg hover:shadow-2xl transition duration-300 transform hover:-translate-y-2">
                        <div class="text-indigo-600 mb-4">
                            <svg class="w-12 h-12" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8v-2m0 12v-2"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8V6m0 12v-2m-6 0h12a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v12a2 2 0 002 2z"></path></svg>
                        </div>
                        <h3 class="text-xl font-semibold mb-3">融資サービス</h3>
                        <p class="text-gray-600 leading-relaxed">
                            事業資金から個人のライフプランまで、多様なニーズに対応する柔軟な融資プランをご提案します。迅速な審査と丁寧なサポートが強みです。
                        </p>
                    </div>

                    <!-- Service 2: 資産運用 -->
                    <div class="bg-white p-8 rounded-2xl shadow-lg hover:shadow-2xl transition duration-300 transform hover:-translate-y-2">
                        <div class="text-indigo-600 mb-4">
                            <svg class="w-12 h-12" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                        </div>
                        <h3 class="text-xl font-semibold mb-3">資産運用サービス</h3>
                        <p class="text-gray-600 leading-relaxed">
                            お客様の目標やリスク許容度に基づき、最適なポートフォリオを構築。長期的な視点で資産を育てるお手伝いをします。
                        </p>
                    </div>

                    <!-- Service 3: コンサルティング -->
                    <div class="bg-white p-8 rounded-2xl shadow-lg hover:shadow-2xl transition duration-300 transform hover:-translate-y-2">
                        <div class="text-indigo-600 mb-4">
                            <svg class="w-12 h-12" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0h.01M15 19v-6a2 2 0 00-2-2h-2a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0h.01M21 19v-6a2 2 0 00-2-2h-2a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0h.01"></path></svg>
                        </div>
                        <h3 class="text-xl font-semibold mb-3">経営コンサルティング</h3>
                        <p class="text-gray-600 leading-relaxed">
                            財務改善、事業承継、M&Aなど、経営課題の解決をサポート。経験豊富な専門家が、お客様の事業成長を力強く支援します。
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Voice Section -->
        <section id="voice" class="py-20 bg-white">
            <div class="container mx-auto px-6">
                <h2 class="text-3xl font-bold text-center mb-12 text-hero-gradient">お客様の声</h2>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <!-- Voice 1 -->
                    <div class="bg-gray-50 p-8 rounded-2xl shadow-inner">
                        <p class="italic text-gray-700 mb-4">
                            「事業拡大のための資金調達に悩んでいましたが、獄臨道様は非常に親身になって相談に乗ってくれました。
                            スピーディーな対応で、無事に融資を受けることができ、事業を軌道に乗せることができました。」
                        </p>
                        <p class="text-right font-medium text-gray-800">- 〇〇様（飲食店経営）</p>
                    </div>
                    <!-- Voice 2 -->
                    <div class="bg-gray-50 p-8 rounded-2xl shadow-inner">
                        <p class="italic text-gray-700 mb-4">
                            「将来の資産形成について漠然とした不安がありましたが、こちらの状況に合わせて丁寧にプランを立てていただき、
                            安心して運用を始めることができました。今後も長くお付き合いしていきたいです。」
                        </p>
                        <p class="text-right font-medium text-gray-800">- 〇〇様（会社員）</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- CTA/Contact Section -->
        <section id="contact" class="py-20 bg-indigo-600 text-white">
            <div class="container mx-auto px-6 text-center">
                <h2 class="text-3xl font-bold mb-4">まずはお気軽にご相談ください</h2>
                <p class="text-lg mb-8">お客様の課題や目標に合わせた最適なソリューションを、専門家がご提案します。</p>
                <a href="#" class="px-8 py-3 bg-white text-indigo-600 text-lg font-semibold rounded-full hover:bg-gray-200 transition duration-300 shadow-xl">お問い合わせフォームへ</a>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-900 text-gray-400 py-12">
        <div class="container mx-auto px-6">
            <div class="flex flex-col md:flex-row justify-between items-center mb-8 space-y-4 md:space-y-0">
                <div class="text-center md:text-left">
                    <h4 class="text-lg font-bold text-white mb-2">株式会社 獄臨道</h4>
                    <p class="text-sm">〒100-0000 東京都千代田区〇〇</p>
                    <p class="text-sm">TEL: 03-XXXX-XXXX</p>
                    <p class="text-sm">貸金業登録番号: 東京都知事(1)第XXXXX号</p>
                </div>
                <nav class="flex space-x-6 text-sm">
                    <a href="#about" class="hover:text-white transition duration-300">会社概要</a>
                    <a href="#services" class="hover:text-white transition duration-300">サービス</a>
                    <a href="#voice" class="hover:text-white transition duration-300">お客様の声</a>
                    <a href="#contact" class="hover:text-white transition duration-300">お問い合わせ</a>
                </nav>
            </div>
            <hr class="border-gray-700 my-8">
            <p class="text-center text-sm">© 2024 株式会社 獄臨道. All Rights Reserved.</p>
        </div>
    </footer>

    <script>
        // Mobile menu functionality
        document.getElementById('mobile-menu-button').addEventListener('click', function() {
            const mobileMenu = document.getElementById('mobile-menu');
            mobileMenu.classList.toggle('hidden');
        });

        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anch
        or => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
