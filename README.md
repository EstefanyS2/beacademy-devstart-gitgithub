Git e github

Projeto criado para instruir os alunos do programa devstart, quanto a utilização do git e github. Utilizaremos este repositório para salvar dicas e comandos úteis do git e também da plataforma github.



# Configuração inicial do Git:

- Git config --global user.name
   'NOME'(configura usuário)
- Git config --global user.email
   'EMAIL'(Configuração de email)

# Funcionalidades/repositório básicos do Git

- Git init: Inicia um repositório;
- Git status: Vizualiza os ststus dos repositório de versionamento;
- Git add: Incluir atualizações a um arquivo especifico no próximo commit;
- Git rm --cached: Remove arquivos rastreados do indice do Git;
- Git log: exibe o histórico de seus commits;
- Git stash: Salva alterações sem commit;
- Git stash pop: Restaura alterações salvas;
- Git stash pop stash@{1}: Aplica stash especifica;
- Git revert: Faz alterações no histórico de commits do repositório;
- Git commit -m: Faz captura de tela no diretório;

# Ramificações:

- Git branch: Realiza a exibição de todas as branch que temos, incluse faz a marcação da branch que esta sendo utilizada no momento.
- Git branch nome_da_branch: Possibilita criar um nome para branch;
- Git checkout: Navegar entre as branch existentes;
- Git checkout -b: nome_da_branch: Além de criar uma nova branch, já acessa a branch que acabou de criar:
- Git branch -d nome_da_branch: Remove uma branch;
- Git merge nome_da_branch: Usado para colocar uma branch dentro de outra branch;
