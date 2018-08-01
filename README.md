# adapt-conflict-ner

Files related to thesis project for Adapting Named Entity Recognition to Conflict Research Domain.

Each folder contains:

* packages-stanford-ner/:
    * CoreNLP_MOD_6589403f24b38470c157a40d2f75c95ee1b3011a/: fork of StanfordNER (Finkel, Grenager and C. Manning, 2005)  (base commit from CoreNLP repository, hash equal to folder name substring), modified minimally to lowercase gazetteers at initialization and at lookup.
    * CoreNLP_NOMOD_6589403f24b38470c157a40d2f75c95ee1b3011a/: copy of the commit, but with no modifications applied.
    * version-difference.diff: diff file showing the exact difference between the two folders.
