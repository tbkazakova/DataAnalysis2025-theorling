# Homework 4

Notebook from the seminar: https://github.com/tbkazakova/DataAnalysis2025-theorling/blob/main/seminars/251212_html.ipynb

Choose any non-English website that contains news, articles, or other texts on different web pages, and a page that links to them.
1. Write code to get the title and text from one page. (2 points)
2. Write code that takes at least 20 links from the main page(s) and then get their titles and texts with the code from the previous step. (3 points)
3. (+ 1 point) If you also get the publication date, author, or some other information.
4. Create a dataframe that contains at least three columns: link (to the page), title, text. (1 point)

|link|title|text|...|
|-|-|-|-|
|https://www.buonenotizie.it/cultura-e-tempo-libero/2025/12/12/mercatini-di-natale-2025/giulia-mastrocicco/|Mercatini di Natale 2025: una piccola guida alternativa tutta Italiana|Dicembre è alle porte e nell’aria si respira lo spirito natalizio. (...) A chi cerca di vivere l’atmosfera natalizia, lontano dalla frenesia delle mete più gettonate, con la nostra piccola guida dal Sud al Nord non resta che scegliere dove andare per lasciarsi sorprendere dalla magia del Natale.|...|

5. Translate the texts into English using a ready-made library. Save the translations in a column. (2 points)

|link|title|text|...|translation|
|-|-|-|-|-|
|https://www.buonenotizie.it/cultura-e-tempo-libero/2025/12/12/mercatini-di-natale-2025/giulia-mastrocicco/|Mercatini di Natale 2025: una piccola guida alternativa tutta Italiana|Dicembre è alle porte e nell’aria si respira lo spirito natalizio. (...) A chi cerca di vivere l’atmosfera natalizia, lontano dalla frenesia delle mete più gettonate, con la nostra piccola guida dal Sud al Nord non resta che scegliere dove andare per lasciarsi sorprendere dalla magia del Natale.|...|December is upon us and the Christmas spirit is in the air. (...) For those looking to experience the Christmas atmosphere, away from the frenzy of the most popular destinations, with our little guide from South to North, all that's left to do is choose where to go to be surprised by the magic of Christmas.|

* You can use [`googletrans`](https://pypi.org/project/googletrans/) or any other library.
```
! pip install googletrans
from googletrans import Translator
translator = Translator()
a = await translator.translate('il tuo testo potrebbe essere qui', src='it', dest="es")
print(a.text)

# tu texto podría estar aquí
```
6. Create a wordcloud from all the texts you collected. (1 point)
