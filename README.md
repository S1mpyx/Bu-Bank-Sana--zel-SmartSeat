# BU BANK SANA ÖZEL

## 🇹🇷 Türkçe

### Proje Özeti

**BU BANK SANA ÖZEL**, RFID tabanlı kimlik doğrulama ile çalışan ve akıllı şehir konsepti kapsamında dezavantajlı bireyler için ayrılmış oturma alanlarına öncelikli erişim sağlayan bir gömülü sistem prototipidir.

### Sistem Mimarisi

* **Mikrodenetleyici:** Arduino Uno
* **Kimlik Doğrulama:** MFRC522 RFID Okuyucu (13.56 MHz, SPI)
* **Çalıştırma Mekanizması:** Mikro Servo Motor (prototip ölçeği)
* **Güç Kaynağı:** Arduino USB bağlantısı (5 V DC)
* **3D Tasarım:** Blender

### Çalışma Prensibi

1. RFID kart okutulur.
2. Kartın UID bilgisi okunur.
3. Arduino UID'yi doğrular.
4. Yetkili kullanıcı tespit edilirse servo motor kilit mekanizmasını açar.
5. Yetkisiz erişimlerde sistem kilitli kalır.

### Gömülü Yazılım

Yazılım **Embedded C/C++** dili kullanılarak geliştirilmiştir.

**Özellikler:**

* RFID UID doğrulama
* SPI haberleşmesi
* PWM servo kontrolü


### Amaç

Kamusal alanlarda dezavantajlı bireyler için ayrılmış oturma alanlarının RFID tabanlı erişim kontrolü ile korunmasını sağlamak. Sistem, bu alanların yetkisiz kişiler tarafından kullanılmasını önleyerek öncelikli oturma hakkını güvence altına almayı, erişilebilirliği artırmayı ve kapsayıcı akıllı şehir uygulamalarını desteklemeyi amaçlamaktadır.

### Geliştiriciler

**Ana Geliştirici**

Yiğit Dağlı

* Sistem Tasarımı
* Embedded Yazılım
* Donanım Entegrasyonu
* 3D Modelleme

**Katkı Sağlayan**

Tahsin Eren Demir

* Fikir Geliştirme
* Sunum Hazırlığı

Not (Türkçe):
Bu proje, TÜBİTAK 4006-C İlçe Bilim Fuarı kapsamında geliştirilmiş ve sergilenmiştir. Prototip, gömülü sistemler, RFID tabanlı erişim kontrolü ve erişilebilir akıllı şehir uygulamalarını tanıtmak amacıyla hazırlanmıştır.

---

# 🇷🇺 Русский

## Описание проекта

**BU BANK SANA ÖZEL** — прототип встроенной системы, предназначенный для обеспечения приоритетного доступа к специально выделенным местам для социально уязвимых групп населения с использованием RFID-аутентификации в рамках концепции умного города.

## Архитектура системы

* **Микроконтроллер:** Arduino Uno
* **Аутентификация:** RFID-модуль MFRC522 (13.56 MHz, SPI)
* **Исполнительный механизм:** микро сервомотор
* **Питание:** стабилизированное DC-питание с фильтрацией
* **3D-модель:** Blender

## Принцип работы

1. RFID-карта сканируется.
2. Считывается UID карты.
3. Arduino проверяет право доступа.
4. При успешной аутентификации сервомотор открывает механизм блокировки.
5. При отсутствии разрешения система остаётся заблокированной.

## Встроенное программное обеспечение

Программное обеспечение разработано на языке **Embedded C/C++**.

**Возможности:**

* Проверка UID
* Обмен данными по SPI
* PWM-управление сервомотором



## Цель

Обеспечить защиту специально выделенных мест для социально уязвимых групп населения в общественных пространствах с помощью RFID-аутентификации. Система предотвращает несанкционированное использование этих мест, обеспечивает приоритетное право на посадку, повышает доступность и поддерживает развитие инклюзивной инфраструктуры умного города.

## Авторы

**Главный разработчик**

Yiğit Dağlı

* Разработка системы
* Встроенное программное обеспечение
* Интеграция оборудования
* Питание: USB-питание от Arduino (5 В DC)
* 3D-моделирование

**Участник проекта**

Примечание (Русский):
Данный проект был разработан и представлен в рамках районной научной выставки TÜBİTAK 4006-C. Прототип создан для демонстрации встроенных систем, RFID-аутентификации, управления доступом и технологий доступной инфраструктуры умного города.

Tahsin Eren Demir

* Разработка концепции
* Подготовка презентации
