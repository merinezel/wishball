KEHANET KÜRESİ — YAYIN PAKETİ

1) Yayınlama (Cloudflare Pages / Netlify / GitHub Pages)
   - Bu klasörün içeriğini olduğu gibi yükle (index.html kökte olmalı). HTTPS şart.
   - Cloudflare Pages: Workers & Pages > Create > Pages > "Upload assets".
   - Netlify: app.netlify.com/drop sayfasına klasörü sürükle.
   - Kendi alan adını projeye bağla (AdSense için şart).

2) AdSense
   - adsense.google.com'da siteni (alan adını) ekle, onay bekle.
   - Onaydan sonra index.html içinde şu satırı bul:  var ADS={client:"",slot:""}
     client: "ca-pub-XXXXXXXXXXXXXXXX", slot: reklam birimi numaran ("Ads > By ad unit > Display").
   - ads.txt içindeki satırı kendi pub numaranla aç. privacy.html'deki e-postayı değiştir.
   - AdSense > Privacy & messaging bölümünden Avrupa/UK için Google onay mesajını yayınla.
   - Reklam yalnızca cevap göründükten sonra, altta tek bir 320x50 banner olarak çıkar.

3) Telefonda
   - İlk ekranda "Ana ekrana ekle" düğmesi var: Android/bilgisayarda doğrudan kurar,
     iPhone'da adım adım gösterir (Paylaş > Ana Ekrana Ekle). Zaten kuruluysa görünmez.
   - Sallamak için ilk açılışta hareket izni ver.
