# Selecao-front-2018
Seleção de programador Front-End Junior

Autor: Martin Pfeifer

Revisores:  Rodrigo Fujioka

Equipe de Avaliação: José Filho, Ana Karla, KLedenilson , Walter Dias, Rodrigo Fujioka, Martin PFeifer

Data:  07/02/2018


## Objetivos
O projeto tem como objetivo avalias as habilidades práticas dos candidatos, alguns questionamentos são incluídos, não a título de cobrança, mas como um informativo de conceitos que serão necessários a oportunidade em aberto.


## Questões básicas

1.	Qual a diferença entre AOT(Ahead-of-time) e JIT(Just-in-time)?
2.	Defina os Lifecycle Hooks e as suas responsabilidades?



## Projeto

Elaborar um projeto prático utilizando Angular na versão 4 (quatro) em diante, o código deve ser disponibilizado no github: https://github.com/publicsoftpb, o candidato irá criar um repositório com seu nome e nome do projeto, exemplo: fulano-selecao-front-2018. Segue abaixo as especificações:

## Itens a serem propostos e avaliados

- Padrões de projeto;
- Qualidade do código;
- Organização dos arquivos;
- Criatividade;

Ps:. Lembre-se que a PublicSoft trabalha, em sua maioria com clientes do setor público. 

### Item Obrigatório
- Interface responsiva 

### Componentes a serem desenvolvidos
1.	Um formulário de Login (Usuário:String , Senha:String , Cidade - (Campo Select))
2.	Um Dashboard contendo gráficos (Um gráfico de barras e um grafico de linhas)
3.	Um formulário de cadastro para entidades pessoa física e jurídica
4.  Todos os itens devem fazer parte de um projeto navegavel, ou seja, é possível chegar a cada item utilizando hiper-links. 

#### 1- Formulário de Login
a - Segue exemplo ilustrativo do login

![loginForm](https://github.com/publicsoftpb/selecao-front-2018/blob/master/login.png) Figura - 1

### 2 - Dashboard
•	A tela do dashboard, deverá ter um header (topo) fixado, com o nome do projeto centralizado, acompanhado com um ícone de um menu na lateral esquerda e um ícone de logout na lateral direita; 

• No conteúdo central, deverá conter 2 (dois) gráficos: linha e barra, com valores estáticos: mêses (Janeiro a Maio) e valores; 

• Por último, deverá conter um footer (rodapé) fixado, com o seguinte nome: 
                                      **“© 2018 PublicSoft - Todos os Direitos Reservados”.**
                                      
•	Segue imagem abaixo meramente ilustrativa do dashboard:

•	Ações ao clicarem nos ícones:

1. **Menu:** Habilita menu lateral, contendo os itens: Dashboard, Cadastro com subMenu (Pessoa), a Figura 2 meramente ilustrativa do menu;	

![figura2](https://github.com/publicsoftpb/selecao-front-2018/blob/master/subMenu.png)Figura 2

2. **Logout:** Redireciona para tela de Login.

![DashBoard](https://github.com/publicsoftpb/selecao-front-2018/blob/master/dashboard.png) Figura - 3


#### 3- Campos dos formulários 

##### (Pessoa)
A tela de cadastro de pessoa, deverá conter uma opção (radio button) do usuário escolher o formulário (Física, Jurídica), todos os campos serão obrigatórios, segue abaixo uma tabela com os campos, tipos e máscaras que irão conter nestes formulários:

|  Campo        |	Tipo	  |  Máscara				        |
|---------------|---------|-------------------------|
|Nome           |Text     |Somente caracteres Aa-Zz	|
|Data Nascimento|Date	    |99/99/9999	              |
|Cpf            |Text     |999.999.999-99           |
|Rg             |Text     |Não possui               |
|Cep            |Text     |99999-999                |
|Logradouro     |Text     |Não possui               |
|Número         |Text     |Não possui               |
|Bairro         |Text     |Não possui               |
|Cidade         |Text     |Não possui               |
|Estado         |Select   |Não possui               |
|Fone           |Text|(99)| 99999-9999              |
|E-mail         |Email    |Não possui               |



##### (Jurídica)
A tela de cadastro de pessoa, deverá conter uma opção (radio button) do usuário escolher o formulário (Física, Jurídica), todos os campos serão obrigatórios, segue abaixo uma tabela com os campos, tipos e máscaras que irão conter nestes formulários:

|  Campo        |	Tipo	  |  Máscara				        |
|---------------|---------|-------------------------|
|CNPJ           |Text     |99.999.999/9999-99       |
|Razão Social   |Text     |Não possui               |
|Nome Fantasia  |Text     |Não possui               |
|Insc. Estadual |Text     |Não possui               |
|Cep            |Text     |99999-999                |
|Logradouro     |Text     |Não possui               |
|Número         |Text     |Não possui               |
|Bairro         |Text     |Não possui               |
|Cidade         |Text     |Não possui               |
|Estado         |Select   |Não possui               |
|Fone           |Text|(99)| 99999-9999              |
|E-mail         |Email    |Não possui               |

**•** Utilize a Figura 4, como exemplo meramente explicativo para o formulário de pessoa:

![FormPessoa](https://github.com/publicsoftpb/selecao-front-2018/blob/master/formPessoa.png) Figura - 4




**•**	Ao selecionar a opção pessoa física, irá carregar o formulário com os campos de pessoa física, e ao selecionar opção pessoa jurídica, irá carregar o formulário com os campos de pessoa jurídica. Quando clicar em salvar, mostrar uma mensagem que foi salvo com sucesso, lembrando que todos os campos deverão estar preenchidos.




