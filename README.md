# UiPath Document Understanding

O framework UiPath Document Understanding facilita o processamento de arquivos recebidos, desde a digitalização de arquivos até a validação de dados extraídos, tudo em um ambiente aberto, extensível e versátil.

## Requisitos
- Crie um ativo com o nome **DuAPIKey** e forneça o valor como chave da API Document Understanding.

## Tipos de Arquivos Suportados
- Arquivos que são imagens
  - Os formatos de imagens suportados são .png, .gif, .jpe, .jpg, .jpeg, .tiff, .tif, .bmp
  - Para arquivos TIFF de várias páginas, o OCR é aplicado a cada página
- Páginas de PDF que
  - Não expõem nenhum conteúdo legível por máquina
  - Contêm imagens que cobrem uma área significativa da página.
