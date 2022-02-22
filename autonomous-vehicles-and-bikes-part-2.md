---
title: Autonomous vehicles and bicycles part 2
subtitle: Why autonomous vehicles have a hard time identifying bicyclists and what is being down to counter that
layout: page
show_sidebar: false
menubar: past_articles_menu
---

## Part 2 - Can autonomous vehicles (AVs) sense bicycles? How sustainable are AVs? And how could current AV popularity shape the future of bicycling in the US?



### *Elaine Herzberg*

In March 2018, [Elaine Herzberg](https://usa.streetsblog.org/2019/03/08/uber-got-off-the-hook-for-killing-a-pedestrian-with-its-self-driving-car/) was struck and killed by an Uber owned self-driving vehicle out for a test drive, as she walked her bike across an Arizona street. She was the first AV-related pedestrian fatality. It should be noted, however, that a backup driver was behind the wheel, and the AEBs had been disabled, so the exact degree of the car’s (and by extension Uber’s) fault is indeterminate.[[1\]](#_ftn1) It was presumed that the car recognized neither Herzberg nor the shape of her bag-laden bicycle, suggesting a lack of thorough vetting for AV’s bicycle identification models. The difference between Tom’s and Elaine’s incidents, however, is that Tom was the unfortunate recipient of an operational braking system, attempting to circumvent collision with a pedestrian. Elaine on the other hand, was the pedestrian in this case, however, the system was not operational, nor did it detect her existence until it was too late. 

![](C:\Users\bleoh\OneDrive\Documents\GitHub\bulma-clean-theme\img\Git hub bikes\Elaine Herzberg Uber car.jpg)

/img/Elaine Herzberg Uber car.jpg



![Elaine Herzberg bike](C:\Users\bleoh\OneDrive\Documents\GitHub\bulma-clean-theme\img\Git hub bikes\Elaine Herzberg Uber car.jpg)

![Elaine Herzberg bike](C:\Users\bleoh\OneDrive\Documents\GitHub\bulma-clean-theme\img\Git hub bikes\Elaine Herzberg bike.jpg)

<img src="C:\Users\bleoh\OneDrive\Documents\GitHub\bulma-clean-theme\img\Git hub bikes\Elaine Herzberg.jpg" alt="Elaine Herzberg" style="zoom: 33%;" />

According to [a report](https://www.ntsb.gov/investigations/AccidentReports/Reports/HAR1903.pdf) released by the National Transportation Safety Board (NTSB) after the accident, the vehicle had flashed a warning of a potential object in the roadway, but only 5.6 seconds before impact. Within this period, the vehicle classified Elaine as another vehicle, an unidentifiable object, a pedestrian, and a bicyclist. While ample theoretical inquiry could debate the culpability of Uber and its alleged technological corner-cutting, what is important for this article is why the system wasn’t able to identify her, and furthermore, predict her movements (i.e. how fast she was going, what orientation she exhibited, what direction she was moving). And with that, how much did her bike affect the way she was perceived?

### **Autonomous Vehicle Collision Stats**

*AV Collisions*

Despite sensationalist belief, Elaine’s tragedy was not usual. Or else, her accident – a head on collision – was not representative of most of the kinds of accidents that self-driving vehicles engage in. In the US especially, we are prone to think that fatal high-speed collisions are the norm for the AVs, given media coverage of such incidents as Elaine’s and also Tesla’s [numerous highway crashes](https://insideevs.com/tag/tesla-autopilot/). Nonetheless, [tentative research](http://www.umich.edu/~umtriswt/PDF/UMTRI-2015-34_Abstract_English.pdf]) from 2019 has shown that in actuality, rear-end collisions encompass the majority of AV accidents at 64.2%, a staggeringly high number considering that the next most frequent accident type for AVs are angle crashes (those that mostly occur at intersections where cars going at perpendicular directions or turning onto another roadway, collide) at 31.4%. Even [conventional vehicles](https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812981) (CVs) with a human driver don’t get close to that rear ending stat; only 28.3% of motor vehicle accidents in the US are rear ends (Though rear-end and angle collisions are still the first and second most common crash type for conventional vehicles). On top of all that, AVs are far more likely to be rear-ended by other vehicles than to do the rear-ending themselves. It’s speculated that this is due to the unconventional way AVs drive. In sticking to the letter of the law as they are programmed to do, they tend to confuse human drivers who are more likely to speed, tailgate, hug the side line, shoot the gaps etc. And, as AVs are hyper aware of any pedestrians or vehicles in front of them, they are more likely to fully stop for their protection, encountering situations where human drivers may instead slow down, make a wide berth, or, if what the AV was perceiving wasn’t actually another person at all, keep on at normal speed.

Perhaps not surprisingly, because of this, AVs have a higher accident rate per miles traveled than conventional vehicles. A study from 2015 calculated that human drivers averaged anywhere from 1.9 – 4.1 crashes per million miles traveled (mmt).[[2\]](#_ftn2) AVs, on the other hand, average about 9.1 crashes per mmt. An alarming stat on the surface; however, as these accidents are largely in the form of rear-endings from other vehicles, they are not nearly as fatal or injurious as conventional vehicle crashes. On top of that, almost ¾ of the crashes occurred with the AV going at a speed of 5mph or lower; however, this again, is probably due to the excessively cautious driving style employed by AVs. But it should be noted that the report doesn’t detail how fast the other vehicles were going and thus how great of an impact the other drivers felt. 

While this study, [and others like it](https://www.sciencedirect.com/science/article/pii/S2352146520301654), provide confident results, three caveats need to be recognized. 1.) AVs, unfortunately don’t exist in the quantities needed to make meaningful comparisons with conventional vehicles. The data acquired from DMV[[3\]](#_ftn3) of combined accident rates for conventional vehicles totals nearly 3 trillion miles as opposed to 1.2 million by AVs. Put another way, that’s 1 AV mile for every 2,500,000 CV mile (10 full vehicle life spans). In fact, [a report](https://www.rand.org/content/dam/rand/pubs/research_reports/RR1400/RR1478/RAND_RR1478.pdf) released by the RAND corporation (a nonprofit research institution) concludes that 100 AVs driving 24 hours a day, 365 days of the year, at an average speed of 25 mph, would need to drive for 12.5 years, or 275 million miles, to conclude with 95% confidence that their failure rate leads to at most 1.09 deaths per 100 million miles. A lot of numbers to process, but in essence, the sample size of this study was too small to make any generalizable statements. 2.) Another limitation the study notes is the context of the vehicle testing, or more specifically, where the vehicles were not tested – icy, stormy, or geographically unstable areas, or otherwise dangerous conditions. It’s unclear how many CVs are involved in accidents due to circumstances outside the driver’s control; it should thus be noted that AV collision results, could significantly differ depending on their location. 3.) The report specifies that none of the accidents AVs were involved in were the AVs fault, however, it’s unclear what they mean by “fault”. It could mean that the AVs didn’t collide with the other vehicles, and by that metric, it wasn’t the AV’s fault. Or it could mean, that the situations where the AVs stopped or slowed and CVs hit them were entirely justified (as in there may have been a pedestrian in the road) and therefore were not the AVs fault. However, as it has been suggested that so many rear-end accidents with AVs occurred because human drivers were surprised by the AVs behavior, I believe there is room to allow for AV culpability. If AVs are not following the intuitive rules of the road that every other driver subscribes to, they may lead to accidents that may have happened otherwise. Thus, I believe it’s prudent to reserve judgement on the exact safety viability of these stats until more information can be obtained.

**So, what of bikes?**

Bicyclists have had a contentious history with vehicles. Given their lack of protection, meeting in unexpected road combat with a vehicle will more than likely result in the [cyclist being injured](file:///D:/hogwash/cyclist injured) if not killed. In [2017](https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812765), 783 bicyclists died on US roadways[[4\]](#_ftn4); 96% (or 753) of those deaths involved a vehicle. Most of the time, this is due to simply not seeing the cyclist; bikes are small and often situated below the driver’s line of sight, and because of their maneuverability, they zip through traffic, perhaps coming up on a driver unawares; a driver may also neglect to check, as happens when opening a door into a bike lane. Either way, drivers are liable to fatally injure a cyclist whether they realize it or not. Take for example, [Katie Mckenna](https://www.rd.com/article/run-over-by-an-eighteen-wheeler/), a New York cyclist turned author and motivational speaker. She was run over by an 18-wheeled truck when it failed to notice her while maneuvering a right turn at an intersection. In [her book](https://www.amazon.com/How-Get-Run-Over-Truck-ebook/dp/B01LY9PYBR), she pulls no punches when identifying bicyclist’s vulnerability on the roadway; the first line queries, “So, how do you get run over by a truck? My first recommendation is to ride a bicycle”. According to her book, she signaled in every way possible that she was there, even wearing bright clothing. This is a sensationalist example, but one that exemplifies a common problem bicyclists have with surrounding vehicles.

[ How to Get Run Over by a Truck]



 ![AVs how to get run over by a truck](C:\Users\bleoh\OneDrive\Documents\GitHub\bulma-clean-theme\img\Git hub bikes\AVs how to get run over by a truck.jpg)

 

*AV Bike Troubles*

As it turns out, AVs have been having trouble with bikes since their inception. A [Slate article](https://slate.com/technology/2018/02/self-driving-cars-struggle-to-detect-cyclists-bicycle-to-vehicle-communications-arent-the-answer.html) cites UC Berkeley research engineer Steven Shladover acknowledging: “Bicycles are probably the most difficult detection problem that autonomous vehicle systems face.” Unlike cars, which have a blocky shape with lots of mass and volume, bikes have a smaller inconsistent shape. Even when bicyclists follow safe legal procedures for switching lanes, the AI can have difficulties interpreting the shapes in its visual field; a bike gets bigger, in a 2D sense, when going from the back to the side views. When viewing the back of a bike, it looks small and compact. And without a holistic understanding of a bicycle’s appearance, it would be hard to predict how far forward the bike extends. So, when viewing a bike from the side, it seems to get bigger and change shape, a seeming improvement for an automated vehicle’s sensing capabilities. However, even this is easily misinterpreted as the side view has more negative space between the wheels and the frame. Not only that but putting an arm out to signal direction, wearing eye catching clothing, or attaching saddle bags and baskets can change the appearance of a bicycle.

And AVs do have trouble interpreting information in their visual field. Tesla vehicles have been noted to confuse the side of close semi-truck with a far-off billboard, and gas station flags adorned with brightly colored loopy writing for stop lights. Google vehicles, while acting in a preferably cautious manner, noticed movements of a bicyclist maintaining balance at an intersection as a sign of forward movement.

The following images exemplify the difference perspective can have on how a bicycle is viewed.

 ![image-20220220144102487](C:\Users\bleoh\AppData\Roaming\Typora\typora-user-images\image-20220220144102487.png)



 

![image-20220220144127955](C:\Users\bleoh\AppData\Roaming\Typora\typora-user-images\image-20220220144127955.png)





Several other kinds of bikes, though not widely used, are still considered legal vehicles on the road, and could thus confuse an AV's technology.



![AV bike shapes 8](C:\Users\bleoh\OneDrive\Documents\GitHub\bulma-clean-theme\img\Git hub bikes\AV bike shapes 8.jpg)

![AV bike shapes 7](C:\Users\bleoh\OneDrive\Documents\GitHub\bulma-clean-theme\img\Git hub bikes\AV bike shapes 7.jpg)

![AV bike shapes 5](C:\Users\bleoh\OneDrive\Documents\GitHub\bulma-clean-theme\img\Git hub bikes\AV bike shapes 5.jpg)

![AV bikes shapes 1](C:\Users\bleoh\OneDrive\Documents\GitHub\bulma-clean-theme\img\Git hub bikes\AV bikes shapes 1.jpg)

![AV bike shapes 4](C:\Users\bleoh\OneDrive\Documents\GitHub\bulma-clean-theme\img\Git hub bikes\AV bike shapes 4.jpg)

![AV bike shape 6](C:\Users\bleoh\OneDrive\Documents\GitHub\bulma-clean-theme\img\Git hub bikes\AV bike shape 6.jpg)

![AV bike shapes 2](C:\Users\bleoh\OneDrive\Documents\GitHub\bulma-clean-theme\img\Git hub bikes\AV bike shapes 2.jpg)

![AV bike shapes 3](C:\Users\bleoh\OneDrive\Documents\GitHub\bulma-clean-theme\img\Git hub bikes\AV bike shapes 3.jpg)



[[1\]](#_ftnref1) Check out [this Medium article](https://onezero.medium.com/who-killed-elaine-herzberg-ea01fb14fc5e), which features an excerpt from *Who’s Driving Innovation*, a book by University of College London Associate Professor in Science and Technology Studies, Jack Stilgoe. It discusses every individual agent’s involvement and culpability in this tragedy, and how we can learn from it for future innovation

[[2\]](#_ftnref2) The variability is due to how many crashes tend not to be reported. Though 1.9 cpmm is a fixed number from the DMV, the researchers here estimated unreported ones as well, and put the actual US crash rate at about 4.1pmm.

[[3\]](#_ftnref3) AV manufacturers are required to report any crash or collision involving AVs within 10 days to the DMV.

[[4\]](#_ftnref4) This report was released by the National Highway Traffic Safety Administration. Unfortunately, I couldn’t pin down more recent stats. Also, they refer to cyclists as pedalcyclists here to include unicycles, tricycles, nonmotorized vehicles, and the like. I will only use bicyclists and cyclists in this article; thus, it’s important to note that these stats may be skewed as they include other kinds of pedal-operational vehicles.