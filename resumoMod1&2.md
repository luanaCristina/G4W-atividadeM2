GitHub

Readme
Título e descrição: Comece com um título claro e conciso que descreva o propósito do seu projeto.
Instrução de instalação: Forneça instruções claras e detalhadas sobre como instalar seu projeto
Exemplos de uso: Forneça exemplos práticos de como usar o seu projeto. Ela mencionou um vídeo.


Mantendo o repositório
1. Configuração do repositório
2. Branches
3. Issues
4. Wikis
5. Pull requests (PR)
6. Proteção de Branches - sintaxe fnmatch (escopo da regra e prevalência

Criar branchs
$ git checkout branch
$ git checkout -b branch

Consultar branch
$ git branch
$ git branch -r

Ferramentas colaborativas
Issue
1. A gente utiliza tanto para sugerir melhorias, solicitar novas features ou reportar bugs.
2. Podemos utilizar o markdown para a formatação do texto. 
3. Exemplos de markdown Tarefas - [] Criar uma tela, Critérios de aceite 1. Como vendedor….
4. Conseguimos associar a issue
5. Utilizar labels ou criar novas labels para classificar a issue. Elas são por projeto
6. Podemos criar branch associando essa issue ao implementar. (Rastreamento)
7. Tem status, exemplo open e closed.
8. Podemos criar templates de issue. Ótimo para ajudar os novos integrantes para saber quais são as principais informações necessária para ajudar o desenvolvedor e testador. Serve para padronizar. 
    1. Podemos criar template yaml e a gente adiciona no .github/ISSUE_TEMPLATE.
    2. Esse template yaml já aparece lá nas opções e é ótimo para garantir que o usuário vai usar o padrão porque ele é um form.
9. Tem identificação única.
10. Podemos atrelar o pullrequest a uma issue utilizando as palavras chaves.
11. Podemos filtrar ou pesquisar. Filter is:issue is:open 
12. Podeos fixar ou Pin Issue
13. Temos que fechar a issue ao finalizar a implementação
14. Podemos adicionar imagens ou url ao abrir a issue utilizando os recursos:
    1. [teste](url)
    2. ![Diagrama 1](flow.png?raw=true "Flow”)
    3. ![Diagrama 1](adicionar a url)
Link da atividade: https://github.com/luanaCristina/G4W-atividadeM2/issues 

PUll Request - Professor wilsonsantosnet
1. Faça commit curtos para evitar erros
2. Após todos os commits finalizados e rodando com sucesso podemos fazer o pull request.
3. Seguindo o padrão do projeto ou equipe.
4. Podemos usar o copilot para code review, se estiver integrado
5. Podemos sugerir alterações e podemos receber sugestões (conversation)
6. Temos status: open, closed or merged (quando for aprovado)
7. Podemos visualizar os commits
8. Check - para verificar o que houve
9. Podemos visualizar as alterações (files changed) para depois aprovar o pull request
10. Temos template tbm que vai ser atrelado ao pull request
11. Temos a possibilidade de linkar a issue
12. A gente revisa no code review. E podemos adicionar uma pessoa responsável com o codeowners usando o template de exemplo:
    1. CODEOWNER @leandromsft
    2. .github/workflows/* @leandromsft
    3. Iac/ @leandro-infra01
13. Podemos fazer um rascunho tbm. 

Discussions - Beatriz
1. Tem diversas categorias
2. Podemos fechar uma discussion
3. Podemos marcar e mencionar no comentário
4. Podemos converter uma discussion para issue
5. Podemos pin
6. A discussion se não estiver aparecendo no repositório temos que clicar em settings e ativar o discussions

Notificações
1. A gente pode receber via mobile
2. A gente pode receber quando for feito um pullrequest
3. Comentários sobre uma thread
4. Quando for mencionado
5. Podemos receber por meio do subscribe na notificação.
6. A gente consegue ver as notificações no Github na caixa de entrada.
7. Tem filtro
8. Posso salvar tbm

Gist
1. Compartilhar parte do código com outras pessoas
2. E pode ser clonado
3. Podemos pesquisar
4. Para criar um gist a gente entra no gist
5. Pode ser secret ou público
6. site: https://gist.github.com/ 
7. exemplo: gist:81823178ab18811392f53ef7204655bf
8. Exemplo público: https://gist.github.com/discover#:~:text=choco%2Dbot%20/-,1.RegistrySnapshot.xml,-Created%20now 

Wiki
1. Serve para a gente definir e documentar o nosso projeto
2. Podemos criar várias páginas
3. Podemos usar markdown

GitHub Pages
1. A gente pode criar uma página com o nosso projeto para demonstrar ao público como funciona o projeto
2. Já criei uma calculadora simples usando html + css e JavaScript
3. https://docs.github.com/pt/pages/getting-started-with-github-pages/creating-a-github-pages-site 
4. https://github.com/collections/github-pages-examples
5. É gerado uma url
6. Podemos identificar quando tem o io
7. Podemos criar um currículo com ele


Link atividades
Issue: https://github.com/luanaCristina/G4W-atividadeM2/issues 
Branch: 
