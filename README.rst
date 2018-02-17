Code-Mixed Hindi-English UD treebank
====================================

----

Requirements
^^^^^^^^^^^^

Install `Tweepy`_

.. _`Tweepy`: https://github.com/tweepy/tweepy

Get your Twitter app keys from https://apps.twitter.com/ and put the keys in the ``crawl_tweets.py`` script.


Crawl Tweets
^^^^^^^^^^^^

::

    python crawl_tweets.py -i tweet_ids_train.txt -a train-annot.json -o tweets_train.conll  # NAACL 2018 Dataset
    python crawl_tweets.py -i tweet_ids_dev.txt -a dev-annot.json -o tweets_dev.conll  # EACL 2017 dataset
    python crawl_tweets.py -i tweet_ids_test.txt -a test-annot.json -o tweets_test.conll  #EACL 2017 dataset


Cite
^^^^

Any publication reporting the work done using this data should cite the following paper:

@article{bhat2017joining,
  title={Joining Hands: Exploiting Monolingual Treebanks for Parsing of Code-mixing Data},
  author={Bhat, Irshad Ahmad and Bhat, Riyaz Ahmad and Shrivastava, Manish and Sharma, Dipti Misra and LTRC, IIIT-H},
  journal={EACL 2017},
  pages={324},
  year={2017}
}

Contact
^^^^^^^

::

    Irshad Ahmad Bhat
    MS-CSE IIITH, Hyderabad
    bhatirshad127@gmail.com
    irshad.bhat@research.iiit.ac.in
