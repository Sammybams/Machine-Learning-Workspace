
# IMDB-Movie-Sentimental-Analysis

Link to dataset: http://ai.stanford.edu/~amaas/data/sentiment/

- Completed building a sentimental anal􏰋ysis model w􏰏ith 88% accurac􏰋y using Naiv􏰊e Ba􏰋yes Classfi􏰑er.

I observ􏰊ed that 􏰏while considering bigrams and trigrams, the accurac􏰋y of the model dropped on data that had stop-􏰏words remov􏰊ed. Words like 􏰣`not􏰤` and `􏰣but􏰤` 􏰏which are classfi􏰑ed as stop-􏰏words can greatl􏰋y affect the polarit􏰋y of the sentiment of a comment or te􏰠xt. And that is w􏰏hy􏰋 m􏰋y best model w􏰏as achie􏰊ved on data that still included stop-􏰏words, but 􏰏was cleaned (html tags, url links, numbers, etc all remov􏰊ed).
