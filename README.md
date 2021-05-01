# Central-Kurdish-Spelling-dataset
Datasets for evaluation of Central Kurdish spell-checking systems

## First Dataset:
Provided by **Arash Amani** (https://github.com/ArashAmani/KurdishSpellChecker):

امانی، آرش، كوچاری، عباس، (١٣٩۶) «بهبود تصحيح املايی در زبان كردی با تغيير وزندهی در كمترين فاصله‌ی ويرايشی»، دومين كنفرانس ملی محاسبات نرم، دانشگاه گيلان.

Acording to the authors, the errors are collected from handwritten answer sheets of Kurdish language learners.

We reviewed the original data:
* Some of the manually corrections words were not correct according to our knowledge.
* Some of them are not from Standard Central Kurdish (from Northern Kurdish, Gorani, or non-standard sub-dialects of Central Kurdish)
* Some of them are not *non-word errors*. They are *real-word errors*, which are correct in certain contexts.
* Some of them are unknown words not found in the Kurdish dictionaries.

## Second Dataset
Provided by **Aso Mahmudi** for evaluation of a proposed spell-checker for his master's thesis.

محمودی، آسو (۱۳۹۸) «طراحی و پیاده‌سازی خطایاب املایی برای زبان کردی (گویش مرکزی)، پایاننامه جهت دریافت درجه کارشناسی ارشد رشته زبانشناسی رایانشی از دانشکده علوم و فنون نوین دانشگاه تهران.

1400 tokens taken randomly from crawled news articles of the website [netewe.net](http://www.netewe.net/):
* 848 words (%60.6) are correct, 546 tokens (%39.0) are non-word errors, and 6 words (%0.4) are non-Kurdish (Arabic).
* For each typo, editing distance (Damerau-Levenshtein algorithm) to its manual correction is calculated.
* 231 typos (%42.3 of typos) are, in fact, two or three merged words.
* Frequency of each word (among 5,895,308 tokens) is reported.
