# Mushroom Identification

## Introduction

In this project, we will explore the different characteristic of mushrooms and how to recognize them as edible or poisonous.
Data set description :

This data set includes descriptions of hypothetical samples corresponding to 23 species of mushrooms drawn from the Audubon Society Field Guide to North American Mushrooms (1981). Each species is identified as definitely edible or definitely poisonous. This latter class was combined with the poisonous one. Each data entry has the full attribute name for each category. This make the data set easier to work with and to be less frustrated in figuring out the meaning behind each record. The Guide clearly states that there is no simple rule for determining the edibility of a mushroom; no rule like "leaflets three, let it be'' for Poisonous Oak and Ivy.

We will try to actually see if we can find a pattern of rules for determining the edibility of a mushroom.


## Data Dictionary form the original csv

| Field | attribut |
| :--- | :--- |
|classes| edible=e, poisonous=p |
|cap-shape| bell=b,conical=c,convex=x,flat=f, knobbed=k,sunken=s|
|cap-surface| fibrous=f,grooves=g,scaly=y,smooth=s|
|cap-color| brown=n,buff=b,cinnamon=c,gray=g,green=r,pink=p,purple=u,red=e,white=w,yellow=y|
|bruises| bruises=t,no=f|
|odor| almond=a,anise=l,creosote=c,fishy=y,foul=f,musty=m,none=n,pungent=p,spicy=s|
|gill-attachment| attached=a,descending=d,free=f,notched=n|
|gill-spacing|close=c,crowded=w,distant=d|
|gill-size| broad=b,narrow=n|
|gill-color| black=k,brown=n,buff=b,chocolate=h,gray=g, green=r,orange=o,pink=p,purple=u,red=e,white=w,yellow=y|
|stalk-shape| enlarging=e,tapering=t|
|stalk-root| bulbous=b,club=c,cup=u,equal=e,rhizomorphs=z,rooted=r,missing=?|
|stalk-surface-above-ring| fibrous=f,scaly=y,silky=k,smooth=s|
|stalk-surface-below-ring|fibrous=f,scaly=y,silky=k,smooth=s|
|stalk-color-above-ring|brown=n,buff=b,cinnamon=c,gray=g,orange=o,pink=p,red=e,white=w,yellow=y|
|stalk-color-below-ring| brown=n,buff=b,cinnamon=c,gray=g,orange=o,pink=p,red=e,white=w,yellow=y|
|veil-type|partial=p,universal=u|
|veil-color| brown=n,orange=o,white=w,yellow=y|
|ring-number| none=n,one=o,two=t|
|ring-type| cobwebby=c,evanescent=e,flaring=f,large=l,none=n,pendant=p,sheathing=s,zone=z|
|spore-print-color| black=k,brown=n,buff=b,chocolate=h,green=r,orange=o,purple=u,white=w,yellow=y|
|population| abundant=a,clustered=c,numerous=n,scattered=s,several=v,solitary=y|
|habitat| grasses=g,leaves=l,meadows=m,paths=p,urban=u,waste=w,woods=d|


## Data Dictionary after modification

| Field | attribut |
| :--- | :--- |
|index|------|
|name|------|
|edibility| edible, poisonous |
|cap-shape| bell, conical, convex, flat, knobbed, sunken |
|cap-surface| fibrous, grooves, scaly, smooth |
|cap-color| brown ,buff, cinnamon, gray, green, pink, purple, red, white, yellow |
|bruises| bruises, no |
|odor| almond, anise, creosote, fishy, foul, musty, none, pungent, spicy |
|gill-attachment| attached, descending, free, notched |
|gill-spacing| close, crowded, distant |
|gill-size| broad, narrow |
|gill-color| black, brown, buff, chocolate, gray, green, orange, pink, purple, red, white, yellow |
|stalk-shape| enlarging, tapering |
|stalk-root| bulbous, club, cup, equal, rhizomorphs, rooted, missing |
|stalk-surface| fibrous, scaly, silky, smooth |
|stalk-color|brown, buff, cinnamon, gray, orange, pink, red, white, yellow|
|veil-type|partial, universal |
|veil-color| brown, orange, white, yellow |
|ring-number| none, one, two |
|ring-type| cobwebby, evanescent, flaring, large, none, pendant, sheathing, zone |
|spore-print-color| black, brown, buff, chocolate, green, orange, purple, white, yellow |
|population| abundant, clustered, numerous, scattered, several, solitary |
|habitat| grasses, leaves, meadows, paths, urban, waste, woods|


## Important Links

* [Final Report Notebook](report.ipynb)
* [EDA Notebook](eda.ipynb)

* [kaggle mushroom classification](https://www.kaggle.com/uciml/mushroom-classification) - The first mushroom classification data set 
* [kaggle mushroom classification updated](https://www.kaggle.com/hatterasdunton/mushroom-classification-updated-dataset) - The updated mushroom classification data set

##   If you want to know more about mushrooms 

* [wildfooduk mushroom-guide](https://www.wildfooduk.com/mushroom-guide/) - Identifying Edible and Poisonous Wild Mushrooms in UK 
* [britannica](https://www.britannica.com/list/7-of-the-worlds-most-poisonous-mushrooms) - 7 of the World’s Most Poisonous Mushrooms
* [Psilocybin mushroom](https://en.wikipedia.org/wiki/Psilocybin_mushroom) - aka 'magic mushroom'
