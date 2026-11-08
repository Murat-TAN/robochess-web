# Robotik Satranç Spor Kulübü (www.robochess.org) - Web Sitesi

Bu proje, **Robotik Satranç Spor Kulübü** için sıfırdan tasarlanmış modern, hızlı, yüksek performanslı, canlı renk paletine sahip, SEO optimize ve mobil uyumlu resmi web sitesidir.

---

## 📁 Proje Dosya Yapısı

* [index.html](file:///C:/Users/Murat%20TAN/.gemini/antigravity/scratch/robochess-web/index.html): Web sitesinin ana sayfası, tüm canlı bölümleri, fotoğraflı galerisi, interaktif satranç bulmacası, WhatsApp entegreli ön kayıt formu ve özel satranç atı (♞) imleci.
* [robots.txt](file:///C:/Users/Murat%20TAN/.gemini/antigravity/scratch/robochess-web/robots.txt): Google ve diğer arama motoru botları için tarama talimatları.
* [sitemap.xml](file:///C:/Users/Murat%20TAN/.gemini/antigravity/scratch/robochess-web/sitemap.xml): Arama motorları için site haritası.
* [404.html](file:///C:/Users/Murat%20TAN/.gemini/antigravity/scratch/robochess-web/404.html): Markaya özel tasarlanmış hatalı hamle / sayfa bulunamadı sayfası.
* [vercel.json](file:///C:/Users/Murat%20TAN/.gemini/antigravity/scratch/robochess-web/vercel.json): Vercel için güvenlik başlıkları ve yapılandırma.
* [_redirects](file:///C:/Users/Murat%20TAN/.gemini/antigravity/scratch/robochess-web/_redirects): Netlify ve Cloudflare Pages için yönlendirme kuralları.
* [.htaccess](file:///C:/Users/Murat%20TAN/.gemini/antigravity/scratch/robochess-web/.htaccess): cPanel ve Apache hosting için HTTPS zorunluluğu ve SEO yönlendirmeleri.
* [robochess-web-deployment.zip](file:///C:/Users/Murat%20TAN/.gemini/antigravity/scratch/robochess-web-deployment.zip): Tüm dosyaların hazır sıkıştırılmış paketi.

---

## 🌐 `www.robochess.org` İçin Yayına Alma Yöntemleri

### Yöntem 1: Netlify ile 3 Dakikada Ücretsiz Yayın (Önerilen)
1. [app.netlify.com/drop](https://app.netlify.com/drop) adresini açın.
2. `robochess-web` klasörünü (veya içindeki dosyaları) tarayıcıdaki kutucuğa sürükleyip bırakın.
3. Site anında yayına girer.
4. **Domain Management** sekmesine tıklayıp `www.robochess.org` alan adınızı ekleyin.
5. Alan adı kayıt firmanızdaki (GoDaddy, Natro, Turhost vb.) DNS ayarlarına Netlify'ın verdiği CNAME / A kaydını girin. Ücretsiz SSL sertifikası otomatik kurulur.

### Yöntem 2: Vercel ile Yayına Alma
1. [vercel.com](https://vercel.com) üzerinde ücretsiz hesap açın.
2. `Add New Project` diyerek klasörü yükleyin veya GitHub ile bağlayın.
3. **Settings > Domains** kısmından `www.robochess.org` ekleyin.

### Yöntem 3: cPanel / Klasik Web Hosting (Turhost, Natro, İsimTescil vb.)
1. Hosting cPanel'inize giriş yapın.
2. **Dosya Yöneticisi (File Manager)** > `public_html` klasörüne girin.
3. Eski dosyaları temizleyip `robochess-web-deployment.zip` dosyasını yükleyin ve **Extract (Çıkar)** deyin.
4. `index.html`, `.htaccess` ve diğer dosyalar doğrudan `public_html` altında olmalıdır.
