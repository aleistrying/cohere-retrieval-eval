# Cohere retrieval eval

Checking how well Cohere Embed finds the right abstract for a scientific claim, using the SciFact dataset from BEIR. Next I want to see what Cohere Rerank changes.

## What's in it
`explore.ipynb` embeds the SciFact corpus and queries, ranks abstracts by cosine similarity and computes recall@k. So far test recall@3 is about 0.74.

## How to run
Download SciFact from BEIR into `data/scifact`, set `COHERE_API_KEY` and run the notebook top to bottom.

## Status
In progress: the rerank comparison is not finished yet.
