## Exercises
1. Get the amount of cities per country in the database. Sort them by country, country_id.

2. Get the amount of cities per country in the database. Show only the countries with more than 10 cities, order from the highest amount of cities to the lowest   

3. Generate a report with customer (first, last) name, address, total films rented and the total money spent renting films. 
   - Show the ones who spent more money first .

4. Find all the film titles that are not in the inventory. 

5. Find all the films that are in the inventory but were never rented. 
   - Show title and inventory_id.  
   - This exercise is complicated. 
   - hint: use sub-queries in FROM and in WHERE or use left join and ask if one of the fields is null

6. Generate a report with:
    - customer (first, last) name, store id, film title, 
    - when the film was rented and returned for each of these customers
    - order by store_id, customer last_name