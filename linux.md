# Linux
## Users
| Command | Description |
| - | - |
| `sudo useradd <username>` | Create user |
| `sudo useradd -m <username>` | Create user and home directory |
| `sudo useradd -m -d /home/dir/path <username>` | Create user with specified home directory | 
| `sudo useradd -u <uid> <username>` | Create user with specified uid |

<!-- diff -u file1 file2 | vim - -->

<!---
Add user to group

sudo usermod -a -G groupname username

List groups a user is part of
groups

Prints information about user and it's groups
id

To get all groups look at
/etc/group 

Get all users from a group
getent group groupname

bash -n < verify syntax
bash -x < show every command executed
bash -v < show line being executed 

set -x turns on show every command
set +x turns off show every command
trap read DEBUG < executes line by line, waiting for user input
trap "" DEBUG < turns of the wait for user input

função para mostrar mensagem de debug
# TODO Make a colourful one M
# TODO Make color be optional
Debug() {
	["$DEBUG" = 1] && echo "$*"
}

Add debug level
0,1,2,3...
Debug() {
	[$1 -le "$DEBUG"] && echo "$*"
}
■ Gravar as mensagens em um arquivo para ser analisado posteriormente.
■ Usar uma cor diferente para cada nível (muito útil!).
■ Mudar o alinhamento da mensagem, deslocando o texto mais à direita quanto
maior for seu nível.
■ Fazer um pré-processamento que verifica outras condições, além do valor de
$DEBUG para decidir se mostra a mensagem ou não.
Não quero estragar sua diversão nem podar sua criatividade, então segue

Debug(){
    [ $1 -le $DEBUG ] || return
    local prefixo
    case "$1" in
         1) prefixo="-- ";;
        2) prefixo="---- ";;
        3) prefixo="------ ";;
        *) echo "Mensagem não categorizada: $*"; return;;
esac
shift
echo $prefixo$*
}
--->

