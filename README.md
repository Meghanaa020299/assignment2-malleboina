 # assignment2-malleboina
# meghanaa malleboina
###### Dogra Art Museum

The museum has a collection of several objects of historical and cultural importance. Among the collections are the Rasmanjari series of the famed Bosohli miniature paintings and some main manuscripts like the beautifully illustrated **Shahnama** and **Sikandernama** in Persian.
***
# Jammu Domestic Airport
1. From the entrance of the airport,take a right and go straight on RS Pura Road for 4.5 miles.
2. Take a left and go for 5.5 miles where you can see Tawi bridge.
3. From Tawi bridge,go straight for 1 mile and take a right there.
4. After 0.5 miles on this road, you will come across Shree Ranbireshwar Temple.
5. Take a left there and go straight for 1.5 miles on this road, the destination will be on the left.

* Tawi Bridge
* Shree Ranbireshwar Temple
* City Chowk Park
* Rani Chadki Mahal

[about me](AboutMe.md)
***
# Must visit cities
The below table gives a short description about the famous places to visit in the particular cities. These cities are always filled with tourists throughout the year.

|City| Location to visit|time to spend|
|---:|---:|---:|
|Agra|Taj Mahal|2 hours|
|Chennai|Marina Beach|3 hours|
|Mysore|Mysore Palace|4 hours|
|Delhi|Red Fort|2 hours|
***
# Motivational Quotes
> To produce a mighty book, you must choose a mighty theme. *Herman Melville*

>If you have no critics, you’ll likely have no success. *Malcolm*
***
# Code Fencing
>How to change add to cart button text for variable products?

<https://stackoverflow.com/questions/73627989/how-to-change-add-to-cart-button-text-for-variable-products>
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
<https://css-tricks.com/snippets/wordpress/dump-all-custom-fields/>