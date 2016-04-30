# nlp-metrics
Python implementation of all the useful Natural Language Metrics

The code for BLEU and ROUGE metrics are not mine, but are from this work. 
https://github.com/tylin/coco-caption.git

However, there was a lot of useless image related code in there. Thus I cleaned up a part of it, to make it suitable for use for general NLP task.

## Wrapper Script
The script 
```
tester.py
```
is a wrapper code, that combines all of necessary metrics, and produces one good result. 

## Run Instructions
```
python tester.py
```

## Reference and Hypothesis
You can provide the directory in tester.py for the directory which contains all of your references and hypothesis. The implementation at present is good for the case when each hypothesis sentence has one reference sentence.

## Notes
1. The Cider metric is removed for not being of much use for the traditional nlp task
2. The Meteor metric is giving errors, which I have not figured out yet. Will update as I get that working. 
3. This work is not properly documented. When I get more time, I will clean it and document it.

## Collaboration
If you wish to add another NLP-metrics, you are welcome to fork, and I can mere your work, if it works successfully.
