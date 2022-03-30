# intibiome
Projeto avaliativo;

## Tecnologias utilizadas
* SCSS: Pré-processador CSS;
* VueJS: Framework JavaScript;
* VueCLI: Para a construção do projeto;
* Node Package Manager (NPM): Para instalação dos pacotes necessários e para execução do servidor local;

## Estrutura das pastas
1. src: Pasta que contém todos os componentes, imagens e códigos do projeto
2. src/assets: Contém todos os arquivos que serão utilizados pelo projeto como um todo. Nesta pasta existem as pastas de: src/assets/img/ que armazena todas as imagens, e src/assets/layouts/ arquivos de layouts CSS/SCSS de comportamentos (mixins, variáveis e etc.);
3. src/components: Pasta referente aos componentes que compõe a página do projeto. Dentro de alguns componentes existem outras pastas de componentes como src/components/Main/ProductCard que são componentes que possuem uma estrutura reutilizável dentro da própria seção principal da página;
4. src/views: Pasta que conteria todas as páginas do projeto;
5. App.vue: Arquivo que concentra os componentes da página

## Estrutura de arquivos das pastas de componentes
Cada componente foi dividido da seguinte forma:
* NomeComponente.html: em que terá a estrutura html do componente;
* NomeComponente.scss: em que terá o estilo referente ao componente;
* NomeComponente.css: arquivo processado do SCSS;
* NomeComponente.css.map: arquivo de configuração do processamento do SCSS;
* NomeComponente.vue: arquivo Vue que referenciará aos de HTML (template) e CSS (estilo) mantendo apenas as funções, estados, variáveis, propriedades e comportamentos utilizadas por cada um dos componentes;  

## Execução em máquina local
1. Baixar o código do github;
2. Executar o comando "npm --install" em seu terminal para instalar todas as dependências necessárias;
3. Ao fim da instalação, executar o comando "npm run serve" em seu terminal para executar o projeto;
4. Por fim, acessar o link de acesso fornecido no prompt de comando em seu navegador de preferência (Ex.: localhost:8080);
* Obs: É necessário ter o NodeJS instalado na máquina
* Para visualização também pode acessar via: https://ropierre.github.io/intebiome-vue/

