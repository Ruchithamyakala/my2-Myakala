# my2-Myakala
# Ruchitha Myakala
### Goa
I like goa because of **amazing beaches** and goa is **world-famous** for its beach life.
-------
## "Activities at my favorite vacation spot" <br>
1.Scuba diving in malvan <br>
2.Trek to Todo waterfalls <br>
3.Snorkeling. <br>

## "List of food at my favorite spot"  
*Panneer <br>
*Biryani <br>
*Chicken fry <br>


[Link to MyStats](MyStats.md)
******
#### Tables
This table consists of sports that I play regularly. It also gives the reason why you should play this sports and the average hours that I play per week.

| Name of the sport | Reason | Hours/Average week |
| ------------------- | ------------------| ---------------|
| Badminton | Playing badminton helps strengthen the heart muscle and I feel like it decreases my stress levels. | 7 |
| Table tennis | Playing table tennis gives me a full-body workout and also helps me improve my strength and stamina. | 6 |
| Kho Kho |  Playing Kho Kho gives me immense stamina and speed skills.It gives me more energy to my body.| 5 |
| Kabaddi | Playing kabaddi increases coordination, concentration and stamina. It helps me to reduce my stress and mood levels and gives happiness. | 8 |
********
### Inspiring Quotations 
> The best and **most beautiful things** in the world cannot be seen or even touched -**they must be felt with the heart** <br>
> The best **preparation** for tomorrow is doing your **best today** - *H.Jackson Brown,Jr.*
********
## Code Snippet 

> I'm trying to retrieve the value from a Custom field as below. It doesn't seem to get any value. Please point out the mistakes in it.[https://stackoverflow.com/questions/66293239/wordpress-how-to-retrieve-custom-field-data-from-the-page]
~~~
<h3>All Post Meta</h3>

<?php 

  // Get all the data 
  $getPostCustom = get_post_custom(); 

    foreach($getPostCustom as $name=>$value) {

        echo "<strong>" . $name . "</strong>"."  =>  ";

        foreach ($value as $nameAr=>$valueAr) {
                echo "<br />";
                echo $nameAr."  =>  ";
                echo var_dump($valueAr);
        }

        echo "<br /><br />";

    }
?>

~~~
<br>
Dump All Custom Fields [https://css-tricks.com/snippets/wordpress/dump-all-custom-fields/]

