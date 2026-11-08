# Projeto M2.1 – Filtragem na Frequência e Segmentação

## Descrição

Este repositório contém a implementação do **Projeto M2.1 – Filtragem na Frequência e Segmentação**, da disciplina de Processamento de Imagens.

O trabalho foi desenvolvido em `Python` utilizando o `Google Colab` e aborda a aplicação de filtros passa-baixa no domínio da frequência e métodos de segmentação de imagens, com o objetivo de analisar a redução de falhas em caracteres e os efeitos da filtragem na preservação dos traços e espaços internos das letras.

## Disciplina

Processamento de Imagens

## Acadêmicas

- Beatriz Pimentel Bagesteiro Alves
- Maria Eduarda Santos
- Yasmin Tarnovski Faccin

## Conteúdo

- Filtragem passa-baixa no domínio da frequência;
- Filtro Ideal;
- Filtro Butterworth (ordens 1, 2 e 4);
- Filtro Gaussiano;
- Frequências de corte (`fc = 0.08` e `fc = 0.16`);
- Segmentação pelo método de Otsu;
- Segmentação por K-means;
- Detecção de bordas pelo método de Canny;
- Análise visual das imagens completas e dos recortes;
- Avaliação da qualidade das imagens por meio das métricas PSNR e SSIM;
- Avaliação das máscaras de região por meio das métricas IoU e Dice;
- Avaliação dos contornos por meio do F1 de bordas;
- Comparação dos resultados dos métodos de segmentação.

## Tecnologias utilizadas

- Python
- Google Colab
- OpenCV
- NumPy
- Matplotlib
- scikit-image (skimage.metrics)

## Arquivo

O arquivo `.ipynb` está disponível neste repositório. Para visualizar e executar o trabalho, é possível baixar o notebook e abri-lo no Google Colab.

- `projeto_m2_1_filtragem_na_frequencia_e_segmentacao.ipynb` - Notebook com as implementações, testes, comparações e resultados do trabalho.

## Dataset

A imagem utilizada no trabalho foi disponibilizada pelo professor.

[Dataset - Operação Morfologia](https://github.com/VielF/ColabProjects/tree/main/dataset/OperacaoMorfologia)

Imagem utilizada: `Fig0907(a)(text_gaps_1_and_2_pixels).tif`.
