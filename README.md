# Extração e Processamento de Dados de PDF

Este projeto é uma aplicação em Python que extrai e processa dados de arquivos PDF. Ele utiliza técnicas de processamento de imagem para corrigir a perspectiva das imagens e OCR (Reconhecimento Óptico de Caracteres) para extrair os dados.

## Funcionalidades
Converte arquivos PDF em imagens

Corrige a perspectiva das imagens

Extrai dados das imagens usando OCR

Salva os dados extraídos em um arquivo Excel

## Requisitos
Python 3.8 ou superior

OpenCV

PyTesseract

Openpyxl

pdf2image

poppler-utils

## Instalação

1. Clone o repositório:
```bash
git clone https://github.com/sacaaa/pdf-to-excel
```

2. Instale os requisitos:
```bash
pip install opencv-python
pip install pytesseract
pip install openpyxl
pip install pdf2image
```
Baixe as bibliotecas [Poppler](https://poppler.freedesktop.org/) e [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) por aqui e cole elas na pasta 'assets'


## Uso

1. oloque seus arquivos PDF no diretório input_pdf e atualize o dicionário COORDINATES conforme o seu PDF.
2. Rode o script:

```bash
python main.py
```

3. Os dados processados serão salvos no diretório output_excel.


Abração, Natanael.

