# cennetiletisim
echo "# cennetiletisim" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/mevlutmercan42-crypto/cennetiletisim.git
git push -u origin main
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CNETMOBIL CMR Klonu</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body { background-color: #0d1117; color: white; }
        .sidebar { background-color: #0b0e14; }
        .card { background-color: #161b22; border-radius: 1.5rem; }
        .gradient-banner {
            background: linear-gradient(90deg, #1e3a8a 0%, #3b82f6 100%);
            border-radius: 2rem;
        }
    </style>
</head>
<body class="flex h-screen overflow-hidden">

    <aside class="sidebar w-64 flex-shrink-0 flex flex-col border-r border-gray-800">
        <div class="p-6">
            <div class="flex items-center space-x-2 text-blue-500 font-bold text-xl">
                <div class="bg-blue-600 text-white p-2 rounded-lg"><i class="fas fa-mobile-alt"></i></div>
                <span>CNETMOBIL <span class="text-gray-400 text-sm">CMR</span></span>
            </div>
        </div>

        <nav class="flex-1 px-4 space-y-2 overflow-y-auto">
            <p class="text-xs text-gray-500 font-semibold uppercase px-2 mb-2">Ana Modüller</p>
            <a href="#" class="flex items-center space-x-3 bg-blue-900/30 text-blue-400 p-3 rounded-xl border border-blue-500/30">
                <i class="fas fa-home"></i> <span>Ana Sayfa</span>
            </a>
            <a href="#" class="flex items-center space-x-3 text-gray-400 p-3 hover:bg-gray-800 rounded-xl transition">
                <i class="fas fa-shopping-cart"></i> <span>Cihaz Alım</span>
            </a>
            <a href="#" class="flex items-center space-x-3 text-gray-400 p-3 hover:bg-gray-800 rounded-xl transition">
                <i class="fas fa-tools"></i> <span>Teknik Servis</span>
            </a>

            <p class="text-xs text-gray-500 font-semibold uppercase px-2 mt-6 mb-2">Fiyat Listeleri</p>
            <a href="#" class="flex items-center space-x-3 text-gray-400 p-3 hover:bg-gray-800 rounded-xl transition">
                <i class="fas fa-plus"></i> <span>Cep + Tablet</span>
            </a>
            <a href="#" class="flex items-center space-x-3 text-gray-400 p-3 hover:bg-gray-800 rounded-xl transition">
                <i class="fas fa-list"></i> <span>YNA List</span>
            </a>
        </nav>

        <div class="p-4">
            <button class="w-full bg-emerald-500 hover:bg-emerald-600 text-white font-bold py-3 rounded-xl flex items-center justify-center space-x-2">
                <i class="fas fa-calculator"></i> <span>TAKSİT HESAPLA</span>
            </button>
        </div>
    </aside>

    <main class="flex-1 overflow-y-auto p-8">
        
        <div class="gradient-banner p-10 relative overflow-hidden mb-8 shadow-2xl">
            <div class="relative z-10">
                <h1 class="text-4xl font-black italic mb-2">Hoş Geldiniz, <span class="text-blue-200">Hayırlı İşler!</span></h1>
                <p class="text-blue-100 opacity-80 uppercase tracking-widest text-sm">CMR MERKEZ - CMR PERSONEL TERMİNALİ</p>
            </div>
            <button class="absolute right-10 top-1/2 -translate-y-1/2 bg-blue-600 hover:bg-blue-700 px-6 py-3 rounded-full font-bold flex items-center space-x-3 transition transform hover:scale-105">
                <span>CİHAZ ALIMA BAŞLA</span>
                <i class="fas fa-chevron-right"></i>
            </button>
            <span class="absolute right-[-20px] bottom-[-40px] text-[150px] font-black opacity-10 select-none">CMR</span>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div class="card p-8 min-h-[300px] border border-gray-800">
                <div class="flex items-center space-x-3 mb-6">
                    <div class="bg-purple-900/30 p-2 rounded-lg text-purple-400"><i class="fas fa-bullhorn"></i></div>
                    <h2 class="text-xl font-bold italic uppercase">Güncel Duyurular</h2>
                </div>
                <p class="text-gray-400">Şu an için aktif bir mağaza duyurusu bulunmamaktadır.</p>
            </div>

            <div class="card p-8 min-h-[300px] border border-gray-800 relative overflow-hidden">
                <div class="flex items-center space-x-3 mb-6">
                    <div class="bg-orange-900/30 p-2 rounded-lg text-orange-400"><i class="fas fa-fire"></i></div>
                    <h2 class="text-xl font-bold italic uppercase">Aktif Kampanyalar</h2>
                </div>
                
                <div class="border border-orange-500/20 bg-orange-500/5 p-6 rounded-2xl border-dashed flex items-center justify-center">
                    <p class="text-orange-500 font-black text-2xl opacity-80 uppercase italic tracking-tighter">
                        🔥 GÜNCEL KAMPANYA BULUNMAMAKTADIR
                    </p>
                </div>
            </div>
        </div>

    </main>
</body>
</html>
