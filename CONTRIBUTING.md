# Guia de Contribuição para o IA Codebase Vortex

Primeiramente, obrigado pelo seu interesse em contribuir para o IA Codebase Vortex! 🎉 A sua ajuda é fundamental para tornar este um recurso cada vez mais completo e valioso para a comunidade.

Este documento fornece um conjunto de diretrizes para contribuir com este projeto. Por favor, reserve um momento para revisá-lo antes de iniciar sua contribuição.

## Sumário

- [Código de Conduta](#código-de-conduta)
- [Como Posso Contribuir?](#como-posso-contribuir)
  - [Reportando Bugs](#reportando-bugs)
  - [Sugerindo Melhorias ou Novas Seções](#sugerindo-melhorias-ou-novas-seções)
  - [Fazendo Contribuições de Conteúdo ou Código](#fazendo-contribuições-de-conteúdo-ou-código)
- [Guia de Estilo](#guia-de-estilo)
  - [Estilo de Markdown](#estilo-de-markdown)
  - [Estilo de Código Python](#estilo-de-código-python)
  - [Mensagens de Commit do Git](#mensagens-de-commit-do-git)
- [Configurando seu Ambiente de Desenvolvimento](#configurando-seu-ambiente-de-desenvolvimento) (Opcional, se for rodar exemplos)
- [Submetendo um Pull Request (PR)](#submetendo-um-pull-request-pr)
- [Questões ou Dúvidas?](#questões-ou-dúvidas)

## Código de Conduta

Este projeto e todos os participantes dele são regidos pelo [Código de Conduta](CODE_OF_CONDUCT.md). Ao participar, espera-se que você siga este código. Por favor, reporte comportamentos inaceitáveis para [Luferath via Issues no GitHub ou contato@vortexhub.tec.br].

## Como Posso Contribuir?

Existem várias maneiras de contribuir, desde reportar um erro de digitação até adicionar uma seção inteira sobre uma nova tecnologia.

### Reportando Bugs

Se você encontrar um bug no conteúdo (ex: informação incorreta, link quebrado, exemplo de código que não funciona, erro de digitação), por favor, abra uma "Issue" no GitHub do projeto `iacodebase-vortex`.
Ao reportar um bug, por favor, inclua:

- Uma descrição clara e concisa do que é o bug.
- Passos para reproduzir o comportamento (se aplicável, ex: para um código).
- O que você esperava que acontecesse.
- O que realmente aconteceu (incluindo mensagens de erro, se houver).
- A localização exata do problema no repositório (link para o arquivo e linha, se possível).

### Sugerindo Melhorias ou Novas Seções

Se você tem ideias para melhorar o conteúdo existente ou sugestões para novas seções, ferramentas ou tópicos que deveriam ser cobertos:

- Verifique se já não existe uma "Issue" aberta sobre o mesmo assunto no [Issues do iacodebase-vortex](https://github.com/Luferath/iacodebase-vortex/issues).
- Se não houver, abra uma nova "Issue" descrevendo sua sugestão.
- Explique por que essa melhoria/adição seria útil para o repositório.
- Seja o mais específico possível.

### Fazendo Contribuições de Conteúdo ou Código

Agradecemos contribuições diretas ao conteúdo e aos exemplos de código!

1.  **Encontre algo para trabalhar:**
    *   Você pode começar por "Issues" abertas no [Issues do iacodebase-vortex](https://github.com/Luferath/iacodebase-vortex/issues), especialmente aquelas marcadas como `good first issue` ou `help wanted`.
    *   Você pode propor suas próprias adições de conteúdo, conforme descrito na seção anterior.

2.  **Fork o repositório:** Clique no botão "Fork" no canto superior direito da página do [iacodebase-vortex no GitHub](https://github.com/Luferath/iacodebase-vortex). Isso criará uma cópia do projeto na sua conta.

3.  **Clone seu fork localmente:**
    ```bash
    git clone https://github.com/SEU_USUARIO/iacodebase-vortex.git
    cd iacodebase-vortex
    ```
    *(Substitua `SEU_USUARIO` pelo seu nome de usuário do GitHub)*

4.  **Crie uma nova branch para suas modificações:**
    ```bash
    git checkout -b nome-da-sua-feature-ou-correcao
    ```
    (ex: `git checkout -b adiciona-doc-fastapi` ou `git checkout -b corrige-typo-readme`)

5.  **Faça suas alterações:**
    *   Adicione ou edite arquivos Markdown.
    *   Adicione ou corrija exemplos de código Python.
    *   Siga o [Guia de Estilo](#guia-de-estilo).

6.  **Adicione e commite suas alterações:**
    *   Use `git add .` para adicionar os arquivos modificados.
    *   Use `git commit -m "Sua mensagem de commit descritiva"` (veja [Mensagens de Commit do Git](#mensagens-de-commit-do-git)).

7.  **Envie suas alterações para o seu fork no GitHub:**
    ```bash
    git push origin nome-da-sua-feature-ou-correcao
    ```

8.  **Abra um Pull Request (PR):**
    *   Vá para a página do repositório original [Luferath/iacodebase-vortex](https://github.com/Luferath/iacodebase-vortex).
    *   Você verá uma mensagem sugerindo a criação de um Pull Request a partir da sua branch recém-enviada. Clique nela.
    *   Alternativamente, vá para a aba "Pull requests" e clique em "New pull request".
    *   Certifique-se de que a branch base é a `main` do repositório `Luferath/iacodebase-vortex` e a branch de comparação é a sua.
    *   Dê um título claro e uma descrição detalhada para seu PR. Explique o *quê* e o *porquê* das suas alterações. Se estiver relacionado a uma "Issue", mencione o número da Issue (ex: "Closes #123").

## Guia de Estilo

### Estilo de Markdown

- Utilize Markdown padrão do GitHub.
- Siga a estrutura e o estilo de formatação já existentes nos arquivos do repositório.
- Para seções de documentação de funções/bibliotecas, tente seguir o formato sugerido no `README.md`:
    - Nome da Função/Conceito/Biblioteca
    - Breve Descrição
    - Parâmetros Principais (se aplicável)
    - Retorno (se aplicável)
    - Exemplo(s) de Código
    - Casos de Uso Comuns
    - Vantagens e Desvantagens/Limitações
    - Referências
- Use linters de Markdown como [markdownlint](https://github.com/DavidAnson/markdownlint) se possível para manter a consistência.

### Estilo de Código Python

- Siga o [PEP 8 -- Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/).
- Use formatadores de código como [Black](https://github.com/psf/black) e linters como [Flake8](https://flake8.pycqa.org/en/latest/) ou [Pylint](https://www.pylint.org/) para manter a consistência do código.
- Inclua docstrings claras para funções e classes.
- Comente o código onde for necessário para explicar lógicas complexas.
- Os exemplos de código devem ser o mais autocontidos e funcionais possível.

### Mensagens de Commit do Git

- Use mensagens de commit claras e concisas.
- O formato preferencial é o [Conventional Commits](https://www.conventionalcommits.org/). Exemplo:
    - `feat: Adiciona documentação para a biblioteca Seaborn`
    - `fix: Corrige link quebrado na seção de NumPy`
    - `docs: Melhora a clareza na introdução sobre Deep Learning`
- Opcionalmente, se for uma mudança pequena, um commit simples como "Corrige erro de digitação em X" é aceitável.

## Configurando seu Ambiente de Desenvolvimento

*(Esta seção é mais relevante se você for rodar ou testar exemplos de código. Para contribuições puramente textuais em Markdown, pode não ser estritamente necessário, mas é bom ter.)*

Recomendamos o uso de ambientes virtuais para gerenciar as dependências do projeto.

1.  **Tenha Python instalado** (versão 3.7 ou superior recomendada).
2.  **Crie e ative um ambiente virtual:**

    Usando `venv` (padrão do Python):
    ```bash
    python3 -m venv .venv  # Ou apenas python -m venv .venv
    source .venv/bin/activate  # No Linux/macOS
    # .venv\Scripts\activate  # No Windows
    ```

    Usando `conda`:
    ```bash
    # Se você criar um arquivo environment.yml no futuro:
    # conda env create -f environment.yml
    # conda activate iacodebase-vortex
    # Ou crie um novo:
    conda create -n iacodebase-vortex python=3.9 # Ajuste a versão conforme necessidade
    conda activate iacodebase-vortex
    ```
3.  **Instale as dependências:**
    ```bash
    # Se você criar um requirements.txt no futuro:
    # pip install -r requirements.txt
    # Ou instale as bibliotecas específicas que você precisa para seus exemplos
    # pip install numpy pandas matplotlib ...
    ```
4.  **(Opcional) Instale ferramentas de desenvolvimento:**
    ```bash
    pip install black flake8 pytest markdownlint-cli # Exemplo
    ```

## Submetendo um Pull Request (PR)

1.  Após enviar suas alterações para seu fork, vá até a página do repositório original [Luferath/iacodebase-vortex](https://github.com/Luferath/iacodebase-vortex).
2.  Clique em "New pull request".
3.  Selecione a branch do seu fork que contém suas alterações (`nome-da-sua-feature-ou-correcao`) e a branch `main` do repositório `Luferath/iacodebase-vortex` como base.
4.  Preencha o título e a descrição do PR:
    - **Título:** Conciso e descritivo (ex: "Adiciona documentação para Plotly" ou "Corrige exemplos em NumPy").
    - **Descrição:** Detalhe as alterações feitas. Explique o *porquê* das mudanças. Se o PR resolve uma "Issue" existente, referencie-a usando `Closes #NUMERO_DA_ISSUE`.
5.  Se o seu PR ainda for um trabalho em progresso, você pode marcá-lo como "Draft" (Rascunho).
6.  Aguarde a revisão do seu PR. Esteja receptivo ao feedback!
7.  Assim que seu PR for aprovado, ele será mesclado ao repositório principal. Parabéns e obrigado!

## Questões ou Dúvidas?

Se você tiver dúvidas sobre como contribuir, ou sobre algum aspecto do projeto, sinta-se à vontade para:

- Abrir uma "Issue" no GitHub do [iacodebase-vortex](https://github.com/Luferath/iacodebase-vortex/issues) com sua pergunta.
- [Adicione outros canais de comunicação se desejar, ex: e-mail direto se preferir para certas questões]

Agradecemos novamente por sua contribuição!
