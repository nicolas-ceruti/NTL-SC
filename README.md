# Análise do Crescimento Urbano no Litoral de Santa Catarina via Imagens de Luzes Noturnas

O trabalho investiga onde e como as áreas urbanas do litoral de Santa Catarina
cresceram entre 2015 e 2025, usando luzes noturnas (NTL) do produto VIIRS Black
Marble (VNP46A2). O pipeline combina pré-processamento de rasters, uma rede
ConvLSTM2D que classifica o padrão temporal de brilho de cada região ao longo dos
anos e análise geoespacial. Como produto final calcula-se o IPA (Índice de Prioridade de
Acesso), que mede o quanto o crescimento de cada município se concentra próximo à
BR-101. Avaliado em uma região de teste geograficamente separada, o modelo alcançou
acurácia de 0,85 e F1-macro de 0,70. Dos 38 municípios litorâneos, 18 concentram o
crescimento até 5 km da rodovia, o que orienta a recomendação de priorizar acesso viário
(IPA alto) ou mobilidade urbana interna (IPA baixo).
