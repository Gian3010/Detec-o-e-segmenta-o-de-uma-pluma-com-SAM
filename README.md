# Detecção e segmentação de uma pluma de fumaça com SAM

Notebook Colab que usa o Segment Anything Model (SAM) para segmentar uma pluma de fumaça em `pluma.png`,
testa três configurações de prompt (caixa; pontos positivos; caixa + positivos + negativos),
aplica melhorias (pós-processamento morfológico, refinamento iterativo e CLAHE) e analisa as limitações.

- `segmentacao_pluma_fumaca_SAM.ipynb`: código e análise
- `pluma.png`: imagem de entrada
