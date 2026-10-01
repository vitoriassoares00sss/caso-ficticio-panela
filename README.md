# Horizonte Consumidor - caso fictício 3 (panela antiaderente)
Atividade preparatória para a N1 da disciplina Inteligência Artificial Jurídica (Prof. Edson
Vaz Lopes).
## Problema
Panela antiaderente cujo revestimento descascou em poucas semanas, apesar de a embalagem
anunciar que "não descasca". A loja recusou a troca alegando política de 7 dias, e o
fabricante negou a garantia. O consumidor pede uma orientação inicial.
## Como navegar
- entrada/ preserva o relato original (nunca vai para a IA);
- apoio/ contém o caso sanitizado e as únicas fontes permitidas na consulta;
- docs/ define as regras, a especificação e os prompts;
- evidencias/ registra a resposta da IA, a verificação, a auditoria e a revisão humana;
- entrega/ contém a orientação final.
## Ordem do fluxo
1. docs/limites_e_sigilo.md
2. apoio/caso_sanitizado.md, apoio/fonte_1.md (cupom, embalagem e política de trocas),
apoio/fonte_2.md (CDC, arts. 18, 24, 26 e 50)
3. docs/especificacao.md
4. docs/prompts/consulta_rag.md → evidencias/resposta_inicial.md
5. evidencias/verificacao.md
6. docs/prompts/auditoria.md (em nova conversa) → evidencias/auditoria.md
7. evidencias/revisao_humana.md
8. entrega/orientacao_inicial.md
## Repositório
GitHub - vitoriassoares00sss/caso-ficticio-panela
## Como executar
Ler docs/prompts/consulta_rag.md e enviar para a IA somente os arquivos de apoio/.