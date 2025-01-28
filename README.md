# IAExp_NLP
Trilha Processamento de Linguagem Natural

1. Mineração de Emoção em Textos com Python e NLTK
2. Processamento de Linguagem Natural com spaCy e Python
3. Mineração e Análise de Dados do LinkedIn
4. Mineração e Análise de Dados do Facebook
5. Inteligência Artificial: Buscas em Textos com Python
6. Sumarização de Textos com Processamento de Linguagem Natural
7. Machine Learning para Competições Kaggle: Especial COVID-19
8. Chatbots com Python e Dialogflow: O Guia para Iniciantes
9. Deep Learning com Python de A à Z: O Curso Completo
10. Processamento de Linguagem Natural com Deep Learning
11. Processamento de Linguagem Natural com BERT e Python
12. Classificação de Áudio com Python: O Guia Completo
13. Assistentes Virtuais em Python: O Guia para Iniciantes
14. Explorando o ChatGPT: Guia Prático para Iniciantes
15. Domine LLMs com LangChain
16. Deep Learning com TensorFlow Hub
17. TensorFlow, Deep Learning e Python: Construa um Chatbot
18. TensorFlow 2.0: Um Guia Completo sobre o novo TensorFlow
19. Deep Learning Prático com TensorFlow e Python

## Bibliotecas

- **NLTK (Natural Language Toolkit)**: Platform for building Python programs to work with human language data
- **spaCy**: Open-source library for advanced Natural Language Processing (NLP) in Python.

## Palavras-Chaves

- **Stop Words**: Palavras comumente usadas (como "o", "a", "um" ou "em") que um mecanismo de pesquisa foi programado para ignorar.
  -   `nltk.corpus.stopwords.words('portuguese')`
- **Stemming**:  Técnica que reduz palavras para suas bases/raízes ao remover prefixos e/ou sufixos.
  - `nltk.stem.RSLPStemmer()`
- **Naive Bayes Classifier**: Algoritmos de aprendizado de máquina supervisionados usados para tarefas de classificação, com base no Teorema de Bayes para encontrar probabilidades.
  - `nltk.NaiveBayesClassifier.train(---)`
- **Part-of-Speech**: Categoria gramatical qque descreve a função de uma palavra em uma sentença.
- `(spacy) token.pos_`
- **Lemmatization**: Retorna as palavras ao seu dicionário ou forma básica, considerando o contexto e o significado.
  - `(spacy) token.lemma_`
- **Named-Entity**: Expressão que pode ser extraída de um texto e é essencial para compreender, concluir ou ignorar um determinado contexto ou ação.
- **Named-Entity Recognition**:  Reconhecer (identificar e classificar) entidades nomeadas presentes em textos escritos em linguagem natural.
  - `(spacy) doc.ents:`, `ent.label_`
- **Dependecy Parsing**: Técnica para identificar as relações gramaticais entre palavras em uma sentença.
  - `displacy.render(my_doc, style="dep", jupyter=True, options={"distance": 90})`
- **Global Vectors for Word Representation (GloVe)**: Algoritmo de aprendizado não supervisionado para obter representações vetoriais para palavras. Utilizado para semelhança entre palavras.
  - `(spacy) Doc.similarity(p2)`
- **Levenshtein (edition) Distance**: Número mínimo de operações necessárias para transformar uma string em outra
  - `from nltk.metrics.distance import edit_distance`
- **N-Grams**: Métrica usada para comparar sequências de texto, como palavras ou frases, com base em n-gramas (tokens). Um n-grama é uma subsequência de n itens de uma dada sequência.
  - `nltk.bigrams`, `nltk.trigrams`, ... 
- **Jaccard Distance**: Métrica usada para calcular a dissimilaridade entre dois conjuntos.
  - `from nltk.metrics.distance import jaccard_distance`
