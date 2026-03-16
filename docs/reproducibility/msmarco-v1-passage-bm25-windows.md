# Reproduction Log: BM25 Retrieval on MS MARCO v1 Passage

## Environment
OS: Windows 10  
Python: 3.14.3  
Java: OpenJDK 21 (Temurin)

## Retrieval Command
python -m pyserini.search.lucene --index msmarco-v1-passage --topics msmarco-passage-dev-subset --output run.msmarco.txt --bm25 --output-format msmarco

## Evaluation Command
python -m pyserini.eval.msmarco_passage_eval msmarco-passage-dev-subset run.msmarco.txt

## Result
MRR@10 = 0.1874  
QueriesRanked = 6980

## Notes
Experiment reproduced successfully on Windows.
