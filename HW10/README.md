# Can Language Models Be Too Big?
---
## Intro
* Problems with larger models
    * Environmental risks
    * Financial costs
    * Difficulty understanding training data

## Background
* __Language Model__ - refers to systems which are trained on string prediction tasks
    * Likelihood of a token (character or word) given either preceding or surrounding context
    * Unsupervised, take text as input, output scores or string predictions
    * Transformer LMs allow for much less data to be used to get similar results

## Environmental & Financial Cost
* Human makes 5t CO2 per year, transformer model took 284t CO2
* Training a BERT base model requires as much energy as a trans-American flight
* Increase in 0.1 BLEU score results in an increase of $150,000 computation cost
* These issues lead to environmental racism, people in India suffering through a monsoon due to these events

## Unfathomable Training Data
* More data can lead to derogatory associations
* __Size does not guarantee diversity__
    * The model will follow the data. Ex. if data comes from US/UK data, the model will have an overrepresentation of white supremacist and misogynistic views
    * Overrepresented young people because they use the internet more
    * To overcome this, they filter out data with obscene words
* __Static data/changing social views__
    * Use language to destabilize dominant narratives
    * Ex. BLM influenced more articles and coverage of shootings and other police violence incidents
* __Encoding bias__
    * Models generate bias against marginalized communities
    * Ex. BERT associates negative words with disabilities
    * A lot of data slips into the datasets from banned subreddits and unreliable news
    * Must understand where the biases may be to find them
    * Words change meaning over time as the world changes
* __Curation, documentation, and accountabilitiy__
    * Models get encoded with poor views due to bad datasets
    * Documentation is an important part of training data

## Down the Garden Path
* Large Transformer LMs are making major gains
* Models do not actually understand the language, just the patterns
* People question what is really being learned about language

## Stochastic Parrots
* There is harm from these models due to their biases
* __Coherence in the eye of the beholder__
    * Transformer LMs capture a much larger window of words when making a prediction
    * There is no intent to LMs and their language
    * The human generates intent as they read due to the machine not having its own intent
    * An LM is a stochastic parrot; it just ties together a sequence of words that it has observed according to probabilistic information without reference to their meaning
* __Risks and harms__
    * Words reflect our views. A model could become harmful due to these views
    * LMs can propagate abusive views and lead to psychological harm
    * Bad actors can take advantage of these LMs to deploy hate speech and other coherent texts
    * Ex. conspiracy theorist using LMs to boost message board activity, making people think they are among many others
* __Summary__
    * Accountability involves responsibility and truthfulness

## Paths Forward
* Researchers must be conscientious of their datasets and the economic/environmental problems associated with these models
* Making sure a dataset does not have biases is important
* These analyses should be done before the research, not after

## Conclusion
* Are large LMs even necessary?
* There are certainly risks associated with these models


