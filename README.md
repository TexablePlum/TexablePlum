<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,40:0d2137,100:0d1117&height=200&section=header&text=Dominik%20Por%C4%99bski&fontSize=54&fontColor=e6edf3&animation=fadeIn&fontAlignY=40&desc=Student%20II%20stopnia%20Informatyki%20%E2%80%94%20Politechnika%20%C5%9Al%C4%85ska&descAlignY=62&descSize=18&descColor=8b949e" width="100%"/>

  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=16&pause=1200&color=58A6FF&center=true&vCenter=true&width=560&lines=.NET+%7C+Java+%7C+Python+%7C+Dart+%7C+C%2B%2B;Clean+Architecture+%7C+CQRS+%7C+DDD;Docker+%7C+Azure+%7C+Redis+%7C+PostgreSQL;Backend+Security+%26+Application+Design" alt="Typing SVG" />

  <br/>

  <p>
    Głównie interesuję się backendem - preferuję ekosystem <strong>.NET</strong>.<br/>
    Tworzę też w Javie, Pythonie, Darcie i C++.<br/>
    W swoich projektach stawiam na czystą architekturę, bezpieczeństwo i jakość kodu.
  </p>

  <br/>

  [![Email](https://img.shields.io/badge/porebskid8%40gmail.com-0d1117?style=flat-square&logo=gmail&logoColor=EA4335)](mailto:porebskid8@gmail.com)
  [![GitHub](https://img.shields.io/badge/TexablePlum-0d1117?style=flat-square&logo=github&logoColor=white)](https://github.com/TexablePlum)
</div>

---

## Technologie

<div align="center">

  <img src="https://skillicons.dev/icons?i=cs,dotnet,java,py,dart,cpp&theme=dark" /><br/>
  <img src="https://skillicons.dev/icons?i=postgres,redis,docker,azure,nginx,linux&theme=dark" /><br/>
  <img src="https://skillicons.dev/icons?i=flutter,git,githubactions,visualstudio,vscode&theme=dark" />

</div>

---

## Główne Projekty

<br/>

### [NEXA](https://github.com/TexablePlum/NEXA-VOD-Service) - platforma VOD z autorskim systemem DRM

![.NET 9](https://img.shields.io/badge/.NET-9.0-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![AES-256](https://img.shields.io/badge/AES--256--GCM-8B0000?style=flat-square&logo=letsencrypt&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)

Samodzielna platforma streamingowa realizująca pełny cykl ochrony treści — od transkodowania i szyfrowania wideo, przez bezpieczną dystrybucję kluczy powiązanych z urządzeniem, aż po egzekwowanie limitów jakości zgodnych z planem subskrypcji.

Architektura mikroserwisowa (DRM server + Content server) ukryta za Nginx, szyfrowanie AES-256-GCM, streaming MPEG-DASH, dwupoziomowy cache. Klient desktopowy WinUI 3 z Shaka Player osadzonym w WebView2. Dwa tryby zabezpieczeń — sprzętowy (TPM/Windows CNG) i programowy (RSA-2048 + DPAPI).

<br/>

### [PixelTree](https://github.com/TexablePlum/PixelTree) - system oświetlenia ARGB LED

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-000000?style=flat-square)
![ESP32-S3](https://img.shields.io/badge/ESP32--S3-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![BLE](https://img.shields.io/badge/BLE-0082FC?style=flat-square&logo=bluetooth&logoColor=white)

Projekt inżynierski - Kompletny prototyp oświetlenia dekoracyjnego ARGB LED.
Zbudowany z wykorzystaniem mikrokontrolera ESP32-S3, estetycznie wykończonego łańcucha adresowalnych diod WS2812D, dwustopniowej regulacji napięcia oraz obudowy z druku 3D.

Zoptymalizowany firmware wykorzystuje podział na rdzenie procesora, jeden rdzeń odpowiada za generowanie ponad 40 konfigurowalnych efektów świetlnych w 60 fps, drugi rdzeń obsługuje stos sieciowy. Urządzenie oferuje łączność Wi-Fi (REST API, mDNS zero-config discovery) oraz BLE z bezpiecznym, szyfrowanym parowaniem (ECDH+AES). Do zarządzania oświetleniem służy dedykowana aplikacja mobilna na systemy iOS i Android stworzona w wieloplatformowym frameworku Flutter.

<br/>

### [CalorieTracker](https://github.com/TexablePlum/CalorieTracker) - REST API do zarządzania żywieniem

![.NET 9](https://img.shields.io/badge/.NET-9.0-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)
![Flutter](https://img.shields.io/badge/Flutter-%2302569B?style=flat-square&logo=flutter&logoColor=white)

Kompleksowy backend systemu do monitorowania diety, zaprojektowany zgodnie z paradygmatami Clean Architecture, CQRS oraz Domain-Driven Design (DDD). Projekt stanowi warstwę serwerową dla dedykowanej [aplikacji mobilnej stworzonej we Flutterze](https://github.com/TexablePlum/CalorieTracker-Flutter), zapewniając skalowalną i przejrzystą strukturę kodu.

Za bezpieczeństwo odpowiada uwierzytelnianie oparte na JWT z mechanizmem refresh tokenów, a poprawność logiki domenowej zapewniają testy jednostkowe. W projekcie wykorzystano narzędzia takie jak FluentValidation oraz AutoMapper. System został wdrożony w chmurze Microsoft Azure przy wykorzystaniu zautomatyzowanego potoku CI/CD w GitHub Actions, który odpowiada również za automatyczne generowanie publikację dokumentacji Swagger/OpenAPI na GitHub Pages przy każdej aktualizacji repozytorium.

---

## Pozostałe Projekty

<div align="center">

| Projekt | Technologie | Opis |
|:--------|:-----------:|:-----|
| [SkyPulse](https://github.com/TexablePlum/SkyPulse) | Flutter · Dart | Mobilna aplikacja pogodowa z indeksem jakości powietrza (AQI), danymi z zewnętrznego API i geolokalizacją |
| [SortAlgorithms](https://github.com/TexablePlum/Sort_Algorithms) | C# | Interaktywna wizualizacja algorytmów sortowania — async/await, tokeny przerwań, responsywne UI |
| [Tetris](https://github.com/TexablePlum/Tetris) | C# · MonoGame | Klon Tetrisa z wieloma motywami graficznymi, systemem punktacji i animowanym UI |
| [PacMan](https://github.com/TexablePlum/PacMan_LibGDX_POiW_2025_proj) | Java · LibGDX | Remake PacMana z dynamicznym generowaniem mapy z JSON i zaawansowanym AI duszków |
| [TensorFlow Mini Projects](https://github.com/TexablePlum/Tensorflow) | Python · TensorFlow · Keras | Eksperymenty ML/DL: CNN, autoenkodery, GAN-y, Q-Learning, fine-tuning VGG16 |

</div>

---

## Certyfikaty

<div align="center">

| [📘 Python for Everybody](https://coursera.org/share/4f8c18b555a4100b668eaeec0234a9ab) | [📗 Fundamentals of Java Programming](https://coursera.org/share/835439e0cf849efce9dab714c0c36969) |
|:---:|:---:|
| [![Python for Everybody](https://github.com/user-attachments/assets/279a9113-a43e-4b56-8d31-692da712016c)](https://coursera.org/share/4f8c18b555a4100b668eaeec0234a9ab) | [![Fundamentals of Java Programming](https://github.com/user-attachments/assets/b47bb268-66fb-41f9-aed9-7b3ca07f6d4c)](https://coursera.org/share/835439e0cf849efce9dab714c0c36969) |

| [📙 Introduction to Deep Learning & Neural Networks with Keras](https://coursera.org/share/c0251258813c2c23f5461e21ce41d742) | [📒 Deep Learning with Keras and TensorFlow](https://coursera.org/share/50aed3ed79422a7ebd9d14666e72071b) |
|:---:|:---:|
| [![Introduction to Deep Learning](https://github.com/user-attachments/assets/8959dabc-451e-420f-8b19-810f8fe01aab)](https://coursera.org/share/c0251258813c2c23f5461e21ce41d742) | [![Deep Learning with Keras and TensorFlow](https://github.com/user-attachments/assets/751882ca-2295-42f4-ad47-f95a7246257f)](https://coursera.org/share/50aed3ed79422a7ebd9d14666e72071b) |

| [📕 C# dla deweloperów .NET](https://www.udemy.com/certificate/UC-d3e72b9d-b1ba-4628-b55d-f1a267ce1669/) | [📔 SOLID i Wzorce Projektowe w C#](https://www.udemy.com/certificate/UC-44c7e55f-55f4-435b-9b64-89b7b9c05f95/) |
|:---:|:---:|
| [![C# dla deweloperów .NET](https://github.com/user-attachments/assets/c15be5f1-3dd9-4ffa-971f-457dd92b83ec)](https://www.udemy.com/certificate/UC-d3e72b9d-b1ba-4628-b55d-f1a267ce1669/) | [![SOLID i Wzorce Projektowe w C#](https://github.com/user-attachments/assets/712fe744-4864-42bf-9484-4d60b4833265)](https://www.udemy.com/certificate/UC-44c7e55f-55f4-435b-9b64-89b7b9c05f95/) |

| [📓 GitHub Copilot dla programistów](https://mycourse.app/DEYlLdAZZSMBgtklD) |
|:---:|
| [![GitHub Copilot dla programistów](https://github.com/user-attachments/assets/b097137b-4dd4-4c1f-bf54-16052397ed77)](https://mycourse.app/DEYlLdAZZSMBgtklD) |

</div>

---

<div align="center">

  ### Kontakt 📬

  Napisz do mnie — chętnie porozmawiam o ciekawych projektach i możliwościach współpracy.

  [![Email](https://img.shields.io/badge/porebskid8%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:porebskid8@gmail.com)
  [![GitHub](https://img.shields.io/badge/TexablePlum-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/TexablePlum)

  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,40:0d2137,100:0d1117&height=120&section=footer" width="100%"/>
</div>
