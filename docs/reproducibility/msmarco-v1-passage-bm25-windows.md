This PR adds my reproduction log entry for the Pyserini BM25 baseline reproduction.

Environment:
OS: Windows 10
Python: 3.11
Java: OpenJDK 21

Steps completed:

    Ran Pyserini BM25 search on msmarco-passage-dev-subset
    Evaluated results using msmarco_passage_eval

Result:
MRR @10 = 0.18741227770955546
QueriesRanked: 6980

banana odyssey
