# Childproofing: Heavy Objects

One of the most common concerns for child safety is the potential injuries occuring from heavy objects, such as TVs, heavy objects on open shelves, heavy objects placed on kitchen countertops, etc. The best way to child proof is to move potentially dangerous items from the reach of children or to mount them in a way that a child cannot move them. AI can help identify those potentially dangerous items by detecting their placements in a home and alert the users. Our Deep learning model serves a great purpose to child proof homes without consulting childproofing experts and if this model is embedded into baby/child monitoring products such as ULO it could make users home safe in real time.

**Motivation behind our model Use Cases**

About every 30 minutes tipped furniture or falling TV sends a child to the emergency room,reports also showed that 349 people were killed between 2000 and 2011 by a falling television, appliance or piece of furniture -- 84 percent of them were kids younger than 9 years old. Falling televisions were more deadly, accounting for 62 percent of these fatalities.

![unsafe TV](https://wmsrc-1x1yusplq.stackpathdns.com/wp-content/uploads/2015/06/toddler-climbing-TV-e1434340192118.jpg)

we built out model to diffrentiate between safe(anchored to wall) and unsafe tv's(tv on top of tables ,furniture etc).

One more prominent hazard from heavy objects is presence of heavy items, such as electronics, cluttered books,aplliances on top of dressers, large furniture ,open shelves etc.

![unsafe shelves](https://www.anchorit.gov/wp-content/uploads/2014/05/11.jpg)

![unsafe shelves](https://cdn.onecrazyhouse.com/wp-content/uploads/2016/02/clever-ways-to-hide-clutter-1.jpg)


Our model can detect this kind of potential hazards and intimate the user.


Our model can detect the presence of heavy objects such as microwave ovens(not anchored) and other dangerous clutter in kitchen countertops which may be a potentail threat to children.


![unsafe kitchen](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSMe2uaxRuVxQ1OYHdzXRF3Agt26Ks62Gtsvr7tQZRilltQmDHpzw)


we built our model to alert the presence of unsafe furniture and unsafe tv at a time in one picture.
 
 
![multiple threats](https://i1.wp.com/www.gritsngrace.com/wp-content/uploads/2016/11/IMG_0963.jpg?ssl=1)

this picture has open shelf with heavy objects and unmounted tv.


**Model**

we are using Multi label classifier based on Resnet 34 using fast AI.

