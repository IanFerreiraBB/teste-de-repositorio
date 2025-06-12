".md" --> Extensão 'markdown' (linguagem de marcação mais simplificada)
Digitar "." na página do repositório do GitHub para abrir o editor web do VSCode
Digitar "!" e dar Enter em arquivo .html para preencher automaticamente estrutura básica de documento HTML

<h1>Sistema de cadastro de jogos</h1>

> Status do projeto: Em desenvolvimento

Para rodar este projeto em sua máquina, digite:

```
node app.js
```

<h3>Comandos Git:</h3>

```git clone <URL>```: Este comando é usado para copiar um repositório remoto (como um no GitHub) para a sua máquina local. Ele baixa todos os arquivos, o histórico de commits e branches do projeto.

```cd <nome_do_diretório>```: Este comando não é específico do Git, mas é fundamental para navegar entre diretórios no seu terminal. Usamos cd para entrar na pasta do repositório que clonamos.

```ls```: Assim como o cd, este é um comando do sistema operacional que lista todos os arquivos e pastas dentro do diretório atual. É útil para verificar se o clone foi bem-sucedido e ver os arquivos do projeto.

```git log```: Este comando mostra o histórico de commits do repositório. Ele exibe informações como o autor, a data e a mensagem de cada commit.

```git log --oneline```: Uma versão mais compacta do git log, que mostra o histórico de commits em uma única linha por commit, incluindo um código de identificação e a mensagem do commit.

```git pull```: Este comando é usado para atualizar o seu repositório local com as últimas alterações feitas no repositório remoto (origem). Ele "puxa" as mudanças do repositório remoto para o seu repositório local.

```git status```: Este comando mostra o estado do seu repositório local, indicando quais arquivos foram modificados, adicionados ou removidos, e se há alguma alteração que ainda não foi commitada.

```git commit```: Este comando é usado para salvar as alterações feitas em seus arquivos no histórico do repositório local. É importante adicionar uma mensagem descritiva ao commit para que você e outros colaboradores possam entender as mudanças feitas.

```git push origin main```: Este comando envia os commits do seu repositório local para o repositório remoto (origem), na branch principal (main). Isso torna suas alterações visíveis para outros colaboradores e as salva no repositório remoto.
Lembre-se que o git push pode exigir configuração de chaves SSH para autenticação com o GitHub, garantindo que você tenha permissão para enviar as alterações para o repositório remoto.

```git restore --source <hashCode> app.js```: Este comando restaurará o arquivo app.js para a versão presente no commit com o hash definido.

```git restore --source <hashCode> .```: Este comando restaurará todos os arquivos modificados para a versão presente no commit com o hash definido.

O comando git add é usado para adicionar arquivos ao índice (staging area) do Git, preparando-os para serem incluídos no próximo commit.

Como usar:

```git add <nome_do_arquivo>```: Adiciona um arquivo específico. Ex: git add contato.html

```git add .```: Adiciona todos os arquivos modificados e novos no diretório atual e subdiretórios.
