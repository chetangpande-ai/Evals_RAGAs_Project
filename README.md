### RAG Evaluation Metrics

## RAGAS - RAG Assessment

# RAG Metrics mental model
```
User Question
|
Retriver------------------>Evals (Context precision, context recall, context entity)
|
Retrived context/Chunks
|
Generator(LLM)------------>Faithfulness, Noise Sensitivity
|
Response------------------>Answer relevancy 
```

Matrics
1. faithfulness/No hallociations-- generated ans stick to the retrived facts(check if llm is hallcinating)
faithful to your source material

score= claims supported by retrived context/total claims

other frameworks- groundness

example1 - 

2. Answer relevancy/Response relevancy


# Evaluation dataset
