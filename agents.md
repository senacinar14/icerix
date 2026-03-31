# 🤖 Proje Ajanı (AI Agent) ve Teknik Yapılandırma

Bu proje, marketlerdeki paketli ürünlerin içeriklerini saniyeler içinde analiz ederek kullanıcıya sağlık odaklı bir rehber sunan bir *Yapay Zeka Ajanı* olarak kurgulanmıştır.

### 🎯 Ajanın Rolü ve Amacı
- *Görev:* Ürün marka, isim veya barkod bilgisini alarak doğrudan *Grok API* üzerinden analiz yapmak.
- *Analiz Mantığı:* Bileşenleri statik bir veritabanından çekmek yerine, yapay zekanın geniş bilgi dağarcığını kullanarak ürünün içerik listesini bulur ve değerlendirir.
- *Sağlık Skoru:* Ürünleri içeriklerine göre Kırmızı (Riskli), Turuncu (Orta) ve Yeşil (Güvenli) renk kodlarıyla sınıflandırır.
- *Açıklama Katmanı:* Her katkı maddesinin neden zararlı veya faydalı olduğuna dair bilimsel dayanaklı kısa açıklamalar sunar.
- *Alternatif Motoru:* Riskli bulunan ürünlere karşı daha sağlıklı alternatif öneriler geliştirir.

### 🛠️ Kullanılan Teknoloji Yığını (Tech Stack)
Proje geliştirme sürecinde farklı yapay zeka modellerinin güçlü yanlarından faydalanılmıştır:

* *Fikir Geliştirme:* ChatGPT & Gemini
* *Kod Yazımı:* Claude
* *Analiz Motoru (API):* Grok (Llama-3 tabanlı modeller)
* *Geliştirme Ortamı:* VS Code
* *Versiyon Kontrol:* GitHub
* *Yayınlama (Deployment):* Netlify

### ⚙️ Çalışma Akışı
1. Kullanıcıdan veri girişi alınır (İsim/Marka/Barkod).
2. Grok API, ürünün içerik listesini gerçek zamanlı olarak tarar.
3. İçerik analizi sonucunda risk puanı ve katkı maddesi detayları oluşturulur.
4. Çıktı, kullanıcı dostu bir arayüzle (Web Coding) anlık olarak sunulur.
