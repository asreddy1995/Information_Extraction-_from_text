# Information_Extraction_from_text
Introduction to Information Extraction
Information Extraction (IE) is a crucial cog in the field of Natural Language Processing (NLP) and linguistics. It’s widely used for tasks such as Question Answering Systems, Machine Translation, Entity Extraction, Event Extraction, Named Entity Linking, Coreference Resolution, Relation Extraction, etc.

In information extraction, there is an important concept of triples.
Different Approaches to Information Extraction
In the previous section, we managed to easily extract triples from a few sentences. However, in the real world, the data size is huge and manual extraction of structured information is not feasible. Therefore, automating this information extraction becomes important.

There are multiple approaches to perform information extraction automatically. Let’s understand them one-by-one:

Rule-based Approach: We define a set of rules for the syntax and other grammatical properties of a natural language and then use these rules to extract information from text.

Supervised: Let’s say we have a sentence S. It has two entities E1 and E2. Now, the supervised machine learning model has to detect whether there is any relation (R) between E1 and E2. So, in a supervised approach, the task of relation extraction turns into the task of relation detection. The only drawback of this approach is that it needs a lot of labeled data to train a model.

Semi-supervised: When we don’t have enough labeled data, we can use a set of seed examples (triples) to formulate high-precision patterns that can be used to extract more relations from the text.

Information Extraction using Python and spaCy
In this section, we will use the very popular NLP library spaCy to discover and extract interesting information from text data such as different entity pairs that are associated with some relation or another.

1. spaCy’s Rule-Based Matching
