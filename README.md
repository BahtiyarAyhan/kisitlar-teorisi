<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kısıtlar Teorisi | Bahtiyar Ayhan</title>
    <style>
        :root { --primary: #2c3e50; --accent: #e67e22; --white: #ffffff; }
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background: #f4f7f6; color: var(--primary); margin: 0; line-height: 1.6; }
        
        /* Üst Bilgi Alanı */
        .hero { 
            background: linear-gradient(rgba(44, 62, 80, 0.85), rgba(44, 62, 80, 0.85)), 
                        url('https://images.unsplash.com/photo-1581091226825-a6a2a5aee158?auto=format&fit=crop&w=1200&q=80');
            background-size: cover;
            background-position: center;
            color: var(--white);
            padding: 5rem 1rem;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0,0,0,0.2);
        }
        
        .hero h1 { font-size: 2.8rem; margin: 0; text-transform: uppercase; letter-spacing: 3px; }
        .hero p { font-size: 1.3rem; opacity: 0.9; margin-top: 15px; font-weight: 300; }

        .container { padding: 2rem; max-width: 900px; margin: auto; }
        h2 { text-align: center; color: var(--primary); margin-bottom: 2rem; border-bottom: 2px solid var(--accent); display: inline-block; width: 100%; padding-bottom: 10px; }
        
        .card { background: var(--white); padding: 1.8rem; margin: 1.5rem 0; border-left: 10px solid var(--accent); border-radius: 12px; box-shadow: 0 6px 25px rgba(0,0,0,0.07); transition: 0.3s; }
        .card:hover { transform: translateY(-5px); box-shadow: 0 10px 30px rgba(0,0,0,0.1); }
        h3 { color: var(--accent); margin-top: 0; font-size: 1.5rem; }
        
        /* İletişim Butonu */
        .contact-btn {
            display: inline-block;
            background: var(--accent);
            color: white;
            padding: 12px 30px;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            margin-top: 20px;
            transition: 0.3s;
        }
        .contact-btn:hover { background: #d35400; transform: scale(1.05); }

        .footer { background: var(--primary); color: var(--white); padding: 3rem 1rem; text-align: center; margin-top: 4rem; }
        @media (max-width: 600px) { .hero h1 { font-size: 2rem; } }
    </style>
</head>
<body>
    <header class="hero">
        <h1>BAHTİYAR AYHAN</h1>
        <p>Stratejik Üretim Yönetimi & Kısıtlar Teorisi Uzmanı</p>
    </header>

    <div class="container">
        <h2>Üretimde Verimlilik ve Kısıtlar Yönetimi</h2>
        
        <div class="card"><h3>1. Darboğazı Tespit Et</h3><p>Üretim akışını sınırlayan en zayıf halkayı belirleyin. Unutmayın, sistemin gücü en zayıf halkası kadardır.</p></div>
        <div class="card"><h3>2. Kısıtı Sömür</h3><p>Darboğaz olan kaynağın (makine veya personel) kapasitesini %100 kullanın. O nokta asla boş durmamalı.</p></div>
        <div class="card"><h3>3. Süreci Senkronize Et</h3><p>Darboğaz dışındaki tüm süreçlerin hızını kısıtın hızına göre ayarlayın. Gereksiz stok biriktirmeyin.</p></div>
        <div class="card"><h3>4. Kapasiteyi Artır</h3><p>Eğer kısıt hala sistemi yavaşlatıyorsa, o bölgeye ek yatırım veya iş gücü sağlayarak kapasiteyi genişletin.</p></div>
        <div class="card"><h3>5. Atalete Teslim Olma</h3><p>Bir kısıt çözüldüğünde yeni bir kısıt doğacaktır. Süreci en baştan başlatarak sürekli iyileştirmeyi sağlayın.</p></div>
    </div>

    <footer class="footer">
        <h3>Profesyonel Çözümler İçin</h3>
        <p>Üretim hatlarınızdaki verimlilik açıklarını birlikte kapatalım.</p>
        <a href="mailto:info@bahtiyarayhan.com" class="contact-btn">Bana E-posta Gönder</a>
        <p style="margin-top: 30px; opacity: 0.6; font-size: 0.9rem;">&copy; 2026 Bahtiyar Ayhan. Tüm Hakları Saklıdır.</p>
    </footer>
</body>
</html>
