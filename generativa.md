# IA Generativa
Simula o comportamento humano utilizando aprendizado de máquina para interagir com o ambiente e executar tarefas com poucas intruções, criando conteúdo original.
## Tipos de geração
- Linguagem natural: cria um texto a partir de uma instrução.
- Código: criação de um código a partir de uma instrução.
- Imagem: cria uma imagem a partir de uma instrução.
## Modelo de Linguagem Grandes (LLM)
Modelos de aprendizado de máquina que executa tarefas de PLN (Processamento de Linguagem Natural).
### Modelo Transformador
Transforma um texto em um conjunto de tokens e os relaciona. Formado por 2 componentes principais:
- Bloco codificador: cria representações semânticas dos dados inciais.
- Bloco decodificador: gera nova sequências de linguagem com base nas informações do codificador.
Primeiro, as palavras são transformadas em tokens, depois, uma inserção (valores em vetor com várias dimensões) é atribuída aos tokens, após, uma camada de atenção analisa os tokens e os associa com base na relação das inserções, por fim, o decodificador seleciona o termo com maior probabilidade de ocorrrer.
## Copilotos
Integrações em aplicações que assistenciam os mesmos na execução de tarefas / experiência do usuário.
## Engenharia de prompts
Processo de aprimoramento de prompts para melhor execução / perfomance.
## Serviço OpenAI do Azure
Solução de nuvem para implantar, personalizar e hospedar modelos de linguagem grande. A segurança corporativa é efetivada por RBAC (controle de acesso baseado em função) e redes privadas.
### Modelos de Linguagem Grande do Azure
- GPT-4
- GPT-3.5
- Incorporação
- DALL-E
