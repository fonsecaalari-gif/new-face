# new-face

Troca de rostos em vídeo com IA (FaceFusion) rodando de graça no Google Colab.

## Abrir o notebook

Clique no badge ou acesse pelo Colab: **Arquivo > Abrir notebook > GitHub** e cole: `fonsecaalari-gif/new-face`

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fonsecaalari-gif/new-face/blob/main/FaceSwap_Colab.ipynb)

## Passo a passo

1. Ative a GPU: **Ambiente de execução > Alterar o tipo de ambiente de execução > T4 GPU**
2. Rode as 3 células na ordem
3. Clique no link `*.gradio.live` gerado na última célula
4. Na interface:
   - **SOURCE**: foto do rosto de referência (frontal, nítida, boa iluminação)
   - **TARGET**: seu vídeo (mp4)
   - Em **PROCESSORS**, marque `face_swapper` (opcional: `face_enhancer`)
   - Clique em **START** e baixe o resultado na aba **OUTPUT**

## Uso responsável

- Apenas com consentimento de todas as pessoas identificáveis
- Indique no conteúdo que foi gerado/editado por IA (LGPD, Lei 26.302/2025)
- Nunca use para impersonação, desinformação ou conteúdo íntimo não consensual
