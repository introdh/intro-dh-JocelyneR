## Reading Prompt

For each reading, pick two sentence/passages. One should be where the had an AHA! moment and one that is unclear, confusing, or needs further explanation. Provide a sentence or two explaining each of your selections.  Provide your response below.

 

### 2017-09-18: Distant reading
AHA!: "The trouble is that Moretti isn’t studying a science. Literature is an artificial universe, and the written word, unlike the natural world, can’t be counted on to obey a set of laws"- This sentence points out one of the main problems with analyzing literature and art merely through statistics or distant reading without the proper context.

Confusing: "You might know your George Eliot from your George Meredith, but you won’t have learned anything meaningful about literature, because your sample size is absurdly small"- Although I understand Moretti's argument, he undermines the importance of specific knowledge over generalized knowledge. Is knowing little about many things better than knowing much about few things?




### 2017-09-25: Topic modeling I
AHA!: "One way to think about how the process of topic modeling works is to imagine working through an article with a set of highlighters. As you read through the article, you use a different color for the key words of themes within the paper as you come across them."- This is a good way to think visualize how topic modeling works

Confusing: "Topic modeling is not necessarily useful as evidence but it makes an excellent tool for discovery."- It seems a little contradictory that although topic modeling is a good tool for discovery it cannot be necessarily useful as evidence. I understanding this to mean that topic modeling is not always exact and that is why it cannot always be used as evidence; yet, this is a feature of most evidence in the humanities and social sciences. 

### 2017-10-02: Topic Modeling II
Mining the Dispatch:
AHA!:"It uses as its evidence nearly the full run of the Richmond Daily Dispatch from the eve of Lincoln's election in November 1860 through the evacuation of the city in April 1865 (at which point publication of the Dispatch ceased) to December 1865 (when publication of the Dispatch resumed), an archive of over 112,000 pieces consisting of nearly 24 million words.3 It uses as its principle methodology topic modeling, a computational, probabilistic technique to uncover categories and discover patterns in and among texts"- This passage explains how data was chosen as well as a brief description of how it was analyzed. 

Confusing: "To be a bit more technical, a topic is a probability distribution of words, statistics for a set of words that indicate the probability of each individual word appearing in a document on a particular topic."- This explaination of what a topic is is, in my opinion, more confusing than explanatory. I have trouble trying to understand a topic as a 'probability distribution of words'.

Signs at 40:
AHA!: "Every topic is a family of words that tend to occur together in articles—as, for example, world, global, and states do. Every article is in turn divided into multiple topics."- For me, this is the best explanation of a topic I have found throughout the multiple readings trying to explain the same thing. It is easier to understand topics as a family of words rather than a 'probability distribution of words'. 

Confusing: "Yet we hope you will discover new patterns and trends yourself—and that you may find this a useful way to (re)discover aspects of the Signs archive and to open up new channels of interpretation for the field of feminist scholarship."- Although not exacly confusing, this passage made me wonder about the subjectivity involved in studying and interpreting the topics produced by topic modeling. 

Text Analysis of Trump Tweets:
AHA!:"These tweets certainly sound like the Trump we all know. Maybe our above analysis isn’t complete: maybe Trump has sometimes, however rarely, tweeted from an iPhone (perhaps dictating, or just using it when his own battery ran out). But what if our hypothesis is right, and these weren’t authored by the candidate- just someone trying their best to sound like him?"- This passage point to one of the main problems with using text analysis to determine authorship since we never know what might have influence a change of style or whether you are dealing with someone trying to sound like someone else. 

Confusing: "We’ll use the simple measure of log odds ratio, calculated for each word as:3 log2(# in Android+1Total Android+1# in iPhone+1Total iPhone+1)
log
2
⁡
(
in Android
+
1
Total Android
+
1
in iPhone
+
1
Total iPhone
+
1
)
android_iphone_ratios <- tweet_words %>%
  count(word, source) %>%
  filter(sum(n) >= 5) %>%
  spread(source, n, fill = 0) %>%
  ungroup() %>%
  mutate_each(funs((. + 1) / sum(. + 1)), -word) %>%
  mutate(logratio = log2(Android / iPhone)) %>%
  arrange(desc(logratio))"- What does this mean? 
  
 Data Miners Dig for Answers about Harper Lee:
 AHA!: “Text mining aims to shed light on authorship and creative process by examining word patterns in individual books, but it also can analyze thousands of texts at once in search of broader trends. Some scholars call this method a vital tool in aid in literary analysis while other dismiss it as digital quackery”- This passage summarizes the overall take on examining word patterns to uderstand broader trends and authorship. It captures the main idea throughout multiple readings as well as the debate on the reliability of the information gather through word patterns.
 
 Confusing:“The findings, which attempt to shed light on a book that has sparked world-wide attention by an author who has famously declined to discuss her work, show Ms. Lee as the undisputed author of both novels but suggest that her style as a writer was more consistent in “Watchman” than “Mockingbird””.- When a two texts presumably by the same author show different writing styles, how do you know which style corresponds more to the author (without analyzing other texts)?


### 2017-10-09: Stylometry

### 2017-10-18: Spatial history

### 2017-10-23: Mapping: A Critical Introductin

### 2017-11-06: Social networks

### 2017-11-13: Layering Networks

### 2017-11-27: Critical DH
