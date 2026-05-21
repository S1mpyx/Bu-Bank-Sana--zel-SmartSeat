English
Project Overview

BU BANK SANA ÖZEL is an embedded systems prototype functioning as an intelligent public seating system. It provides priority-based access control using RFID authentication and mechanical actuation within a smart city concept.

System Architecture
Microcontroller: Arduino Uno
Authentication: MFRC522 RFID Reader (13.56 MHz, SPI)
Actuation: Micro Servo Motor (prototype scale)
Power: Stabilized DC supply with filtering capacitors
Structure: Designed and simulated in Blender
Working Principle

RFID card is scanned → UID is read → Arduino verifies access → if authorized servo activates mechanical lock → otherwise system remains locked

Embedded Software

Developed in embedded C/C++. Features RFID UID verification, SPI communication, PWM servo control, noise filtering, and power stability management.

Challenges

Servo activation caused voltage drops and instability. This was solved by improving power distribution, adding capacitors, and optimizing firmware timing.

Purpose

Demonstration of embedded systems, RFID authentication, servo control, and smart infrastructure concepts.

Authors

Lead Developer: Yiğit Dağlı (system design, embedded software, hardware integration, 3D modeling)
Contributor: Tahsin Eren Demir (concept development and presentation)

Türkçe
Proje Özeti

BU BANK SANA ÖZEL, RFID tabanlı kimlik doğrulama ile çalışan ve akıllı şehir konseptinde öncelikli erişim sağlayan gömülü sistem prototipidir.

Sistem Mimarisi
Mikrodenetleyici: Arduino Uno
Kimlik Doğrulama: MFRC522 RFID Okuyucu (13.56 MHz, SPI)
Çalıştırma: Mikro servo motor (prototip ölçeği)
Güç: Filtrelenmiş sabit DC besleme
Yapı: Blender ile tasarlanmış ve simüle edilmiştir
Çalışma Prensibi

RFID kart okutulur → UID okunur → Arduino doğrular → yetkiliyse servo çalışır ve kilit açılır → değilse sistem kilitli kalır

Gömülü Yazılım

Embedded C/C++ ile geliştirilmiştir. RFID doğrulama, SPI haberleşme, PWM servo kontrolü, gürültü filtreleme ve güç stabilizasyonu içerir.

Sorunlar

Servo motor çalışırken voltaj düşüşü ve kararsızlık oluştu. Güç dağıtımı iyileştirilerek, kondansatör eklenerek ve yazılım zamanlaması optimize edilerek çözüldü.

Amaç

Gömülü sistemler, RFID doğrulama, servo kontrol ve akıllı altyapı teknolojilerini göstermek.

Yazarlar

Ana geliştirici: Yiğit Dağlı (sistem tasarımı, gömülü yazılım, donanım entegrasyonu, 3D modelleme)
Katkı: Tahsin Eren Demir (fikir geliştirme ve sunum)

Русский
Описание проекта

BU BANK SANA ÖZEL — это прототип встроенной системы, которая обеспечивает приоритетный доступ в рамках концепции умного города с использованием RFID-аутентификации.

Архитектура системы
Микроконтроллер: Arduino Uno
Аутентификация: RFID модуль MFRC522 (13.56 MHz, SPI)
Привод: микро сервомотор (прототип)
Питание: стабилизированное DC с фильтрацией
Конструкция: разработана и смоделирована в Blender
Принцип работы

RFID карта сканируется → считывается UID → Arduino проверяет доступ → при разрешении активируется сервомотор → механизм открывается, иначе остаётся закрытым

Встроенное ПО

Разработано на C/C++. Включает проверку UID, SPI связь, PWM управление сервомотором, фильтрацию шума и стабилизацию питания.

Проблемы

При работе сервомотора возникали падения напряжения и нестабильность. Проблема решена улучшением питания, добавлением конденсаторов и оптимизацией таймингов.

Цель

Демонстрация RFID систем, встроенной электроники, сервоконтроля и технологий умной инфраструктуры.

Авторы

Главный разработчик: Yiğit Dağlı (система, код, оборудование, 3D моделирование)
Участник: Tahsin Eren Demir (разработка идеи и презентация)
