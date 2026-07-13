<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>石鎚黒茶 - 日本の貴重な後発酵茶</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+JP:wght@400;700&family=Zen+Kaku+Gothic+New:wght@400;500;700&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        tea: {
                            light: '#E6E2D3', // 薄い茶色
                            DEFAULT: '#A68A64', // 基本の茶色
                            dark: '#5C4A38',  // 濃い茶色
                            black: '#2C231A'  // 黒茶をイメージした黒
                        },
                        accent: {
                            green: '#748B6F', // 葉をイメージした緑
                            red: '#B85D43'    // 差し色の赤茶
                        }
                    },
                    fontFamily: {
                        serif: ['"Noto Serif JP"', 'serif'],
                        sans: ['"Zen Kaku Gothic New"', 'sans-serif'],
                    },
                    backgroundImage: {
                        'washi': "url('data:image/svg+xml,%3Csvg width=\"100\" height=\"100\" xmlns=\"http://www.w3.org/2000/svg\"%3E%3Cfilter id=\"n\"%3E%3CfeTurbulence type=\"fractalNoise\" baseFrequency=\"0.5\" numOctaves=\"3\" stitchTiles=\"stitch\"/%3E%3C/filter%3E%3Crect width=\"100\" height=\"100\" fill=\"%23fdfbf7\"/%3E%3Crect width=\"100\" height=\"100\" filter=\"url(%23n)\" opacity=\"0.2\"/%3E%3C/svg%3E')"
                    }
                }
            }
        }
    </script>
    <style>
        /* カスタムアニメーションや微調整用のCSS */
        body {
            background-image: theme('backgroundImage.washi');
            background-attachment: fixed;
        }
        .text-vertical {
            writing-mode: vertical-rl;
            text-orientation: mixed;
        }
        .fade-in {
            animation: fadeIn 1.5s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .section-divider {
            height: 2px;
            background: linear-gradient(to right, transparent, theme('colors.tea.DEFAULT'), transparent);
            margin: 3rem 0;
        }
        /* 画像のプレースホルダー用のスタイル */
        .img-placeholder {
            background-color: theme('colors.tea.light');
            display: flex;
            align-items: center;
            justify-content: center;
            color: theme('colors.tea.dark');
            font-size: 1.2rem;
            font-weight: bold;
        }
    </style>
</head>
<body class="font-sans text-tea-black antialiased leading-relaxed">

    <!-- ヒーローセクション（大見出し） -->
    <header class="relative bg-tea-dark text-white overflow-hidden shadow-lg">
        <div class="absolute inset-0 opacity-40">
            <!-- 背景画像（プレースホルダーを使用） -->
            <img src="https://placehold.co/1920x1080/5C4A38/ffffff?text=Ishizuchi+Mountain" alt="石鎚山系" class="w-full h-full object-cover object-center" onerror="this.style.display='none'">
        </div>
        <div class="relative z-10 max-w-5xl mx-auto px-4 py-24 md:py-32 flex flex-col items-center justify-center text-center fade-in">
            <p class="text-tea-light text-lg md:text-xl mb-4 font-serif tracking-widest">愛媛県西条市 幻の特産品</p>
            <h1 class="text-5xl md:text-7xl font-serif font-bold mb-6 tracking-wider border-b-2 border-accent-red pb-4">石鎚黒茶</h1>
            <p class="text-xl md:text-2xl font-serif text-tea-light max-w-2xl mx-auto leading-loose">
                二度の発酵が織りなす、<br class="md:hidden">黄金色のしずくと酸味の調和。
            </p>
        </div>
        <!-- 装飾的な波形 -->
        <div class="absolute bottom-0 w-full overflow-hidden leading-none z-10">
            <svg class="relative block w-full h-12 md:h-16" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
                <path d="M321.39,56.44c58-10.79,114.16-30.13,172-41.86,82.39-16.72,168.19-17.73,250.45-.39C823.78,31,906.67,72,985.66,92.83c70.05,18.48,146.53,26.09,214.34,3V120H0V95.8C59.71,118.08,130.83,121.57,189.9,109.28Z" fill="#fdfbf7"></path>
            </svg>
        </div>
    </header>

    <main class="max-w-4xl mx-auto px-4 py-12 md:py-20">
        
        <!-- 導入文 -->
        <section class="mb-16 text-center">
            <h2 class="text-3xl font-serif font-bold text-tea-dark mb-6">石鎚黒茶とは</h2>
            <p class="text-lg text-tea-dark md:px-12 text-left md:text-center leading-loose">
                西日本最高峰、石鎚山の麓に位置する愛媛県西条市の一部地域でのみ作られている、非常に珍しいお茶です。<br>
                日本に数種類しかないとされる「後発酵茶（あとに発酵させるお茶）」の一つであり、その独特の製法から「幻のお茶」とも呼ばれています。
            </p>
        </section>

        <div class="section-divider"></div>

        <section class="mb-16">
            <h2 class="text-3xl font-serif font-bold text-tea-dark text-center mb-12">
                <span class="inline-block border-b-4 border-accent-green pb-2">石鎚黒茶 3つの魅力・特徴</span>
            </h2>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- 特徴1 -->
                <div class="bg-white rounded-xl shadow-md overflow-hidden transform transition duration-300 hover:scale-105 border border-tea-light">
                    <div class="h-48 img-placeholder w-full object-cover">
                        <img src="https://placehold.co/400x300/748B6F/ffffff?text=Double+Fermentation" alt="二段発酵" class="w-full h-full object-cover" onerror="this.style.display='none'">
                    </div>
                    <div class="p-6">
                        <div class="flex items-center mb-4">
                            <span class="bg-accent-red text-white font-bold rounded-full w-8 h-8 flex items-center justify-center mr-3">1</span>
                            <h3 class="text-xl font-bold text-tea-dark">世界でも珍しい「二段発酵」</h3>
                        </div>
                        <p class="text-sm text-gray-700 leading-relaxed">
                            石鎚黒茶の最大の特徴は、糸状菌（カビの一種）による好気発酵と、乳酸菌による嫌気発酵の<strong class="text-accent-red">二度の発酵工程</strong>を経る「二段発酵」です。この複雑な製法が、他に類を見ない独特の風味を生み出します。
                        </p>
                    </div>
                </div>

                <!-- 特徴2 -->
                <div class="bg-white rounded-xl shadow-md overflow-hidden transform transition duration-300 hover:scale-105 border border-tea-light">
                    <div class="h-48 img-placeholder w-full object-cover">
                        <img src="https://placehold.co/400x300/A68A64/ffffff?text=Golden+Color+%26+Sour+Taste" alt="黄金色と酸味" class="w-full h-full object-cover" onerror="this.style.display='none'">
                    </div>
                    <div class="p-6">
                        <div class="flex items-center mb-4">
                            <span class="bg-accent-red text-white font-bold rounded-full w-8 h-8 flex items-center justify-center mr-3">2</span>
                            <h3 class="text-xl font-bold text-tea-dark">爽やかな酸味と黄金色の水色</h3>
                        </div>
                        <p class="text-sm text-gray-700 leading-relaxed">
                            お茶を淹れると、美しい黄金色（水色：すいしょく）になります。乳酸発酵による<strong class="text-accent-red">フルーティーで爽やかな酸味</strong>と、まろやかな甘みが特徴で、一般的な緑茶とは全く異なる味わいを楽しめます。
                        </p>
                    </div>
                </div>

                <!-- 特徴3 -->
                <div class="bg-white rounded-xl shadow-md overflow-hidden transform transition duration-300 hover:scale-105 border border-tea-light">
                    <div class="h-48 img-placeholder w-full object-cover">
                        <img src="https://placehold.co/400x300/5C4A38/ffffff?text=Cultural+Heritage" alt="文化的遺産" class="w-full h-full object-cover" onerror="this.style.display='none'">
                    </div>
                    <div class="p-6">
                        <div class="flex items-center mb-4">
                            <span class="bg-accent-red text-white font-bold rounded-full w-8 h-8 flex items-center justify-center mr-3">3</span>
                            <h3 class="text-xl font-bold text-tea-dark">国指定の無形民俗文化財</h3>
                        </div>
                        <p class="text-sm text-gray-700 leading-relaxed">
                            一時は生産者が激減し存続が危ぶまれましたが、地域の人々の努力により伝統製法が受け継がれています。2023年には、その製法が<strong class="text-accent-red">国の重要無形民俗文化財</strong>に指定され、歴史的・文化的な価値も高く評価されています。
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <div class="section-divider"></div>

        <section class="mb-16">
            <h2 class="text-3xl font-serif font-bold text-tea-dark text-center mb-12">
                <span class="inline-block border-b-4 border-tea-DEFAULT pb-2">おすすめの飲み方・活用法</span>
            </h2>

            <div class="space-y-8">
                <!-- 活用法1 -->
                <div class="flex flex-col md:flex-row bg-white rounded-2xl shadow-sm border border-tea-light overflow-hidden">
                    <div class="md:w-1/3 bg-tea-light p-6 flex flex-col justify-center items-center text-center border-b md:border-b-0 md:border-r border-white">
                        <div class="w-16 h-16 bg-white rounded-full flex items-center justify-center mb-4 shadow-sm">
                            <svg class="w-8 h-8 text-tea-dark" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                        </div>
                        <h3 class="text-xl font-bold text-tea-dark">1. ホットでじっくり味わう</h3>
                    </div>
                    <div class="md:w-2/3 p-6 md:p-8 flex items-center">
                        <div>
                            <h4 class="text-lg font-bold mb-2 text-tea-dark">基本の美味しい淹れ方</h4>
                            <p class="text-gray-700 leading-relaxed">
                                急須に茶葉（約3〜5g）を入れ、熱湯を注ぎます。<br>
                                抽出時間は長め（3〜5分）がおすすめ。じっくり蒸らすことで、石鎚黒茶特有の酸味と香りが引き立ちます。食事のお供はもちろん、脂っこい食事の後に飲むと口の中がさっぱりします。
                            </p>
                        </div>
                    </div>
                </div>

                <!-- 活用法2 -->
                <div class="flex flex-col md:flex-row-reverse bg-white rounded-2xl shadow-sm border border-tea-light overflow-hidden">
                    <div class="md:w-1/3 bg-accent-green bg-opacity-20 p-6 flex flex-col justify-center items-center text-center border-b md:border-b-0 md:border-l border-white">
                        <div class="w-16 h-16 bg-white rounded-full flex items-center justify-center mb-4 shadow-sm">
                            <svg class="w-8 h-8 text-accent-green" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z"></path></svg>
                        </div>
                        <h3 class="text-xl font-bold text-tea-dark">2. 冷やしてアイスティーに</h3>
                    </div>
                    <div class="md:w-2/3 p-6 md:p-8 flex items-center">
                        <div>
                            <h4 class="text-lg font-bold mb-2 text-tea-dark">夏場にぴったりの爽やかさ</h4>
                            <p class="text-gray-700 leading-relaxed">
                                濃いめに煮出した石鎚黒茶を、たっぷりの氷を入れたグラスに注いで急冷します。または、水出しポットで一晩かけてゆっくり抽出するのもおすすめです。<br>
                                冷やすことで酸味がよりシャープに感じられ、スポーツ後や暑い夏の日にお茶代わりにゴクゴク飲める爽やかなドリンクになります。
                            </p>
                        </div>
                    </div>
                </div>

                <!-- 活用法3 -->
                <div class="flex flex-col md:flex-row bg-white rounded-2xl shadow-sm border border-tea-light overflow-hidden">
                    <div class="md:w-1/3 bg-accent-red bg-opacity-10 p-6 flex flex-col justify-center items-center text-center border-b md:border-b-0 md:border-r border-white">
                        <div class="w-16 h-16 bg-white rounded-full flex items-center justify-center mb-4 shadow-sm">
                            <svg class="w-8 h-8 text-accent-red" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 15.546c-.523 0-1.046.151-1.5.454a2.704 2.704 0 01-3 0 2.704 2.704 0 00-3 0 2.704 2.704 0 01-3 0 2.704 2.704 0 00-3 0 2.704 2.704 0 01-3 0 2.701 2.701 0 00-1.5-.454M9 6v2m3-2v2m3-2v2M9 3h.01M12 3h.01M15 3h.01M21 21v-5a2 2 0 00-2-2H5a2 2 0 00-2 2v5h18z"></path></svg>
                        </div>
                        <h3 class="text-xl font-bold text-tea-dark">3. 料理やスイーツの隠し味に</h3>
                    </div>
                    <div class="md:w-2/3 p-6 md:p-8 flex items-center">
                        <div>
                            <h4 class="text-lg font-bold mb-2 text-tea-dark">発酵茶ならではのコクをプラス</h4>
                            <p class="text-gray-700 leading-relaxed">
                                飲むだけでなく、料理の調味料としても活用できます。茶葉を細かく挽いて塩と混ぜた「黒茶塩」は、天ぷらや肉料理によく合います。<br>
                                また、抽出したお茶をご飯を炊く際の水代わりに使った「茶飯」や、ゼリーやパウンドケーキなどのスイーツの生地に練り込むと、独特の風味と酸味がアクセントになります。
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <section class="mt-20 bg-tea-dark text-white rounded-3xl p-8 md:p-12 text-center shadow-xl relative overflow-hidden">
            <!-- 背景の装飾円 -->
            <div class="absolute -top-16 -right-16 w-32 h-32 bg-accent-red rounded-full opacity-20"></div>
            <div class="absolute -bottom-16 -left-16 w-48 h-48 bg-tea-DEFAULT rounded-full opacity-20"></div>
            
            <div class="relative z-10">
                <h2 class="text-2xl md:text-3xl font-serif font-bold mb-6">石鎚黒茶を味わってみませんか？</h2>
                <p class="mb-8 text-tea-light max-w-2xl mx-auto">
                    伝統製法で作られる石鎚黒茶は生産量が限られていますが、西条市内の道の駅や特産品店、一部のオンラインショップでお求めいただけます。
                </p>
                <a href="#" class="inline-block bg-white text-tea-dark font-bold py-3 px-8 rounded-full shadow-lg hover:bg-tea-light transition duration-300 transform hover:-translate-y-1">
                    販売店情報を確認する
                </a>
                <p class="text-xs text-tea-light mt-4 opacity-75">※リンクはダミーです</p>
            </div>
        </section>

    </main>

    <footer class="bg-tea-black text-tea-light py-8 text-center mt-12 border-t-4 border-tea-DEFAULT">
        <p class="text-sm">
            &copy; 2026 石鎚黒茶ファンサイト. All rights reserved.<br>
            <span class="text-xs opacity-50 mt-2 block">※このサイトはサンプルとして作成されたものです。</span>
        </p>
    </footer>

</body>
</html>
