![microservices](https://user-images.githubusercontent.com/98756562/190171771-1c644541-0278-460f-9c6f-3c361c2eb23a.png)



# Microsserviços: conceito, vantagens e desvantagens dessa arquitetura

Entenda como funcionam os microsserviços e quais as vantagens e desvantagens deles

Microsserviços, nasceram em 2009, mas sua fama e popularidade começou realmente entre 2014 e 2015, quando o mercado reconheceu que o modelo de arquitetura era, de fato, atraente para o desenvolvimento de softwares em nuvem. Desde então tem se consolidado como um padrão cada vez mais comum e preferido pelos desenvolvedores, sobretudo agora com o mundo se movendo para a cloud computing.

No entanto a falta do conjunto de skills apropriadas, bem como muitos sistemas legados, e falta de apoio corporativo são as principais razões por que as organizações ainda não integraram microsserviços em suas aplicações ou têm dificuldade de escalar.
Isso significa que, apesar de difundido o conceito de microsserviços, ainda há pouca clareza sobre vantagens e desvantagens da tecnologia. Então, é o que veremos neste texto.

### O que é microsserviços?  

É mais fácil explicar o que é arquitetura de microsserviços contrastando-a com a arquitetura monolítica, pois ela representa uma mudança do paradigma centralizador para um paradigma descentralizador de construção de aplicações.

![monolito-microsserviços](https://user-images.githubusercontent.com/98756562/190196378-1b0eca01-0c60-43eb-b154-da29858f4bd8.png)

*Aplicativos monolíticos podem ser bem-sucedidos, porém serão frustrantes – especialmente quando mais aplicações forem implementadas em nuvem. Ciclos de desenvolvimento são amarrados – uma mudança feita em uma pequena parte do aplicativo requer que o monolito inteiro seja republicado. Ao longo do tempo ficará cada vez mais difícil manter uma estrutura modular, o que torna mais difícil fazer com que mudanças afetem apenas um módulo. Escalar requer escalar o aplicativo inteiro, não apenas as partes que requerem mais recursos.*

Em contraste com a arquitetura monolítica, que funciona como um único serviço, a arquitetura de microsserviços é a composição de um único software baseada em um conjunto de peças altamente especializadas, autônomas e simples.

Essa arquitetura tem um acoplamento flexível e fraco de suas partes. Isso significa que não é preciso considerar o impacto de cada componente no aplicativo como um todo: cada um pode ser mantido por uma equipe pequena, escrito em uma linguagem própria, atualizado e modificado independentemente da aplicação principal e escalado à vontade, sem recompilação e reimplantação do sistema como um todo.

Até por serem cloud nativos, os microsserviços funcionam normalmente com cloud computing, ainda que não exclusivamente.

### Quatro Vantagens dos microsserviços

1. Facilidade e rapidez na atualização e implantação dos serviços

Com microsserviços, atualizações e mudanças podem ser feitas sem projetos e aprovações complexas, pois são menores em escopo e independentes.Esqueça demorar semanas para fazer coisas relativamente simples. A integração e a entrega são contínuas.

2. Aumentar a flexibilidade da infraestrutura

Boa parte da rapidez e da facilidade vem da independência dos serviços entre si, ou seja, de sua flexibilidade. Os componentes do aplicativo não precisam compartilhar código, modelos de dados e database comuns.

3. Escalabilidade

Com microsserviços, cada serviço pode escalar independentemente para atender uma demanda.  

Isso significa que a ampliação se torna bem dimensionada e precisa, realizada apenas nos serviços que precisam dela, requerendo menos infraestrutura do que aplicativos monolíticos.

4. Estandardização de serviços

Dentro da arquitetura de microsserviços, há vários padrões de design, comunicação e de integração que ajudam a lidar com desafios bem comuns, como backend-for-frontend (BFF), entidades e agregações, descoberta de serviços etc.


### Por que a arquitetura de microsserviços pode ser útil a organizações?

Para grandes empresas, adotar a arquitetura de microsserviços significa acabar com a dependência de um hardware particular ou de um software fornecedor. Ademais, elas podem ter sua infraestrutura melhorada sem afetar grande parte das aplicações. 

Já para pequenos negócios e startups pode ser uma forma de viabilizar projetos complexos. Se, antes, eles tinham uma quase intransponível desvantagem em relação às grandes empresas, que podiam bancar grandes data centers e uma grande equipe para mantê-los, a arquitetura de microsserviços democratiza mais esse acesso.  

Todas as organizações, potencialmente, podem acessar as APIs da Amazon ou do Google para usar seus ativos. Isso permite que softwares e aplicativos complexos sejam construídos rapidamente, usando serviços construídos e mantidos por outros.

### Desvantagens da arquitetura de microsserviços

Ora, depois de enfatizarmos tantos benefícios da arquitetura de microsserviços, será que ainda tem lugar para alguma desvantagem? Sim.
A maioria dos problemas que podem surgir com uso da arquitetura de microsserviços tem a ver, justamente, com sua lógica descentralizadora, que apresenta – como tudo – prós e contras.

1.	Complexidade

É fácil perceber que um sistema formado por partes autônomas e especializadas forma um todo bem complexo, distribuído. Uma arquitetura monolítica, por outro lado, tem o benefício de ser um sistema centralizado e blocado.
Por isso, seguindo Martin Fowler, especialista em arquitetura de software, “não considere migrar para microsserviços a menos que você já tenha um sistema que seja muito complexo para gerenciar como um monolito”. 

2.	Governança 

Com vários componentes completamente distintos trabalhando juntos em um único aplicativo, a governança pode deixar a desejar.

3.	Integração com aplicações monolíticas legadas

Como não se comunica com outros serviços, o uso da rede em um monolito é bem menor. Esse baixo tráfego de rede é uma vantagem que pode se perder na migração para microsserviços. Isso porque ter muitos pequenos serviços pode gerar uma cadeia de comunicação extremamente prolixa e interdependente, comprometendo o funcionamento da rede.

4.	Segurança

Algumas vulnerabilidades dos microsserviços são resultados diretos de sua natureza aberta, com uma ampla superfície sujeita a ataques. Sobretudo quando os microsserviços não estiverem bem definidos, documentados e estandardizados por meio de APIs seguras, a segurança também pode se tornar um problema.


Há casos em que migrar de um monolito para microsserviços pode ser muito vantajoso, melhorando um sistema.

Em outros, como vimos, nem tanto. Além disso, sem a construção de um monolito modular e uma boa distribuição das peças, as desvantagens podem se sobrepor às vantagens da arquitetura.

### Resumo

Conhecemos a linguagem básica que você pode utilizar ao conversar com seus colegas de trabalho sobre microsserviços enquanto tomam um café. Também vimos que os sistemas monolíticos não são inerentemente ruins e podem até mesmo ajudar no crescimento dos negócios de sua empresa, na mesma medida em que os microsserviços poderão atrasá-lo se você os usar na hora errada; no longo prazo, porém, os microsserviços poderão melhorar o modo como os usuários interagem com seus sitemas.
