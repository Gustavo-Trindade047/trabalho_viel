# Aluno Gustavo G. Trindade
# Professor Viel

Trabalho desenvolvido com o intuito de explicar as linhas do código passadas pelo professor Viel na aula, espero que esteja claro e didático.

As operações morfológicas são técnicas empregadas no processamento de imagens com o intuito de alterar sua forma, estrutura e características. São executadas por meio da aplicação de um elemento estruturante, que é uma matriz de determinado tamanho e forma, sobre a imagem.

Existem diversas operações morfológicas disponíveis, algumas das quais são ilustradas neste código.

Erosão: Essa operação diminui as dimensões das áreas brancas (ou claras) na imagem, eliminando detalhes finos e contornos. É realizada ao percorrer a imagem com o elemento estruturante e, para cada posição, se ao menos um pixel coberto pelo elemento estruturante estiver preto (ou escuro), o pixel correspondente na imagem resultante é definido como preto.

Dilatação: Por sua vez, a dilatação aumenta as dimensões das áreas brancas, preenchendo espaços vazios e conectando objetos próximos. Também percorre a imagem com o elemento estruturante e, para cada posição, se ao menos um pixel coberto pelo elemento estruturante estiver branco, o pixel correspondente na imagem resultante é definido como branco.

Gradiente morfológico: Essa operação realça as bordas e contornos dos objetos presentes na imagem. É realizada pela diferença entre a imagem resultante da dilatação e a imagem resultante da erosão.

Abertura: A abertura consiste na aplicação sequencial de uma erosão seguida de uma dilatação. É útil para remover detalhes pequenos e ruídos, além de suavizar as bordas dos objetos.

Fechamento: O fechamento, por sua vez, é o inverso da abertura, sendo executado com uma dilatação seguida de uma erosão. Ele preenche espaços vazios e conecta regiões próximas, sendo útil para fechar buracos nos objetos.

Essas operações morfológicas possuem diversas aplicações, tais como eliminação de ruídos, segmentação de objetos, detecção de bordas, preenchimento de áreas e em muitas outras áreas do processamento de imagens.
