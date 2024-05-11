# Mega_ProjetoImersao
o projeto apresenta um sistema de busca semântica e reescrita de texto utilizando a API do Google Gemini. Ele permite aos usuários criar embeddings de texto para realizar consultas semânticas em um conjunto de documentos, identificando o conteúdo mais relevante com base no significado da consulta. Além disso, o sistema oferece a capacidade de reescrever textos de forma mais natural e descontraída, utilizando modelos de IA generativa. O projeto é uma ferramenta valiosa para estudantes e desenvolvedores interessados em aplicações de busca inteligente e processamento de linguagem natural.
Exemplos de Uso:

1.Geração de Embeddings para Consulta Semântica:
python
titulo = "Inteligência Artificial Avançada"
texto = "Explorando as profundezas da IA e suas aplicações no mundo moderno."
embeddings = gerar_embeddings(titulo, texto)
print("Embeddings gerados:", embeddings)

2.Busca Semântica em Documentos:
Python
consulta = "Como a IA pode ser aplicada na medicina?"
documento_relevante = buscar_documento(consulta, df_documentos)
print("Documento mais relevante encontrado:", documento_relevante)

3.Resscrita de Texto com IA:
Python
texto_original = "A IA está transformando o setor de tecnologia."
texto_reescrito = reescrever_texto(texto_original)
print("Texto reescrito de forma descontraída:", texto_reescrito)

Esses exemplos demonstram como o sistema pode ser utilizado para explorar e interagir com conteúdos de forma semântica e criativa, abrindo novas possibilidades para o desenvolvimento de aplicações de IA.
