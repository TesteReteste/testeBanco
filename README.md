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

- [Visual Studio 2019](https://visualstudio.microsoft.com/pt-br/downloads/)
- [ASP.NET Core 3.1](https://dotnet.microsoft.com/download/dotnet-core/3.1)
- [SQL Server Management Studio (SSMS)](https://docs.microsoft.com/pt-br/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver15) 
- [Windows](https://docs.microsoft.com/pt-br/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver15) 

# Tecnologias e ferramentas

O projeto foi desenvolvido com as seguintes tecnologias:

- [Visual Studio 2019](#vs2019)
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

O .NET Core é um framework livre e de código aberto para os sistemas operacionais Windows, Linux e macOS, ou seja, multiplataforma. É um sucessor de código aberto do .NET Framework. O projeto é desenvolvido principalmente pela Microsoft e lançado com a Licença MIT.

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


## Criando o modelo

Normalmente, acessamos os dados de um banco de dados pré-existente. Contudo, será feito uma abordagem diferente, criando primeiro o código, conhecido como code first, e em seguida será criado o banco de dados com base nas classes criadas, conhecidas como entidades:

## Conectando o Entity Framework ao Banco de Dados

Agora, será a parte do framework, o Entity Framework Core, criar o banco de dados e gerar tabelas a partir do código criado no passo anterior, além de gerenciar a troca de informação do banco de dados com o sistema.


<span data-ttu-id="6437f-104" class="__web-inspector-hide-shortcut__">Versões estáveis</span>

<table class="table"><caption class="visually-hidden">Versões estáveis</caption>
<thead>
<tr>
<th style="text-align: left;"><span data-ttu-id="6437f-105">Versão</span><span class="sxs-lookup"><span data-stu-id="6437f-105">Release</span></span></th>
<th><span data-ttu-id="6437f-106">Estrutura de destino</span><span class="sxs-lookup"><span data-stu-id="6437f-106">Target framework</span></span></th>
<th><span data-ttu-id="6437f-107">Com suporte até</span><span class="sxs-lookup"><span data-stu-id="6437f-107">Supported until</span></span></th>
<th><span data-ttu-id="6437f-108">Links</span><span class="sxs-lookup"><span data-stu-id="6437f-108">Links</span></span></th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: left;"><a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore" data-linktype="external"><span data-ttu-id="6437f-109">EF Core 3.1</span><span class="sxs-lookup"><span data-stu-id="6437f-109">EF Core 3.1</span></span></a></td>
<td><span data-ttu-id="6437f-110">.NET Standard 2.0</span><span class="sxs-lookup"><span data-stu-id="6437f-110">.NET Standard 2.0</span></span></td>
<td><span data-ttu-id="6437f-111">3 de dezembro de 2022 (LTS)</span><span class="sxs-lookup"><span data-stu-id="6437f-111">December 3, 2022 (LTS)</span></span></td>
<td><a href="https://devblogs.microsoft.com/dotnet/announcing-entity-framework-core-3-1-and-entity-framework-6-4/" data-linktype="external"><span data-ttu-id="6437f-112">Comunicado</span><span class="sxs-lookup"><span data-stu-id="6437f-112">Announcement</span></span></a></td>
</tr>
<tr>
<td style="text-align: left;"><span data-ttu-id="6437f-113"><del><a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/3.0.3" data-linktype="external">EF Core 3.0</a></del></span><span class="sxs-lookup"><span data-stu-id="6437f-113"><del><a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/3.0.3" data-linktype="external">EF Core 3.0</a></del></span></span></td>
<td><span data-ttu-id="6437f-114">.NET Standard 2.1</span><span class="sxs-lookup"><span data-stu-id="6437f-114">.NET Standard 2.1</span></span></td>
<td><span data-ttu-id="6437f-115">Expirou em 3 de março de 2020</span><span class="sxs-lookup"><span data-stu-id="6437f-115">Expired March 3, 2020</span></span></td>
<td><span data-ttu-id="6437f-116"><a href="https://devblogs.microsoft.com/dotnet/announcing-ef-core-3-0-and-ef-6-3-general-availability/" data-linktype="external">Comunicado</a> / <a href="ef-core-3.x/breaking-changes" data-linktype="relative-path">Alterações de falha</a></span><span class="sxs-lookup"><span data-stu-id="6437f-116"><a href="https://devblogs.microsoft.com/dotnet/announcing-ef-core-3-0-and-ef-6-3-general-availability/" data-linktype="external">Announcement</a> / <a href="ef-core-3.x/breaking-changes" data-linktype="relative-path">Breaking changes</a></span></span></td>
</tr>
<tr>
<td style="text-align: left;"><span data-ttu-id="6437f-117"><del><a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/2.2.6" data-linktype="external">EF Core 2.2</a></del></span><span class="sxs-lookup"><span data-stu-id="6437f-117"><del><a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/2.2.6" data-linktype="external">EF Core 2.2</a></del></span></span></td>
<td><span data-ttu-id="6437f-118">.NET Standard 2.0</span><span class="sxs-lookup"><span data-stu-id="6437f-118">.NET Standard 2.0</span></span></td>
<td><span data-ttu-id="6437f-119">Expirado em 23 de dezembro de 2019</span><span class="sxs-lookup"><span data-stu-id="6437f-119">Expired December 23, 2019</span></span></td>
<td><a href="https://devblogs.microsoft.com/dotnet/announcing-entity-framework-core-2-2/" data-linktype="external"><span data-ttu-id="6437f-120">Comunicado</span><span class="sxs-lookup"><span data-stu-id="6437f-120">Announcement</span></span></a></td>
</tr>
<tr>
<td style="text-align: left;"><a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/2.1.14" data-linktype="external"><span data-ttu-id="6437f-121">EF Core 2.1</span><span class="sxs-lookup"><span data-stu-id="6437f-121">EF Core 2.1</span></span></a></td>
<td><span data-ttu-id="6437f-122">.NET Standard 2.0</span><span class="sxs-lookup"><span data-stu-id="6437f-122">.NET Standard 2.0</span></span></td>
<td><span data-ttu-id="6437f-123">21 de agosto de 2021 (LTS)</span><span class="sxs-lookup"><span data-stu-id="6437f-123">August 21, 2021 (LTS)</span></span></td>
<td><a href="https://devblogs.microsoft.com/dotnet/announcing-entity-framework-core-2-1/" data-linktype="external"><span data-ttu-id="6437f-124">Comunicado</span><span class="sxs-lookup"><span data-stu-id="6437f-124">Announcement</span></span></a></td>
</tr>
<tr>
<td style="text-align: left;"><span data-ttu-id="6437f-125"><del><a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/2.0.3" data-linktype="external">EF Core 2.0</a></del></span><span class="sxs-lookup"><span data-stu-id="6437f-125"><del><a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/2.0.3" data-linktype="external">EF Core 2.0</a></del></span></span></td>
<td><span data-ttu-id="6437f-126">.NET Standard 2.0</span><span class="sxs-lookup"><span data-stu-id="6437f-126">.NET Standard 2.0</span></span></td>
<td><span data-ttu-id="6437f-127">Expirado em 1º de outubro de 2018</span><span class="sxs-lookup"><span data-stu-id="6437f-127">Expired October 1, 2018</span></span></td>
<td><a href="https://devblogs.microsoft.com/dotnet/announcing-entity-framework-core-2-0/" data-linktype="external"><span data-ttu-id="6437f-128">Comunicado</span><span class="sxs-lookup"><span data-stu-id="6437f-128">Announcement</span></span></a></td>
</tr>
<tr>
<td style="text-align: left;"><span data-ttu-id="6437f-129"><del><a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/1.1.6" data-linktype="external">EF Core 1.1</a></del></span><span class="sxs-lookup"><span data-stu-id="6437f-129"><del><a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/1.1.6" data-linktype="external">EF Core 1.1</a></del></span></span></td>
<td><span data-ttu-id="6437f-130">.NET Standard 1.3</span><span class="sxs-lookup"><span data-stu-id="6437f-130">.NET Standard 1.3</span></span></td>
<td><span data-ttu-id="6437f-131">Expirado em 27 de junho de 2019</span><span class="sxs-lookup"><span data-stu-id="6437f-131">Expired June 27 2019</span></span></td>
<td><a href="https://devblogs.microsoft.com/dotnet/announcing-entity-framework-core-1-1/" data-linktype="external"><span data-ttu-id="6437f-132">Comunicado</span><span class="sxs-lookup"><span data-stu-id="6437f-132">Announcement</span></span></a></td>
</tr>
<tr>
<td style="text-align: left;"><span data-ttu-id="6437f-133"><del><a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/1.0.6" data-linktype="external">EF Core 1.0</a></del></span><span class="sxs-lookup"><span data-stu-id="6437f-133"><del><a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/1.0.6" data-linktype="external">EF Core 1.0</a></del></span></span></td>
<td><span data-ttu-id="6437f-134">.NET Standard 1.3</span><span class="sxs-lookup"><span data-stu-id="6437f-134">.NET Standard 1.3</span></span></td>
<td><span data-ttu-id="6437f-135">Expirado em 27 de junho de 2019</span><span class="sxs-lookup"><span data-stu-id="6437f-135">Expired June 27 2019</span></span></td>
<td><a href="https://devblogs.microsoft.com/dotnet/entity-framework-core-1-0-0-available/" data-linktype="external"><span data-ttu-id="6437f-136">Comunicado</span><span class="sxs-lookup"><span data-stu-id="6437f-136">Announcement</span></span></a></td>
</tr>
</tbody>
</table>




# Como usar

[Em breve...]

# Referências

[https://pt.wikipedia.org/wiki/.NET_Core](https://pt.wikipedia.org/wiki/.NET_Core)

# Licença
Este projeto está sob a licença do MIT. Consulte a [LICENÇA](https://github.com/TesteReteste/lim/blob/master/LICENSE) para obter mais informações.
