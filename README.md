**Vinheria Agnello**

**Sobre o projeto**:
O projeto Vinheria Agnello consiste em um desenvolvimento de um site para uma vinheria especializada em vendas de vinhos internacionais e nacionais. O objetivo é criar uma forma digital para a empresa, apresentando sua identidade, seus produtos e informações.
Além disso, o projeto busca proporcionar uma experiência próxima a consultoria presencial oferecida pela equipe da vinheria. Disponobilizando informações que auxiliem o cliente em sua escolha e criando uma aproximação entre a vinheria e seus consumidores. 

---

**Estrutura do projeto**:
O site é dividido em páginas e seções que organizam da Vinheria Agnello. Cada parte possui uma finalidade específica para deixar a experiência do usuário mais satisfatória possível. 

Página inicial (index.html):
        A pagina inicial funciona como uma introdução a vinheria. Nela, são apresentadas a identidade da empresa, sua proposta e informações introdutórias sobre a marca. A página também destaca a tradição da empresa, os cuidados com seus produtos e a experiência oferecida aos consumidores. E também, o final da página possui formas de contato com a vinheria, facilitando a comunicação entre o cliente e a equipe da empresa. 
        O objetivo é apresentar a marca e direcioná-los aos outros conteúdos do site por meio do menu de navegação. 

Página catálogo (catalogo.html):
        A pagina catálogo apresenta os destaques disponíveis para venda na Vinheria Agnello. Nela são apresentadas as informações sobre os diferentes rótulos, permitindo que o usuário conheça melhor as opções oferecidas e encontre um vinho que esteja de acordo com suas preferências. 
        Além disso, a página oferece uma tabela de guia de harmonização para auxiliar o cliente para a escolha do seu vinho. E também, o final da página possui formas de contato com a vinheria, facilitando a comunicação entre o cliente e a equipe da empresa. 

Página consultoria (consultoria.html):
        Essa página possui o serviço de consultoria especializada em vinhos oferecido pela Vinheria Agnello de forma gratuita. A proposta é levar para o ambiente digital a experiência de orientação que os clientes encontram na loja física. 
        Na página o usuário encontra uma explicação de como funciona a consultoria, desde o primeiro contato com a equipe até a indicação dos rótulos mais adequados para cada ocasião. Também são apresentados exemplos de situações em que a consultoria pode ajudar. 
        Além disso, a página possui uma seção de perguntas frequentes, esclarecendo dúvidas sobre o funcionamento e o custo da consultoria, e disponibiliza um direcionamento para a página de contato. 
        A página também conta com um link externo para um conteúdo da Salton "3 Estratégias Infalíveis para se Tornar um Especialista em Degustação de Vinhos". O conteúdo foi adicionado como material complementar para os visitantes que desejam se aprofundar mais no mundo dos vinhos. 

Página Nossa história (sobre.html):
        A página apresenta a trajetória da Vinheria Agnello e a origem da empresa. O conteúdo conta sobre a história de Giulio Agnello e sua relação com o vinho, mostrando como essa paixão deu origem ao negócio.
        A página também apresenta como a vinheria trabalha atualmente destacando o cuidado na seleção e no armazenamento dos vinhos e a importância de oferecer recomendações de acordo com cada cliente e ocasião. 
        Além da história são apresentados os principais diferenciais e também as principais formas de contato com a empresa. 

Página Contato (contatos.html):
        A pagina contato foi desenvolvida para facilitar a comunicação com os clientes. A página possui um formulário de contato, no qual o usuário pode informar seu nome completo, e-mail e enviar uma mensagem para a equipe. 
        Além do formulário, são disponibilizados outras formas de contato com a empresa, permitindo que o cliente escolha a melhor forma de comunicação. 

---

**Efeitos visuais**:
Para deixar a navegação mais dinâmica, o site utiliza efeitos em CSS, organizados no arquivo `efeito.css` (importado no início do `style.css`) e em regras do próprio `style.css`.

Pseudo-classes:
    - `:hover`: ao passar o mouse, os links do menu mudam de cor e sobem levemente, as imagens das seções aumentam e os cards de vinho do catálogo sobem.
    - `:any-link`: aplica o efeito do menu apenas nos links de navegação (`nav a:any-link:hover`).
    - `:focus-visible`: destaca o botão de enviar do formulário de contato quando é acessado pelo teclado.
    - `:visited`: mantém a cor dos links do menu depois de visitados.

Pseudo-elementos:
    - `::after`: cria uma linha dourada decorativa (60px de largura e 3px de altura) abaixo dos títulos das seções.
    - `::selection`: muda a cor do texto selecionado pelo usuário para fundo vinho e letras brancas.

Transições (`transition`):
    - Links do menu: a cor de fundo, a cor do texto e o movimento mudam suavemente em 0,5 segundo.
    - Imagens das seções e cards de vinho: os efeitos de aumentar e subir acontecem de forma suave, em 0,5 a 1 segundo.
    - Botões da página de consultoria: a cor de fundo muda suavemente em 0,3 segundo.

Transformações (`transform`):
    - `translateY()`: os links do menu sobem 3px e os cards de vinho sobem 5px ao passar o mouse.
    - `scale(1.05)`: as imagens das páginas aumentam 5% ao passar o mouse.

Animações (`@keyframes`):
    - `aparecer`: o conteúdo principal de cada página surge suavemente, subindo 20px enquanto ganha opacidade.

---

**Tecnologias utilizadas**
    - HTML
    - CSS (pseudo-classes, pseudo-elementos, transições, transformações e animações com @keyframes)

---

**Integrantes**
    - Amanda Souza de Barros 
    - Mariana do Nascimento 

---

**Link para o site**
https://amandasb2612.github.io/vinheria-agnello/