# "The Flavor Text of Middle Earth" Infographic

![](https://github.com/bennkeel/LOTR/blob/master/Infographic_Final.png)

Whenever a Magic set or show captures me, I often get a wild idea to make something in response. For instance, I loved Ikoria's fit with the Monster Hunter series, so I made a [crossover video](https://www.reddit.com/r/magicTCG/comments/gcgnw2/mtgmhw_crossover_concept_clip/). This project aligned with my need to practice R and Python while job hunting after grad school.
s
For this set, nearly all if not all the flavor text comes from the Lord of the Rings books either as direct quote or paraphrasing. I was captured by the a fruitful sense of discovery when reading the book again and finding the sentence these different cards reference. I was curious where the most flavor texts fall in the series, if they group up in interesting ways or not. I marked up a few observations on the graphic itself.

## Process:
1.  Forked this repository from @jblazzy
2.  Scraped the card list and flavor text and card cost of all black-border cards in [Scryfall's card image gallery](https://scryfall.com/sets/ltr?order=set&as=grid). See "FT_Scrape_1.ipynb" file for notebook of Beautiful Soup and Pandas code.
3. Imported this data set into R, cleaned the text, and found all but 15 matches for 194 cards. Explore that code in the [R Markdown](https://github.com/bennkeel/LOTR/blob/master/TalesOfMiddleEarth.html)
4.  Manually confirmed matches for 15 missing cards and for the ~15 that had conflicted matches based on the order of the search.
5.  Graphed the count of items by color and chapter, and split them by color.
![](https://github.com/bennkeel/LOTR/blob/master/images/Graph_1.jpg)
![](https://github.com/bennkeel/LOTR/blob/master/images/facet_wrap color graph.jpg)
6.  Built the layout scene of the 3D model using [this book asset](https://sketchfab.com/3d-models/book-28e028e981604aacb25766852aa279ed).
7.  Imported the graph and manually placed the tabs into the books.
![](https://github.com/bennkeel/LOTR/blob/master/modelRef_3.jpg)
9.  Adjusted the composition, textured the books and cards through Blender UV's and Photoshop. Adjusted their material shaders to work well with the lighting.
![](https://github.com/bennkeel/LOTR/blob/master/modelRef_1.jpg)
10.  Exported the rendered result into Illustrator, and made all text edits there. "Middle Earth" font [sourced here](https://www.fontspace.com/category/lord-of-the-rings).
