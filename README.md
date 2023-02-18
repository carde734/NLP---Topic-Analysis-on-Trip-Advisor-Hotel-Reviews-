# NLP---Topic-Analysis-on-Trip-Advisor-Hotel-Reviews-


Online customer reviews are very insightful
and have a direct impact on revenue for
hotel owners.

However, since these reviews are written by
thousands of users, there’s a possibility that
some reviews present grammar mistakes,
resulting in a loss of data quality as a
drawback. With that in mind, this research
focused on analyzing whether spellchecking applied in the pre-processing
phase of data, could be impacting topic
modeling analysis on hotel reviews.
Topic modeling was explored using
BERTopic as the main algorithm and LDA
as a baseline. As expected, BERTopic’s
generated topics revealed a better efficiency
than LDA regarding their coherence and
overall quality.
Surprisingly, the research revealed that
spell-checking usage not only doesn’t seem
to bring more value to the analysis but also
disclosed some negative aspects (words that
were incorrectly tagged as misspelled) at a
cost of higher computational demand.
