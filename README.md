# Restful Booker API Testing

## Layihə haqqında

Bu layihə Postman vasitəsilə Restful Booker API üzərində Manual API Testing bacarıqlarını inkişaf etdirmək məqsədilə hazırlanmışdır.

Layihədə autentifikasiya, CRUD əməliyyatları, müsbət (Positive) və mənfi (Negative) test ssenariləri, həmçinin avtomatlaşdırılmış Postman testləri hazırlanmışdır.

## İstifadə olunan alətlər

- Postman
- REST API
- JavaScript
- GitHub

## Authentication

- Token yaradılması

## CRUD əməliyyatları

- Booking yaratmaq
- Booking məlumatını əldə etmək
- Bütün booking-ləri əldə etmək
- Booking məlumatını yeniləmək
- Booking-i silmək
- Silinmiş booking-in yoxlanılması

## Positive Test Ssenariləri

- Token uğurla yaradılır
- Booking uğurla yaradılır
- Booking məlumatı düzgün qaytarılır
- Booking uğurla yenilənir
- Booking uğurla silinir
- Silinmiş booking üçün 404 qaytarılır

## Negative Test Ssenariləri

- Yanlış login məlumatları
- Mövcud olmayan Booking ID
- Token olmadan Update əməliyyatı
- Token olmadan Delete əməliyyatı
- Yanlış endpoint
- Boş Body ilə Booking yaratmaq

## Avtomatlaşdırılmış Testlər

Layihədə aşağıdakı yoxlamalar aparılmışdır:

- Status Code yoxlanışı
- Response Body yoxlanışı
- Response Time yoxlanışı
- Məlumatların doğruluğunun yoxlanışı
- Authentication yoxlanışı

## Environment Variables

- baseUrl
- token
- bookingId

## Collection Runner

Bütün request-lər Collection Runner vasitəsilə ardıcıl şəkildə icra olunur və bütün testlər uğurla tamamlanır.

## Repository 

- Postman Collection
- Postman Environment
- README.md
