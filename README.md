Author: Bárbara Ayres


Sumário 
- [1. Guia Linux](#1-guia-linux)
  - [1.1. Comando `pwd`](#11-comando-pwd)
    - [1.1.1. Exemplo de uso](#111-exemplo-de-uso)
  - [1.2. Comando `ls`](#12-comando-ls)
    - [1.2.1. Exemplo de uso](#121-exemplo-de-uso)
  - [1.3. Comando `cd`](#13-comando-cd)
    - [1.3.1. Exemplo de uso](#131-exemplo-de-uso)
  - [1.4. Comando `tree`](#14-comando-tree)
    - [1.4.1. Exemplo de uso](#141-exemplo-de-uso)
  - [1.5. Comando `find`](#15-comando-find)
    - [1.5.1. Exemplo de uso](#151-exemplo-de-uso)
  - [1.6. Comando `touch`](#16-comando-touch)
    - [1.6.1. Exemplo de uso](#161-exemplo-de-uso)
  - [1.7. Comando `cat`](#17-comando-cat)
    - [1.7.1. Exemplo de uso](#171-exemplo-de-uso)
  - [1.8. Comando `less e more`](#18-comando-less-e-more)
    - [1.8.1. Exemplo de uso](#181-exemplo-de-uso)
  - [1.9. Comando `head e tail`](#19-comando-head-e-tail)
    - [1.9.1. Exemplo de uso](#191-exemplo-de-uso)
  - [1.10. Comando `nano`](#110-comando-nano)
    - [1.10.1. Exemplo de uso](#1101-exemplo-de-uso)
  - [1.11. Comando `vim`](#111-comando-vim)
    - [1.11.1. Exemplo de uso](#1111-exemplo-de-uso)
  - [1.12. Comando `cp`](#112-comando-cp)
    - [1.12.1. Exemplo de uso](#1121-exemplo-de-uso)
  - [1.13. Comando `mv`](#113-comando-mv)
    - [1.13.1. Exemplo de uso](#1131-exemplo-de-uso)
  - [1.14. Comando `rm`](#114-comando-rm)
    - [1.14.1. Exemplo de uso](#1141-exemplo-de-uso)
  - [1.15. Comando `mkdir`](#115-comando-mkdir)
    - [1.15.1. Exemplo de uso](#1151-exemplo-de-uso)
  - [1.16. Comando `rmdir`](#116-comando-rmdir)
    - [1.16.1. Exemplo de uso](#1161-exemplo-de-uso)
  - [1.17. Comando `chmod`](#117-comando-chmod)
    - [1.17.1. Exemplo de uso](#1171-exemplo-de-uso)
  - [1.18. Comando `chown`](#118-comando-chown)
    - [1.18.1. Exemplo de uso](#1181-exemplo-de-uso)
  - [1.19. Comando `whoami`](#119-comando-whoami)
    - [1.19.1. Exemplo de uso](#1191-exemplo-de-uso)
  - [1.20. Comando `id`](#120-comando-id)
    - [1.20.1. Exemplo de uso](#1201-exemplo-de-uso)
  - [1.21. Comando `su`](#121-comando-su)
    - [1.21.1. Exemplo de uso](#1211-exemplo-de-uso)
  - [1.22. Comando `sudo`](#122-comando-sudo)
    - [1.22.1. Exemplo de uso](#1221-exemplo-de-uso)
  - [1.23. Comando `passwd`](#123-comando-passwd)
    - [1.23.1. Exemplo de uso](#1231-exemplo-de-uso)
  - [1.24. Comando `ps`](#124-comando-ps)
    - [1.24.1. Exemplo de uso](#1241-exemplo-de-uso)
  - [1.25. Comando `top e htop`](#125-comando-top-e-htop)
    - [1.25.1. Exemplo de uso](#1251-exemplo-de-uso)
  - [1.26. Comando `kill e killall`](#126-comando-kill-e-killall)
    - [1.26.1. Exemplo de uso](#1261-exemplo-de-uso)
  - [1.27. Comando `uptime`](#127-comando-uptime)
    - [1.27.1. Exemplo de uso](#1271-exemplo-de-uso)
  - [1.28. Comando `df`](#128-comando-df)
    - [1.28.1. Exemplo de uso](#1281-exemplo-de-uso)
  - [1.29. Comando `du`](#129-comando-du)
    - [1.29.1. Exemplo de uso](#1291-exemplo-de-uso)
  - [1.30. Comando `free -h`](#130-comando-free--h)
    - [1.30.1. Exemplo de uso](#1301-exemplo-de-uso)
  - [1.31. Comando `uname -a`](#131-comando-uname--a)
    - [1.31.1. Exemplo de uso](#1311-exemplo-de-uso)
  - [1.32. Comando `hostname`](#132-comando-hostname)
    - [1.32.1. Exemplo de uso](#1321-exemplo-de-uso)
  - [1.33. Comando `grep`](#133-comando-grep)
    - [1.33.1. Exemplo de uso](#1331-exemplo-de-uso)
  - [1.34. Comando `timedatectl`](#134-comando-timedatectl)
    - [1.34.1. Exemplo de uso](#1341-exemplo-de-uso)
  - [1.35. Comando `sysctl`](#135-comando-sysctl)
    - [1.35.1. Exemplo de uso](#1351-exemplo-de-uso)
  - [1.36. Comando `ping`](#136-comando-ping)
    - [1.36.1. Exemplo de uso](#1361-exemplo-de-uso)
  - [1.37. Comando `curl`](#137-comando-curl)
    - [1.37.1. Exemplo de uso](#1371-exemplo-de-uso)
  - [1.38. Comando `wget`](#138-comando-wget)
    - [1.38.1. Exemplo de uso](#1381-exemplo-de-uso)
  - [1.39. Comando `scp`](#139-comando-scp)
    - [1.39.1. Exemplo de uso](#1391-exemplo-de-uso)
  - [1.40. Comando `ssh`](#140-comando-ssh)
    - [1.40.1. Exemplo de uso](#1401-exemplo-de-uso)
  - [1.41. Comando `netstat`](#141-comando-netstat)
    - [1.41.1. Exemplo de uso](#1411-exemplo-de-uso)
  - [1.42. Comando `ss`](#142-comando-ss)
    - [1.42.1. Exemplo de uso](#1421-exemplo-de-uso)
  - [1.43. Comando `ip a`](#143-comando-ip-a)
    - [1.43.1. Exemplo de uso](#1431-exemplo-de-uso)
  - [1.44. Comando `systemctl`](#144-comando-systemctl)
    - [1.44.1. Exemplo de uso](#1441-exemplo-de-uso)
  - [1.45. Comando `locate`](#145-comando-locate)
    - [1.45.1. Exemplo de uso](#1451-exemplo-de-uso)
  - [1.46. Comando `which e whereis`](#146-comando-which-e-whereis)
    - [1.46.1. Exemplo de uso](#1461-exemplo-de-uso)
  - [1.47. Comando `sort`](#147-comando-sort)
    - [1.47.1. Exemplo de uso](#1471-exemplo-de-uso)
  - [1.48. Comando `uniq`](#148-comando-uniq)
    - [1.48.1. Exemplo de uso](#1481-exemplo-de-uso)
  - [1.49. Comando `wc`](#149-comando-wc)
    - [1.49.1. Exemplo de uso](#1491-exemplo-de-uso)
  - [1.50. Comando `tar`](#150-comando-tar)
    - [1.50.1. Exemplo de uso](#1501-exemplo-de-uso)
  - [1.51. Comando `zip e unzip`](#151-comando-zip-e-unzip)
    - [1.51.1. Exemplo de uso](#1511-exemplo-de-uso)
- [2. Atalhos de Terminal Úteis](#2-atalhos-de-terminal-úteis)

# 1. Guia Linux

Este guia tem como objetivo apresentar exemplos práticos dos principais comandos Linux. Cada comando contém uma breve descrição e um exemplo de uso.

## 1.1. Comando `pwd`

```bash
Mostra o diretório atual absoluto (caminho completo desde a raiz).
```

### 1.1.1. Exemplo de uso

```bash
$ pwd
/home/barbara/Documentos

# Usar em scripts para saber o diretório de execução
DIR_ATUAL=$(pwd)
echo "Script executado de: $DIR_ATUAL"
```

## 1.2. Comando `ls`

```bash
Lista arquivos e diretórios. Sem opções, mostra apenas nomes..
```

### 1.2.1. Exemplo de uso

```bash
# Listagem simples
$ ls
documentos  imagens  musica  videos

# Listagem detalhada
$ ls -l
total 16
drwxr-xr-x 2 usuario usuario 4096 Set 22 10:30 documentos
drwxr-xr-x 2 usuario usuario 4096 Set 22 10:31 imagens
-rw-r--r-- 1 usuario usuario 1024 Set 22 10:32 arquivo.txt

# Listar com tamanhos legíveis
$ ls -lh
total 16K
drwxr-xr-x 2 usuario usuario 4,0K Set 22 10:30 documentos
-rw-r--r-- 1 usuario usuario 1,2M Set 22 10:32 video.mp4

# Listar ordenado por tamanho (maior primeiro)
$ ls -lS
```

## 1.3. Comando `cd`

```bash
Muda de diretório.
```

### 1.3.1. Exemplo de uso

```bash
# Ir para diretório home
$ cd ~
$ cd /home/usuario

# Voltar ao diretório anterior
$ cd -

# Ir para diretório raiz
$ cd /

# Navegação relativa
$ cd ../outrapasta
$ cd ../../nivelacima
```

## 1.4. Comando `tree`

```bash
Mostra a estrutura de diretórios em formato de árvore.
```

### 1.4.1. Exemplo de uso

```bash
# Instalar (Ubuntu/Debian)
$ sudo apt install tree

# Uso básico
$ tree
.
├── documentos
│   ├── trabalho
│   └── pessoal
├── imagens
│   └── ferias
└── musica

# Mostrar apenas 2 níveis de profundidade
$ tree -L 2

# Incluir arquivos ocultos
$ tree -a
```

## 1.5. Comando `find`

```bash
Busca arquivos e diretórios com critérios avançados.
```

### 1.5.1. Exemplo de uso

```bash
# Buscar por nome (case insensitive)
$ find /home -iname "*.txt"

# Buscar arquivos modificados nos últimos 7 dias
$ find /var/log -type f -mtime -7

# Buscar arquivos maiores que 10MB
$ find / -size +10M

# Executar comando nos arquivos encontrados
$ find . -name "*.tmp" -exec rm {} \;

# Buscar e mostrar detalhes
$ find . -type f -name "*.conf" -ls
```

## 1.6. Comando `touch`

```bash
Cria arquivo vazio.
```

### 1.6.1. Exemplo de uso

```bash
$ touch notas.txt
$ ls
notas.txt
```

## 1.7. Comando `cat`

```bash
Exibe, concatena ou cria arquivos.
```

### 1.7.1. Exemplo de uso

```bash
# Ver conteúdo
$ cat arquivo.txt

# Ver com numeração de linhas
$ cat -n script.sh

# Concatenar múltiplos arquivos
$ cat arquivo1.txt arquivo2.txt > combinado.txt

# Criar arquivo rápido
$ cat > novo_arquivo.txt
Texto digitado aqui
Ctrl+D para salvar
```

## 1.8. Comando `less e more`

```bash
Visualizadores de texto com paginação.
```

### 1.8.1. Exemplo de uso

```bash
# Less (mais recursos - pode voltar páginas)
$ less arquivo_grande.log
Comandos dentro do less:
- Espaço: próxima página
- b: página anterior
- /texto: buscar
- q: sair

# More (mais simples)
$ more arquivo.txt
```

## 1.9. Comando `head e tail`

```bash
Mostram início ou fim de arquivos.
```

### 1.9.1. Exemplo de uso

```bash
# Primeiras 10 linhas (padrão)
$ head arquivo.log

# Primeiras 20 linhas
$ head -n 20 arquivo.log

# Últimas 15 linhas
$ tail -n 15 arquivo.log

# Acompanhar arquivo em tempo real (log)
$ tail -f /var/log/syslog

# Mostrar a partir da linha 50
$ tail -n +50 arquivo.log
```

## 1.10. Comando `nano`

```bash
Editor de texto simples para terminal.
```

### 1.10.1. Exemplo de uso

```bash
# Abrir arquivo
$ nano arquivo.txt
```

## 1.11. Comando `vim`

```bash
Editor de texto avançado e poderoso.
```

### 1.11.1. Exemplo de uso

```bash
$ vim notas.txt
```

## 1.12. Comando `cp`

```bash
Copia arquivos e diretórios.
```

### 1.12.1. Exemplo de uso

```bash
# Copiar arquivo
$ cp origem destino

# Copiar com preservação de atributos
$ cp -p arquivo.txt backup/

# Copiar diretório recursivamente
$ cp -r diretorio/ backup/

# Copiar com confirmação
$ cp -i *.txt destino/

# Copiar mostrando progresso
$ cp -v arquivo grande.iso /backup/
```

## 1.13. Comando `mv`

```bash
Move ou renomeia arquivos e diretórios.
```

### 1.13.1. Exemplo de uso

```bash
# Renomear arquivo
$ mv nome_antigo.txt nome_novo.txt

# Mover para outro diretório
$ mv arquivo.txt /outro/diretorio/

# Mover múltiplos arquivos
$ mv *.jpg /home/usuario/imagens/

# Mover com backup em caso de sobrescrita
$ mv -b arquivo.txt destino/
```

## 1.14. Comando `rm`

```bash
Remove arquivos e diretórios.
```

### 1.14.1. Exemplo de uso

```bash
# Remover arquivo
$ rm arquivo.tmp

# Remover com confirmação
$ rm -i *.log

# Remover diretório vazio
$ rmdir diretorio

# Remover diretório recursivamente
$ rm -rf diretorio/

# Remover arquivos com padrão específico
$ find . -name "*.tmp" -exec rm {} \;
```

## 1.15. Comando `mkdir`

```bash
Cria novo diretório.
```

### 1.15.1. Exemplo de uso

```bash
# Criar diretório simples
$ mkdir novapasta

# Criar estrutura de diretórios
$ mkdir -p projetos/{src,bin,doc}

# Criar com permissões específicas
$ mkdir -m 755 diretorio_publico

# Criar múltiplos diretórios
$ mkdir dir1 dir2 dir3
```

## 1.16. Comando `rmdir`

```bash
Remove diretório vazio.
```

### 1.16.1. Exemplo de uso

```bash
$ rmdir imagens
```

## 1.17. Comando `chmod`

```bash
Altera permissões de arquivos e diretórios.
```

### 1.17.1. Exemplo de uso

```bash
# Permissões numéricas (octal)
# 0: ---     1: --x     2: -w-     3: -wx
# 4: r--     5: r-x     6: rw-     7: rwx

# Exemplos:
$ chmod 755 script.sh    # rwxr-xr-x
$ chmod 644 arquivo.txt  # rw-r--r--
$ chmod 700 diretorio/   # rwx------

# Permissões simbólicas
$ chmod u+x script.sh    # adiciona execução para dono
$ chmod go-w arquivo.txt # remove escrita grupo/outros
$ chmod a+r arquivo      # leitura para todos

# Recursivo em diretórios
$ chmod -R 755 public_html/
```

## 1.18. Comando `chown`

```bash
Altera o dono e grupo de arquivos/diretórios.
```

### 1.18.1. Exemplo de uso

```bash
# Mudar dono
$ sudo chown usuario arquivo.txt

# Mudar dono e grupo
$ sudo chown usuario:grupo arquivo.txt

# Mudar apenas grupo
$ sudo chown :www-data site/

# Recursivo
$ sudo chown -R usuario:usuario /home/usuario/
```

## 1.19. Comando `whoami`

```bash
Mostra o usuário atual.
```

### 1.19.1. Exemplo de uso

```bash
$ whoami
usuario
```

## 1.20. Comando `id`

```bash
Exibe UID, GID e grupos do usuário.
```

### 1.20.1. Exemplo de uso

```bash
$ id
uid=1000(usuario) gid=1000(usuario) groups=1000(usuario),27(sudo)
```

## 1.21. Comando `su`

```bash
Troca de usuário.
```

### 1.21.1. Exemplo de uso

```bash
$ su root
Senha:
# whoami
root
```

## 1.22. Comando `sudo`

```bash
Executa comandos com privilégios de superusuário(root).
```

### 1.22.1. Exemplo de uso

```bash
# Executar comando como root
$ sudo comando

# Editar arquivos de sistema
$ sudo nano /etc/hosts

# Tornar-se root temporariamente
$ sudo su -

# Listar privilégios sudo do usuário
$ sudo -l
```

## 1.23. Comando `passwd`

```bash
Altera a senha de um usuário
```

### 1.23.1. Exemplo de uso

```bash
# Alterar própria senha
$ passwd

# Alterar senha de outro usuário (root)
$ sudo passwd usuario

# Bloquear conta
$ sudo passwd -l usuario

# Desbloquear conta
$ sudo passwd -u usuario
```

## 1.24. Comando `ps`

```bash
Mostra processos em execução.
```

### 1.24.1. Exemplo de uso

```bash
# Processos do usuário atual
$ ps

# Todos os processos
$ ps aux

# Processos em formato de árvore
$ ps auxf

# Buscar processo específico
$ ps aux | grep apache

# Mostrar processos por uso de CPU
$ ps aux --sort=-%cpu

# Mostrar processos por uso de memória
$ ps aux --sort=-%mem
```

## 1.25. Comando `top e htop`

```bash
Monitores de processos em tempo real.
```

### 1.25.1. Exemplo de uso

```bash
# Top (nativo)
$ top
Comandos: q-sair, k-matar processo, M-ordenar memória

# Htop (mais amigável - instalar)
$ sudo apt install htop
$ htop
# Interface colorida, scroll horizontal, mais interativo
```

## 1.26. Comando `kill e killall`

```bash
Encerra processos.
```

### 1.26.1. Exemplo de uso

```bash
# Listar sinais
$ kill -l

# Encerramento gracioso (padrão)
$ kill 1234

# Forçar encerramento
$ kill -9 1234

# Encerrar por nome
$ killall firefox

# Encerrar processos do usuário
$ pkill -u usuario
```

## 1.27. Comando `uptime`

```bash
Mostra tempo ligado e carga do sistema.
```

### 1.27.1. Exemplo de uso

```bash
$ uptime
14:30:01 up 15 days,  3:25,  2 users,  load average: 0.15, 0.08, 0.05
# Load average: 1min, 5min, 15min (ideal < nº de CPUs)
```

## 1.28. Comando `df`

```bash
Espaço livre em discos.
```

### 1.28.1. Exemplo de uso

```bash
# Formato legível
$ df -h

# Mostrar tipo de sistema de arquivos
$ df -T

# Excluir sistemas específicos
$ df -h -x tmpfs -x devtmpfs

# Espaço inode
$ df -i
```

## 1.29. Comando `du`

```bash
Uso de disco por arquivos/diretórios.
```

### 1.29.1. Exemplo de uso

```bash
# Tamanho de diretório
$ du -sh /home/usuario

# Tamanho de todos os subdiretórios
$ du -h --max-depth=1 /var

# Ordenar por tamanho
$ du -h /var/* | sort -hr

# Excluir certos tipos
$ du -h --exclude="*.tmp" diretorio/
```

## 1.30. Comando `free -h`

```bash
Mostra uso de memória RAM.
```

### 1.30.1. Exemplo de uso

```bash
# Formato legível
$ free -h
              total    used    free    shared  buff/cache   available
Mem:           15G     4.2G    8.1G     123M        2.7G         10G

# Atualizar a cada 2 segundos
$ free -h -s 2
```

## 1.31. Comando `uname -a`

```bash
Exibe informações do kernel e sistema.
```

### 1.31.1. Exemplo de uso

```bash
$ uname -a
Linux pc01 5.15.0-105-generic #114-Ubuntu SMP x86_64 GNU/Linux
```

## 1.32. Comando `hostname`

```bash
Mostra ou define o nome da máquina.
```

### 1.32.1. Exemplo de uso

```bash
$ hostname
pc01
```

## 1.33. Comando `grep`

```bash
Busca padrões em texto usando expressões regulares.
```

### 1.33.1. Exemplo de uso

```bash
# Busca simples
$ grep "erro" arquivo.log

# Busca case insensitive
$ grep -i "error" sistema.log

# Busca recursiva em diretórios
$ grep -r "function" src/

# Mostrar linhas ao redor do match
$ grep -A 2 -B 2 "exceção" log.txt

# Buscar com expressão regular
$ grep "^[0-9]" arquivo.txt

# Contar ocorrências
$ grep -c "sucesso" relatorio.txt
```

## 1.34. Comando `timedatectl`

```bash
Controla data, hora e timezone do sistema.
```

### 1.34.1. Exemplo de uso

```bash
$ timedatectl
               Local time: Mon 2025-09-22 14:35:12 -03
           Universal time: Mon 2025-09-22 17:35:12 UTC
                 Time zone: America/Sao_Paulo (-03, -0300)
```

## 1.35. Comando `sysctl`

```bash
Exibe e altera parâmetros do kernel em tempo real.
```

### 1.35.1. Exemplo de uso

```bash
$ sysctl -a | grep net.ipv4.ip_forward
net.ipv4.ip_forward = 0

$ sudo sysctl -w net.ipv4.ip_forward=1
net.ipv4.ip_forward = 1
```

## 1.36. Comando `ping`

```bash
Testa a conectividade com outro host.
```

### 1.36.1. Exemplo de uso

```bash
# Ping simples
$ ping google.com

# Limitar número de pacotes
$ ping -c 4 8.8.8.8

# Definir intervalo entre pacotes
$ ping -i 2 exemplo.com

# Tamanho específico de pacote
$ ping -s 1024 destino.com

# Ping com timestamp
$ ping -D google.com
```

## 1.37. Comando `curl`

```bash
Faz requisições HTTP, útil para ver IP público.
```

### 1.37.1. Exemplo de uso

```bash
# Baixar arquivo
$ curl -O https://exemplo.com/arquivo.zip

# Ver cabeçalhos HTTP
$ curl -I https://google.com

# Enviar dados POST
$ curl -X POST -d "dados=valor" https://api.com

# Autenticação
$ curl -u usuario:senha https://api.com

# Ver IP público
$ curl ifconfig.me
```

## 1.38. Comando `wget`

```bash
Baixa arquivos da internet.
```

### 1.38.1. Exemplo de uso

```bash
# Download simples
$ wget https://exemplo.com/arquivo.iso

# Continuar download interrompido
$ wget -c url

# Download recursivo (site inteiro)
$ wget -r --level=1 https://site.com

# Limitar velocidade
$ wget --limit-rate=100k url

# Download em background
$ wget -b url
```

## 1.39. Comando `scp`

```bash
Copia arquivos via SSH.
```

### 1.39.1. Exemplo de uso

```bash
# Copiar arquivo local para remoto
$ scp arquivo.txt usuario@servidor:/caminho/

# Copiar remoto para local
$ scp usuario@servidor:/remoto/arquivo.txt ./local/

# Copiar diretório recursivo
$ scp -r pasta/ usuario@servidor:/destino/

# Preservar atributos
$ scp -p arquivo usuario@servidor:/destino/
```

## 1.40. Comando `ssh`

```bash
Conexão segura a servidores remotos.
```

### 1.40.1. Exemplo de uso

```bash
# Conexão básica
$ ssh usuario@servidor.com

# Conexão com porta específica
$ ssh -p 2222 usuario@servidor

# Executar comando remoto
$ ssh usuario@servidor "ls -la"

# Tunelamento SSH
$ ssh -L 8080:localhost:80 usuario@servidor

# Usar chave específica
$ ssh -i ~/.ssh/chave_privada usuario@servidor
```

## 1.41. Comando `netstat`

```bash
Estatísticas de rede e conexões.
```

### 1.41.1. Exemplo de uso

```bash
# Todas as conexões
$ netstat -a

# Conexões TCP
$ netstat -at

# Conexões UDP
$ netstat -au

# Portas escutando
$ netstat -tulnp

# Estatísticas de interface
$ netstat -i
```

## 1.42. Comando `ss`

```bash
Versão moderna do netstat.
```

### 1.42.1. Exemplo de uso

```bash
# Mais rápido que netstat
$ ss -tulnp

# Conexões estabelecidas
$ ss -t state established

# Mostrar processos
$ ss -tp

# Filtrar por porta
$ ss -t sport = :80
```

## 1.43. Comando `ip a`

```bash
Mostra interfaces de rede e endereços IP.
```

### 1.43.1. Exemplo de uso

```bash
$ ip a
2: enp0s3: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500
    inet 192.168.1.20/24 brd 192.168.1.255 scope global enp0s3
```

## 1.44. Comando `systemctl`

```bash
Controla serviços systemd.
```

### 1.44.1. Exemplo de uso

```bash
# Ver status do serviço
$ systemctl status apache2

# Iniciar serviço
$ sudo systemctl start servico

# Parar serviço
$ sudo systemctl stop servico

# Reiniciar serviço
$ sudo systemctl restart servico

# Habilitar inicialização automática
$ sudo systemctl enable servico

# Listar serviços
$ systemctl list-units --type=service
```

## 1.45. Comando `locate`

```bash
Busca rápida por nomes de arquivos.
```

### 1.45.1. Exemplo de uso

```bash
# Atualizar base de dados
$ sudo updatedb

# Busca simples
$ locate arquivo.txt

# Busca case insensitive
$ locate -i "DOCUMENTO"

# Limitar resultados
$ locate -n 20 "*.conf"
```

## 1.46. Comando `which e whereis`

```bash
Localizam comandos no sistema.
```

### 1.46.1. Exemplo de uso

```bash
# Which - mostra caminho do executável
$ which python
/usr/bin/python

# Whereis - mostra binário, source e man pages
$ whereis python
python: /usr/bin/python /usr/lib/python2.7 /usr/include/python2.7
```

## 1.47. Comando `sort`

```bash
Ordena linhas de texto.
```

### 1.47.1. Exemplo de uso

```bash
# Ordem alfabética
$ sort arquivo.txt

# Ordem reversa
$ sort -r arquivo.txt

# Ordem numérica
$ sort -n numeros.txt

# Remover duplicatas
$ sort -u arquivo.txt

# Ordenar por coluna específica
$ sort -k2,2 dados.txt
```

## 1.48. Comando `uniq`

```bash
Remove ou reporta linhas duplicadas.
```

### 1.48.1. Exemplo de uso

```bash
# Remover duplicatas (arquivo precisa estar ordenado)
$ sort arquivo.txt | uniq

# Mostrar apenas duplicatas
$ sort arquivo.txt | uniq -d

# Contar ocorrências
$ sort arquivo.txt | uniq -c
```

## 1.49. Comando `wc`

```bash
Conta linhas, palavras e caracteres.
```

### 1.49.1. Exemplo de uso

```bash
# Contagem completa
$ wc arquivo.txt
  linhas  palavras  caracteres  arquivo

# Apenas linhas
$ wc -l acesso.log

# Apenas palavras
$ wc -w documento.txt

# Apenas caracteres
$ wc -m texto.txt
```

## 1.50. Comando `tar`

```bash
Arquiva e compacta arquivos.
```

### 1.50.1. Exemplo de uso

```bash
# Criar arquivo tar
$ tar -cf arquivo.tar pasta/

# Extrair tar
$ tar -xf arquivo.tar

# Criar tar.gz (compactado)
$ tar -czf arquivo.tar.gz pasta/

# Extrair tar.gz
$ tar -xzf arquivo.tar.gz

# Listar conteúdo
$ tar -tf arquivo.tar
```

## 1.51. Comando `zip e unzip`

```bash
Compactação compatível com Windows.
```

### 1.51.1. Exemplo de uso

```bash
# Criar zip
$ zip -r arquivo.zip pasta/

# Extrair zip
$ unzip arquivo.zip

# Extrair para diretório específico
$ unzip arquivo.zip -d destino/

# Listar conteúdo
$ unzip -l arquivo.zip
```

# 2. Atalhos de Terminal Úteis

```bash
# Navegação e Edição
Ctrl + A            # Início da linha
Ctrl + E            # Fim da linha
Ctrl + U            # Limpar até início
Ctrl + K            # Limpar até fim
Ctrl + W            # Apagar palavra anterior
Ctrl + Y            # Colar texto cortado

# Controle de Processos
Ctrl + C            # Interromper processo
Ctrl + Z            # Suspender processo
Ctrl + D            # Fim de arquivo (logout)
Ctrl + L            # Limpar tela

# Histórico
Ctrl + R            # Busca reversa no histórico
!!                  # Repetir último comando
!abc                # Executar último comando começando com abc
```
