# psi-atividade1-Hugley2

1.
Model: Gerencia os dados e o banco de dados.
View: Templates HTML para a interface.
Controller: Rotas do Flask que gerenciam a lógica de requisição e resposta.
Se a lógica de dados ficasse nas rotas o código ficaria poluído, difícil de manter, sem reuso e com testes complicados devido ao alto acoplamento.

2. 
 Se a URL mudar na rota, o url_for atualiza o link no HTML automaticamente.
 Trata parâmetros e caracteres especiais da URL corretamente de forma dinâmica.

3.
Armazena o estado e a identidade do usuário logado durante a navegação.
Garante que apenas usuários autenticados criem resenhas, vincula o autor correto ao registro e impede invasões por envios diretos de formulário.
