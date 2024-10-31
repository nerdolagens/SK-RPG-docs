# Introducao ao repositorio

## mapa do repositorio

### .github/workflows/ci.yml
mermao nao mexe nessa merda mas nem fodendo, este arquivo e responvsavel por fazer auto deploy do codigo pra branch gh-pages, pode se dizer que ele transforma todos os arquivos md para a pagina front end, voce raramente (provavelmente nunca) vai ter que mexer com isso

### .gitignore
se voce nao sabe o que e isso pode se jogar da janela

### mkdocs.yml
este e nosso arquivo de configuracao da ferramenta mkdocs, ele e responvsavel em fazer a configuracao da nav, configuracoes do markdown e adicionar funcionalidades especiais, voce tera que vir aqui com frequencia pois e necessario editar a nav sempre que uma nova tela e adicionada, se voce nao sabe fazer isso toma 

- link da ferramenta: https://www.mkdocs.org/
- link do tema: https://squidfunk.github.io/mkdocs-material/

vai pesquisar vagabundo, se mandar mensagem pro iuri perguntando esta sujeito a paulada

### docs
e aqui que fica todo o conteudo da documentacao e onde voce provavelmente vai trabalhar 99% do tempo inserindo todo o conteudo de texto em arquivos markdown (.md)

dentro do diretorio assets ficam algumas coisas externas ao conteudo mas que fazem parte do frontend como scripts, stylesheets e imagens

## instalando depedencias

- obviamente voce precisar ter o git e uma chave SSH configurada em seu pc, mete no chatgpt e fodase 
- baixa o python 3.12 pela microsoft store, se vc n usa windows entao pau no seu cu, pesquisa

- agora instale as libs do python com o comando:
        
        pip install mkdocs mkdocs-material

- clona a porra do repositorio
    git clone git@github.com:nerdolagens/SK-RPG-docs.git

se deu erro ao clonar o repositorio o por que voce e burro e nao sabe configurar git e SSh, mete o erro do console no gpt e se vira

se tudo deu certo ate aqui parabens! voce tem o repositorio local do projeto e tudo que precisa pra comecar a trabalhar sem ser remunerado, suba suas alteracoes diretamente pra branch main e nao se esqueca de atualizar seu repositorio local antes de comecar a escrever, se voce nao sabe fazer isso por que caralhos vc ta aqui?

LINK DO SITE: https://nerdolagens.github.io/SK-RPG-docs
