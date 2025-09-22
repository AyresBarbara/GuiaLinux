---
Author: Bárbara Ayres
---

Sumário - [1. Guia Linux](#1-guia-linux)
  - [1.1. Comando `pwd`](#11-comando-pwd)
    - [1.1.1. Exemplo de uso](#111-exemplo-de-uso)
  - [1.2. Comando `ls`](#12-comando-ls)
    - [1.2.1. Exemplo de uso](#121-exemplo-de-uso)
  - [1.3. Comando `ls-l`](#13-comando-ls-l)
    - [1.3.1. Exemplo de uso](#131-exemplo-de-uso)
  - [1.4. Comando `ls-a`](#14-comando-ls-a)
    - [1.4.1. Exemplo de uso](#141-exemplo-de-uso)
  - [1.5. Comando `cd`](#15-comando-cd)
    - [1.5.1. Exemplo de uso](#151-exemplo-de-uso)
  - [1.6. Comando `cd ..`](#16-comando-cd-)
    - [1.6.1. Exemplo de uso](#161-exemplo-de-uso)
  - [1.7. Comando `tree`](#17-comando-tree)
    - [1.7.1. Exemplo de uso](#171-exemplo-de-uso)
  - [1.8. Comando `find`](#18-comando-find)
    - [1.8.1. Exemplo de uso](#181-exemplo-de-uso)
  - [1.9. Comando `touch`](#19-comando-touch)
    - [1.9.1. Exemplo de uso](#191-exemplo-de-uso)
  - [1.10. Comando `cat`](#110-comando-cat)
    - [1.10.1. Exemplo de uso](#1101-exemplo-de-uso)
  - [1.11. Comando `less`](#111-comando-less)
    - [1.11.1. Exemplo de uso](#1111-exemplo-de-uso)
  - [1.12. Comando `head`](#112-comando-head)
    - [1.12.1. Exemplo de uso](#1121-exemplo-de-uso)
  - [1.13. Comando `tail`](#113-comando-tail)
    - [1.13.1. Exemplo de uso](#1131-exemplo-de-uso)
  - [1.14. Comando `nano`](#114-comando-nano)
    - [1.14.1. Exemplo de uso](#1141-exemplo-de-uso)
  - [1.15. Comando `vim`](#115-comando-vim)
    - [1.15.1. Exemplo de uso](#1151-exemplo-de-uso)
  - [1.16. Comando `cp`](#116-comando-cp)
    - [1.16.1. Exemplo de uso](#1161-exemplo-de-uso)
  - [1.17. Comando `mv`](#117-comando-mv)
    - [1.17.1. Exemplo de uso](#1171-exemplo-de-uso)
  - [1.18. Comando `rm`](#118-comando-rm)
    - [1.18.1. Exemplo de uso](#1181-exemplo-de-uso)



# 1. Guia Linux

Este guia tem como objetivo apresentar exemplos práticos dos principais comandos Linux. Cada comando contém uma breve descrição e um exemplo de uso.

## 1.1. Comando `pwd`

```bash
Mostra o diretório atual
```

### 1.1.1. Exemplo de uso

```bash
$ pwd
/home/barbara/Documentos
```

## 1.2. Comando `ls`

```bash
Lista arquivos e pastas no diretório atual.
```

### 1.2.1. Exemplo de uso

```bash
$ ls
arquivo.txt   imagens   projetos   script.sh
```

## 1.3. Comando `ls-l`

```bash
Lista arquivos em formato detalhado (permissões, dono, tamanho, data).
```

### 1.3.1. Exemplo de uso

```bash
$ ls -l
-rw-r--r--  1 usuario usuario   1200 set 21 12:30 arquivo.txt
drwxr-xr-x  2 usuario usuario   4096 set 20 14:10 imagens
```

## 1.4. Comando `ls-a`

```bash
Lista todos os arquivos, incluindo ocultos (aqueles que começam com .).
```

### 1.4.1. Exemplo de uso

```bash
$ ls -a
.  ..  .bashrc  .gitignore  projeto  notas.txt
```

## 1.5. Comando `cd`

```bash
Muda de diretório.
```

### 1.5.1. Exemplo de uso

```bash
$ cd /etc
$ pwd
/etc
```

## 1.6. Comando `cd ..`

```bash
Volta um diretório.
```

### 1.6.1. Exemplo de uso

```bash
$ pwd
/home/usuario/Documentos
$ cd ..
$ pwd
/home/usuario
```

## 1.7. Comando `tree`

```bash
Mostra a estrutura de diretórios em formato de árvore.
```

### 1.7.1. Exemplo de uso

```bash
$ tree
.
├── imagens
│   ├── foto1.jpg
│   └── foto2.png
├── projetos
│   └── site
└── arquivo.txt
```

## 1.8. Comando `find`

```bash
Busca arquivos no sistema.
```

### 1.8.1. Exemplo de uso

```bash
$ find /home/usuario -name "arquivo.txt"
/home/usuario/Documentos/arquivo.txt
```

## 1.9. Comando `touch`

```bash
Cria arquivo vazio.
```

### 1.9.1. Exemplo de uso

```bash
$ touch notas.txt
$ ls
notas.txt
```

## 1.10. Comando `cat`

```bash
Mostra conteúdo de um arquivo.
```

### 1.10.1. Exemplo de uso

```bash
$ cat notas.txt
Lista de compras:
- Arroz
- Feijão
- Café
```

## 1.11. Comando `less`

```bash
Lê arquivos grandes com paginação.
```

### 1.11.1. Exemplo de uso

```bash
$ less /var/log/syslog
```

## 1.12. Comando `head`

```bash
Mostra as primeiras linhas de um arquivo.
```

### 1.12.1. Exemplo de uso

```bash
$ head -n 5 notas.txt
Lista de compras:
- Arroz
- Feijão
- Café
```

## 1.13. Comando `tail`

```bash
Mostra as últimas linhas de um arquivo.
```

### 1.13.1. Exemplo de uso

```bash
$ tail -n 3 notas.txt
- Feijão
- Café
- Açúcar
```

## 1.14. Comando `nano`

```bash
Editor de texto no terminal.
```

### 1.14.1. Exemplo de uso

```bash
$ nano notas.txt
```

## 1.15. Comando `vim`

```bash
Editor de texto avançado.
```

### 1.15.1. Exemplo de uso

```bash
$ vim notas.txt
```

## 1.16. Comando `cp`

```bash
Copia arquivos.
```

### 1.16.1. Exemplo de uso

```bash
$ cp notas.txt /home/usuario/Backup/
```

## 1.17. Comando `mv`

```bash
Move ou renomeia arquivos.
```

### 1.17.1. Exemplo de uso

```bash
$ mv notas.txt lista_compras.txt
```

## 1.18. Comando `rm`

```bash
Remove arquivos.
```

### 1.18.1. Exemplo de uso

```bash
$ rm lista_compras.txt
```
