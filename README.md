# testeBanco

Um estudo introdutório sobre criação de banco de dados usando Entity Framework e ASP.NET CORE 2.0.

<h4 align="center"> 
  <a href="#sobre-o-projeto">Sobre o projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Pré-requisitos">Pré-requisitos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Tecnologias-e-ferramentas">Tecnologias e ferramentas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp; 
  </br>
  <a href="#Demonstração">Demonstração</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Como-usar">Como usar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Licença">Licença</a>
</h4>

<br/>

<p align="center">
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License MIT">
  </a>
</p>


# Sobre o projeto

Este é um projeto básico de uma aplicação utilizando o padrão *`MVC`*, criando uma WebAPI, usando o [asp.net core 3.1](https://dotnet.microsoft.com/download/dotnet-core/3.1).
É utilizado um padrão que define um conjunto de práticas para criar e consumir a Web APIs, conhecido como [OData](https://docs.microsoft.com/en-us/odata/) (Open Data Protocol). Por meio das conveções da URL do OData, pode-se expor uma API, tornando-a mais flexível e fácil para consultas específicas, requisitadas pelo cliente da API.                                              
A API fará conexão com um banco de dados, o [SQL Server](https://www.microsoft.com/pt-br/sql-server/), com sua estrutura criada e populada previamente.

# Pré-requisitos

- [Visual Studio 2019](https://dotnet.microsoft.com/download/dotnet-core/3.1)
- [SQL Server Management Studio (SSMS)](https://docs.microsoft.com/pt-br/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver15) 
- [Windows](https://docs.microsoft.com/pt-br/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver15) 

# Tecnologias e ferramentas

O projeto foi desenvolvido com as seguintes tecnologias:

- [Visual Studio 2019](#Pré-requisitos)
- [Asp.NET Core 3.1](#Pré-requisitos)
- [SQL Server Management Studio (SSMS)](#Pré-requisitos)
- [SQL Server](#Pré-requisitos)
- [HTML5](#Pré-requisitos)
- [CSS3](#Pré-requisitos)
- [Javascript](#Pré-requisitos)
- [C#](#Pré-requisitos)
- [OData](#Pré-requisitos)

# Demonstração

![ScreenshotBD](https://github.com/renanegobbi/App/blob/master/github/BD.png)

![TelaApp](https://github.com/renanegobbi/App/blob/master/github/screenshot1.png)


# Criando o Projeto ASP.NET Core MVC

O .NET Core é um framework livre e de código aberto para os sistemas operacionais Windows, Linux e macOS. É um sucessor de código aberto do .NET Framework. O projeto é desenvolvido principalmente pela Microsoft e lançado com a Licença MIT.

A seguir, estão as versões do framework .NET Core com suas respectivas versões de suportade pelo Visual Studio:

<table class="wikitable">
<tbody><tr>
<th>Versão
</th>
<th>Data de lançamento
</th>
<th>Lançado com
</th>
<th>Última atualização
</th>
<th>Data última atualização
</th>
<th>Suporte termina<sup id="cite_ref-16" class="reference"><a href="#cite_note-16"><span>[</span>16<span>]</span></a></sup>
</th></tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.NET Core 1.0 </font></font><sup id="cite_ref-17" class="reference"><a href="#cite_note-17"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> 17 </font></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">]</font></font></span></a></sup></td>
<td>2016-06-27</td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Atualização 3 do Visual Studio 2015</font></font></td>
<td>1.0.16</td>
<td>2019-05-14</td>
<td style="background-color: #FDB3AB;" title="Versão antiga, já não mantida" data-sort-value="27 junho 2019"><span style="display: none;">Versão antiga, já não mantida:</span> 27 junho 2019
</td></tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.NET Core 1.1 </font></font><sup id="cite_ref-18" class="reference"><a href="#cite_note-18"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> 18 </font></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">]</font></font></span></a></sup></td>
<td>2016-11-16</td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Visual Studio 2017 versão 15.0</font></font></td>
<td>1.1.13</td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2019-05-14</font></font></td>
<td style="background-color: #FDB3AB;" title="Versão antiga, já não mantida" data-sort-value="27 junho 2019"><span style="display: none;">Versão antiga, já não mantida:</span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> 27 junho 2019
</font></font></td></tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.NET Core 2.0 </font></font><sup id="cite_ref-19" class="reference"><a href="#cite_note-19"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> 19 </font></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">]</font></font></span></a></sup></td>
<td>2017-08-14</td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Visual Studio 2017 Versão 15.3</font></font></td>
<td>2.0.9</td>
<td>2018-07-10</td>
<td style="background-color: #FDB3AB;" title="Versão antiga, já não mantida" data-sort-value="1 outubro 2018"><span style="display: none;">Versão antiga, já não mantida:</span> 1 outubro 2018
</td></tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.NET Core 2.1 </font></font><sup id="cite_ref-20" class="reference"><a href="#cite_note-20"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> 20 </font></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">]</font></font></span></a></sup></td>
<td>2018-05-30</td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Visual Studio 2017 Versão 15.7</font></font></td>
<td>2.1.16 (<a href="/wiki/Suporte_de_longo_prazo" title="Suporte de longo prazo">LTS</a>)</td>
<td>2020-01-14</td>
<td class="templateVersion co" style="background-color: #FEF8C6;" title="Versão mais antiga, ainda mantida" data-sort-value="21 agosto 2021"><span style="display: none;">Versão mais antiga, ainda mantida:</span> 21 agosto 2021
</td></tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.NET Core 2.2 </font></font><sup id="cite_ref-21" class="reference"><a href="#cite_note-21"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> 21 </font></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">]</font></font></span></a></sup></td>
<td>2018-12-04</td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Visual Studio 2017 Versão 15.9</font></font></td>
<td>2.2.8<sup id="cite_ref-Nov2019Update_22-0" class="reference"><a href="#cite_note-Nov2019Update-22"><span>[</span>22<span>]</span></a></sup></td>
<td>2019-11-19</td>
<td style="background-color: #FDB3AB;" title="Versão antiga, já não mantida" data-sort-value="23 dezembro 2019"><span style="display: none;">Versão antiga, já não mantida:</span> 23 dezembro 2019
</td></tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.NET Core 3.0 </font></font><sup id="cite_ref-23" class="reference"><a href="#cite_note-23"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> 23 </font></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">]</font></font></span></a></sup></td>
<td>2019-09-23<sup id="cite_ref-:0_12-1" class="reference"><a href="#cite_note-:0-12"><span>[</span>12<span>]</span></a></sup></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Visual Studio 2019 versão 16.3</font></font></td>
<td>3.0.3</td>
<td>2020-02-18</td>
<td style="background-color: #FDB3AB;" title="Versão antiga, já não mantida" data-sort-value="3 março 2020"><span style="display: none;">Versão antiga, já não mantida:</span> 3 março 2020
</td></tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.NET Core 3.1</font></font></td>
<td>2020-01-15</td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Visual Studio 2019 versão 16.4</font></font></td>
<td>3.1.2<sup id="cite_ref-27" class="reference"><a href="#cite_note-27"><span>[</span>27<span>]</span></a></sup> (LTS)</td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2020-02-18</font></font></td>
<td class="templateVersion c" style="background-color: #D4F4B4;" title="Versão estável atual" data-sort-value="3 dezembro 2022"><span style="display: none;">Versão estável atual:</span> <b>3 dezembro 2022</b>
</td></tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.NET 5 </font></font><sup id="cite_ref-28" class="reference"><a href="#cite_note-28"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> 28 </font></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">]</font></font></span></a></sup></td>
<td>2020-11 (projeção)</td>
<td></td>
<td></td>
<td></td>
<td>
</td></tr></tbody></table>


# Como usar

[Em breve...]

# Referências

[https://pt.wikipedia.org/wiki/.NET_Core](https://pt.wikipedia.org/wiki/.NET_Core)

# Licença
Este projeto está sob a licença do MIT. Consulte a [LICENÇA](https://github.com/TesteReteste/lim/blob/master/LICENSE) para obter mais informações.
