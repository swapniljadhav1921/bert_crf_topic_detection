# Detecting Potential Topics In News Using BERT, CRF and Wikipedia

Abstract : At Dailyhunt, we want to identify named-entities like names, locations, organisations from the news with 13+ Indian languages and use them for building better recommendation and notifications algorithms. But we also need to identify n-grams which do not necessarily fit in the definition of Named-Entity, yet important. For example "me too movement", "beef ban", "alwar mob lynching". In this exercise, given a english-language text we are trying to detect case-less names, locations, organisations and important n-grams  which convey important information and can be used as topics and/or hashtags. Model is built using Wikipedia titles data, Dailyhunt English news corpus and BERT-Multilingual{devlin2018bert} pre-trained model, Bi-GRU{2014arXiv1412.3555C} and CRF architecture, shows promising results when compared with industry best Flair, Spacy and Stanford-caseless-NER.



### Data Files
* Sample Train Data File => sample_train_data.tsv.gz
* Cased NERs output => sample_english_news.out.limited
* Sample Model output => penglish_sample_news.tsv
* All possible NERs for benchmark files => all_possible_ner_set.txt
* benchmark_file1.tsv => Model outputs batch 1
* benchmark_file11.tsv => Model outputs batch 2
