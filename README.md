# Tweet-Sentiment-Extraction

![Issues](https://img.shields.io/github/issues/shlok-sethia/Tweet-Sentiment-Extraction)
[![License](https://img.shields.io/github/license/shlok-sethia/Tweet-Sentiment-Extraction)](https://github.com/shlok-sethia/Tweet-Sentiment-Extraction/blob/master/LICENSE)
![](https://img.shields.io/github/repo-size/shlok-sethia/Tweet-Sentiment-Extraction.svg?label=Repo%20size&style=flat-square)&nbsp;

"My ridiculous dog is amazing." [sentiment: positive]

With all of the tweets circulating every second it is hard to tell whether the sentiment behind a specific tweet will impact a company, or a person's, brand for being viral (positive), or devastate profit because it strikes a negative tone. Capturing sentiment in language is important in these times where decisions and reactions are created and updated in seconds. But, which words actually lead to the sentiment description? In this competition you will need to pick out the part of the tweet (word or phrase) that reflects the sentiment.

The selected_text is a subset of text <br />
The selected_text contains only one segment of text,i.e,It does not jump between two sentences.For Eg:- If text is 'Spent the entire morning in a meeting w/ a vendor, and my boss was not happy w/ them. Lots of fun. I had other plans for my morning' The selected text can be 'my boss was not happy w/ them. Lots of fun' or 'Lots of fun' but cannot be 'Morning,vendor and my boss

## What am I predicting?
I'm attempting to predict the word or phrase from the tweet that exemplifies the provided sentiment. The word or phrase should include all characters within that span (i.e. including commas, spaces, etc.). The format is as follows:

id,"word or phrase that supports the sentiment"

### For example:
2,"very good" <br />
5,"I am neutral about this" <br />
6,"bad" <br />
8,"if you say so!" <br />
etc.
