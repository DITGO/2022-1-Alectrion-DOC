---
layout: default
title: Plano de Custos
parent: Documentos
nav_order: 5
---

# Plano de Custo

## Introdução
Este documento visa apresentar a estimativa de custos, orçamentos e controle, para que o projeto possa ser realizado dentro do orçamento planejado.

## Unidade de medida
Nesta seção são apresentadas as unidades de medidas utilizadas.

- h = Horas
- S = Semana
- A = Ano
- M = Mês
- W = Watt
- KW = Kilowatts

## Nível de exatidão

A faixa de ±10% será utilizada para estimar a variação dos valores.

## Recursos humanos

Para a estimativa utilizamos o custo anual por aluno de instituto federal, de acordo com [vivendobauru](https://www.vivendobauru.com.br/quanto-custa-um-aluno-para-a-unb/) este aluno custa cerca de R$ 27.850/A (dado 2020).

A equipe é formada por 13 alunos, cursando as disciplinas de EPS e MDS.

Para o calculo utilizaremos o custo semanal do aluno e o número de semanas previstos para a realização das atividades especificadas no [cronograma EPS](https://github.com/fga-eps-mds/A-Disciplina-MDS-EPS/blob/master/PlanosDeEnsino/EPS-cronograma-hrn.md).


### Valores utilizados:
- Custo/A aluno = R$ 27.850
- Semana/A = 56 
- Custo do aluno/semana = Custo/A aluno ÷ semanas/A 
- Semanas/projeto = 16
- N° alunos equipe = 13


### Custo total
- Custo/A = N° alunos equipe x Custo do aluno/S 
- Custo projeto =  Semanas/projeto x  Custo/A 


## Equipamentos

O custo com equipamentos será considerado como R$ 0 pois todos os membros da equipe possuem computadores onde podem realizar as atividades.

## Ferramentas

Neste projeto serão utilizadas ferramentas Open Sources  e plataformas gratuitas. Portanto o custo, será considerado como R$ 0.

## Capacitação

A capacitação será realizada por meio de treinamentos dados pelos membros de EPS e cursos.

### Curso(s):
- Plataforma Udemy, curso "[Projeto Completo NodeJS, React, React Native, TypeScript](https://www.udemy.com/courses/search/?src=ukw&q=Projeto+Completo+NodeJS%2C+React%2C+React+Native%2C+TypeScript)" custo R$ 27,90. 



## Infraestrutura
O custo de infraestrutura incluirá custo com energia elétrica e internet. 

### Internet
 Para calculo do custo de internet utilizaremos o preço médio de planos de 200mb/M, que de acordo com [melhorescolha](https://melhorescolha.com/internet-banda-larga/brasilia-df/) é cerca de R$ 99,99.

#### **Valores utilizados**
- Custo/S internet = 99,99 ÷ 4
- Semanas/projeto = 16
- N° Alunos equipe = 13

#### **Custo total**

- Custo/S = Custo/S internet * N° Alunos equipe 
- Custo projeto = Custo/S * Semanas/projeto

### Energia
De acordo com [neoenergiabrasilia](https://www.neoenergiabrasilia.com.br/residencial-e-rural/Documents/2022-04-tarifas-abril/Grupo-B.pdf) o custo do KW/h residencial, consumo ativo, de brasília é cerca de R$ 0.57(dado 2022). Segundo [cultura](https://cultura.uol.com.br/noticias/26097_6-maneiras-de-economizar-na-conta-de-luz-do-home-office.html), um notebook consome em média cerca de 65W/h(dado 2021). Estes valores serão usados como base do calculo para o custo da eletricidade, levando em consideração o tempo que cada membro irá trabalhar de sua residencia(4 horas por semana).

#### **Valores utilizados**
- Consumo notebook em KW/h = Potencia * horas ÷ 1000 => 65 * 1 ÷ 1000 = 0.065
- Horas/S = 4
- Tarifa por KW/h = R$ 0.57
- Semanas/projeto = 16
- N° Alunos equipe = 13

#### **Custo total**
- Custo/S = N° Alunos equipe * Horas/S * consumo notebook em KW/h * tarifa => 13 * 4 * 0.065 * 0.57 ≈ R$ 1,95
- Custo projeto = Semanas/Projeto * Custo/S por aluno  => 16 * 1,95  =  R$ 31,2

### Total infraestrutura

- Custo/S = Custo internet/S + Custo energia/S => 325 + 1,95 ≈ R$ 327
- Custo projeto = Custo internet projeto * Custo energia projeto => 5.200 +  31,2 = R$ 5.231,2


## Custo total Projeto
O custo total do projeto, levando em consideração os pontos descritos a cima, apresentado abaixo com margem de 10% e estimado em R$ 108.635,2(± 10.863,52), os cálculos podem ser vistos na planilha:

[Plano de Custos](https://docs.google.com/spreadsheets/d/1GpBh9sL4wy0KlOb_R2ydSjVwxI1n9eXRnERpj0aF1nw/edit?usp=sharing)

<iframe width="1200" height="600" style="-webkit-transform:scale(0.8);-moz-transform-scale(0.8);" frameborder="0" scrolling="yes" src="https://docs.google.com/spreadsheets/d/1GpBh9sL4wy0KlOb_R2ydSjVwxI1n9eXRnERpj0aF1nw/edit?usp=sharing"></iframe>

## Referências

> GUIA PMBOK®. Disponível em: https://brasil.pmi.org/brazil/PMBOKGuideAndStandards.aspx

> Projeto Completo NodeJS, React, React Native, TypeScript. Udemy. Disponível em: https://www.udemy.com/courses/search/?src=ukw&q=Projeto+Completo+NodeJS%2C+React%2C+React+Native%2C+TypeScript

> TABELA DE TARIFAS DE ENERGIA ELÉTRICA. NEOENERGIA. Disponível em: https://www.neoenergiabrasilia.com.br/residencial-e-rural/Documents/2022-04-tarifas-abril/Grupo-B.pdf

> Compare plane em Brasília/DF. Melhor escolha. Disponível em: https://melhorescolha.com/internet-banda-larga/brasilia-df/

> Quanto custa um aluno para a UnB?. Vivendo bauru. Disponível em: https://www.vivendobauru.com.br/quanto-custa-um-aluno-para-a-unb/

## Histórico da revisão

|**Data**|**Descrição**|**Autor(es)**|
|--------|-------------|-------------|
|13/07/2022|Criação do documento| João Pedro Soares, Lucas Alexandre e Moacir |
|15/07/2022|Custos gerais| Moacir |
|17/07/2022|Adiciona tabela e referência| Moacir |
|11/08/2022|Adicionado/criada Planilha e iframe | Guilherme Leal|