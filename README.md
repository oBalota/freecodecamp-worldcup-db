# 🏆 World Cup Database (Dünya Kupası Veritabanı)

[English](#english) | [Türkçe](#türkçe)

---

## English

### 📝 Project Description
This project is a part of the **freeCodeCamp Relational Database Certification**. The goal is to create a PostgreSQL database that stores World Cup tournament data since 2014, insert data from a CSV file using a Bash script, and perform various statistical queries on the database.

### 🚀 Key Features
*   **Database Design:** Built with PostgreSQL, establishing structured relationships between teams and match statistics.
*   **Automation Script (`insert_data.sh`):** A robust Bash script that parses a `games.csv` file, automatically avoids duplicates, dynamically fetches team IDs, and populates the database efficiently under the 20-second test limit.
*   **Analytical Queries (`queries.sh`):** A collection of optimized SQL queries extracting specific details such as champion history, average goals, and advanced string matching using aggregates and joins.

### 🛠️ Tech Stack & Skills
*   **Database:** PostgreSQL / SQL
*   **Scripting:** Bash / Linux Terminal
*   **Tools:** Git & GitHub

---

## Türkçe

### 📝 Proje Açıklaması
Bu proje, **freeCodeCamp Relational Database (İlişkisel Veritabanı) Sertifikasyonu** kapsamında geliştirilmiştir. Projenin amacı, 2014 yılından bu yana oynanan Dünya Kupası turnuva verilerini depolayan bir PostgreSQL veritabanı tasarlamak, bir Bash script'i vasıtasıyla CSV dosyasındaki verileri otomatik aktarmak ve veritabanı üzerinde çeşitli istatistiksel SQL sorguları yürütmektir.

### 🚀 Öne Çıkan Özellikler
*   **Veritabanı Tasarımı:** Takımlar ve maç istatistikleri arasında yapılandırılmış ilişkiler kuran PostgreSQL mimarisi.
*   **Otomasyon Script'i (`insert_data.sh`):** `games.csv` dosyasını satır satır okuyan, mükerrer kayıtları (duplicate) önleyen, dinamik ID eşleştirmesi yapan ve 20 saniyelik test sınırının altında çalışan optimize edilmiş Bash script'i.
*   **Analitik Sorgular (`queries.sh`):** Şampiyonluk geçmişi, gol ortalamaları ve gelişmiş metin eşleştirmeleri gibi spesifik verileri `JOIN` ve `GROUP BY` gibi yapılarla çeken optimize SQL sorguları.

### 🛠️ Kullanılan Teknolojiler ve Yetkinlikler
*   **Veritabanı:** PostgreSQL / SQL
*   **Scripting:** Bash / Linux Terminali
*   **Araçlar:** Git & GitHub