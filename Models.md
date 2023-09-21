Models

|            | Params | Tokens (bn.) | A100 hours | Training FLOPS | English NLP Tasks | MMLU | GSM8K | HumanEval | DROP | Hellaswag |
|------------|--------|--------------|------------|----------------|-------------------|------|-------|-----------|------|-----------|
| PaLM 8B    | 8 B    | 780          | -          | 37.4 Z         | 51.2              | 25.2 |       |           |      |           | 
| PaLM 62B   | 62 B   | 795          | -          | 295.7 Z        | 64.8              | 53.7 |       |           |      |           |
| PaLM 540B  | 540 B  | 780          | -          | 2527.2 Z       | 70.3              | 69.3 |       |           |      |           |
| Chinchilla | 70 B   | 1400         | -          |                | 588 Z             | 65.2 | 67.5  |           |      |           |
| Gopher     | 280 B  | 300          | -          | 504 Z          | 59.5              |      |       |           |      |           | 
| GPT-3      | 175 B  | 300          | -          |                | 65.4              |      |       |           |      |           |
| GPT-4      | 220 B  |              |            |                |                   |      |       |           |      |           |
| Llama      | 65 B   | 1400         | 1.03 m     |                |                   | 35.1 |       |           |      |           |
| Llama 2    | 70 B   | 2000         | 1.72m      |                |                   |      |       |           |      |           |
| BERT       | .34 B  | 3.3          |            |                |      
| Claude 1   |        |              |            |                |                |      |      |       |           |      |           |


From Llama 1 paper - "(T)raining a 65B-parameter model (..) on 2048 A100 GPU (...) over our dataset containing 1.4T tokens takes approximately 21 days"
Llama 2 paper 