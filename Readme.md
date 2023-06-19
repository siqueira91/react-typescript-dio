
#### Desafios

<h3></h3>
[&#10003;] Implementar os métodos de depósito (deposit) e saque (withdraw) na classe DioAccount
  - Os valores dos saldos devem ser alterados, de acordo com o valor informado para depósito
  - Apenas contas com o status true e saldo (balance) maior que o valor solicitado podem fazer saques

[&#10003;] Implementar o método de empréstimo (getLoan) na classe CompanyAccount
  - Os valores do saldos deve ser acrescidos, de acordo com o valor informado para empréstimo
  - Apenas contas com o status true podem fazer empréstimo

[&#10003;] Criar um novo tipo de conta a partir da DioAccount
  - Esta conta não deve receber novos atributos
  - Esta conta terá um método de depósito, que acresce 10 a mais ao valor informado para depósito. (Ex: Um depósito de 100, será de 110 no final)

[&#10003;] Todos os atributos de qualquer conta devem ser privados

[&#10003;] Os atributos name e accountNumber não podem ser alterados internamente ou externamente

[&#10003;] Criar instancias para cada um dos tipos de conta no app.ts e executar os métodos possíveis.


<h3>Desafio 02 </h3>

[ ] Crie os componentes referentes aos elementos na página inicial
  - Crie um componente para o header, com o título da aplicação
  - Crie um componente para o botão, que aceite onClick como uma das props do componente
  - Refatore o componente Card para receber o formulário de login. Ao invés de chamar elemento por elemento na página inicial, apenas o componente Card deve ser chamado.

[ ] Crie uma função de Boas vindas
  - Ao clicar no botão, deve aparecer um alert com uma mensagem de boas vindas
  - Crie o teste unitário da função


<h3>Desafio 03 </h3>

[ ] Incluir validação da senha no campo de login
  - Para logar, além do email faça a validação com a senha informada pelo usuário.
  - Durante a implementação, aplique o TDD e escreva os testes unitários para a nova validação

[ ] Implemente um sistema de login com a Context API
  - Seguindo os exemplos demonstrados ao longo do curso, crie um estado global para realizar o login
  - Utilize o localStorage para armazenar os dados do usuário ao logar
  - Caso os dados do usuário existam no localStorage, a tela de login não deve ser exibida

[ ] Crie uma página para exibir as informações do usuário
  - Crie uma página onde será exibido o nome, email
  - Esta página só poderá ser acessada caso a usuária esteja logada
  - Caso a usuária não esteja logada, deve ser mantida na página com a tela de login
  - Escreva os testes unitários para as funções criadas ou refatoradas.

[ ] Fazer o deploy no Netlify e compartilhar o link da página


<h3>Desafio 04 </h3>

[ ] Incluir os testes unitários pendentes no controller
  - Verificar a resposta de erro caso o usuário não informe o name
  - Verificar se a função getAllusers está sendo chamada

[ ] Implementa uma validação para o campo email
  - O usuário nâo pode ser criado caso não informe o email
  - Escreva o teste unitário

[ ] Refatorar e implementar a rota para deletar o usuário
  - Refatore a rota para deletar usuários
  - Escreva os testes unitários necessários