# Named-Entity-Recognition-using-BERT
The goal of a named entity recognition (NER) system is to identify all textual mentions of the named entities. This can be broken down into two sub-tasks: identifying the boundaries of the NE, and identifying its type.

Named entity recognition is a task that is well-suited to the type of classifier-based approach. In particular, a tagger can be built that labels each word in a sentence using the IOB format, where chunks are labelled by their appropriate type.

The IOB Tagging system contains tags of the form:

B - {CHUNK_TYPE} – for the word in the Beginning chunk I - {CHUNK_TYPE} – for words Inside the chunk O – Outside any chunk The IOB tags are further classified into the following classes –

geo = Geographical Entity org = Organization per = Person gpe = Geopolitical Entity tim = Time indicator art = Artifact eve = Event nat = Natural Phenomenon
