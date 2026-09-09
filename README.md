- TypeScript é um superset - adicional ao js onde a a genbte consegue trabalhar com linguagem estatica trazer mais inteligencia pro nosso codigo.

- TypeScript é uma linguagem de programação fortemente tipada que converte o código final em js.

- O node não entende ts por padrão diferente de Deno, Bun e outras plataformas que executam código JS no server-side. Por isso precisamos de ts pra js.


- SQLite e um banco SQL relacional -- banco relacionais pra quem quer aprender no inicio acaba sendo melhor.

- Bom usar o SQLite agora porque não é necessário subir nenhum banco agora, nem docker.

- Plugins nada mais é do que separar pedaçinhos da nossa aplicação em mais arquivos para melhor organização do projeto e facilitar manutenção.

# RF 

- [x] O usuário deve poder criar uma nova transação;
- [x] O usuário deve poder obter um resumo de sua conta;
- [x] O usuário deve poder listar todas transações que já ocorreram;
- [x] O usuário deve poder visualizar uma transação única;

# RN

- [x] A transação pode ser do tipo crédito que somará ao valor total, ou débito subtrairá;
- [] Deve ser possível identificarmos o usuário entre as requisições;
- [] O usuário só pode visualizar transações o qual ele criou;

// Cookies sao basicamente formas da gente manter contexto entre reqs, ou seja, no momento que voce acessa um site, esse site jhoje pela LGPD pergunta se voce quer aceitar os cookies, ele salva alguma informacao como um id dentro do meu navegador sem que eu perceba. Isso para validar que a mesma pessoa baseado no ID fez tais requisicoes dentro da aplicacao.