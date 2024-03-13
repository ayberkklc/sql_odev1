# sql_odev1
<br></br><b> Soru 1 </b> 
SELECT title, description FROM film
<br></br><b> Soru 2 </b> 
SELECT * FROM film 
WHERE length > 60 AND length < 75
<br></br><b> Soru 3 </b>
SELECT * FROM film 
WHERE rental_rate = 0.99 AND replacement_cost = 12.00 OR replacement_cost = 28.99
<br></br><b> Soru 4 </b>
SELECT * FROM customer
WHERE first_name = 'Mary' 
<em><i>Mary Smith </em></i>
<br></br> <b> Soru 5</b>
SELECT * FROM film
WHERE NOT length > 50 AND NOT (rental_rate = 2.99 OR rental_rate = 4.99)





