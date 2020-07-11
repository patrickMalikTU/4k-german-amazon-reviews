# 4k-german-amazon-reviews
## General
This is a collection of 4000 German Amazon-Reviews.
The Reviews were handpicked from the ''Bücher'' and ''DVD & Blu-ray'' sections of amazon. Duplicates were avoided as much as possible and all of the Datapoints were checked for correct spelling and somewhat correct grammar. Reviews with grave mistakes in those departments were corrected, if those changes did not destroy the original meaning and general structure of the review. Punctuation was also added, if needed. Most of those checks were done with the online spellchecker of Duden. (https://www.duden.de/rechtschreibpruefung-online). Certain words that would not be recognized as proper german, but are common expressions were kept in, also various grammatically interesting sentences were kept.
In general only reviews that do not go on about the contents of the respective medium were chosen, also inappropriate comments were not considered and therefore did not make it into this collection.
Since I did not need reviews with a 3-star rating, there are none in this collection.

##  Structure
To make those Datapoints as easy-to-use as possible, every category (1-, 2-, 4- and 5-stars) is represented by a file with the respective name and 1000 reviews of that category. Each line contains one review, and a review does not have any line breaks.
The order of the reviews within those files is not randomized, but still in the order they were picked in.
To make further processes easier, they are in a simple .txt format.

## Translations
The translations-folder contains all the reviews translated from german into english, by microsoft azure's translation-service. They are in the same order as their german counterparts.