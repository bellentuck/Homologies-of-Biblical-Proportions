<b>Goal:</b><br />
Compute structural homologies (and distinctions!) between various editions of the Bible.

<b>Means:</b><br />
Count Vectorization + Latent Dirichlet Allocation; i.e., topic modeling. 

<b>Textual Acquisition; or, Scraping Bibles:</b><br />
<i>
Source: biblestudytools.com<br />
Corpora: 27 English Bible editions (-> 24)<br />
Documents: 1189 chapters per Bible<br />
Data: 32,103 webpages of scripture<br />
</i>
Acquisition via web scraping; storage via MongoDB.

<b>Analysis:</b><br />
Preprocessing via PyData stack and NLP, including vectorization; unsupervised topic modeling via LDA, clustering via K-means; additional analysis via Jaccard metrics.

<b>What's a Homology?</b><br />
Homologies are similarities in the properties between different structures, or within different levels of a particular structure. The term <i>isomorphism</i> is also used to mean much the same thing.<br />
Literary <i>structural homologies</i> may be identified at the word-to-word level of syntax and at the topic-to-topic level of narrative in a story.<br />
(blackwellreference.com; see: structuralism, narratology)

<b>What's Count Vectorization?</b><br />
Corpus of documents → matrix of token counts.<br />
I.e., Corpus + UTF-8 Encoding + Cleaning + Tokenization - Stopwords = Count Matrix.<br />

<b>What's Latent Dirichlet Allocation (LDA)?</b><br />
Corpus -> Documents -> Tokens -> Topics --> Corpus. <br />
I.e.,<br /> 
Corpus: collection of documents<br /> 
Documents: texts in corpus<br /> 
Tokens: n-grams in each text (e.g., words)<br /> 
Topics: What’s likely to have generated this corpus?
