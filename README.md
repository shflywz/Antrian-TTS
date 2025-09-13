<p align="center">
<a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a>
</p>

<p align="center">
<a href="https://github.com/username/antrian-tts/actions"><img src="https://github.com/username/antrian-tts/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License"></a>
</p>

# Antrian-TTS

**Antrian-TTS** adalah sistem antrian berbasis web dengan **Text-to-Speech (TTS)** otomatis. Dibangun menggunakan Laravel 11, Docker (Sail), PostgreSQL, Redis, MySQL, Queue Worker, Mailpit, Meilisearch, dan Selenium untuk automasi testing.

---

## **Fitur Utama**

- Manajemen antrian online
- TTS otomatis untuk setiap antrian
- Queue worker untuk memproses job TTS secara real-time
- Database PostgreSQL (utama) dan MySQL (opsional)
- Redis sebagai cache dan queue
- Meilisearch untuk pencarian cepat
- Mailpit untuk testing email
- Selenium untuk automasi browser/testing

---

## **Stack Teknologi**

- **Backend:** Laravel 11 (PHP 8.4 via Sail)
- **Database:** PostgreSQL 17, MySQL 8
- **Cache/Queue:** Redis
- **Search Engine:** Meilisearch
- **Email Testing:** Mailpit
- **Browser Automation:** Selenium (Chromium)
- **Containerization:** Docker + Laravel Sail
- **Queue Worker:** Laravel Queue (Redis)

---

## **Persiapan Sistem**

1. Clone repository

```bash
git clone https://github.com/username/antrian-tts.git
cd antrian-tts
