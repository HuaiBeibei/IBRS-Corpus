# IBRS-Corpus

This is the corpus using in IBRS model

## annotation.xml and bugreports.xml 
  These files are corpus from paper "Automatic Summarization of Bug Reports". We correct some errors in it.
## intentions.csv 
  It is corpus for intention classifier. We annotate each sentence in bugreports.xml with a  intention category 
  (use a number (0-6) represent). Each row consists of the bug report ID the sentence in, sentence content and the intention category
  
  0 is Bug Description. 1 is Fix Solution. 2 is Opinion Expressed. 3 is Information Seeking. 4 is Information Giving. 5 is Meta/Code. 6 is Emotion Expressed.
