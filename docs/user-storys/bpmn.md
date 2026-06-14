# Requisitos Funcionais

## Catálogo e perfil de locais

| ID | Descrição | Prioridade |
|----|-----------|------------|
| RF-01 | O sistema deve exibir informações de segurança de cada local com campo estruturado e descrição qualitativa (iluminação, movimentação, presença de segurança). | |

## Busca e filtros

| ID | Descrição | Prioridade |
|----|-----------|------------|
| RF-02 | O sistema deve validar a entrada do usuário antes de processar a busca, exibindo mensagem orientativa quando a consulta for inválida ou vazia. | |
| RF-03| O sistema deve exibir mensagem de "sem resultados" com sugestões alternativas de termos ou categorias quando nenhum local for encontrado. | |

## Recomendações e personalização

| ID | Descrição | Prioridade |
|----|-----------|------------|
| RF-04 | O sistema deve exibir recomendações de locais em alta e recém-cadastrados na tela inicial, sem necessidade de busca ativa. | |
| RF-05 | O sistema deve armazenar e utilizar o perfil de preferências culturais e gastronômicas do usuário para gerar recomendações personalizadas. | |
| RF-06 | O sistema deve combinar recomendações personalizadas com conteúdo em alta, garantindo diversidade mesmo para usuários com perfil definido. | |

## Avaliações de usuários

| ID | Descrição | Prioridade |
|----|-----------|------------|
| RF-07 | O sistema deve destacar avaliações que mencionam adequação para famílias ou crianças. | |

## Assistente conversacional (IA)

| ID | Descrição | Prioridade |
|----|-----------|------------|
| RF-08 | O assistente deve interpretar o contexto da pergunta do usuário, considerando histórico da conversa e intenção, antes de buscar informações. | |
| RF-09| O assistente deve informar ao usuário de forma clara quando não encontrar informações, sem encerrar o fluxo abruptamente, oferecendo alternativas de ação. | |
| RF-10 | O sistema deve oferecer ao usuário a opção de acessar o assistente IA diretamente a partir da tela de resultados de busca. | |

---

# Histórias de Usuário

Perspectiva do usuário. O que ele quer e por quê.

## Descoberta e navegação

| ID | História |
|----|----------|
| HU-01 | Como moradora, quero ver horários e preços antes de sair, para não ir a um lugar sem informação suficiente. |
| HU-02 | Como novo morador, quero descobrir lugares além dos mais conhecidos, para explorar a região além do óbvio. |
| HU-03 | Como usuário sem destino definido, quero ver sugestões de locais em alta e novidades ao abrir o app, para me inspirar sem precisar pesquisar. |
| HU-04 | Como usuário em busca de um local específico, quero pesquisar por nome, categoria ou cidade e receber resultados do catálogo regional, para encontrar o que preciso rapidamente. |
| HU-05 | Como usuário que não encontrou o que buscava, quero receber uma mensagem clara de "sem resultados" com sugestões do que tentar, para não encerrar minha busca frustrado. |

## Segurança e confiança

| ID | História |
|----|----------|
| HU-06 | Como visitante que planeja trazer a família, quero ver informações claras sobre segurança do local, para me sentir confiante ao planejar um passeio com minha esposa e filhos. |

## Planejamento e informação

| ID | História |
|----|----------|
| HU-07 | Como usuário recorrente da plataforma, quero que o sistema aprenda minhas preferências culturais e gastronômicas com o tempo, para receber sugestões cada vez mais alinhadas ao meu gosto. |

## Assistente conversacional

| ID | História |
|----|----------|
| HU-08 | Como usuário interessado na cultura do Cariri, quero conversar com um assistente que entenda minhas preferências culturais e gastronômicas, para receber sugestões personalizadas ao meu gosto. |
| HU-09 | Como usuário do chatbot, quero que o assistente entenda o contexto da minha pergunta e não apenas palavras-chave isoladas, para receber respostas mais precisas e naturais. |
| HU-10 | Como usuário que não obteve resposta do chatbot, quero ser direcionado para uma ação alternativa, para não ficar preso em um beco sem saída dentro da plataforma. |
| HU-11 | Como usuário que viu os resultados mas quer saber mais, quero ter acesso rápido ao assistente IA a partir da tela de resultados, para aprofundar minha pesquisa sem recomeçar do zero. |