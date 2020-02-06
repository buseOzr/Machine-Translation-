# Machine Translation Project

Machine translation is an active and challenging research area with important
use in the industry. There are many machine translation models that have been proposed
over the years, each with different architectural characteristics. In this project we develop
a machine translation prototype system, with the main objective being to analyse which
characteristics or strategies could bring the highest improvements on the quality of machine
translation, considering the constraint of having limited computational resources. The
project will use a corpus of parallel phrases from French to English, and as a base model
we will consider a shallow LSTM encoder-decoder. The report will show that it is crucial
to have a good amount of high-quality training data, which can improve the translations
more than variations in the architecture of the model. Considering our context a shallow
model with bidirectional encoder and 512 LSTM units and also having a well chosen pretrained
Word2Vec will give the best accuracy. Using a deep architecture in this case drove
down the BLEU score, due to computational limitations that prevented us from using
large amounts of training data. Changes will be observed in the choice of language pairs
as well, considering the differences in syntax and semantics between languages. Thus, a
translation from French to English will be shown to have a slightly higher quality than
the translation from German to English.
