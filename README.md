<h1 align="center">
  <img alt="Aluracast" src="https://raw.githubusercontent.com/nayarawatanuki/css-grid__aluracast/main/src/assets/img/readme/Aluracast_cover.png#vitrinedev"/>
</h1>

### Índice

* [:pencil: Descrição do Projeto](#pencil-descrição-do-projeto)
* [:white_circle: Status do Projeto](#white_circle-status-do-projeto)
* [:hammer: Funcionalidades e Demonstração da Aplicação](#hammer-funcionalidades-e-demonstração-da-aplicação)
* [:open_file_folder: Acesso ao Projeto](#open_file_folder-acesso-ao-projeto)
* [:rocket: Abrir e rodar o projeto](#rocket-abrir-e-rodar-o-projeto)
* [:keyboard: Tecnologias utilizadas](#keyboard-tecnologias-utilizadas)
* [:woman_technologist: Desenvolvedor(a) do Projeto](#woman_technologist-desenvolvedora-do-projeto)

</br>

## :pencil: Descrição do Projeto
O projeto **[AluraCast](https://nayarawatanuki.github.io/css-grid__aluracast/)**, é uma proposta de página web para podcasts. 
Esse projeto contém o objetivo de aprender a fazer uma página totalmente responsiva, suportando todas as resoluções e dispositivos.

</br>Desenvolvido para o curso de **CSS: CONSTRUINDO LAYOUTS COM GRID** da plataforma [Alura](https://www.alura.com.br/).

</br>

## :white_circle: Status do Projeto
> Projeto concluído :white_check_mark:

</br>

## :hammer: Funcionalidades e Demonstração da Aplicação
A construção/estrutura da página foi pensada e focada mais na parte de `styles` (`CSS`), logo o projeto já foi iniciado com o (`HTML`) pronto. 
Com decorrer do projeto, foi adaptado para telas maiores. Pois o objetivo é conseguir visualizar e utilizar a página em qualquer resolução ou dispositivo.
</br>
</br>
**Estilização CSS:**</br>
Foi aprendido e utilizado: 
- Diversos usos da configuração grid `display: grid`;

- Sobre Grid Container vs Grid Item
  - As principais diferenças e características dessas duas categorias de elementos.

  - Grid Container
    - Como o próprio nome indica, é um container que aloca todos os itens do Grid, atua como elemento pai e é nele que o display: grid deve ser aplicado.
  - Grid Item
    - Esses elementos são os filhos diretos do Grid Container. No exemplo abaixo há um Grid Container com três Grid Items.

- Como aplicar as propriedades:
  - `display: grid`
  - `grid-area`
  - `grid-template-areas`
  - `grid-template-columns`

- Grid Line
  - São linhas ou traços que atuam como uma divisória entre as linhas e colunas. Existem as Grid Lines horizontais (linhas) e as verticais (colunas). Por meio delas realiza-se uma contagem, no exemplo abaixo está destacado a linha/traço 4 vertical.

- Grid Cell
  - A célula é um espaço entre 4 grid lines que se cruzam. É a menor unidade no Grid, muito parecido com uma célula de tabela. 

- Grid Area
  - É um conjunto de uma ou mais grid cells que formam uma área que pode ser nomeada. 

- Grid Track
  - Uma trilha de grade é o espaço entre duas grid lines adjacentes. Essa trilha pode ser uma linha completa ou uma coluna completa.

- Unidade de CSS fr
  - Como utilizar dimensões flexíveis por meio da fração.

- Como aplicar as propriedades:
  - `grid-column`
  - `grid-column-start`
  - `grid-column-end`
  - `grid-row`
  - `grid-row-start`
  - `grid-row-end`
  - `grid-template-rows`

- Como trabalhar simultaneamente com as linhas e colunas.

- Gap
  - Como aplicar espaçamentos entre linhas e colunas.

- Alinhamento
  - Como alinhar um ou mais grid items vertical e horizontalmente.

- Como aplicar as propriedades:
  - `column-gap`
  - `row-gap`
  - `justify-self`
  - `align-self`
  - `align-items`
  - Função `repeat()`

- `auto-fill`
  - Preenche a linha do Grid Container com novas colunas sempre que há espaço para caber mais uma, o objetivo é preencher a linha com o máximo de colunas possível. 
  Caso o viewport seja maior do que a largura do Grid container e número de colunas existentes, haverá um espaço sobrando do lado direito, as colunas não expandirão o tamanho para preencher esse vazio.

- `auto-fit`
  - Ajusta o tamanho das colunas para ocupar o tamanho total do espaço disponível do container, expandindo-as para que não fique nenhum espaço sobrando.

- Sobre responsividade:
  - Adaptação de propriedades do CSS para telas de 360px e 1024px;
  - Uso da função minmax();
  - Uso do repeat count: auto-fit.

- Como otimizar um projeto com o uso das variáveis de CSS;
- Uso avançado da função minmax;
- Como incluir o gap na largura das colunas.

- Essencial o uso do `@media screen and (max-width: XXXpx)`, utilizamos para resoluções de 1024px (iPad) e 1400px (desktop). 
Esse rescurso possibilitou adequar cada um dos elementos da página para as devidas resoluções. Com isso foi muito utilizado a configuração de `display: none` e `display: block`.
E com a repetição do recurso em muitos momentos, foi aprendido a atribuir a configuração apenas 1x para todas as classes necessárias de cada resolução.

</br>

**Isso tudo foi realizado com as seguintes aulas:** 
- Sobre Grid Container vs Grid Item
  - As principais diferenças e características dessas duas categorias de elementos.
- Como aplicar as propriedades `display: grid`;
- Unidade de CSS fr;
- Grid Lines
  - A realizar a contagem por meio dos traços horizontais e verticais.
- Como trabalhar simultaneamente com as linhas e colunas;
- Gap;
- Alinhamento;
- Função `repeat()`;
- Como escrever de forma mais compacta padrões que se repetem;
- Sobre responsividade;
- Como otimizar um projeto com o uso das variáveis de CSS;
- Uso avançado da função minmax;
- Como incluir o gap na largura das colunas.

</br>

## :open_file_folder: Acesso ao projeto
Você pode acessar o [código fonte do projeto](https://github.com/nayarawatanuki/css-grid__aluracast) ou 
[baixá-lo](https://github.com/nayarawatanuki/css-grid__aluracast/archive/refs/heads/main.zip).

Caso obte por baixá-lo: 
Após baixar o projeto, você pode abrir com o VS Code. Para isso, abra o explorer (primeiro icone no menu) clique em:
- Abir pasta ou Open folder
- Procure o local onde o projeto está localizado e o selecione (Caso o projeto seja baixado em zip, é necessário extraí-lo antes de procurá-lo)
- Por fim, clique em Selecionar pasta ou Select Folder

</br>

## :rocket: Abrir e rodar o projeto
Caso tenha interesse em visualizar o que foi realizado: [AluraCast](https://nayarawatanuki.github.io/css-grid__aluracast/) 

Ou, caso prefira baixá-lo clicando [aqui](https://github.com/nayarawatanuki/css-grid__aluracast/archive/refs/heads/main.zip).

> Após baixar o projeto, abra a pasta do projeto (Caso o projeto seja baixado em zip, é necessário extraí-lo antes de abrir), então clique no:
> - Aqruivo **``index.html``**
> - O projeto abrirá em seu navegador padrão (aconselho configurar para o Chrome, se possível)

</br>

## :keyboard: Tecnologias utilizadas
![HTML + CSS](https://raw.githubusercontent.com/nayarawatanuki/css-grid__aluracast/main/src/assets/img/readme/html-css.PNG)</br>

</br>

## :woman_technologist: Desenvolvedor(a) do Projeto
:star: [Nayara Watanuki](https://github.com/nayarawatanuki)
