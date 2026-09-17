# SQL_sakila-project
A broad exploratory data analysis using a sample database in MySQL

## About the Database
Sakila databases is a sample database in MSQL that allows beginners to practice, learn and get familiar with SQL

### Few sample questions 
*1. List all films with a rental rate greatwer than 2.99*

```
select * from film where rental_rate > 2.99;
```

*2. Find the total number of films in each category, ordered from highest to lowest*

```
select name, category_id, count(film_id) as total_high from film_category join category using (category_id) group by name, category_id order by total_high desc;
```

[LinkedIn](https://www.linkedin.com/in/shukurat-ayomide-248363437)

