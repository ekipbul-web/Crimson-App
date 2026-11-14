# Gizlilik Politikası

Son güncelleme: 14 Kasım 2026 · Geliştirici: Crimson (ekipbul-web) · İletişim: [Telegram](https://t.me/+ExCaZUzHODQxMjZi) veya [GitHub](https://github.com/ekipbul-web/Crimson-App/issues)
**Kısaca:** Crimson’ın kendi sunucusu yoktur. Seni takip etmez, analiz veya reklam aracı kullanmaz, verilerini toplamaz ya da satmaz. Veriler yalnızca senin telefonunda ve senin seçtiğin hizmetlerle işlenir.

### Telefonunda saklananlar

Sohbet geçmişi, notlar, hafıza, rutinler, ayarlar ve girdiğin API anahtarları yalnızca cihazında saklanır. API anahtarları Android Keystore ile şifrelenir. Uygulama yedeklemeye kapalıdır. Uygulamayı kaldırırsan hepsi silinir. Ayarlar’daki “Tüm verilerimi sil” seçeneğiyle de silebilirsin. “Yedekle” dediğinde oluşan dosya sohbetlerini ve notlarını içerir (API anahtarları dahil değildir) ve senin seçtiğin yerde saklanır.

### Üçüncü taraflara giden veriler

Crimson, işlevlerini yerine getirmek için senin seçtiğin hizmetlere istek gönderir. Bu hizmetlerin kendi gizlilik politikaları geçerlidir.

- **Yapay zekâ sağlayıcıları:** Google Gemini, OpenAI, Anthropic, Groq, OpenRouter. Yazdıkların, söylediklerin (metne çevrilmiş hâliyle), eklediğin fotoğraf, PDF ve ses dosyaları yanıt üretmek için sağlayıcıya gönderilir. Yalnızca anahtarını girdiğin sağlayıcılar kullanılır.

- **Bulut sesi:** Açıksa yanıt metni OpenAI, Google veya ElevenLabs’e gönderilir.

- **Konuşma tanıma:** Cihazının konuşma tanıma servisi kullanılır (genelde Google).

- **Yardımcı servisler:** Hava durumu için Open-Meteo, haberler için Google Haberler, web araması için DuckDuckGo, döviz kurları için open.er-api.com. Yalnızca ilgili soruyu sorduğunda çağrılır.

- **“Hey Crimson” modeli:** Açtığında bir kez alphacephei.com’dan indirilir, sonrasında dinleme cihazda ve çevrimdışı yapılır. Ses kaydı gönderilmez.

- **Akıllı ev:** Kendi Home Assistant adresine gider.

- **Güncelleme denetimi:** “Güncellemeleri denetle”ye dokunduğunda GitHub’a (api.github.com) tek bir istek gider.

- **Sorun bildir, Telegram, Instagram, Destek ol:** Yalnızca sen dokunduğunda ilgili sayfayı tarayıcında açar. Uygulama bu sayfalara veri göndermez. “Sorun bildir” GitHub’da, sürüm numarası, Android sürümü, cihaz modeli ve son hata mesajıyla önceden doldurulmuş bir form açar; göndermeden önce düzenleyebilirsin. Sohbetin eklenmez.

### İzinler ve neden istendikleri

- **Mikrofon:** Sesli komut ve “Hey Crimson”.

- **Kişiler, Takvim:** Yalnızca sen istediğinde arama, mesaj ve etkinlik işleri için okunur.

- **Bildirim erişimi (isteğe bağlı):** Bildirimleri okumak için.

- **Erişilebilirlik hizmeti (isteğe bağlı):** Telefonu senin adına kullanmak için ekrandaki yazıları okur, dokunur, yazar, kaydırır. Bu açıkken ekrandaki yazılar yapay zekâ sağlayıcına gönderilebilir. Parola, kart numarası ve doğrulama kodu yazmaz, geri dönüşü olmayan işlemlerden önce sorar. İstediğin an Ayarlar’dan kapatabilirsin.

- **Uygulama kilidi (isteğe bağlı):** Telefonun ekran kilidini (PIN, desen, parmak izi) kullanır. Kimlik bilgilerin Crimson’a verilmez.

- **Alarm, bildirim, ayarlar, ön plan servisi:** Alarm, hatırlatıcı, rutin, widget ve parlaklık ayarı için.

### Çocuklar

Uygulama 13 yaşından küçüklere yönelik değildir.

### Haklarınız ve iletişim

Veriler yalnızca sende olduğu için silmek istersen “Tüm verilerimi sil”i kullanman ya da uygulamayı kaldırman yeterli. Sorular için Telegram veya GitHub üzerinden ulaşabilirsin.

---

# Privacy Policy

Last updated: November 14, 2026 · Developer: Crimson (ekipbul-web) · Contact: [Telegram](https://t.me/+ExCaZUzHODQxMjZi) or [GitHub](https://github.com/ekipbul-web/Crimson-App/issues)
**In short:** Crimson has no server of its own. It does not track you, use analytics or ads, and never collects or sells your data. Everything is processed on your phone and by the services you choose.

### Stored on your phone

Chat history, notes, memory, routines, settings and the API keys you enter are stored only on your device. API keys are encrypted with the Android Keystore. The app is excluded from backups and uninstalling removes everything. You can also use “Delete all my data” in Settings. A file created with “Back up” contains your chats and notes (API keys are not included) and stays wherever you save it.

### Data sent to third parties

- **AI providers:** Google Gemini, OpenAI, Anthropic, Groq, OpenRouter. What you type or say (as text), plus photos, PDFs and audio you attach, are sent to the provider whose key you added, to generate answers.

- **Cloud voice:** If on, reply text goes to OpenAI, Google or ElevenLabs.

- **Speech recognition:** Your device’s speech service (usually Google).

- **Helper services:** Open-Meteo (weather), Google News, DuckDuckGo (web search), open.er-api.com (exchange rates), only when you ask for them.

- **“Hey Crimson” model:** Downloaded once from alphacephei.com; listening then runs offline on the device. No audio is uploaded.

- **Smart home:** Requests go to your own Home Assistant address.

- **Update check:** Tapping “Check for updates” sends one request to GitHub (api.github.com).

- **Report a problem, Telegram, Instagram, Support:** They only open the related page in your browser when you tap them; the app sends no data to those pages. “Report a problem” opens a GitHub form pre-filled with the app version, Android version, device model and last error message, which you can edit before sending. Your chat is not included.

### Permissions

Microphone (voice, wake word); Contacts and Calendar (only when you ask); Notification access and Accessibility service (both optional; with Accessibility on, on-screen text may be sent to your AI provider; the app never types passwords, card numbers or verification codes and asks before irreversible actions); App lock (optional, uses your phone’s screen lock); alarms, notifications, settings, widget and foreground service for alarms, reminders and routines.

### Children

Not intended for children under 13.

### Contact

Questions: Telegram or GitHub.
