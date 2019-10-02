# FRON-END Challenge

## O Desafio Mobile

Você recebeu a tarefa de desenvolver algumas features para uma empresa do segmento fitness.


A Análise de Negócios mapeou as seguintes histórias em ordem de prioridade:

1. Eu como usuário desejo enviar minha foto e visualizar qual foto enviei para caso deseje alterar, possa enviar uma outra.
2. Eu como usuário desejo cadastrar meu nome completo, cpf, celular (obrigatórios) e poderei cadastrar data de nascimento e Gênero (opcionais).
3. Eu como usuário, após avançar da primeira parte do cadastro desejo poder cadastrar um CEP e automaticamente meus dados como Enderenço, Número, Bairro, Cidade e Estado serão completados. Apenas esses campos são obrigatórios.
4. Eu como usuário, após concluir o meu cadastro de endereço, desejo avançar para a próxima tela, onde poderei visualizar os planos num efeito Carousel.
Para ficar mais divertido, eu como usuário, na tela de planos, desejo visualizar um gif em cada slide de plano. Esse gif pode ser aleatório ou no tema de atividades relacionadas a academia (fica a escolha do candidato).
Não precisar ser algo grande.
5. Eu como usuário desejo visualizar uma tela de que o cadastro foi concluído com sucesso, após avançar na tela de Planos.


## Detalhes técnicos

Na história 1, faça o upload local e a mudança da imagem para que o usuário possa visualizar a imagem.

Na história 2, os campos NOME, CPF e CELULAR são obrigatórios e os demais opcionais. Você também precisa validar todos os campos de acordo com formatação. 

Em todas as telas, ao clicar em avançar, se houver algum campo obrigatório não preenchido, ou algum campo inválido, esses items precisam ser destacados para o usuário e o 
mesmo não poderá avançar até preencher corretamente os campos.

Na história 2, o CPF precisa ser válido.

Na história 3, você pode usar a API da [VIACEP](https://viacep.com.br/ws/${cep}/json/)

Na história 3, o usuário só poderá avançar se os dados estiverem completos.

Na história 4, você poderá consumir o giphy da API [Data Giphy](https://developers.giphy.com/docs/api/endpoint) e adicionar 5 giphys em qualquer parte da tela de plano.
Conforme mencionado anteriormente, você pode usar giphys aleatórios ou relacionados a academias ou musculação. O usuário poderá visualizar outros planos, então você precisará mockar 
5 planos alterando o nome no plano, descrição e valor. Por exemplo na imagem do figma está, mega
então adicione: Fit, Omega, Beta e Ultra com os valores respectivamente: R$200, R$300, R$400 e R$500.

## Orientações gerais

* Siga as histórias na ordem de prioridade. Procure focar em pequenos entregáveis. Tudo bem se não conseguir entregar tudo, mas faça o máximo que puder no tempo proposto que são 7 dias corridos.
* O foco da tarefa é somente pensando no mobile.
* Nós iremos avaliar a qualidade no código, as boas práticas e sua atenção com a qualidade na implementação. Tenha atenção aos detalhes e
busque tratar condições de cross-browser, responsividade, experiência do usuário, fidelidade ao layout no figma.
* O README deverá ter instruções detalhadas de como rodar a aplicação. 
* Envie-nos um link público do projeto no github. **Não abra PRs para este repositório.**
* Mostre suas habilidades em HTML/CSS e com um framework JS (React, Angular e VueJS)
* *O objetivo desta etapa não é somente resolver o problema proposto.* Mesmo que estes problemas não sejam extensos, nós esperamos que você encaminhe um código que acredite ser de qualidade, possível de ser rodado e evoluído. Use esse problema para nos mostrar as práticas que você utiliza no dia-a-dia para escrever um bom código.
* Documentação da API: [Current giphy data](https://developers.giphy.com/docs/api/)
* Acesso ao Projeto a ser seguido: [Figma](https://www.figma.com)
```
Link: https://www.figma.com/file/1v1AXVFBwzc7niX6bMQgcG/teste?node-id=0%3A1
```
 Através do link acima, faça sua conta no figma e possa visualizar com detalhes, atributos de estilos dos elementos que compõe o design.
 Acesse o projeto teste onde terá 4 telas para você seguir e exportar os icones que precisar.

* Faça testes unitários para models e serviços. Testes de integração também são bem vindos.
* Caso tenha alguma dúvida sobre esse desafio, você pode nos encaminhar via e-mail.
* Caso tenha sugestões de melhorias ou críticas em relação ao desafio ou estrutura inicial do projeto, sinta-se à vontade de nos enviar via e-mail.

## PLUS NA ATIVIDADE
* Transformar a página em PWA
