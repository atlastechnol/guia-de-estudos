# Guia de estudos Front-End Enginner

## O que será abordado neste guia:
Estudos de Tecnologias
Padrões de estrutura e código
Testes e performance
Comunicação
Ferramentas

## Estudos de Tecnologias:
Durante o período de avaliação são solicitados conhecimentos em algumas linguagens, frameworks, bibliotecas ou bundler.

### Sendo eles:
Vue
Vuex
PHP
Laravel (Blade, Routes, Templates)
Axios
Webpack
SSR ou SSG
CSS / SASS / SCSS

## Padrões de estrutura e código:
A Atlas a fim de facilitar o desenvolvimento coletivo da aplicação escolheu alguns padrões para serem seguidos na criação de códigos e estrutura de pastas. Assim facilitando que qualquer desenvolvedor que for fazer manutenção em um código já existente consiga de forma ágil entender aquele código e sua estrutura e realizar a correção ou implementação de novos recursos.

### Para isso usamos:
Nomenclatura BEM, ou BEM CSS;
Ícones dentro de arquivos blade;
Ícones dentro de componentes Vuejs;
Nested Selector;
Nomenclatura camelCase;
Utilizar early return;
Vue: Bind de Classes CSS;
Nomenclatura dos componentes Vue deve ser no padrão kebab-case;
Nomenclatura dos arquivos .vue deve ser no formato Pascal Case;
Nomenclatura dos Slots devem ser no padrão kebab-case;
Ordem das Options do componente Vue Deve ser do VueJS;
Template Engine Blade Laravel;


## Testes e performance:
Um programador sempre terá que ser tudo dentro de uma empresa, o designer, o QA (Quality Assurance), o PM (Product Manager) ou PO (Product Owner). Porque é dever do programador verificar se o design entregue a ele é um design que é possível ser aplicado na programação e se não vai quebrar-lo em demais dispositivos. Precisa também agir como um QA, analisando seu código, vendo se o mesmo funciona antes de finalizar, afinal de contas é um entregável seu. E por algumas vezes podemos pegar algumas regras de negócio que poderiam ser melhor, ou estão diferentes das tarefas anteriores, e cabe aos programadores avisar que encontrou esses problemas.

Sendo assim é esperado que sejam realizados os seguintes testes na plataforma:

## Pixel Perfect:
Trazer para a interface visual, utilizando programação, exatamente como está na plataforma de prototipação de Interfaces. Aqui na Atlas, utilizamos o figma. 
Por exemplo: Se na plataforma está 20px para a margem esquerda do botão, na sua programação deve estar 20px, de acordo com a plataforma de Prototipação;
Obs: Para que esse processo seja o mais fidedigno possível, não é recomendado utilização de medidas variáveis;

## Mobile First:
O desenvolvimento esperado na Atlas sempre será a partir da menor tela para a maior, ou, do Mobile para o Desktop. Sendo assim todo o desenvolvimento de CSS é realizado a partir de 360px, e então, utilizamos os breakpoints para cada dispositivo.

## Manutenibilidade:
É responsabilidade do desenvolvedor garantir que seu código esteja em perfeitas condições de ser mantido pela equipe de desenvolvimento, isto é, todo seu código tem que ser o mais fácil possível de se entender e tentar minimizar a quantidade de ramificações que seu código pode fazer. Separar-los em componentes pode ajudar o próximo desenvolvedor a entender que tudo referente a aquele bloco do sistema se encontra naqueles arquivos.

## Comunicação:
Aprenda como se expressar bem e ser compreendido. Pratique e escreva MUITO!
Desenvolvedores trabalham demais com comunicação, síncrona e assíncrona, e auxílio.

Faça muito uso de boas práticas de comunicação e da ética no trabalho!
Existem cursos interessantes sobre CNV (Comunicação Não Violenta), que ajudam bastante a compreender sobre comunicação.

Ajudar outro desenvolvedor de forma neutra, sem criticar a pessoa ou seu desenvolvimento, descrevendo com clareza e objetividade como pode melhorar o seu código, com base em documentações de auxílio.

Poderia dizer que a comunicação é grande parte do trabalho, e base de conhecimento para um desenvolvedor. É de extrema importância sabermos nos comunicar, tanto de forma síncrona ou assíncrona!

## Ferramentas:
Durante todo o tempo que estiver executando serviços de desenvolvimento você precisará usar algumas ferramentas no seu dia a dia, seja para melhorar as suas entregas, ou para ajudar a equipe de PMs a entender sobre as tarefas e sobre o seu tempo gasto com as atividades.

### Docker:
Docker é um projeto que torna a criação e gerenciamento de containers Linux muito mais fácil. Ele ajuda administradores a implementar e executar qualquer aplicativo em qualquer infraestrutura de forma rápida e confiável.

Aprenda mais sobre docker e como utilizá-lo.

### Git e Github:
Git e Github: Estratégias de ramificação, Conflitos e Pull Requests
O git tem vários comandos que são utilizados no nosso dia-a-dia, alguns exemplos são:

git fetch
git pull
git commit
git push
git checkout
git reset

Aprenda mais sobre comandos Git, e o uso do Github, que é uma plataforma para controlar e compartilhar o seu código.

### Figma:
Figma é um editor gráfico de vetor e prototipagem de projetos de design baseado principalmente no navegador web, com ferramentas offline adicionais para aplicações desktop.
Nesse editor estarão disponíveis todas as interfaces dos projetos que a Atlas precisará que seja desenvolvido. A partir do figma podemos pegar imagens, folhas de estilos(css) e também cotas de alinhamento dos objetos. Assim garantindo o Pixel Perfect.
Referências e estudos:
Segue alguns links para te ajudar a entender mais sobre tudo que foi falado neste guia.

### BEM CSS: 
[BEM](http://getbem.com/introduction/)
[BEM em 5 minutos](https://medium.com/trainingcenter/bem-em-5min-f5c80fd23439)
[BEM: guia definitivo do padrão CSS mais famoso](https://desenvolvimentoparaweb.com/css/bem/)
[BEM and SASS: A Perfect Match](https://andrew-barnes.medium.com/bem-and-sass-a-perfect-match-5e48d9bc3894)
 
### VUE:
[Escutando Eventos] (https://br.vuejs.org/v2/guide/events.html#Escutando-Eventos)
[Método em Manipuladores](https://br.vuejs.org/v2/guide/events.html#Metodos-em-Manipuladores)
[Chamada Direta de Métodos](https://br.vuejs.org/v2/guide/events.html#Chamada-Direta-de-Metodos)
[Modificadores de Evento](https://br.vuejs.org/v2/guide/events.html#Modificadores-de-Evento)
[Modificadores de Teclado](https://br.vuejs.org/v2/guide/events.html#Modificadores-de-Teclado)
[Teclas Modificadoras de Sistema](https://br.vuejs.org/v2/guide/events.html#Teclas-Modificadoras-de-Sistema)
[Escutando Eventos](https://br.vuejs.org/v2/guide/events.html#Escutando-Eventos)
[Método em Manipuladores](https://br.vuejs.org/v2/guide/events.html#Metodos-em-Manipuladores)
[Chamada Direta de Métodos](https://br.vuejs.org/v2/guide/events.html#Chamada-Direta-de-Metodos)
[Modificadores de Evento](https://br.vuejs.org/v2/guide/events.html#Modificadores-de-Evento)
[Modificadores de Teclado](https://br.vuejs.org/v2/guide/events.html#Modificadores-de-Teclado)
[Teclas Modificadoras de Sistema](https://br.vuejs.org/v2/guide/events.html#Teclas-Modificadoras-de-Sistema)
[Inputs e Data Binding](https://www.youtube.com/watch?v=bdD04cHOKfY)
[Utilizando o Vue CLI](https://www.youtube.com/watch?v=yrxG24n1oXI)
[Criando componentes](https://www.youtube.com/watch?v=ec046jmrgXQ)
[Entendendo os Lifecycle hooks (ciclo de vida)](https://www.youtube.com/watch?v=yzXOZZQPSeM)
[Hierarquia de componentes](https://www.youtube.com/watch?v=H5PopRSJBTY&list=RDCMUCDoFiMhpOnLFq1uG4RL4)
[Métodos](https://www.youtube.com/watch?v=745aPtV_W60&list=RDCMUCDoFiMhpOnLFq1uG4RL4xag)
[Renderização de listas (v-for)](https://www.youtube.com/watch?v=GvGYlBYtlAk&list=RDCMUCDoFiMhpOnLFq1uG4RL4)
[Eventos (@submit e @click)](https://www.youtube.com/watch?v=h8Z-pRhe-dw&list=RDCMUCDoFiMhpOnLFq1uG4RL4)
[Reutilização de componentes](https://www.youtube.com/watch?v=njcYIgHhFMc&list=RDCMUCDoFiMhpOnLFq1uG4RL4)
[Criando formulário de cadastro](https://www.youtube.com/watch?v=mCfqTo9LdL8&list=RDCMUCDoFiMhpOnLFq1uG4RL4)
[Ambientando Vue no Laravel](https://www.youtube.com/watch?v=NtM9B12lARw)
[Vue Guide](https://br.vuejs.org/v2/guide/)
 
### VUEX:
[VueX Guide](https://vuex.vuejs.org/)
[Estado](https://vuex.vuejs.org/ptbr/guide/state.html)
[Getters](https://vuex.vuejs.org/ptbr/guide/getters.html)
[Mutações](https://vuex.vuejs.org/ptbr/guide/mutations.html)
[Ações](https://vuex.vuejs.org/ptbr/guide/actions.html)
[Módulos](https://vuex.vuejs.org/ptbr/guide/modules.html)
[Learn VueX](https://scrimba.com/learn/vuex)
[Gerenciando estado com Vuex](https://www.youtube.com/watch?v=qq8yJmXys6U)
 
### Webpack:
[Entry](https://webpack.js.org/concepts/entry-points/)
[Output](https://webpack.js.org/concepts/output/)
[Loaders](https://webpack.js.org/concepts/loaders/)
[Plugins](https://webpack.js.org/concepts/plugins/)
[Curso Webpack 5 Essencial](https://www.youtube.com/watch?v=bKk_4jtXq0Y)
[Webpack - Curso rápido para iniciantes](https://www.youtube.com/watch?v=sU3W2ZTt-8I)
[Webpack](https://webpack.js.org/)
[Compiling Assets](https://laravel.com/docs/5.7/mix)
 
### Template Engine Blade:
[Blades Laravel](https://laravel.com/docs/8.x/blade)
[Blade engine utilizando templates no laravel](https://www.devmedia.com.br/blade-engine-utilizando-templates-no-laravel/36749)
