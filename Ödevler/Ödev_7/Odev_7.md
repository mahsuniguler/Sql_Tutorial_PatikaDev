# Ödev 7

1. film tablosunda bulunan filmleri rating değerlerine göre gruplayınız.
```
SELECT rating, count(*) FROM film GROUP BY rating
```
2. film tablosunda bulunan filmleri replacement_cost sütununa göre grupladığımızda film sayısı 50 den fazla olan replacement_cost değerini ve karşılık gelen film sayısını sıralayınız.
```
SELECT replacement_cost, COUNT(*) FROM film GROUP BY replacement_cost HAVING COUNT(*) > 50
```
3. customer tablosunda bulunan store_id değerlerine karşılık gelen müşteri sayılarını nelerdir? 
```
SELECT store_id, COUNT(*) FROM customer  GROUP BY store_id
```
4. city tablosunda bulunan şehir verilerini country_id sütununa göre gruplandırdıktan sonra en fazla şehir sayısı barındıran country_id bilgisini ve şehir sayısını paylaşınız.
```
SELECT country_id, COUNT(city) FROM city GROUP BY country_id ORDER BY COUNT(city) DESC LIMIT 1
```

## Patika.dev profilime gitmek için [tıklayınız](https://academy.patika.dev/tr/@mahsuniglr).
## Linkedin profilime gitmek için [tıklayınız](https://linkedin.com/in/mustafamahsuni).
## Github profilime gitmek için [tıklayınız](https://github.com/mahsuniguler).