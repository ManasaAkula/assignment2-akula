### Manasa Akula
I am Manasa Akula. I am passionte about learning new technologies so, I choose computers as my major. I am currently pursuing my masters in applied computer science at Northwest missouri state university.

[My Profile Photo](Manasa_Akula.jpg)
 
 -----
## Countries to visit
I want to visit the countries that are mentioned in below table. Which are the top destinations for travelers to spend the quality time. There are four countries and reasons to visit are mentioned below.

| Country Name | Reasons to visit | Days to spend |
|   -----    | ----- | ----- |
| Spain | Madrid, the capital of Spain and its center of culture, commerce, and government, is one of the most diverse cities in Europe and one of the top destinations for travelers. The vibrant nightlife, delicious tapas, and some of the top art museums in all of Europe make the central neighborhoods an exceptionally fun place to visit. | 15 days |
| Switzerland | The European nation of Switzerland is stunning. It is one of the most well-liked travel destinations in the globe because it has a lot to offer tourists. It has mountains, lakes, and waterfalls, drawing thousands of tourists each year. Switzerland is renowned as the home of cheese and chocolate.| 20 days|
| Turkey | The majority of Turkey's tourist attractions are historical sites and beach resorts around the Aegean and Mediterranean Seas. In addition, Turkey has gained popularity as a spa, wellness, and cultural getaway. | 10 days|
| Australia | One of the most desirable travel destinations in the world is Australia, with its stunning natural surroundings, multicultural cultures, top-notch food and wine, weather, way of life, and welcoming and outgoing population. | 15 days |

----
# Funny Quotes

>  “It's not true that I had nothing on. I had the radio on.” *-Marilyn Monroe*

>  “I’m writing a book. I’ve got the page numbers done.”  *-Steven Wright*

----
## Code Fencing
### PHP Code

> How to make automatic copyright webpage footer in php using a function?

Question Link <https://stackoverflow.com/questions/16415898/how-to-make-automatic-copyright-webpage-footer-in-php-using-a-function/16415925#16415925>


```
<?php function auto_copyright($year = 'auto'){ ?>
   <?php if(intval($year) == 'auto'){ $year = date('Y'); } ?>
   <?php if(intval($year) == date('Y')){ echo intval($year); } ?>
   <?php if(intval($year) < date('Y')){ echo intval($year) . ' - ' . date('Y'); } ?>
   <?php if(intval($year) > date('Y')){ echo date('Y'); } ?>
<?php } ?>

```
Link to access the code snippet <https://css-tricks.com/snippets/php/automatic-copyright-year/>
 