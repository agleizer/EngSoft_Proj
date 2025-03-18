# 1. Introdução
## 1.1 Propósito do documento de requisitos
&nbsp; Este documento tem como objetivo definir os requisitos funcionais e não-funcionais do aplicativo
web <b>ObraDireta</b>, que conecta diretamente clientes a profissionais da construção civil,
eliminando intermediários e otimizando a execução dos serviços.

&nbsp; Este documento procura determinar os requisitos de alto nível necessários para desenvolver o projeto.
Com os requisitos, será possível definir quais tecnologias, metodologias, processos e atividades serão necessários
para desenvolver o sistema.

## 1.2 Escopo do produto
&nbsp;O sistema permitirá que clientes busquem e contratem diretamente profissionais específicos para serviços
de construção e reforma, garantindo a sequência ideal de execução dos serviços através de uma análise automatizada
de dependências e laudos técnicos.

&nbsp; O sistema terá uma lista de projetos de construção variados propostos por usuários diferentes, aos quais, diferentes
profissionais podem se propor a participar ou os próprios donos dos projetos podem ir a busca desses profissionais.

&nbsp; Esse sistema contará com um algoritmo de busca próprio que vai determinar quais profissionais se encaixam melhor
no projeto de acordo com suas caracteristicas, como sua natureza, fase, local e quais profissionais faltam. Além da
busca automática, os donos dos projetos podem buscar manualmente por profissionais caso queiram alguem mais específico.

&nbsp; O sistema envolverá o uso de tecnologias e técnicas variadas como **algoritmos de recomendação**, de
**geolocalização** e de **Orçamento unificado**.

## 1.3 Definições, acrônimos e abreviaturas

### Definições

**Cliente**: Pessoa que busca contratar serviços de construção.

**Dono do projeto**: pessoa que propoe o projeto e busca por profissionais no aplicativo.

**Projeto**: Planejamento de uma obra ou reforma, incluindo as etapas necessárias e os profissionais envolvidos.

**Profissional**: Especialista em uma área da construção civil (ex.: encanador, eletricista, gesseiro).

**Laudo técnico**: Documento emitido por um profissional que detalha o serviço a ser realizado e suas dependências.

**Orçamento unificado**: Calculo de todos os custos acumulados do projeto.

**Algoritmo de recomendação**: algoritmos usados para determinar conteúdo personalizado ao cliente.

**Geolocalização**: Tecnologia utilizada para identificar a localização geográfica de clientes e profissionais, otimizando a logística e o tempo de atendimento.

**Dependência**: Relação entre serviços da construção civil em que um trabalho precisa ser concluído antes do início de outro (ex.: caça vazamentos antes de um conserto de encanamento).

### Acrônimos e abreviaturas

**API** – (<i>Application Programming Interface</i>) – Interface de Programação de Aplicações

**ART** (Anotação de Responsabilidade Técnica)**: Documento que registra a responsabilidade técnica de um profissional sobre um serviço ou obra.
Geolocalização: Tecnologia utilizada para identificar a localização geográfica de usuários e profissionais, otimizando a logística dos serviços.

**B2C (Business to Consumer)** – Modelo de negócios no qual empresas vendem produtos ou serviços diretamente para consumidores finais.

**B2B (Business to Business)** – Modelo de negócios no qual empresas oferecem serviços ou produtos para outras empresas.

**CAU** – (Conselho de Arquitetura e Urbanismo) – Entidade responsável por projetos de arquitetura e urbanismo

**CREA** (Conselho Regional de Engenharia e Agronomia) – Entidade responsável pela regulamentação de engenheiros, arquitetos e técnicos da área.
CAU (Conselho de Arquitetura e Urbanismo) – Órgão regulador das atividades profissionais de arquitetos e urbanistas.

**ERP** (<i>Enterprise Resource Planning</i>) – Sistema de Gestão Empresarial

**GPS** – (<i>Global Positioning System</i>) – Sistema de Posicionamento Global. Usado para geolocalização e geoprocessamento.

**OD** (ObraDireta) – Abreviação do nome deste proejto

**SaaS** – (<i>Software as a Service</i>) – modelo de software baseado em assinatura online

## 1.4 Referências
### Concorrentes relevantes:
GetNinjas: https://www.getninjas.com.br/

99freelancers: https://www.99freelas.com.br/

Freelancer: https://freelancer.com.br/

Upwork: https://www.upwork.com/

Workana: https://www.workana.com/

### Artigos sobre GetNinjas e mercado nacional:
[GetNinjas (NINJ3): modelo de negócio, operação e perspectivas](https://monitormercantil.com.br/getninjas-ninj3-modelo-de-negocio-operacao-e-perspectivas/)

[Startup GetNinjas, análise de modelo de negócio](https://ei20152.wordpress.com/2015/09/16/startup-getninjas-entendendo-o-modelo-de-negocio/)

[Descubra os segredos da GetNinjas](https://www.projetodraft.com/getninjas/)

[GetNinjas anuncia primeiras parceirias](https://valor.globo.com/empresas/noticia/2024/04/12/getninjas-anuncia-primeiras-parcerias-em-novo-modelo-de-negcios-para-ampliar-oferta-de-servios.ghtml)

[GetNinjas firma parcerias](https://startups.com.br/negocios/getninjas-firma-parcerias-para-expandir-servicos-e-voltar-a-crescer/)

[GetNinjas desenvolve projeto para se tornar uma empresa totalmente ESG](https://tiinside.com.br/20/07/2022/getninjas-desenvolve-projeto-para-se-tornar-uma-empresa-totalmente-esg/)

[Getninjas: o perverso leilão digital de trabalho humano](https://outraspalavras.net/tecnologiaemdisputa/getninjas-o-perverso-leilao-digital-de-trabalho-humano/)

### Discussoes e reclamações:
[Reclame Aqui GetNinjas](https://www.reclameaqui.com.br/empresa/getninjas/)
obs: duras criticas ao modelo de negócio no qual prestadores compram "moedas"

[o que acham do GETNINJAS? piorou ai pra voces? ](https://www.reddit.com/r/brasil/comments/16fko4n/o_que_acham_do_getninjas_piorou_ai_pra_voces/)

[GetNinjas - Um relato de decepção ](https://www.reddit.com/r/empreendedorismo/comments/1g31fp7/getninjas_um_relato_de_decep%C3%A7%C3%A3o/)

[App GetNinjas é o puro suco da precarização das relações de tabalho ](https://www.reddit.com/r/antitrampo/comments/14fjjah/app_getninjas_%C3%A9_o_puro_suco_da_precariza%C3%A7%C3%A3o_das/)

[ GetNinjas scam, almost fell for it, anyone else? ](https://www.reddit.com/r/golpes/comments/1iy53xr/golpe_do_getninjas_quase_ca%C3%AD_algu%C3%A9m_mais/?tl=en)

[Me f*di demais no GetNinjas](https://www.reddit.com/r/desabafos/comments/qxla5t/me_fudi_demais_no_getninjas/)

[GetNinjas para profissionais é bom? ](https://www.reddit.com/r/brasil/comments/x3ocg8/getninjas_para_profissionais_%C3%A9_bom/?tl=pt-br)

## 1.5 Visão geral do restante do documento
O documento vai detalhar os aspectos funcionais e não-funcionais do sistema, além de restrições e requisitos específicos para a implementação da solução proposta.

# 2. Descrição Geral
## 1. Perspectiva do produto
O aplicativo visa agilizar e simplificar a contratação de serviços da construção civil, conectando diretamente clientes a profissionais especializados, sem a intermediação de terceiros. Além disso, organiza a execução das etapas do serviço com base em dependências identificadas pelos próprios profissionais após a elaboração de laudos técnicos. O sistema também gera um orçamento unificado considerando todas as etapas necessárias identificadas todo o material que será necessário, e oferece integração com fornecedores desses materiais para compra imediata.

## 2. Funções do produto
Cadastro de clientes e profissionais.

Solicitação de serviços pelo cliente, com descrição detalhada do problema.

Busca por profissionais qualificados com base em avaliações e geolocalização.

Análise de dependências para o serviço a ser executava e sugestão automática de profissionais adicionais para as dependências identificadas.

Emissão de laudos técnicos.

Planejamento integrado de execução e orçamento.

Integração com fornecedores de materiais.


## 3. Características dos usuários
Clientes leigos em construção, que precisam de orientação em relação à natureza e à sequência ideal dos serviços a serem realizados.

Profissionais especializados que desejam receber demandas diretamente pelo app.

Empresas do setor que podem utilizar o sistema para organização de serviços. **(será que está dentro do escopo?)**

Empresas varejistas do setor de construção civíl que podem integrar seu ecommerce ao serviço, para compra imediata do material identificado pelos profissionais para execução de seus serviços.

## 4. Restrições gerais


## 5. Suposições de dependências


# 3. Requisitos específicos (requisitos funcionais e não-funcionais)
# 4. Apêndices
# 5. Índice
