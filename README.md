# InformationRetrieval
Information Retrieval


##Lucene
Tutorial: http://lucene.apache.org/core/quickstart.html 
Link: http://mirror.nexcess.net/apache/lucene/java/6.4.0/

##Solr
Tutorial: http://lucene.apache.org/solr/resources.html#tutorials
Link: http://apache.osuosl.org/lucene/solr/6.4.0/

##Commands

`java -cp "bin:lib/*" IndexTREC -docs /path/to/cd45/documents`


`java -cp "bin:lib/*" BatchSearch -index /path/to/index -queries /path/to/title-queries.301-450 -simfn default > default.out`

Replace default and bm25.


`trec_eval -q -M1000 /path/to/qrels.trec6-8.nocr /path/to/an/output/file`

./trec_eval -q -M1000 -m P.5 ../test-data/qrels.trec6-8.nocr ../default.out .



./trec_eval -q -M1000 -m all_trec ../test-data/qrels.trec6-8.nocr ../bm25.out .





