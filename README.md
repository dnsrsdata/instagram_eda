### Sobre o problema

O mundo da criação de conteúdo no Instagram é extremamente dinâmico e 
diversificado. A plataforma é conhecida por ser altamente visual, com foco em 
imagens e vídeos, e é amplamente utilizada por uma variedade de usuários, desde 
indivíduos comuns até celebridades, influenciadores, marcas e empresas.

Por isso, aos que começaram ou pretendem começar nesse mundo, seria interessante
entender como perfis de sucesso se relacionam com determinadas características,
apontando assim diferentes caminhos para o usuário.

### Objetivo

Com dados da plataforma, é de interesse dos usuários entenderem como perfis de
sucesso se relacionam com determinadas variáveis. Com isso, uma análise 
exploratória pode apontar um caminho que eles podem seguir para aumentar as 
chances de sucesso na plataforma.

### Sobre os dados

O conjunto utilizado é composto por dados coletados em dezembro de 2022. Suas 
colunas são as seguintes:
- Rank: classificação.
- name: arroba de usuário.
- instagram name: nome de usuário.
- Category_1: categoria do perfil.
- Category_2: categoria do perfil.
- followers: quantidade de seguidores.
- country: país do usuário.
- Eng. (Auth.): engajamento do mês.
- Eng. (Avg.): engajamento médio.

Para download, siga o seguinte link: [Social Media Dataset](https://www.kaggle.com/datasets/ramjasmaurya/top-1000-social-media-channels)

### Instruções para execução do projeto

Esse projeto foi desenvolvido usando o Python 3.10.12. Para executar o projeto,
siga os passos abaixo:

1. Clone o repositório:
```sh
git clone https://github.com/dnsrsdata/instagram_eda
```
2. Instale o poetry:
```sh
pip install poetry
```
3. Inicie o poetry:
```sh
poetry init
```
4. Instale as dependências do projeto:
```sh
poetry install
```
5. Execute o notebook

### Descrição dos arquivos

    - notebooks
    |- EDA.ipynb  # Notebook contendo a análise exploratória dos dados
    |
    - relatorio
    |- analise_instagram.pdf  # Relatório em pdf usado para apresentar o resultado da análise 
    |
    - README.md  # Arquivo contando informações do projeto
    - poetry.lock # Arquivo contendo as informações sobre os pacotes usados
    - pyproject.toml # Arquivo contendo informações sobre o projeto e dependências usadas

### Resultados

As descobertas foram condensadas em um arquivo pdf de relatório, visando
facilitar o consumo dos insights. Confira a solução na pasta ```relatorio```.