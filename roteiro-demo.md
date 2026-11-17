# Roteiro de demonstração (3 a 5 minutos)

Serve para o vídeo e para os prints. Tenha antes: um vídeo curto nomeado `ATENTO - Teste seguro.mp4` (até 25 MB) fora da pasta, o chat aberto em outra aba e a planilha aberta.

| Tempo | Etapa | O que mostrar |
|---|---|---|
| 0:00 | Problema | Tela com a descrição do problema (seção 1 da documentação): treinamento repetido para novatos e reciclagem |
| 0:30 | Ingestão no n8n | Canvas do workflow de ingestão; explicar em uma frase: Drive, limite de 25 MB, Whisper, trechos, índice, registro |
| 1:15 | Consulta no n8n | Canvas do workflow de consulta: chat, agente, ferramenta de busca, modelo principal e reserva |
| 1:45 | Prompt | Prompt do agente; destacar a regra de responder só com os trechos, a citação de minuto e a frase "Não encontrei isso nos treinamentos gravados." |
| 2:15 | Disparo | Arrastar o vídeo para a pasta Treinamentos no Drive |
| 2:45 | Execução | Executions do n8n: nós verdes, saída do Whisper com o texto, saída de "Montar trechos" com os trechos e minutos |
| 3:15 | Registro | Aba Treinamentos com a linha nova |
| 3:30 | Pergunta dentro do conteúdo | No chat: "Como faço o teste do ATENTO com segurança?"; mostrar passos e a fonte com o minuto |
| 4:15 | Pergunta fora do conteúdo | No chat: "Como configuro o Power BI?"; mostrar a resposta "Não encontrei isso nos treinamentos gravados." |
| 4:40 | Encerramento | Limitações (25 MB, índice em memória) e próximos passos (banco vetorial persistente, leitura automática do Teams) |

## Prints (alternativa ao vídeo)

1. Pasta Treinamentos no Drive com o vídeo.
2. Canvas do workflow de ingestão.
3. Canvas do workflow de consulta.
4. Prompt do agente (nó "Agente de treinamentos").
5. Execução da ingestão: saída do nó "Transcrever (Groq Whisper)".
6. Saída do nó "Montar trechos" com minuto e ferramenta.
7. Aba Treinamentos do Sheets com a linha registrada.
8. Chat com a pergunta dentro do conteúdo e a resposta com fonte.
9. Chat com a pergunta fora do conteúdo e a resposta "Não encontrei isso nos treinamentos gravados."
