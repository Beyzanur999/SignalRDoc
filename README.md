# SignalRDoc
SignalR teknolojisini kullanarak farklı cihazlardan bağlanan kullanıcıların ortak bir ortam üzerinde eş zamanlı düzenleme yapabildiği bir uygulama
# 📡 Real-Time Collaborative Editor with SignalR

Bu proje, **SignalR** teknolojisi kullanılarak geliştirilen, farklı cihazlardan bağlanan kullanıcıların **ortak bir ortam üzerinde eş zamanlı olarak düzenleme yapabildiği** gerçek zamanlı bir web uygulamasıdır.

## 🚀 Özellikler

- Gerçek zamanlı veri aktarımı (SignalR ile)
- Farklı cihazlardan eş zamanlı düzenleme imkânı
- Kullanıcı bağlantı takibi
- Anlık güncelleme yayını
- Otomatik yeniden bağlanma
- Basit ve anlaşılır arayüz (HTML + JavaScript)

---

## 🛠 Kullanılan Teknolojiler ve Kütüphaneler

- ASP.NET Core (.NET 6 veya üzeri)
- SignalR (Microsoft.AspNetCore.SignalR)
- JavaScript (Vanilla JS)
- HTML/CSS
- Visual Studio (IDE olarak)
  
---

## 📁 Proje Dosya Yapısı

RealTimeCollaborativeEditor/
│
├── RealTimeCollaborativeEditor.csproj
├── Program.cs
├── Startup.cs (ya da Program.cs içinde yapılandırıldıysa Startup yok)
├── Hubs/
│ └── CollaborationHub.cs
├── wwwroot/
│ ├── index.html
│ └── script.js
├── Properties/
│ └── launchSettings.json
└── README.md

yaml
Copy
Edit

---

## ⚙️ Kurulum ve Çalıştırma

1. **Projeyi klonlayın:**

```bash
git clone https://github.com/kullaniciadi/RealTimeCollaborativeEditor.git
cd RealTimeCollaborativeEditor
Wi-Fi IP Adresini Girin (launchSettings.json)

Ağ üzerinden farklı cihazlarla test yapabilmek için launchSettings.json dosyasındaki applicationUrl alanına bilgisayarınızın yerel ağ (Wi-Fi) IP adresini girin.

json
Copy
Edit
"applicationUrl": "http://192.168.x.x:5000"
🔍 IP adresinizi öğrenmek için terminale (cmd, powershell) şunu yazabilirsiniz:

bash
Copy
Edit
ipconfig
Uygulamayı çalıştırın:

Visual Studio üzerinden "Start" diyerek ya da terminalden:

bash
Copy
Edit
dotnet run
Tarayıcıda açın:

Projeyi çalıştırdıktan sonra farklı cihazlarda aynı IP ve port üzerinden uygulamayı açın:

cpp
Copy
Edit
http://192.168.x.x:5000
🧪 Nasıl Test Edilir?
Aynı ağa bağlı farklı cihazlarda uygulamayı tarayıcıda açın.

Ortak düzenleme alanında yazı/düzenleme yapıldığında, tüm cihazlarda eş zamanlı olarak görünmelidir.

✨ Katkı Sağlama
Pull request'ler her zaman memnuniyetle karşılanır. Büyük değişiklikler planlıyorsanız lütfen önce bir issue açarak neyi değiştirmek istediğinizi tartışın.
