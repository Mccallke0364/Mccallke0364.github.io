---
title: "Mathematics Department Scheduling Optimization" 
date: 2004-12-28
lastmod: 2024-07-12
tags: ["linear programming", "mathematics", "scheduling", "optimization", "CERCA"]
author: ["Annabelle Piotrowski", "Katherine McCallum", "Dr. Abra Brisbin"]
description: "This poster is on the optimization of the Mathematics Department Scheduling process using linear programming." 
summary: "This poster shows the progress of the project that optimizes preferences for scheduling classes for a semester in the mathematics department" 
cover:
    image: "content/posters/Scheduled linear programming/resized_Desk_Man.jpg"
    alt: "Man frustrated at his desk"
    relative: false
# editPost:
#     URL: "https://github.com/pmichaillat/hugo-website"
#     Text: "Journal of Canine Science"

---

---

##### Download

+ [Poster](CERCA_scheduling_poster_version_2.pdf)
+ [Presentation](DS_150_Final_Project_Presentation.pptx)
+ [PresentationPDF](DS_150_Final_Project_Presentation.pdf)
<!-- + [Paper](paper2.pdf)
+ [Online appendix](appendix2.pdf)
+ [Code and data](https://github.com/pmichaillat/wunk) -->

---

##### Abstract
Math Department Scheduling Using Linear Programming
Annabelle Piotrowski, Katherine McCallum, Dr. Abra Brisbin
Scheduling classes is a challenging and time-consuming task. The mathematical technique of linear
programming has the potential to simplify this challenge, by building a model of linear constraints to find the most
optimal solution that satisfies all the constraints. In this project, we are implementing a linear programming model
using the Cplex library in Python. The objective function represents instructor satisfaction with different courses
and the constraints represent limitations such as the fact that one instructor cannot teach two courses at the
same time. These constraints allow many ways to build a schedule. The goal of our program is to identify the
most optimal solution, that maximizes the professor's satisfaction and class availability. Our model can
successfully use binary variables to assign professors to classes at specific times during the week on a small
scale. We will present a system for encoding the preferences about class times and constraints about maximum
and minimum numbers of credits and classes, as well as a method of visualizing the resulting schedules. We will
also present preliminary results from an alternative method of encoding combinations of courses, times, and
professors, using meeting patterns instead of individual days of the week.

---
<!-- 
##### Figure 2: Dimensions of a sausage dog

![](paper2.png)

--- -->
<!-- 
##### Citation

Prinzel, Florianus, and Moritz-Maria von Igelfeld. 2004. "The Finer Points of Sausage Dogs." *Journal of Canine Science* 43 (2): 89–109. http://www.alexandermccallsmith.com/book/the-finer-points-of-sausage-dogs.

```BibTeX
@article{PI04,
author = {Florianus Prinzel and Moritz-Maria von Igelfeld},
year = {2004},
title ={The Finer Points of Sausage Dogs},
journal = {Journal of Canine Science},
volume = {43},
number = {2},
pages = {89--109},
url = {http://www.alexandermccallsmith.com/book/the-finer-points-of-sausage-dogs}}
```

--- -->

<!-- ##### Related material

+ [Presentation slides](presentation2.pdf)
+ [Wikipedia entry](https://en.wikipedia.org/wiki/The_Finer_Points_of_Sausage_Dogs) -->
