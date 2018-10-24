# QBLink dataset

Dataset for emnlp'18 paper "A dataset and baselines for sequential open-domain question answering"

Introduction
--------

QBLink is a new dataset about 18,000 question sequences, each sequence consists of three naturally occurring and correlated human-authored questions (totaling around 56,000 unique questions). 

Dataset Example
--------

**Lead-in:** Only twenty-one million units in this system will ever be created. For 10 points each:

**Question 1**: Name this digital payment system whose transactions are recorded on a “block chain”.

**Answer**: Bitcoin

**Question 2**: Bitcoin was invented by this person, who, according to a dubious Newsweek cover story, is a 64- year-old Japanese-American man who lives in California.

**Answer**: Satoshi Nakamoto

**Question 3:** This online drugs marketplace, Chris Bor- glum’s one-time favorite, used bitcoins to conduct all of its transactions. It was started in 2011 by Ross Ulbricht using the pseudonym Dread Pirate Roberts.

**Answer**: Silk Road


Dataset Download
--------

The dataset is split into train, dev, and test set, and we process it into json file. You can download the full dataset here:
https://sites.google.com/view/qanta/resources

Dataset Format
--------

Each question sequence has the following:

**Id**: question sequence id 

**Tournament**: tournament the question sequence in

**Leadin**: lead in sentence of the question sequence

**Category**: category the question sequence in 

**Sub Category:** sub category the question sequence in

**Question 1**: first question of the sequence, including **question text**, **answer**, **wiki page** the answer mapped

**Question 2**: second question of the sequence, including **question text**, **answer**, **wiki page** the answer mapped

**Question 3**: third question of the sequence, including **question text**, **answer**, **wiki page** the answer mapped


