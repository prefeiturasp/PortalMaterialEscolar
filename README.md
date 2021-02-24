# Estratégia de Transformação Digital e Governo Aberto na SME

Como um governo pode atuar para garantir o bem comum de todos? Na SME, acreditamos que um dos meios para isso seja garantir transparência e prestação de contas e constante relação entre governo e sociedade para o desenvolvimento e implementação de políticas públicas. 

A Portaria SME nº 8.008, de 12 de novembro de 2018 oficializou a estratégia da Secretaria Municipal de Educação de SP para que nossas ações sejam pautadas nos princípios de Governo Aberto e para usarmos os valores e benefícios do mundo digital para melhorarmos nossos processos e serviços para os cidadãos. Com isso, pretendemos: 

- aumentar os níveis de transparência ativa e de abertura de dados, garantindo a proteção de dados pessoais; 
- instituir metodologias ágeis e colaborativas como parte do processo de desenvolvimento e de evolução de sistemas administrativos e de serviços digitais; 
- fortalecer o controle das políticas educacionais e da aplicação de recursos por parte da gestão e da sociedade; 
- promover espaços e metodologias de colaboração entre governo, academia, sociedade civil e setor privado. 

O [Ateliê do Software](http://forum.govit.prefeitura.sp.gov.br/uploads/default/original/1X/c88a4715eb3f9fc3ceb882c1f6afe9e308805a17.pdf) é uma das ferramentas para operacionalização. Baseado em um modelo de contratação inspirado pelos movimentos ágil e de Software Craftsmanship, trabalhamos com equipes multidisciplinares para o desenvolvimento de produtos que beneficiam toda a comunidade escolar (técnicos da SME e DREs, gestores, professores, alunos e famílias) e concretizam os objetivos da Estratégia de Transformação Digital e Governo Aberto “Pátio Digital”.

**Conteúdo:**
 1. [Sobre o Produto](#Sobre-o-Produto)
 2. [Sobre o Time](#Sobre-o-Time)
 3. [Como surgiu](#Como-surgiu)
 4. [Links Úteis](#Links-Úteis)
 5. [Comunicação](#Comunicação)
 6. [Como contribuir](#como-contribuir)
 7. [Repositórios](#Repositórios)
 8. [Documentações Auxiliares](#Documentações-Auxiliares)
 9. [Instalação e Configuração](#Instalação-e-Configuração)

# Sobre o Produto

## Visão de Futuro

Para **as empresas do ramo de material escolar**

Que **queiram se tornar fornecedores da Secretaria Municipal de Educação de São Paulo (SME)**

O **Portal do Material Escolar**

É **um portal** 

Que **permite seu cadastramento como fornecedor, informando dados cadastrais, upload de documentos obrigatórios, endereço das lojas físicas e valor de venda dos itens que compõem os kits de material escolar de todas as modalidades de ensino.**

## Objetivos de Negócio

Criação de um novo portal para gestão de fornecedores de material escolar para o kit do aluno e para facilitar a busca destes estabelecimentos para os responsáveis. O portal permite o cadastro de fornecedores com ponto físico em São Paulo, podendo este fornecer os produtos que compõem os kits de cada modalidade de ensino. Durante o cadastro, os fornecedores deverão informar dados cadastrais, endereço das lojas, tabela de preço e documentações necessárias. O estudante e as famílias poderão comprar os itens que ele desejar dentro de um valor máximo estipulado para cada modalidade, em múltiplos estabelecimentos. 

**O que é/Faz**
 
- Um portal de informações para estudantes e famílias e fornecedores em relação ao novo modelo descentralizado de compra de material escolar pelos estudantes e famílias da Rede Municipal de Educação de São Paulo
- Uma busca para que os estudantes e famílias localizem os fornecedores credenciados
- Cadastra novos fornecedores interessados em vender o material escolar diretamente aos estudantes e famílias
- Uma área administrativa para SME para acompanhar e apoiar o processo de cadastramento dos fornecedores
 
**O que não é/não faz**
  
- Não é um comércio eletrônico e nem um marketplace de venda de material escolar

## Personas

### Estudantes e famílias

- **Necessidades:** precisam encontrar mais facilmente os estabelecimentos que ofertam a compra dos kits com o cartão oferecido pela Secretaria Municipal de Educação 

### Fornecedores

- **Necessidades:** precisam de um portal que possibilite cadastro facilitado de seus estabelecimentos para oferta dos itens que compõem os kits de material escolar de todas as modalidades de ensino

### Administrador SME

- **Necessidades:** precisam um sistema que permita o gerenciamento simplificado dos fornecedores cadastrados

## Funcionalidades

**Cadastro do Fornecedor**: permite que um fornecedor realize seu cadastro, informando da empresa, lojas físicas, tabela de preço dos materiais fornecidos, upload de documentos exigidos no edital e foto da fachada das lojas

**Busca de Lojas Credenciadas**: permite que estudantes e famílias possam realizar a busca de lojas credenciadas à partir de um endereço ou utilizando demais filtros

**Portal do Administrador**: permite que os administradores do sistema tenham acesso aos dados informados pelos fornecedores que realizaram o cadastro, podendo assim validar documentações e demais dados e caso aprovado, alterar o status do fornecedor para que o mesmo seja considerado como um fornecedor credenciado

## Roadmap

- Desenvolvimento do componente de avaliação de satistação e realização de piloto
- Integração com a API da empresa de pagamento

# Sobre o Time:

<table>
<thead>
<tr>
<th>Papel</th>
<th>Titular</th>
<th>Suplente</th>
</tr>
</thead>
<tbody>
<tr>
<td>Product Owner</td>
<td>@nataliagoes e Renata Garrido</td>
<td>@thaisbrianezi</td>
</tr>
<tr>
<td>Agente de Governança</td>
<td>@fgonsales</td>
<td>Victor Silva</td>
</tr>
<tr>
<td>Gerente de Projeto</td>
<td>Andrea Paiva</td>
<td>-</td>
</tr>
<tr>
<td>Scrum Master</td>
<td>@augustocbrito</td>
<td>-</td>
</tr>
<tr>
<td>Analista UX/UI</td>
<td></td>
<td>-</td>
</tr>
<tr>
<td>Analista Programador</td>
<td></td>
<td>@kelwys</td>
</tr>
</tbody>
</table>

# Como surgiu

## Fase de Descoberta:

Demanda solicitada por NUMEL (Núcleo de Uniforme, Material Escolar e Logística) e priorizada pelo gabinete. O produto foi pautado nas necessidades dos usuários e também nos dois documentos abaixo:

- [EDITAL DE CREDENCIAMENTO SME/COSERV/DIAL – Numel Nº 007/2020]
(https://portalmaterialescolar.sme.prefeitura.sp.gov.br//django_media/EDITAL_18.02.2021.pdf)
- [INSTRUÇÃO NORMATIVA SME Nº 57, DE 14 DE DEZEMBRO DE 2020]
(http://legislacao.prefeitura.sp.gov.br/leis/instrucao-normativa-secretaria-municipal-de-educacao-sme-57-de-14-de-dezembro-de-2020)
- [LEI MUNICIPAL Nº 17.437/2020](http://legislacao.prefeitura.sp.gov.br/leis/lei-17437-de-12-de-agosto-de-2020)

**Oficina:**

Foi realizada oficina com servidores da SME para identificação e debate dos desafios e criação coletiva de soluções, que se tornaram concretas no desenvolvimento do portal.

## Protótipos:

**Protótipos construídos para a Sprint 1:** 
[https://www.figma.com/file/7q2kXI9oAjSpAw9dLopRXa/%5BMATERIAL-ESCOLAR%5D-Portal-do-Material-Escolar_Sprint01-29062020?node-id=10%3A8](https://www.figma.com/file/7q2kXI9oAjSpAw9dLopRXa/%5BMATERIAL-ESCOLAR%5D-Portal-do-Material-Escolar_Sprint01-29062020?node-id=10%3A8)

# Links Úteis:

**Homologação:**
[https://hom-portalmaterialescolar.sme.prefeitura.sp.gov.br/](https://hom-portalmaterialescolar.sme.prefeitura.sp.gov.br/)

**Produção:**
[https://portalmaterialescolar.sme.prefeitura.sp.gov.br/](https://portalmaterialescolar.sme.prefeitura.sp.gov.br/)

# Comunicação:

| Canal de comunicação | Objetivos |
|----------------------|-----------|
| [Issues do Github](https://github.com/prefeiturasp/PortalMaterialEscolar/issues) | - Sugestão de novas funcionalidades<br> - Reportar bugs<br> - Discussões técnicas |

# Como contribuir

Contribuições são **super bem vindas**! Se você tem vontade de construir o Portal do Material Escolar conosco, veja o nosso [guia de contribuição](./CONTRIBUTING.md) onde explicamos detalhadamente como trabalhamos e de que formas você pode nos ajudar a alcançar nossos objetivos. Lembrando que todos devem seguir  nosso [código de conduta](./CODEOFCONDUCT.md).

# Repositórios:

[PortalMaterialEscolar](https://github.com/prefeiturasp/PortalMaterialEscolar)

# Instalação e Configuração:

## Para desenvolver

1.  Clone o repositório.
2.  Crie um Virtualenv com Python 3.6
3.  Ative o Virtualenv.
4.  Instale as dependências.
5.  Configure a instância com o .env
6.  Execute os testes.
7.  Faça um Pull Request com o seu desenvolvimento

```console
git clone https://github.com/prefeiturasp/PortalMaterialEscolar-BackEnd.git back
cd back
python -m venv .venv
source .venv/bin/activate
pip install -r requirements\local.txt
cp env_sample .env
pytest
```

## Tema do Admin
Para instalar o tema do Admin

```console
python manage.py loaddata admin_interface_theme_uswds.json
```

## Filas Celery
**Subir o Celery Worker**
```console
celery  -A config worker --loglevel=info
```

**Subir o Celery Beat**
```console
celery  -A config beat --loglevel=info
```

**Monitorar os processos no celery**
```console
flower -A config --port=5555
```

**Limpar os processos no celery**
```console
celery  -A config purge
```

