# SP: Simple Structured Perceptron tagger in Python

The code implements a simple structured perceptron tagger. 

Train a model:

`
python simpletagger.py --train TRAINFILE --test TESTFILE
`

Expects CoNLL input (sentences delimited by a newline, words and tag delimited by tab).

* Add your own features (see `get_features` method).
* Not memory efficient. 
* See all options by running `python simpletagger.py`

Please let me know if you plan to extend/improve this code basis.

