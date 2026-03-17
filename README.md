# Data-Science-Masters-Dissertation

This dissertation investigates how the meaning of a word can change over time in online
environments. This meaning change can be characterised as sematic drift, where the meaning
of a word evolves away from its original understanding over a period of time. The specific
type of semantic drift that is focused on within this dissertation is pejorative drift. This is
where a word’s meaning has evolved to become more negative.
The investigation in this study is grounded in sociolinguistic theory that is informed by the
concept of indexicality of word meaning. It develops a hybrid computational methodology by
combining sentiment analysis, word embeddings and graph-based modelling to effectively
detect and visualise semantic drift.
Video metadata (e.g. video titles, video description and top-level comments) was collected
from YouTube using the Data API. This data was process and analysed using natural
language processing toolkits to compute sentiment scores and track the distributional changes
of a word’s meaning through cosine similarity word embedding comparisons. A semantic
graph database was constructed in Neo4j to visualise the relational drift of a word’s meaning,
showing the co-occurrence patterns between users and their comments across time.
The results from this investigation showed a clear declination of sematic trend for the chosen
word ‘woke’ while also confirming this drift through measurable shifts is distributional
representations. This confirmed the hypothesis that the word ‘woke’ had undergone
pejoration. The Neo4j graph outputs revealed a changing contextual environment for the
target word that further supports how the word had undergone recontextualisations of its
semantic neighbourhood. However, due to some technical constraints, a full relational
comparison could not be made for all the years.
The study demonstrated the value of computational approaches to capturing as part of
ongoing theory-based language analysis. It also highlighted the importance of context in
shaping meaning as language terms are expansively used within dynamic online
communities.
