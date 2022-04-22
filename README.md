# Projeto Clone Netflix

Projeto do Bootcamp DIO de Front End baseado no layout da Netflix

O layout foi baseado na Netflix e o projeto foi adaptado a uma plataforma de reviews em vídeo de Jogos Eletrônicos.
No menu, foram criadas categorias para PC e os consoles de última geração.

Mudanças em relação ao projeto apresentado em aula:

 - Menu fixo no topo da página.
 - Links do menu levam para as categorias
 - Inserido um vídeo do youtube no botão Ver Review. 
 - O VS Code indicava erro no atributo linear-gradient da imagem de fundo do jogo principal. Retirado o 100% inserido ao final do atributo e o programa parou de indicar o erro. Não houve mudança em relação à visualização no Live Server

Problemas a serem resolvidos:

 - A imagem do jogo principal não é exibida quando o arquivo html é aberto. A imagem somente é exibida na visualização pelo Live Server. A inserção da imagem como background está de acordo com a documentação.
 - O link no menu leva até a seção, mas o menu fica sobreposto ao início do conteúdo da seção. Não encontrei uma maneira da margem inferior do header terminar no início da seção a qual o link direciona.
 - Não encontrei o código para que o vídeo de review fosse aberto na própria página sobrepondo o conteúdo. Aparentemente, isso é feito com JavaScript.