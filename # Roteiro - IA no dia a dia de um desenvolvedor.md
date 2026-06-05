# Roteiro - IA no dia a dia de um desenvolvedor (15 minutos)

## 1. Abertura e pergunta: IA vai substituir profissionais?( 1 minuto)

### Resposta:

> - Provavelmente não da forma como normalmente imaginamos.

### O mais provável é que:

> - profissionais que utilizam IA sejam mais produtivos;
> - profissionais que aprendam a trabalhar com IA tenham vantagem competitiva;
> - tarefas repetitivas sejam cada vez mais automatizadas.

## 2. Explicar IA como assistente e acelerador de produtividade.( 1 minuto)

> Quando falamos de Inteligência Artificial, muitas pessoas imaginam algo capaz de substituir completamente o trabalho humano.
>
---
> Na prática, o que vemos hoje é algo diferente.
> 
> A IA funciona muito mais como um assistente e um acelerador de produtividade.
> 
> Um assistente porque ela ajuda: 
> - a responder dúvidas
> - sugerir soluções
> - revisar trabalhos
> - encontrar informações.
> 
> E um acelerador porque tarefas que antes levavam horas podem ser realizadas em minutos.
---
> No desenvolvimento de software, por exemplo, ela pode criar uma estrutura inicial de projeto, gerar testes, documentar código ou sugerir melhorias.
---
> Mas quem continua entendendo o problema, tomando decisões e validando o resultado é o profissional.

## 3. Exemplo Docker Compose: do básico às boas práticas.( 2 minutos)

> Como não temos muito tempo, vamos partira para alguns exemplos:
> - abre o ChatGpt(que já deve estar aberto por sinal)
> - adiciona o prompt.
> - gera o docker-compose
> - exibe e explica o que aconteceu.
>

##### **>>>>>>>>>>> PROMPT EXEMPLO 1: >>>>>>>>>>>>>>>>>**



```
Inicio de desenvolvimento de um serviço de autenticação que utiliza linguagem java, posgresql e keycloak, preciso de um docker-compose para iniciar o desenvolvimento.
```
>
> Melhore a solução considerando:
>

##### **>>>>>>>>>>> PROMPT EXEMPLO 1.1: >>>>>>>>>>>>>>>>>**


```
Agora o projeto evoluiu e se faz necessária a criação de um docker-compose mais adequado para direcionamento do projeto ir para produção levando em consideração os seguintes pontos: 

- PostgreSQL 17
- Volumes persistentes
- Banco authdb
- Rede dedicada
- Healthchecks
- Variáveis em .env
- Restart automático
- Importação de realm

```
#### O que falar

> "Aqui existe uma lição importante.
> 
> O valor não está apenas na IA.
> 
> O valor está na combinação:
> 
> - Conhecimento humano + IA.
> 
> Quanto melhor o contexto fornecido, melhor será o resultado."

## 4. CRUD completo: entidade, endpoints, testes unitários e integração.( 3 minutos)

>
> Agora vamos imaginar uma tarefa extremamente comum: 
> 
> **Precisamos criar uma funcionalidade para manter os dados de clientes, adicionar, alterar e até remover.**
> 
> 
> 
> Usar a frase:
> 
> "Tradicionalmente isso exigiria várias classes, endpoints, testes e documentação."
 
##### **>>>>>>>>>>> PROMPT EXEMPLO 2: >>>>>>>>>>>>>>>>>**

```
Crie uma API REST para manutenção
de clientes.

Gere:

- Entidade
- Repository
- Service
- Controller
- DTOs
- Tratamento de exceções

```

>
> Falar: "Em segundos a IA produz toda a estrutura inicial."
> 
> 

## 5. Revisão de código e sugestões de melhoria.( 2 minutos)
>
> "Software não é apenas código. Software precisa de qualidade."
> 

##### **>>>>>>>>>>> PROMPT EXEMPLO 2.1: >>>>>>>>>>>>>>>>>**

```
Gere testes unitários
para esta API utilizando:

- JUnit 5
- Mockito

Considere:

- sucesso
- cliente inexistente
- e-mail inválido
```
>
> "A IA agora não está criando funcionalidade. Está ajudando a garantir qualidade."
> 


## 6. Migração Java para .NET e Python.( 2 minutos)

>
> "A IA não elimina a necessidade de conhecimento técnico. Ela reduz o tempo gasto em tarefas repetitivas para que possamos dedicar mais tempo à análise, qualidade e tomada de decisão."
> 

>
> O que falar
> 
>"Uma das características mais interessantes da IA é que ela não conhece apenas sintaxe.
> 
> Ela conhece conceitos de desenvolvimento.
> 
> Quando pedimos uma conversão entre linguagens, ela não traduz apenas palavras.
> 
> Ela tenta preservar arquitetura, responsabilidades e regras de negócio."
> 
---
#### Um cenário adverso surge:

> 
> "Imagine que acabamos de criar nossa API de clientes em Java."
> 
> "Agora surge uma necessidade."
> 
> "Outra equipa da empresa trabalha com .NET."
> 
> 

##### **>>>>>>>>>>> PROMPT EXEMPLO 3: >>>>>>>>>>>>>>>>>**

```
Converta esta API Spring Boot para .NET.

Mantenha:

- arquitetura em camadas
- DTOs
- validações
- endpoints REST
- tratamento de exceções

```
>
> "A IA consegue gerar uma estrutura muito próxima do que um desenvolvedor .NET criaria manualmente."
> 
> "Ela não apenas converte a linguagem."
> 
> "Ela converte a solução."
> 
> ---
> 
> "Percebam que a arquitetura continua a existir.

--- 
#### Agora imagine outro cenário:

> 
> "Uma equipa de ciência de dados ou automação prefere Python."

##### **>>>>>>>>>>> PROMPT EXEMPLO 3.1: >>>>>>>>>>>>>>>>>**

```
Converta esta API para Python utilizando FastAPI.

Mantenha:

- separação de responsabilidades
- validações
- endpoints REST
- documentação automática

```
#### O Resultado:

>
> "A IA produz uma estrutura completamente diferente na implementação, mas semelhante na organização."
> 

## 7. Discussão arquitetural e apoio à tomada de decisão.( 2 minutos)

#### O que mudou?
>
> Java
> 
> Classes
> 
> Spring
> 
> Annotations
> 
> ↓
> 
> .NET
> 
> Controllers
> 
> Dependency Injection
> 
> Attributes
> 
> ↓
> 
> Python
> 
> FastAPI
> 
> Pydantic
> 
> Routers
> 

--- 

>
> Antigamente, migrar entre tecnologias exigia semanas de pesquisa, hoje a IA ajuda a acelerar esse processo, ela não substitui o aprendizado mas reduz muito a curva inicial.
> 

## 8. Aplicações em outras profissões.( 2 minutos)

> Mas no nosso caso desta apresentação, não há somente desenvolvedores aqui, então segue alguns exemplos para aplicação a outras profissões

- Advogados
	- resumir processos;
	- analisar documentos;
	- gerar rascunhos.
- Médicos
	- apoio à análise de exames;
	- organização de informações.
- Professores
	- criação de material didático;
	- exercícios;
	- planos de aula.
- Gestores
	- elaboração de relatórios;
	- análise de indicadores;
	- planeamento.
- Desenvolvedores
	- geração de código;
	- testes;
	- documentação;
	- revisão técnica.

## Mensagem final

>
> A IA não substitui o especialista. 
> 
> Ela amplia a capacidade do especialista, tecnicamente e na produtividade.
> 