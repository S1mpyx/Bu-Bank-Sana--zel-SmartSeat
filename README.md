English
1. Project Overview
BU BANK SANA ÖZEL is an embedded systems prototype that functions as an intelligent public seating system. It provides priority-based access control using RFID authentication and mechanical actuation within a smart city concept.

2. System Architecture

Microcontroller: Arduino Uno

Authentication: MFRC522 RFID Reader (13.56 MHz, SPI)

Actuation: Micro Servo Motor (Prototype Scale)

Power: Stabilized DC supply with filtering capacitors

Structure: Designed and simulated in Blender

3. Working Principle
RFID card is scanned → UID is read → Arduino verifies access → if authorized servo activates mechanical lock → if not, system remains locked

4. Embedded Software
Developed in embedded C/C++. Features include RFID UID verification, SPI communication, PWM servo control, noise filtering, and power stability handling.

5. Challenges
Servo activation caused voltage drops and instability. This was solved by improving power distribution, adding capacitors, and optimizing firmware timing.

6. Purpose
Demonstration of embedded systems, RFID authentication, servo control, and smart infrastructure concepts.

7. Authors

Lead: Yiğit Dağlı (system design, embedded software, hardware integration, 3D modeling)

Contributor: Tahsin Eren Demir (concept development and presentation)

Türkçe
1. Proje Özeti
BU BANK SANA ÖZEL, RFID tabanlı kimlik doğrulama ile çalışan ve akıllı şehir konseptinde öncelikli erişim sağlayan gömülü sistem prototipidir.

2. Sistem Mimarisi

Mikrodenetleyici: Arduino Uno

Kimlik Doğrulama: MFRC522 RFID Okuyucu (13.56 MHz, SPI)

Sürücü: Mikro Servo Motor (Prototip Ölçekli)

Güç: Filtrelenmiş sabit DC besleme

Yapı: Blender ile tasarlanmış ve simüle edilmiştir

3. Çalışma Prensibi
RFID kart okutulur → UID okunur → Arduino doğrular → yetkiliyse servo çalışır ve kilit açılır → değilse sistem kilitli kalır

4. Gömülü Yazılım
Embedded C/C++ ile geliştirilmiştir. RFID doğrulama, SPI haberleşme, PWM servo kontrolü, gürültü filtreleme ve güç stabilizasyonu içerir.

5. Sorunlar
Servo motor çalışırken voltaj düşüşü ve kararsızlık oluştu. Güç dağıtımı iyileştirilerek, kondansatör eklenerek ve yazılım zamanlaması optimize edilerek çözüldü.

6. Amaç
Gömülü sistemler, RFID doğrulama, servo kontrol ve akıllı altyapı teknolojilerini göstermek.

7. Yazarlar

Ana geliştirici: Yiğit Dağlı (sistem tasarımı, gömülü yazılım, donanım entegrasyonu, 3D modelleme)

Katkı: Tahsin Eren Demir (fikir geliştirme ve sunum)

Русский
1. Описание проекта
BU BANK SANA ÖZEL — это прототип встроенной системы, обеспечивающий приоритетный доступ в рамках концепции умного города с использованием RFID-аутентификации.

2. Архитектура системы

Микроконтроллер: Arduino Uno

Аутентификация: RFID модуль MFRC522 (13.56 MHz, SPI)

Привод: микросервопривод (масштаб прототипа)

Питание: стабилизированное DC с фильтрацией

Конструкция: разработана и смоделирована в Blender

3. Принцип работы
Сканируется RFID карта → считывается UID → Arduino проверяет доступ → при разрешении активируется сервомотор → механизм открывается, иначе остаётся закрытым

4. Встроенное ПО
Разработано на C/C++. Включает проверку UID, SPI связь, PWM управление сервомотором, фильтрацию шума и стабилизацию питания.

5. Проблемы
Возникали падения напряжения при работе сервомотора. Проблема решена улучшением питания, добавлением конденсаторов и оптимизацией таймингов.

6. Цель
Демонстрация RFID систем, встроенной электроники, сервоконтроля и технологий умной инфраструктуры.

7. Авторы

Главный разработчик: Yiğit Dağlı (система, код, оборудование, 3D)

Участник: Tahsin Eren Demir (развитие концепции и презентация)
