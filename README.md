NLP-coreference-resolution
==========================

Coreferene resolution with Java

I use the Standford CoreNLP to the the corefence resolution, a sysytem with the best performance for the present. 
The algorithm is called "The Multi-Pass Sieve Coreference Resolution System", a deterministic and rule-based system with two stages. Stage one is mention detection where more attention is paid to recall than to precision. Stage two is coreference resolution which is based on a succession of ten independent coreference models applied from highest to lowest precision.  

This model performs really good with Anaphora, but performs really bad when it comes to cases such as Cataphora, Split antecedents or Coreferring noun phrases.

In my code, after identifying the corefence, I will replace the pronouns with the original representation.
