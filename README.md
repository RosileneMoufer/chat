# chat

Desenvolvimento de um chat simples com Flutter e Firebase.
Neste projeto aprendi como utilizar FirebaseAnimatedList, uma classe do Firebase que auxilia na busca e exibição de dados vindo do banco no Firebase, criando e controlando um container com scroll a medida que os itens são inseridos ou removidos, com isso, não há utilidade de utilizar a função setState().
Utilizei o Firebase Realtime Database como backend para que as mensagens em tempo real apareçam sejam exibidas para o usuário quando salvas no BD (stream).
A função setState() é utilizada para limpar o input quando a mensagem for enviada pelo usuário.
