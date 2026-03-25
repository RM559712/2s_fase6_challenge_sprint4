# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/images/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# Enterprise Challenge - Sprint 4 - YOUVISA

## 👨‍👩 Grupo

Grupo de número <b><PENDENTE></b> formado pelos integrantes mencionados abaixo.

## 👨‍🎓 Integrantes: 
- <a href="https://www.linkedin.com/in/cirohenrique/">Ciro Henrique</a> ( <i>RM559040</i> )
- <a href="https://www.linkedin.com/in/marcofranzoi/">Marco Franzoi</a> ( <i>RM559468</i> )
- <a href="https://www.linkedin.com/in/rodrigo-mazuco-16749b37/">Rodrigo Mazuco</a> ( <i>RM559712</i> )

## 👩‍🏫 Professores:

### Tutor(a) 
- <a href="https://www.linkedin.com/in/leonardoorabona/">Leonardo Ruiz Orabona</a>

### Coordenador(a)
- <a href="https://www.linkedin.com/in/profandregodoi/">André Godoi</a>

## 📜 Descrição

<b>Referência</b>: <PENDENTE>

### [...]

[...]



### x. Especificações Técnicas

Este tópico tem como objetivo apresentar informações técnicas relacionadas ao funcionamento e à estrutura da ferramenta desenvolvida.

#### x.1 Frontend

Abaixo estão listadas as informações dos componentes principais utilizados no <i>frontend</i> do projeto:

- [React](https://react.dev/): Esse framework é utilizado para compor toda a estrutura de <i>frontend</i> do projeto. A versão utilizada é 19.2.2;
- [Vite](https://vite.dev/guide/): Essa ferramenta de build e servidor de desenvolvimento é utilizada na geração da estrutura de <i>frontend</i> do projeto. A versão utilizada é 7.2.2;
- [Tailwind Css](https://tailwindcss.com/): Esse framework css é utilizado para customização do layout da ferramenta. A versão utilizada é 3.3.3;
- [Headless UI](https://headlessui.com/): Esse componente é utilizado para exibição de componentes do tipo <i>modal</i>. A versão utilizada é 2.2.9;
- [Axios](https://axios-http.com/ptbr/docs/intro): Essa biblioteca JavaScript é utilizada para realizar requisições HTTP com o <i>backend</i>. A versão utilizada é 1.13.2.

Abaixo estão listadas as páginas disponíveis.

##### x.1.1

[...]

#### x.2 Backend

Abaixo estão listadas as informações dos componentes principais utilizados no <i>backend</i> do projeto:

- [Django Rest](https://www.django-rest-framework.org/): Esse framework é utilizado para compor toda a estrutura de <i>backend</i> do projeto. A versão utilizada é 5.2.8.

Abaixo estão listados os métodos disponíveis na API do projeto.

##### x.2.1 `/api/[...]/[...]`

[...]

Esse serviço recebe os seguintes parâmetros no padrão Python:

- `[...]`: [...]

Esse serviço retorna os seguintes parâmetros no padrão Javascript:

- `status`: Status principal da requisição com serviço (<i>`boolean`</i>);
- `sMessage`: Caso ocorra algum tipo de erro, será retornada uma mensagem com detalhes (<i>`string`</i>);
- `oData`: Objeto contendo parâmetros retornados pelo serviço (<i>`object`</i>);
- `oData > [...]`: [...]
- 

[...]

#### x.3 Banco de dados	

Abaixo estão listadas as informações relacionadas ao banco de dados:

- O banco de dados utilizado no projeto é o [MySQL](https://www.mysql.com/0) na versão 8.0.43;
- O banco de dados está instanciado no serviço [RDS](https://aws.amazon.com/pt/rds) da [AWS](https://aws.amazon.com/pt) localizado na região `us-east-1a` e na classe de instância `db.t4g.micro`;
- A estrutura do banco de dados pode ser acessada clicando [aqui](https://github.com/RM559712/2s_fase6_challenge_sprint4/blob/main/scripts/mysql/2s_fase6_challenge_sprint4.sql).

### 5. Demonstração

É possível assistir um vídeo demonstrando a execução das funcionalidades mencionadas acima através deste [link](<PENDENTE>).

## 📁 Estrutura de pastas

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

1. <b>assets</b>: Diretório para armazenamento de arquivos complementares da estrutura do sistema.
    - Diretório "images": Diretório para armazenamento de imagens.

2. <b>config</b>: Diretório para armazenamento de arquivos em formato <i>json</i> contendo configurações.

3. <b>document</b>: Diretório para armazenamento de documentos relacionados ao sistema.

4. <b>scripts</b>: Diretório para armazenamento de scripts.

5. <b>src</b>: Diretório para armazenamento de código fonte do sistema.

6. <b>tests</b>: Diretório para armazenamento de resultados de testes.
    - Diretório "images": Diretório para armazenamento de imagens relacionadas aos testes efetuados.

7. <b>README.md</b>: Documentação do projeto em formato markdown.

<i><strong>Importante</strong>: A estrutura de pastas foi mantida neste formato para atender ao padrão de entrega dos projetos.</i>

## 🔧 Como executar o código

Como se trata de uma versão utilizando <strong>Django</strong> e <strong>React + Vite</strong>, para execução das funcionalidades, os seguintes passos devem ser seguidos:

1. Acessar o diretório <b>src/backend</b>
    - Criar o arquivo .env utilizando como referência a documentação [README.MD](https://github.com/RM559712/2s_fase6_challenge_sprint4/tree/main/src/backend#exemplos-de-par%C3%A2metros-para-o-arquivo-env). Os parâmetros estão disponíveis na entrega do projeto;
    - Inicializar o ambiente a partir do comando `.\venv\Scripts\activate`;
    - Instalar as dependências do projeto a partir do comando `pip install -r requirements.txt`;
    - No caso de execução de testes em um ambiente específico, o banco de dados deverá ser criado a partir do comando `python manage.py migrate`
    - Inicializar o servidor a partir do comando `python manage.py runserver`;
    - Para fins de teste, o serviço pode ser testado em ambiente local através da url padrão `http://localhost:8000/`.

2. Acessar o diretório <b>src/frontend</b>
    - Criar o arquivo .env utilizando como referência a documentação [README.MD](https://github.com/RM559712/2s_fase6_challenge_sprint4/tree/main/src/frontend#exemplos-de-par%C3%A2metros-para-o-arquivo-env). Os parâmetros estão disponíveis na entrega do projeto;
    - Inicializar o servidor a partir do comando `npm run dev`;
    - Para fins de teste, o serviço pode ser testado em ambiente local através da url padrão `http://localhost:5173/`.
    - As dependências do projeto estão presentes no arquivo "package.json";

3. Acessar o diretório <b>scripts/mysql</b>
    - Caso seja necessário criar o banco de dados em outro ambiente, basta executar as queries do arquivo [2s_fase6_challenge_sprint4.sql](https://github.com/RM559712/2s_fase6_challenge_sprint4/blob/main/scripts/mysql/2s_fase6_challenge_sprint4.sql)

Para essa versão não são solicitados parâmetros para acesso como por exemplo <i>username</i>, <i>password</i>, <i>token access</i>, etc.

## 🗃 Histórico de lançamentos

* 1.0.0 - 29/04/2026

## 📋 Licença

Desenvolvido pelo Grupo <PENDENTE> para o projeto da fase 6 (<i>Enterprise Challenge - Sprint 4 - YOUVISA</i>) da <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a>. Está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>