# JOBTalk

nlp tool{set}, pipeline, and custom datasets aimed at assisting job seeker / career wanters/needers/havers.

Business Factory type stuff.

![Image of Advice](https://cdn.pixabay.com/photo/2018/08/25/15/32/counselling-3630323_960_720.png)


#TOOLS TODOs:

- installation script
- snippets:
 - check for zshrc in $HOME
 -
 - zshrc path update for tools dir
 > #probs a zsh path var.. code below is likely overkill or needs to test the path given
 > test ls $ZSHCONFIGPATH/.zshrc && ( cp $ZSHCONFIGPATH/.zshrc $ZSHCONFIGPATH/zshrc.ttbak[date] $ZSHCONFIGPATH/.zshrc echo '[export path]' >> $ZSHCONFIGPATH/.zshrc ) || ".zshrc not found in path $ZSHCONFIGPATH.\
 > Please add following code to your .zshrc:\
 > ...."

> 


- dataprep
 - employ nltk or other nlp framework options for data processing
 - update regex's to leverage hyperscan in * manner relevant to* employed technique for processing text. e.g. *sh scripts vs py vs binaries
