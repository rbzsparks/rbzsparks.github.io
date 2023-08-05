---
layout: default
title: personal
permalink: /personal
---

<div class="main_carousel">
        {% for image in site.data.carousel %}
        <div class="carousel_element">
        <img src="{{site.url}}{{site.baseurl}}/images/carousel/{{image.image}}" width="100%" alt="{% if image.alt %}{{image.alt}}{% else %}{{image.label}}{% endif %}"/>
        <p>{{image.label}}</p>
        </div>
        {% endfor %}
    </div>

<script>
        $(".main_carousel").slick({
        dots: true,
        speed: 1000,
        adaptiveHeight: true,
        autoplay: true,
        slidesToShow: 1,
        //fade: true,
        responsive: [
            {
            breakpoint: 480,
            settings: {
                slidesToShow: 1,
                slidesToScroll: 1,
            }
            }
        ]
        });
 </script>

### Background

 I was born and raised in Illinois, and spent most of my time growing up in Plainfield. I was frequently between two households, one with my single father and another with my mother, stepfather, older half-brother, and younger half-sister. After my mother and stepfather divorced, I spent far less time with my father and was moved between 5 homes over a 6-year period between elementary school and early high-school. These transitions were also paired with concerns about financial security, my family's well-being, and my sexuality. The turbulence, tension, and underlying causes of these transitions often felt impairing, but I also was still able to grow into a young adult who had many close friends, could care for himself & others, worked often while taking advanced classes, and "succeeded" enough to end up at Stanford University as a First-Generation college student. My model of the world looks very different from others' models (and vice-versa), so how did I get here? My personal context informs many of my interests and guides my approach to my work: one that is compassionate, authentic, and in-servce of my communities and others who have also wanted life to feel even just a li'l less heavy. 
 <br>

### Other Fun Facts

* My siblings and I all have different fathers, so I am both the "Middle" child, and an only child :\)

* I have an extensive background in the service industry, including 5 years at a Panera Bread, 1 year as a waiter at [Johnston's SaltBox](http://johnstonsaltbox.com/) (if you're in the Bay, Go - top tier Brunch), and 1 year as a Barista at StarBucks during COVID. I'm very proud of my service industry background and like to believe I'm both a better person and worker for it!

* When I was much younger, I played Wizard101 and somehow found myself as an admin on a [Community Wiki Website](https://www.wizard101central.com/wiki/Wizard101_Wiki) for the game. I did this through High School and really thought I would study Computer Science because of it. I was wrong :\] (but was able to pick up some useful front-end skills)

* When I was 13, I flew alone to New York to visit family (my dad's entire side is on Long Island). When I got to Baltimore for a layover, my flight was cancelled. In short, every single flight I was put on after that was cancelled. A kind woman I met at the airport offered to rent a car and drive us from Baltimore to Long Island, and I went along with it. Janet, if you ever see this, thank you for the ride and Wendy's Nuggets! Mom, if you see this, I'm sorry I told you I got on a plane and landed safely in LI. <br>

### Personal Interests

I welcome chats about any of these fun things!

**Music**: And I mean listening, I have absolutely no musical talent to speak to! Beyoncé is my number 1, I love her music and love getting to experience her art (attended Formation World Tour in May 2016 and Renaissance in August 2023). Other music favs: Dermot Kennedy, Chloe, FLO, Doja Cat, Omar Apollo, Jazmine Sullivan, & Jeremy Zucker.

**Cooking**: My mother and father have always been incredible cooks, and from an early age I wanted to be a chef (though, my grandmother told me this was only a hobby). I (and most of my immediate family) take great pride in my cooking and enjoy trying and improvising new recipes. Perhaps my favorite form of relaxation :\)

**Movies & Shows**: Big Little Lies, The Boys, The Real HouseWives, Vanderpump Rules, Modern Family, Horror Movies (Jeeper's Creepers, A NightMare on Elm Street, Halloween, Get Out, The Menu, House of Wax), Pretty Little Liars, Scooby Doo 2: Monsters Unleashed, Small Soldiers, Shrek 2

**Childhood Favorites**: Power Rangers, Pokémon, Elmo, Barney, Scooby Doo, Krypto the Super Dog, Max & Ruby, Bakugan, Strawberry Short Cake, Kid Cuisine, Naruto, Furby


    


