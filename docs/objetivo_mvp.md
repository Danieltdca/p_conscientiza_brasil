**Escopo inicial**: Federal (Câmara e Senado) — período: 2023–2025.


**Problema**: classificar políticos em Esquerda / Centro / Direita.


**Abordagem**: rótulo objetivo via votações nominais → cálculo de ponto ideal (1D) → discretização em E/C/D.


**Textos usados**: discursos e ementas de PLs para validação por NLP.


**Métricas**: macro-F1 por classe; relatório de confusão; calibração.


**Critérios de aceite do MVP:**


1. Obter theta (ponto ideal) para ≥ 80% dos deputados em 2023–2025;


2. Classificador de texto com macro-F1 ≥ 0,60 em validação;


3. Dashboard simples com posição (E/C/D) + explicações básicas;


4. Registros de integridade exibidos apenas com fonte e data oficiais.


**Ética e limites**: sem inferências difamatórias; só fatos com fontes oficiais; mensagens de incerteza na UI.
