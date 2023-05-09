
# Comandos Git
![](https://media2.giphy.com/media/Qo2dupDib32rkTY4hX/giphy.gif?cid=ecf05e47ra1q9kaeylvc0bhabe9ppleh8syht0b46hly3qta&ep=v1_gifs_related&rid=giphy.gif&ct=s)
## Autores

- [@uelberbell](https://www.github.com/uelberbell)

<br>

Git é um sistema de controle de versão de código fonte amplamente utilizado para gerenciar projetos de software. Aqui estão alguns comandos básicos do Git que podem ajudá-lo a começar:

<br>

## Configuração do Git
- Configure o Git com suas informações pessoais antes de começar a trabalhar com ele:
```bash
    git config --global user.name "Seu Nome"
    git config --global user.email "seu-email@seu-email.com"
```
<br>

## Iniciando um repositório
- Para iniciar um novo repositório, execute o seguinte comando na pasta do projeto:
```bash
    git init
```

<br>

## Clonando um repositório
- Para clonar um repositório existente, execute o seguinte comando:
```bash
    git clone <url do repositório>
```
<br>

## Trabalhando com arquivos
- Para adicionar um arquivo ao índice do Git, execute o seguinte comando:
```bash
    git add <nome do arquivo>
```
- Para adicionar todos os arquivos modificados ao índice do Git, execute o seguinte comando:
```bash
    git add .
```
- Para confirmar as alterações e criar um novo commit, execute o seguinte comando:
```bash
    git commit -m "sua mensagem contendo informçãos sobre a modificação realizada"
```
<br>

## Ramificações
- Para criar uma nova ramificação, execute o seguinte comando:
```bash
    git branch <nome da ramificação>
```
- Para mudar para uma ramificação específica, execute o seguinte comando:
```bash
    git checkout <nome da ramificação>
```

<br>

## Fusão
- Para mesclar uma ramificação específica em sua ramificação atual, execute o seguinte comando:
```bash
    git merge <nome da ramificação>
```
<br>

## Envio de alterações para um repositório remoto
- Para enviar suas alterações para um repositório remoto, execute o seguinte comando:
```bash
    git push <nome do repositório remoto> <nome da ramificação>
```
<br>

## Recebendo alterações de um repositório remoto
- Para receber as alterações de um repositório remoto, execute o seguinte comando:
```bash
    git pull <nome do repositório remoto> <nome da ramificação>
```
<br>

## Verificando o estado do repositório
- Para verificar o status atual do seu repositório, execute o seguinte comando:
```bash
    git status
```
Isso mostrará quais arquivos foram modificados, quais arquivos estão no índice e prontos para serem confirmados em um novo commit e se há alguma ramificação pendente para ser mesclada.

<br>

## Visualizando o histórico de commits
- Para visualizar o histórico de commits do repositório, execute o seguinte comando:
```bash
    git log
```
Isso mostrará uma lista de todos os commits, incluindo as mensagens de commit, autores, datas e outras informações relevantes.

<br>

## Desfazendo alterações
- Para desfazer as alterações em um arquivo que ainda não foi confirmado em um commit, execute o seguinte comando:
```bash
    git checkout <nome do arquivo>
```
- Para desfazer um commit e reverter para um estado anterior do repositório, execute o seguinte comando:
```bash
    git revert <hash do commit>
```

<br>

## Ignorando arquivos
 - Para ignorar arquivos específicos, como arquivos temporários ou arquivos de configuração local, crie um arquivo chamado ".gitignore" na raiz do seu repositório e adicione o nome desses arquivos a ele.

<br>

## Conclusão
Esses são apenas alguns dos comandos mais comuns do Git que você pode usar para gerenciar seu projeto. Para saber mais sobre Git e como usá-lo de maneira mais avançada, consulte a documentação oficial do Git ou faça um curso de Git. Boa sorte com seus projetos!

<br>

## Feedback

Se você tiver algum feedback, por favor nos deixe saber por meio de uelberbell@gmail.com

