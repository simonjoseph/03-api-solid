# App

GymPass style App.

## RFs (requisitos funcionais)

- [ ] Deve ser possível se cadastrar;
- [ ] Deve ser possível se autentica;
- [ ] Deve ser possível obter o perfil de um usuário logado;
- [ ] Deve ser possível obter o número de check-Ins realizados pelo usuário logado;
- [ ] Deve ser possível o usuário boter seu historico de check-ins;
- [ ] Deve ser possível o user buscar academinas próximas;
- [ ] Deve ser possível o user buscar academias pelo nome;
- [ ] Deve ser possível o user realizar check-in em uma academia;
- [ ] Deve ser possível validar o check-in de um user;
- [ ] Deve ser possível cadastrar uma academia;

## RNs (Regra de negócio)

- [ ] O user não deve poder se cadastrar com email duplicado;
- [ ] o user não deve fazer 2 checkins no mesmo dia;
- [ ] o user não pode fazer checkins se não estiver perto (100m) da acadenia;
- [ ] o checkin só pode ser validado até 20 minutos após criado;
- [ ] o checkin so pode ser validado por admin;
- [ ] A cademia só pode ser cadastrada por admin;

## RNFs (Requisitos não funcionais)

- [ ] A senha do user precisa estar criptografada;
- [ ] Os dados da aplicação precisam estar persistidos em um banco PostgresSQL;
- [ ] Todas listas de dados precisam estar paginadas com 20 itens por página;
- [ ] O user deve ser identificado por um JWT (JSON Web Token);
