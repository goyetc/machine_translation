# machine_translation
Using decoder encoder framework for english to spanish translation, and back, with BLEU scores

## Part 1 
* process text
* eng to spanish

## Part 2
* spanish to english

## Part 3
* Use test set from beginning -  created true/unobserved test set by pulling a random sample of 5000 sets and then partitioning that sample into train and test sets
* We will extract the translations after the first english -> spanish training steps, and then use those translations as the source for a spanish to english translation. 
* The tokenizations will also be used from the second model, as we are treating the translated words from the original model in part 1 as the ground trouth in part 3. 
