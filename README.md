**Código fonte da dissertação de mestrado intitulada "Estratégias para Detecção Precoce de Predadores Sexuais em Conversas realizadas na Internet"**

---

O código foi desenvolvido em notebooks Jupyter utilizando o ambiente Google Colaboratory, sendo de fácil execução.

**Passos para executar os notebooks:**

- Criar um arquivo chamado "config.py" com a mesma estrutura do arquivo "config_example.py" dentro da pasta "config";
- No arquivo "config.py", inserir o caminho da pasta do projeto na variável "DRIVE_PATH";
- No arquivo "config.py", inserir o caminho da pasta de resultados na variável "RESULTS_PATH";
- Fazer upload dos arquivos "config.py", "bert.py", "classification.py" e "utils.py" no ambiente conectado do Google Colaboratory.

Os notebooks podem rodar localmente, mas podem ser necessárias configurações adicionais.

A base de dados do PAN 2012, utilizada como conjunto de dados neste trabalho, pode ser obtida [neste link](https://pan.webis.de/data.html#pan12-sexual-predator-identification).

O texto da dissertação pode ser acessado [neste link](https://www.cos.ufrj.br/index.php/pt-BR/publicacoes-pesquisa/details/15/3062).
# Projeto-Final-BMT
Projeto Final de Busca e Mineração de Texto

A combinação entre Busca e Mineração de Texto e algoritmos classificadores de aprendizado de máquina permite extrair diversos sentidos de problemas de natureza escrita.
Entre eles, a dissertação de mestrado de Marcelle Campos Panzariello se debruça especificamente na detecção de predadores sexuais em conversas online. 
Para tal, um tratamento extensivo dos dados foi implementado junto com uma bateria de experimentos utilizando diversos algoritmos de aprendizado de máquina, entre eles SVM, K-Nearest-Neighbors, Árvores Aleatórias, entre outros.
No entanto, 
entre os filtros colocados para processar o texto da melhor forma,
os links compartilhados entre os usuários foram descartados por completo da análise.
A proposta deste trabalho é realizar um novo experimento neste contexto, 
dessa vez considerando as URLs trocadas entre os usuários.
