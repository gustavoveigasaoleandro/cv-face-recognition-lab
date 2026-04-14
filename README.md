# OpenCV Face Recognition Lab

Laboratorio de reconhecimento facial com OpenCV, comparando Eigenfaces, Fisherfaces e LBPH a partir de um notebook.

## Arquivos

- `face_recognition_lab.ipynb`: notebook principal do estudo
- `classificadores/haarcascade_frontalface_default.xml`: cascade para deteccao facial
- `imagens/`: imagens de exemplo usadas no laboratorio

## Como executar

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook face_recognition_lab.ipynb
```

## Dependencias

O notebook usa OpenCV com modulo `face`, alem de `matplotlib` e `scikit-learn`.

## Nota de publicacao

Este repositorio foi preparado de forma conservadora para GitHub:

- o dataset completo de faces foi removido
- os arquivos `shape_predictor_5_face_landmarks.dat` e `shape_predictor_68_face_landmarks.dat` foram removidos por tamanho e por serem artefatos externos
- o notebook foi mantido como material de estudo, mas pode exigir que voce reponha localmente os datasets e modelos auxiliares para reproduzir todo o fluxo original
