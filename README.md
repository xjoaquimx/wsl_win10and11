# wsl_win10and11
Passo a passo para instalação do WSL no Windows 10 e 11.

# Instalar Linux no Windows 10 com WSL + Python

## Informções importantes antes da instalação

Para atualizar para o WSL 2, você precisa estar executando o Windows 10. 

Para sistemas x64: Versão 1903 ou superiores, com o Build 18362 ou superiores.
Para sistemas ARM64: Versão 2004 ou superiores, com o Build 19041 ou superiores.
Os builds inferiores a 18362 não dão suporte a WSL 2. 
Use o Assistente do Windows Update para atualizar a sua versão do Windows.


Para ver sua Versão e Build do seu Windows:

Aperte Win+PauseBreak ou Win+PB no seu teclado,
Na parte de Especificações do Windows encontrará a Versão e a Build/Compilação do SO.

## 1) Instalar o WSL


https://docs.microsoft.com/pt-br/windows/wsl/install-manual

## 2) Instalar Ubuntu

Iniciar -> Microsoft Store: procurar Ubuntu

Definir um usuário e senha

## 3) Instalar o Windows Terminal

Iniciar -> Microsoft Store: procurar Windows Terminal

Botão drop down -> Configurações -> Inicialização -> Perfil padrão: Ubuntu

## 4) Testar terminal
```bash
cd ~
cd /mnt/c
ls
```

## 5) Instalar extensão Remote WSL no VS Code

Depois abra uma pasta no VS Code pelo terminal Linux
```bash
code .
```

## 6) Instalar Python
**Atenção: favor instalar a versão 14 do Node, conforme comando abaixo**
## Pelo site oficial

https://www.python.org/downloads/

## Pelo terminal Linux

```bash
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install python3
sudo apt-get install python3-pip
```
