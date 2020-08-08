# Sentence Autocomplete

Sentence autocomplete is a common application natural language processing which can be observed every day. We get our sentences completed by google, our phone keyboards and even by some people also. :)


!["Google Sentence Autocomplete"](/imgs/auto.png)


In this repository, I have implemented a simple next word suggestor using the N-gram model. The training data is taken from `my Facebook` messages, so if you want to run the notebooks, please follow the steps below.

## Running notebooks steps
1. Go to your Facebook account and download messages data in JSON format
2. Place the inbox folder in the same directory as the notebooks
3. Run the code

## N-gram model
N-gram is probably the easiest concept to understand in the whole machine learning space, I guess. An N-gram means a sequence of N words. So for example, “Technical blog” is a 2-gram (a bigram), “A Technical blog post” is a 4-gram, and “Write on Paper” is a 3-gram (trigram).
