# Homework 2

For this homework, please use the file ['Three men in a boat.txt'](https://github.com/tbkazakova/DataAnalysis2025-theorling/blob/main/data/Three%20men%20in%20a%20boat.txt).

## 1. Frequent words (3 points)
What are the most common words in the file? Print the top-20 words and their number of occurrences.

Example:
```
the  5465
of  3167
...
and  3042
to  2761
a  2052
```

## 2. Chapter Summary (4 points)

The first paragraph after the chapter number usually contains a summary of the chapter.

For example:
```
CHAPTER I.
 Three invalids.—Sufferings of George and Harris.—A victim to one hundred and seven fatal maladies.—Useful prescriptions.—Cure for liver complaint in children.—We agree that we are overworked, and need rest.—A week on the rolling deep?—George suggests the River.—Montmorency lodges an objection.—Original motion carried by majority of three to one.
...
CHAPTER II.
 Plans discussed.—Pleasures of “camping-out,” on fine nights.—Ditto, wet nights.—Compromise decided on.—Montmorency, first impressions of.—Fears lest he is too good for this world, fears subsequently dismissed as groundless.—Meeting adjourns.
```
Find such summaries and save them in a dictionary in which the keys are chapter numbers and the values ​​are summaries without the "-" symbols.

For example:
```
{'I': 'Three invalids. Sufferings of George and Harris. (...) Original motion carried by majority of three to one.',
'II': 'Plans discussed. Pleasures of “camping-out,” on fine nights. Ditto, wet nights. (...) Meeting adjourns.'
...}
```
Find such summaries and save them in a dictionary in which the keys are chapter numbers and the values ​​are summaries without the "-" symbols. (There are 19 chapters in the text.)

## 3. No pictures (3 points)
This file marks the places where there were pictures in the book.

For example:
```
[Picture: Graphic of three men in a rowing boat]
...
[Picture: Montmorency] 
```

Remove all such references to pictures from the text and save the remaining text to `no_pictures.txt` file.

Tip: use regular expressions.


