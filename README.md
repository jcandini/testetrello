# Teste de Caixa Preta

O objetivo deste projeto é realizar um teste de caixa preta na tela de login do Trello. A tela de login do Trello oferece diversas funcionalidades, incluindo a entrada de e-mail, opções para login com diferentes provedores externos (Google, Microsoft, Apple, Slack), links para recuperação de senha e criação de uma nova conta. O teste de caixa preta visa verificar o comportamento correto dessas funcionalidades, garantindo que o usuário possa acessar a plataforma de forma eficaz e segura. Serão desenvolvidos cenários de teste abrangentes para cobrir uma variedade de casos de uso e situações, incluindo testes de entrada de dados válidos e inválidos, testes de integração com provedores externos e testes de usabilidade e segurança. O uso do Selenium em conjunto com o Google Chrome será fundamental para automatizar os testes e garantir uma cobertura abrangente da tela de login do Trello.

## Aplicativo escolhido

O Trello é uma plataforma de gerenciamento de projetos baseada em nuvem que permite aos usuários organizar e colaborar em projetos de forma visual e intuitiva. Com um sistema de quadros, listas e cartões, o Trello oferece uma maneira flexível e personalizável de planejar, acompanhar e concluir tarefas individuais e em equipe. Os usuários podem criar quadros para diferentes projetos, adicionar listas para organizar as etapas do projeto e criar cartões para representar tarefas específicas. Além disso, o Trello oferece recursos como atribuição de membros, comentários, prazos e integrações com outras ferramentas populares, tornando-o uma escolha popular para equipes de todas as dimensões e setores.

## Pré-requisitos

### Softwares Utilizados:
- Selenium WebDriver ([link](https://www.selenium.dev/))
- Google Chrome ([link](https://www.google.com/chrome))

## Conteúdo do Repositório

1. **Documentação:**
   - `README.md`: Documento principal do repositório com informações sobre os testes, ambiente de desenvolvimento e instruções para execução.

2. **Outros Arquivos:**
   - `screenshots`: Pasta contendo capturas de tela dos testes para referência.

## Instalação

**Ferramentas utilizadas:** Google Chrome e Selenium IDE  
**Sistema operacional:** MacOS  
**Dados do navegador:** Google Chrome Versão 124.0.6367.92  

## Executando os testes

1. **Entrada de E-mail:**
   - Digitar um e-mail válido e clicar em "Continuar".
   - Deixar o campo de e-mail em branco e clicar em "Continuar".
   - Digitar um e-mail inválido (sem "@" ou sem domínio válido) e clicar em "Continuar".
   - Digitar um e-mail com espaços em branco antes e/ou depois do e-mail e clicar em "Continuar".
   - Digitar um e-mail sem um domínio válido (por exemplo, "usuario@dominio" sem ".com", ".net", etc.) e clicar em "Continuar".
   - Digitar um e-mail com caracteres especiais inválidos (por exemplo, "usuario@domínio.com") e clicar em "Continuar".
   - Digitar um e-mail com letras maiúsculas e minúsculas misturadas (por exemplo, "Usuario@Dominio.com") e clicar em "Continuar".

2. **Botões de Login Externo:**
   - Clicar no botão "Login com o Google" e verificar o processo de login com o Google.
   - Clicar no botão "Login com o Microsoft" e verificar o processo de login com o Microsoft.
   - Clicar no botão "Login com a Apple" e verificar o processo de login com a Apple.
   - Clicar no botão "Login com o Slack" e verificar o processo de login com o Slack.

3. **Opções Adicionais:**
   - Clicar no link "Não conseguiu entrar?" e verificar o redirecionamento para a página de recuperação de senha.
   - Clicar no link "Crie uma conta" e verificar o redirecionamento para a página de registro.

4. **Integração entre os Elementos:**
   - Digitar um e-mail válido e clicar em "Continuar" para prosseguir para a próxima etapa.
   - Digitar um e-mail válido e clicar em "Login com o Google" para verificar o processo de login com o Google.
   - Digitar um e-mail válido e clicar em "Login com o Microsoft" para verificar o processo de login com o Microsoft.
   - Digitar um e-mail válido e clicar em "Login com a Apple" para verificar o processo de login com a Apple.
   - Digitar um e-mail válido e clicar em "Login com o Slack" para verificar o processo de login com o Slack.

5. **Manipulação de Campos de Entrada:**
   - Testar o recurso de autocompletar do navegador no campo de e-mail.
   - Digitar um e-mail válido, clicar em "Continuar", e depois limpar o campo de e-mail para verificar a limpeza correta.

6. **Teste de Acesso Negado:**
   - Tentar fazer login com um e-mail válido, mas senha incorreta e verificar se o acesso é negado.

7. **Teste de Limite de Caracteres:**
   - Tentar fazer login com um e-mail que contenha o número máximo de caracteres permitido pelo campo de entrada e verificar se o login é processado corretamente.

8. **Teste de Recuperação de Senha:**
   - Clicar no link "Não conseguiu entrar?" e verificar se é redirecionado para a página de recuperação de senha.
   - Digitar um e-mail válido para recuperação de senha e verificar se recebe um e-mail com instruções para redefinir a senha.
   - Tentar acessar a conta com a senha antiga após a redefinição de senha e verificar se é negado o acesso.
   - Clicar em "Política de privacidade".
   - Clicar em "Termos de serviço".
   - Clicar em "Mais".
   - Clicar em "Não consigo acessar a conta" e disponibilizar um e-mail inválido.
   - Clicar em "Criar conta" e fornecer um e-mail inexistente.
     

   Registro de teste
    https://github.com/jcandini/testetrello/blob/main/TESTE%20TRELLO.side;


## Autores

- João Vitor Candini
- 212032
