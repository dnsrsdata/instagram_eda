### Sobre o problema

O mundo da criação de conteúdo no Instagram é extremamente dinâmico e 
diversificado. A plataforma é conhecida por ser altamente visual, com foco em 
imagens e vídeos, e é amplamente utilizada por uma variedade de usuários, desde 
indivíduos comuns até celebridades, influenciadores, marcas e empresas.

Por isso, aos que começaram ou pretendem começar nesse mundo, seria interessante
entender como certos grupos se relacionam com determinadas características,
apontando assim diferentes caminhos para o usuário.

### Objetivo

Com dados da plataforma, é de interesse dos usuários entenderem como determinados
grupos se relacionam com determinadas variáveis. Com isso, uma clusterização dos
perfis atuais, aliada a uma análise exploratória pode apontar um caminho que
eles podem seguir para garantir o sucesso no caminho de interesse.

Além disso, uma análise temporal dos de cada categoria também pode apontar
caminhos primissores.

### Sobre os dados

O conjunto utilizado é composto por dados coletados em diferentes momentos 
de 2022. Suas colunas são as seguintes:
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

### Métricas de avaliação

Para avaliar a divisão dos cluster, a **silhouette score** em conjunto do 
**elbow method**, serão utilizados.

### Melhorias


### Instruções para execução do projeto

Esse projeto foi desenvolvido usando o Python 3.10.12. Para executar o projeto,
siga os passos abaixo:

1. Clone o repositório:
```sh
git clone https://github.com/dnsrsdata/instagram_segmentation
```
2. Instale o poetry:
```sh
pip install poetry
```
3. Instale as dependências do projeto:
```sh
poetry install
```
4. Execute os notebooks

### Descrição dos arquivos

### Resultados
