# FRON-END Challenge

## O Desafio

Você recebeu a tarefa de desenvolver algumas features para uma empresa do segmento fitness.


A Análise de Negócios mapeou as seguintes histórias em ordem de prioridade:

1. Eu como usuário desejo enviar minha foto e visualizar qual foto enviei para caso deseje alterar, enviando outra.
2. Eu como usuário desejo poder cadastrar meu nome completo, cpf, celular e após concluir poderei cadastrar data de nascimento e Gênero.
3. Eu como usuário, após avançar da primeira parte do cadastro desejo poder cadastrar um CEP e automaticamente meus dados como Enderenço, Número, complemento, bairro, cidade e estado serão completados.
4. Eu como usuário, após concluir o meu cadastro de endereço, desejo avançar para a próxima tela, onde poderei visualizar os planos que desejarei visualizar um
efeito Carousel slider.
5. Eu como usuário na tela de planos desejo visualizar uns gifs no slide.
6. Eu como usuário desejo visualizar uma tela de que o cadastro foi concluído com sucesso, após avançar na tela de Planos.


## Detalhes técnicos

Na história 1, faça o upload local e a mudança da imagem para que o usuário possa visualizar a imagem que está em no temporário.


Na história 2, o usuário só poderá preencher os dados como data de nascimento e gênero se os dados como NOME, CPF e CELULAR estiverem preenchidos.

Na história 2, mostrar uma mensagem para o usuário de que o campo é obrigatório.

Na história 2, o CPF precisa ser válido.

Na história 2, o usuário só poderá avançar caso os campos obrigatórios estejam preenchidos.

Na história 3, você pode usar a API da viacep`https://viacep.com.br/ws/${cep}/json/`

Na história 3, o usuário só poderá avançar se os dados estiverem completos

Na história 4, você poderá consumir o giphy da API [Data Giphy](https://developers.giphy.com/docs/api/endpoint) e adicionar 5 giphys em qualquer parte da tela de plano.

Na história 5, o usuário poderá visualizar outros planos, então você precisará colocar uns 5 planos só altere o nome no plano, por exemplo na imagem do figma está, mega
então adicione: Fit, Omega, Beta e Ultra com os valores respectivamente: R$200, R$300, R$400 e R$500.

## Orientações gerais

* Siga as histórias na ordem de prioridade. Procure focar em pequenos entregáveis. Tudo bem se não conseguir entregar tudo, mas faça o máximo que puder no tempo proposto que são 7 dias.
* Nós iremos avaliar a qualidade no código, as boas práticas e sua atenção com a qualidade na implementação. Tenha atenção aos detalhes e
busque tratar condições de cross-browser, responsividade, experiência do usuário, fidelidade ao layout no figma.
* O README deverá ter instruções detalhadas de como rodar a aplicação. 
* Envie-nos um link público do projeto no github. **Não abra PRs para este repositório.**
* Mostre suas habilidades em HTML/CSS e com um framework JS (React, Angular e VueJS)
* *O objetivo desta etapa não é somente resolver o problema proposto.* Mesmo que estes problemas não sejam extensos, nós esperamos que você encaminhe um código que acredite ser de qualidade, possível de ser rodado e evoluído. Use esse problema para nos mostrar as práticas que você utiliza no dia-a-dia para escrever um bom código.
* Documentação da API: [Current giphy data](https://developers.giphy.com/docs/api/)
* Acesso ao Projeto a ser seguido: [Figma](https://www.figma.com)
```
email: produto@totalpass.com.br
senha: teste1234
```
 Acesse o projeto teste onde terá 4 telas para você seguir e exportar os icones que precisar.

* Faça testes unitários para models e serviços. Testes de integração também são bem vindos.
* Caso tenha alguma dúvida sobre esse desafio, você pode nos encaminhar via e-mail.
* Caso tenha sugestões de melhorias ou críticas em relação ao desafio ou estrutura inicial do projeto, sinta-se à vontade de nos enviar via e-mail.

## PLUS NA ATIVIDADE

* Paginação com giffs retornando os primeiros 5 e de alguma forma carregar mais nas outras páginas
* Transformar a página em PWA