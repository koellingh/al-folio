---
layout: page
title: Gucci Mane Re-inspired
description: A series of twitterbots designed to arbitrarily generate inspirational tweets using the grammatical structures and vocabulary of a fixed set of inspirational tweets from Gucci Mane himself (@gucci1017)
img: /assets/img/gucci_mane.jpg
importance: 5
category: Digital Humanities
---

I aimed to emulate Victor Yngve’s computer pro-gram that used a grammar to generate text from the children’s book ”The Little Train”.  In substitution for ”The Little Train”, I used a series of inspirational tweets from Gucci Mane (@gucci1017).I separated each word from his tweets by its function in the sentence (nouns, adjectives, presentverbs, past verbs, etc.) and identified the different sentence structures in the tweets (commands,phrases, etc.). The grammar arbitrarily picks a sentence structure, and then fills that sentence structure with any of the vocabulary from the tweets. 

After  generating  a  bunch  of  inspirational  quotes, I chose my favorite to laser cut onto a plaque in the wood shop at Carleton.  The plaque includes the quote, a signature, and a roman numeral. The signature is an ice cream cone with lightning bolts coming out of the right side and the top of the cone; this cone is symbolic of Gucci Mane in that he has this tattooed on his right cheek. The roman numeral in the bottom right signifies the copy of the plaque; the one pictured below is the first copy made. There will be a total of two copies made.

Here is a list of Used Tweets:
- More action less talk!
- The more you learn the more you earn
- Time to go super hard.- Demand the most out yourself!
- Don’t be be scared to try.
- Go harder.
- Wake up go hard go to sleep repeat!
- Stay ready so you don’t have to get ready.
- Don’t underestimate yourself
- Think bigger.
- Work on yourself
- Stop being lazy.
- Watch who you take advice from
- Keep going.
- Stay focused.
- Believe it then achieve it
- The only thing you can do is do more!
- Whoever said it would be easy lied!
- Successful people do what unsuccessful people want to do.
- If you want it work for it!
- It ain’t gone be easy
- Losses are lessons!
- Just keep getting better!
- Life is real.
- It ain’t gone be easy!
- Health is wealth.
- Talk is cheap.
- I make moves not excuses.
- Water stops fire and love stops hate.
- United we ball divided we fall.


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
