---
layout: page
title: Translating Artificial Versifying
description: English Versification for the Billion: Translating the Early Latin Poetry Generator "Artificial Versifying" (1677)
img: /assets/img/artificial_versifying.jpg
importance: 4
category: Digital Humanities
---

Amid the Great Plague of London (1665–1666), a man named John Peter developed a peculiar system allowing for the procedural generation of Latin poetry. A decade later, in 1677, Peter's system was published in a landmark booklet, titled "Artificial Versifying," whose subtitle proclaims that anyone "that only knows the A.B.C. and can count 9" may use it to produce "true Latin, true verse, and good sense".

The system itself centers on six tables in which letters are distributed across grids of cells. To generate a line of poetry, the user first produces a string of six digits (e.g., "952129"). Next, each digit is used to retrieve a sequence of letters from the table corresponding to that digit's position in the string. The letters obtained from a given table form one of nine words contained in that table, and the concatenation of the six chosen words constitutes a line of Latin verse in dactylic hexameter. The system is capable of generating 9^6, or 531,441, lines of verse.

As a bizarre forerunner of electronic literature, "Artificial Versifying" was wildly successful: the booklet appeared in three editions, and its procedure was reprinted in books and periodicals for the next 200 years. Sadly, Peter's innovative system has received scant treatment by scholars working in this area today. This limited coverage is incommensurate to its importance as a groundbreaking work produced centuries ahead of its time. Indeed, its combinatorial method is similar to those employed in early computer poetry, such as Theo Lutz's "Stochastische Texte".

We have carried out the first translation into English of the "Artificial Versifying" system. While it would be easy to translate any one of the 531,441 hexameter verses that the system can produce, we sought instead to translate the system itself into English. This only entailed translating the 54 words in the six tables, but the process raised a number of interesting challenges nonetheless. The major difficulty is in preserving both meaning and meter, and in total we identified twelve features of the original system that we sought to maintain. In wrangling with interrelations between these features at the level of combinatorics, our design space was not unlike Peter's. While a core aim of this process has been to make "Artificial Versifying" accessible to non-Latin speakers today, this act of translation has helped us to better appreciate the triumph of the system's design.

While our project seeks to celebrate an unheralded pioneering effort in the area that became electronic literature, we situate this work amid emerging scholarship on the challenges and opportunities of translating computational textual artifacts. This subarea of translation studies is perhaps best characterized by the Renderings project carried out by Nick Montfort, Piotr Marecki, and other collaborators in the last decade, though others have taken it up. In this paper, we will show that the peculiar considerations inherent in the translation of computational textual artifacts are already present in protocomputational works that are sufficiently procedural, such as "Artificial Versifying."

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/1.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/3.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/5.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/5.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal it's glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/6.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/11.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/" target="_blank">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/6.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/11.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
```
