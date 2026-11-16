# Notas técnicas

## Arquitetura

A aplicação é mantida em um único documento HTML. A estrutura, os estilos e a lógica JavaScript estão reunidos em `index.html`, sem etapa de build.

## Renderização visual

- O elemento principal exibe a imagem ou o vídeo respeitando o enquadramento escolhido.
- O Canvas 2D é utilizado para desenhar partículas e o campo de luz ambiente.
- A amostragem de cores da mídia alimenta a composição do ambiente.
- A Web Audio API analisa frequências do vídeo quando a reação ao som está habilitada.

## Compatibilidade

Recomenda-se utilizar uma versão atualizada de Chrome, Firefox, Edge ou Safari. A disponibilidade de recursos de áudio e tela cheia depende das permissões e capacidades do navegador.
