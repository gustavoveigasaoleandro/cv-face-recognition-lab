# cv-face-recognition-lab

Laboratorio de reconhecimento facial com OpenCV, cobrindo preparacao de imagens, extracao de faces e avaliacao de reconhecedores classicos.

## Conteudo

- `face_recognition_lab.ipynb`: notebook principal do experimento.
- `classificadores/`: classificadores auxiliares, como Haar Cascade.
- `imagens/`: amostras reduzidas usadas para demonstracao.
- `requirements.txt`: dependencias do projeto.

## Objetivo

O repositorio demonstra um fluxo didatico de reconhecimento facial:

- leitura e organizacao de imagens;
- deteccao facial com classificadores pre-treinados;
- padronizacao de amostras;
- treino e comparacao de metodos classicos;
- avaliacao com metricas de classificacao.

## Dados e Artefatos

O dataset completo e arquivos pesados de landmarks nao foram publicados. A versao do repositorio mantem apenas uma amostra e recursos suficientes para estudo do notebook.

## Como Executar

Instale as dependencias:

```bash
pip install -r requirements.txt
```

Abra o notebook:

```bash
jupyter notebook face_recognition_lab.ipynb
```

## Cuidados

Reconhecimento facial envolve privacidade e vieses. Este repositorio deve ser tratado como estudo tecnico, nao como solucao pronta para identificacao de pessoas em ambiente real.
