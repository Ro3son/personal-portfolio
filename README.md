# personal-portfolio-webpage

Este projeto surgiu no FreeCodeCamp nos cursos de [Responsive Web Design](https://www.freecodecamp.org/learn/responsive-web-design/) e [Front End Development Libraries](https://www.freecodecamp.org/learn/front-end-development-libraries/).

O projeto segue a documentação encontrada no [Bootstrap 5](https://getbootstrap.com/docs/5.1/getting-started/introduction.
Na navbar temos um logo que é um ícone com o seletor :hover e propriedade transform. E somente em telas com min-width: 1200px o ícone se move. Temos uma lista com hyperlinks para as seções e um menu toggle responsivo.

Este projeto contém três sections: SOBRE, PROJETOS e CONTATO.
Todas as sections e a navbar contém a classe .container para um melhor design responsivo.

Na section SOBRE há uma série de ícones com o seletor :hover e propriedade transform com as stacks conhecidas.
Na section PROJETOS temos uma classe .row com quatro flex items.
Na seção de CONTATO temos alguns ícones e um mapbox.

Por fim, no elemento footer temos um botão para retornar ao topo da página.

Verificou-se em um dispositivo móvel um "problema" com a altura na seção projetos. A solução estava
na diferença entre as unidades % e vh.

Bootstrap 5 suporta os mais recentes navegadores.
Este projeto foi "testado" no Mozilla Firefox, Brave, Chrome e Edge.
