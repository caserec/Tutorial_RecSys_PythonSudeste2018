# Workshop Monitora Summer 2nd Edição

Título: Personalização de conteúdo: Utilizando sistemas de recomendação baseado no comportamento de usuários

Palestrante: Arthur Fortes da Costa

Data: Quarta, 21/02/2018

# Resumo:

Os sistemas de recomendação são uma subárea de recuperação de informação (do inglês, Information Retrival) que tem por objetivo fazer novas sugestões personalizadas que possam vir a ser de interesse do usuário, com base nos seus feedback (sejam implícitos ou explícitos) ou nas escolhas feitas por outros usuários com gostos similares. Ao navegar por sites como Amazon, Facebook e Americanas você já se deparou com frases como “Quem viu este produto, viu também…”, “Clientes que compraram este item também compraram…” e “Porque você comprou este produto…” ? Ou quem sabe, ao assistir um filme ou ouvir uma música no Netflix/ Spotify, encontrou, dentre as sugestões, alguma outra produção que se encaixava direitinho com seu gosto? Nesta palestra, serão apresentados os principais conceitos e estratégias que os sistemas utilizam para transformar dados em informação personalizada altamente poderosa.


# Requisitos: 

- Python >= 3.4
- Numpy
- Scipy
- Pandas
- sklearn
- jupyter
- caserecommender == 1.0.1

# Bases de Dados

Movie Lens 100k (Pasta /dataset)

[Other Databases](https://github.com/ArthurFortes/Datasets-for-Recommneder-Systems)


# Mini Desafio

Criar um perfil representativo do usuário para utilizar no algoritmo User Attribute KNN, 
baseado em item recommendation (Ranking). O algoritmo está disponível na ferramenta 
[CaseRecommender](https://github.com/ArthurFortes/CaseRecommender/blob/master/caserec/recommenders/item_recommendation/item_attribute_knn.py). 

O arquivo de perfil de usuário deve seguir o seguinte formato: 

usuário(sep)metadado(característica)(sep)valor(se houver, pode ser implícito)

Por default, na ferramenta, (sep)=\t.

## Avaliar Workshop

[Formulário de avaliação](https://docs.google.com/forms/d/e/1FAIpQLSeYEM55GCeoPs03m5TFrExYHlxP8rhSVKDommrKw2cv-iKdvA/viewform?usp=sf_link)

