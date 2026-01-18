# 🚀 Jarvis Altyapı Projesi

Bu proje, **Lande Systems** operasyonları için geliştirilmiş, Docker tabanlı modern bir web sunucusu ve izleme (monitoring) altyapısıdır.

## 🛠️ Kullanılan Teknolojiler
* **Docker & Docker Compose:** Konteyner orkestrasyonu.
* **Nginx:** Yüksek performanslı Web Sunucusu.
* **Uptime Kuma:** Gerçek zamanlı sistem izleme ve alarm sistemi.
* **Linux (Ubuntu Server):** Ana işletim sistemi (AMD Ryzen 9 Gücü ile).

## 📂 Proje Mimarisi
Proje tek bir `docker-compose.yml` dosyası üzerinden yönetilmektedir.
- **Port 8080:** Web Arayüzü (Lande Systems Karşılama Ekranı)
- **Port 3001:** İzleme Paneli (Uptime Kuma Dashboard)

## ⚡ Kurulum ve Çalıştırma

Projeyi ayağa kaldırmak için aşağıdaki komut yeterlidir:

```bash
docker compose up -d
