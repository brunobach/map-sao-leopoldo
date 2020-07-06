<h1 align="center">Mapa coroplético São Leopoldo 🗺</h1>
<h4 align="center"> 
	Exemplo de Mapa coroplético Coronavírus São Leopoldo / Rio Grande Do Sul 🗺 !
</h4>
<p align="center">	
	  <img alt="Repository size" src="https://img.shields.io/github/repo-size/brunobach/map-sao-leopoldo">
	  <a href="https://linkedin.com/in/bruno-bach">
    <img alt="Made by BrunoBach" src="https://img.shields.io/badge/made%20by-bruno-bach">
  </a>
  
  <a href="https://github.com/brunobach/map-sao-leopoldo/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/brunobach/map-sao-leopoldo">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
   <a href="https://github.com/brunobach/map-sao-leopoldo/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/brunobach/map-sao-leopoldo?style=social">
  </a>
</p>
<p align="center">

<p align="center">
  <a href="#-Descrição">Descrição</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-Projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-Tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-usar">Como Usar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-how-to-contribute">Como contribuir</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

## ✍ Descrição: Como funciona o projeto??

> Criação de um mapa coroplético para o município de São Leopoldo/RS com o intuito de adicionar interatividade aos usuários do Painel "Coronavírus" da  [Prefeitura de São Leopoldo: CoronaVirus](https://www.saoleopoldo.rs.gov.br/coronavirus/).
<p align="center">
    <img alt="Exemplo do mapa leaflet" src="https://raw.githubusercontent.com/brunobach/map-sao-leopoldo/master/src/public/assets/example.gif">
</p>

# Lista de Bairros São Leopoldo/RS

## Checklist de conclusão de geojson por bairro

| OK | Região  | Nome |  População |
|-------|---------|------|------------|
|<input type="checkbox" checked>| Centro|   Centro	         |   12.929
|<input type="checkbox" checked>| Centro	 |   Cristo Rei	     |   3.796
|<input type="checkbox" checked>| Centro	 |   Fião	           | 1.506
|<input type="checkbox" checked>| Centro	 |   Morro do Espelho|	2.526
|<input type="checkbox" checked>| Centro	 |   Padre Reus	     |   1.687
|<input type="checkbox" checked>| Centro	 |   São José	       | 2.321
|<input type="checkbox" checked>| Leste	  |  Feitoria	        |36.808
|<input type="checkbox" checked>| Nordeste|	Rio dos Sinos	    |4.705
|<input type="checkbox" checked>| Nordeste|	Santos Dumont	    |24.543
|<input type="checkbox" checked>| Norte1  |	Boa Vista	        |2.220
|<input type="checkbox" checked>| Norte1	 |   Scharlau	       | 14.456
|<input type="checkbox" checked>| Norte2  |    Arroio da Manteiga|	21.585
|<input type="checkbox" checked>| Norte2	 |   Campina	        |    13.736
|<input type="checkbox" checked>| Oeste	  |  São João Batista	|2.456
|<input type="checkbox" checked>| Oeste	  |  São Miguel	      |  7.545
|<input type="checkbox" checked>| Oeste	  |  Vicentina	       | 13.140
|<input type="checkbox" checked>| Sudeste	|    Campestre	     |   6.619
|<input type="checkbox" checked>| Sudeste	|    Pinheiro	      |  3.130
|<input type="checkbox" checked>| Sudeste	|    Rio Branco	    |    5.779
|<input type="checkbox" checked>| Sudeste	|    Santo André	   |     5.890
|<input type="checkbox" checked>| Sul	    |    Duque de Caxias|	    9.694
|<input type="checkbox" checked>| Sul	    |    Fazenda São Borja|	2.542
|<input type="checkbox" checked>| Sul	    |    Jardim América	|    5.788
|<input type="checkbox" checked>| Sul	    |    Santa Teresa	  |  8.486


## 💻 Projeto : Estrutura

```bash
📂 -- map-sao-leopoldo
    |-- .gitignore
    |-- LICENSE
    |-- .editorconfig
    ┗-- README.md
    📂 -- src
        |-- 📂 geojson
        |-- 📂 public
        |  |-- 📂 assets
        |  |  |-- brasao.ico
        |  |  ┗-- logo.png
        |  |-- 📂 scripts
        |  |  ┗-- map.js
        |  ┗-- 📂 utils
        |    ┗-- bairros.md
        |
        ┗-- index.html
```

## 🛸 Tecnologias

This project was developed with the following technologies:

- [Javascrit][javascript]
- [leaflet][leaflet]


## 🧰 Como usar

To clone and run this project, you'll need [Git](https://git-scm.com).

From your command line:

### 📥 Como baixar via cmd/terminal 

```bash
# Clone this repository
$ git clone https://github.com/brunobach/map-sao-leopoldo/

# Go into the repository
$ cd map-sao-leopoldo/src/public/

# Install dependencies
$ open index.html

```

### 📲 Ou escaneie o codigo no seu dispositivo
<h1 align="center">
  <img alt="QRcode Git" title="QRcode Git" src="https://chart.googleapis.com/chart?chs=150x150&cht=qr&chl=https://github.com/brunobach/map-sao-leopoldo/" width="150px" />
</h1>


## 🤔 Como contribuir

-  Make a fork;
-  Create a branch with your feature: `git checkout -b my-feature`;
-  Commit changes: `git commit -m 'feat: My new feature'`;
-  Make a push to your branch: `git push origin my-feature`.

_After merging your receipt request to done, you can delete a branch from yours_

## 📝 License

This project is under the MIT license. See the [LICENSE](https://github.com/brunobach/map-sao-leopoldo/blob/master/LICENSE) for details.

Made with by Bruno Bach :wave: [Get in touch!](https://www.linkedin.com/in/bruno-bach/)

[javascript]: https://www.javascript.com/
[leaflet]: https://leafletjs.com/
[yarn]: https://yarnpkg.com/