# Ödev 6

1. film tablosunda bulunan rental_rate sütunundaki değerlerin ortalaması nedir?
```
SELECT AVG(rental_rate) AS AVG FROM film
```
2. film tablosunda bulunan filmlerden kaç tanesi 'C' karakteri ile başlar?
```
SELECT COUNT(title) FROM film WHERE title LIKE 'C%'
```
3. film tablosunda bulunan filmlerden rental_rate değeri 0.99 a eşit olan en uzun (length) film kaç dakikadır?
```
SELECT MAX(length) FROM film WHERE rental_rate = 0.99
```
4. film tablosunda bulunan filmlerin uzunluğu 150 dakikadan büyük olanlarına ait kaç farklı replacement_cost değeri vardır?
```
SELECT COUNT(DISTINCT replacement_cost) FROM film WHERE length > 150
```

## Patika.dev profilime gitmek için [tıklayınız](https://academy.patika.dev/tr/@mahsuniglr).
## Linkedin profilime gitmek için [tıklayınız](https://linkedin.com/in/mustafamahsuni).
## Github profilime gitmek için [tıklayınız](https://github.com/mahsuniguler).