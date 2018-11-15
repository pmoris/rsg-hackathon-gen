# Generating a bioinformatics paper

The goal of this hackathon project is to build a framework that can generate a bioinformatics paper. To help you get started, we've collected a few resources and tips below.

First, we've listed a couple of similar projects [below](#Examples) that might serve as an inspiration.

You'll also find a few techniques that can help you get started. [Markov chains](#Markov-chains) are the . [Neural network](#recurrent-neural-networks) approaches

The data we've provided is a dump of the [PMC Open Access dataset]!(https://www.ncbi.nlm.nih.gov/pmc/tools/openftlist/). It contains open access research articles from multiple journals in XML format. More specifically, both the contents and meta-data of the articles if encoded in the [Journal Archive and Interchange Tag Set (JATS)](https://jats.nlm.nih.gov/archiving/) format.

Lastly, here are a few general tips.

Since the time of this coding session is limited compared to a multi-day hackathon, we advice you to clearly outline your vision in a structured manner. Which aspects are essential? Which parts are merely nice to have? Which aspects can be prototyped via toy examples? Do you want to focus on an abstract generator first before tackling a full paper? Will you assign another person to generate tables, flowcharts or (tikz) images? How will you create a corpus with a specific scientific focus?

Next, try to divide the task into more bite-sized chunks that can be distributed over your team in such a way that no part of the chain is (overly) dependant on any other part. You can do this by for example, again relying on toy examples or by coding in a a more general manner.

Lastly, we kindly ask you to respect your team mates. Be humble and don't let your ego get in the way of the team. And most of all, have a good time!


## Examples

- https://pdos.csail.mit.edu/archive/scigen/
- http://thatsmathematics.com/blog/mathgen/
- https://filiph.github.io/markov/
- https://www.essaysoft.net/essay-generator.html

## Markov chains

- https://hackernoon.com/automated-text-generator-using-markov-chain-de999a41e047
- https://rosettacode.org/wiki/Markov_chain_text_generator
- https://rmhogervorst.nl/cleancode/blog/2017/01/21/content/post/2017-01-21-markov-chain/
- https://rpubs.com/malcolmbarrett/shakespeare
- https://wiki.ubc.ca/Text_generation_with_LSTM_and_Markov_Chain

### Implementations and packages

- https://github.com/jsvine/markovify
- https://github.com/abresler/markovifyR

## Recurrent neural networks

- https://blog.paperspace.com/recurrent-neural-networks-part-1-2/
- https://chunml.github.io/ChunML.github.io/project/Creating-Text-Generator-Using-Recurrent-Neural-Network/
- https://medium.com/@shivambansal36/language-modelling-text-generation-using-lstms-deep-learning-for-nlp-ed36b224b275
- https://www.kaggle.com/shivamb/beginners-guide-to-text-generation-using-lstms
- https://medium.freecodecamp.org/applied-introduction-to-lstms-for-text-generation-380158b29fb3
- https://www.tensorflow.org/tutorials/sequences/text_generation
- https://medium.com/phrasee/neural-text-generation-generating-text-using-conditional-language-models-a37b69c7cd4b
- https://www.analyticsvidhya.com/blog/2018/03/text-generation-using-python-nlp/
- https://machinelearningmastery.com/text-generation-lstm-recurrent-neural-networks-python-keras/
- https://towardsdatascience.com/generating-text-with-lstms-b0cdb6fc7bca
- https://minimaxir.com/2018/05/text-neural-networks/
- https://medium.com/coinmonks/word-level-lstm-text-generator-creating-automatic-song-lyrics-with-neural-networks-b8a1617104fb
- https://wiki.ubc.ca/Text_generation_with_LSTM_and_Markov_Chain

### Implementation and packages

- https://github.com/minimaxir/textgenrnn
- https://github.com/karpathy/char-rnn
- https://jjallaire.github.io/deep-learning-with-r-notebooks/notebooks/8.1-text-generation-with-lstm.nb.html

## In the news...

- https://link.springer.com/article/10.1007/s11192-012-0781-y
- https://www.nature.com/news/publishers-withdraw-more-than-120-gibberish-papers-1.1476
- https://retractionwatch.com/2015/03/23/an-end-to-fake-papers-new-software-to-check-for-scigen-created-manuscripts/
- https://www.enago.com/academy/scigen-boon-bane-academic-research-industry/
- https://www.theguardian.com/technology/shortcuts/2014/feb/26/how-computer-generated-fake-papers-flooding-academia
- https://www.sciencemag.org/news/2015/03/hoax-detecting-software-spots-fake-papers
