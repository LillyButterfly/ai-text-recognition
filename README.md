Aqui está o `README.md` atualizado com a observação sobre as limitações do **Vision Framework** no reconhecimento de textos com fontes variadas e imagens com fundo transparente:

---

# Projeto de Reconhecimento de Texto com iPhone 12 (iOS 17)

Este projeto tem como objetivo realizar o reconhecimento de texto em imagens utilizando o **Vision Framework**, uma tecnologia nativa do iOS. O projeto foi desenvolvido e testado em um **iPhone 12** rodando **iOS 17**.

## Ferramentas Utilizadas

- **Dispositivo**: iPhone 12
- **Sistema Operacional**: iOS 17
- **Framework Utilizado**: Vision Framework (nativo do iOS)

## Descrição do Projeto

O reconhecimento de texto foi realizado em imagens capturadas com o iPhone e processadas diretamente no dispositivo utilizando a API de reconhecimento de texto do **Vision Framework**. A API permite identificar e extrair texto de imagens com precisão, e o projeto demonstra como isso pode ser feito de forma simples e eficiente.

### Estrutura do Projeto

- **inputs/**: Pasta contendo as imagens utilizadas para o reconhecimento de texto.
- **output/**: Pasta contendo os arquivos de texto extraídos a partir das imagens.
- **README.md**: Arquivo de documentação com explicações sobre o processo e insights adquiridos.

## Como Funciona o Reconhecimento de Texto

1. **Captura de Imagens**: As imagens contendo o texto a ser extraído foram capturadas com a câmera do iPhone 12.
2. **Processamento de Texto**: O Vision Framework foi utilizado para realizar o reconhecimento de texto em tempo real diretamente no dispositivo.
3. **Extração e Armazenamento**: O texto extraído foi salvo e armazenado na pasta **output**.


### Limitações Encontradas

- **Fontes Variadas**: O Vision Framework apresentou dificuldade em reconhecer textos em imagens que possuem **fontes muito diferentes** ou com estilos gráficos contrastantes na mesma imagem. Isso impacta a precisão do OCR.
- **Imagens com Fundo Transparente**: O reconhecimento de texto em imagens com **fundo transparente** também não foi eficaz, gerando dificuldades na identificação e extração precisa do conteúdo.

### Insights e Aprendizados

- O **Vision Framework** é altamente eficiente e fácil de integrar em projetos iOS para reconhecimento de texto.
- O processamento de texto é feito diretamente no dispositivo, o que oferece maior privacidade e rapidez ao realizar OCR.
- O desempenho no **iPhone 12** rodando **iOS 17** foi excelente, com um reconhecimento de texto rápido e preciso, exceto nos casos mencionados acima.

## Possibilidades Futuras

- **Expansão para vídeos**: Usar o Vision Framework para realizar reconhecimento de texto em tempo real em vídeos.
- **Aprimoramento do suporte a múltiplos idiomas**: Testar o reconhecimento de texto em diferentes línguas e scripts.
- **Interface de usuário**: Criar uma interface gráfica que permita ao usuário tirar fotos e ver os textos reconhecidos na tela do dispositivo.


## Conclusão

Este projeto demonstra como é possível usar tecnologias nativas do iOS para realizar reconhecimento de texto com alta precisão. Apesar das limitações em reconhecer textos com fontes variadas e imagens com fundo transparente, o **Vision Framework** ainda é uma excelente solução para a maioria das aplicações de OCR.

---

Se precisar de mais ajustes, só avisar!
