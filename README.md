# cv-face-recognition-lab

Laboratório de reconhecimento facial com OpenCV, cobrindo preparação de imagens, extração de faces e avaliação de reconhecedores clássicos.

## Conteúdo

- `face_recognition_lab.ipynb`: notebook principal do experimento.
- `classificadores/`: classificadores auxiliares, como Haar Cascade.
- `imagens/`: amostras reduzidas usadas para demonstração.
- `requirements.txt`: dependências do projeto.

## Objetivo

O repositório demonstra um fluxo didático de reconhecimento facial:

- leitura e organização de imagens;
- detecção facial com classificadores pre-treinados;
- padronização de amostras;
- treino e comparação de métodos clássicos;
- avaliação com métricas de classificação.

## Dados e Artefatos

O dataset completo e arquivos pesados de landmarks não foram publicados. A versão do repositório mantem apenas uma amostra e recursos suficientes para estudo do notebook.

## Como Executar

Instale as dependências:

```bash
pip install -r requirements.txt
```

Abra o notebook:

```bash
jupyter notebook face_recognition_lab.ipynb
```

## Cuidados

Reconhecimento facial envolve privacidade e vieses. Este repositório deve ser tratado como estudo técnico, não como solução pronta para identificação de pessoas em ambiente real.
