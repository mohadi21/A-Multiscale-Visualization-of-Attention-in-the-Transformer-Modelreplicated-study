# A-Multiscale-Visualization-of-Attention-in-the-Transformer-Modelreplicated-study

Natural Language Processing (NLP) is one of the fastest
growing fields of artificial intelligence. It is centered on
the understanding of human language, represented by textual
data, by computers. Question Answer (QA) is a NLP
subfield in which an algorithm receives a short text (a context)
and is trained to answer natural questions relating to
that text by highlighting the most relevant passage to answer
the question in the context text. This approach can be
generalized to Open-Domain QA (or large Close Domain
QA), with the added difficulty that the context text is not
given and instead must be retrieved from a much larger set
of documents by the algorithm. Although the field of NLP
research is extremely active, most of the effort is focused
around the English language.
However, it would be wrong to say that no effort is made
in other languages. Recently, state-of-the-art NLP architectures
have been adapted to the French language (Camem-
BERT and FlauBERT) and have paved the way for research
on a variety of tasks that were not possible before).
In this work, we present the work of Jesse Vig (2019) who
introduced a tool for visualizing attention in the Transformer
at multiple scales. he demonstrated the tool on GPT-
2 and BERT, and he presented three use cases. However,
Jesse introduced a high-level model view, which visualizes
all layers and heads of attention in a single interface, and
a low-level neuron view, which shows how individual neurons
interact to produce attention. He also adapt the tool
from the original encoder-decoder implementation to the
GPT-2 decoder-only model and then the BERT encoderonly
model.
