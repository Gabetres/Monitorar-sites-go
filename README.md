# Monitoramento de Sites


Este é um programa simples em Go que permite monitorar sites e registrar logs de seu status de disponibilidade. Ele oferece as seguintes funcionalidades:

- Iniciar o monitoramento de sites.
- Exibir logs do monitoramento anterior.
- Sair do programa.

## Pré-requisitos

Antes de usar o programa, verifique se você tem o Go instalado em seu sistema. Você pode baixar e instalar o Go em [golang.org](https://golang.org/dl/).

## Como usar

1. Clone ou baixe o repositório para o seu computador.
2. Certifique-se de que o arquivo "sites.txt" está no mesmo diretório do programa. Este arquivo deve conter a lista de sites que você deseja monitorar, um por linha.
3. Abra um terminal e navegue até o diretório onde o programa está localizado.
4. Execute o programa com o comando `go run monitorar.go`.

## Funcionalidades

### 1. Iniciar monitoramento

Esta opção permite iniciar o monitoramento dos sites listados no arquivo "sites.txt". O programa fará solicitações HTTP aos sites e registrará logs indicando se o site está online ou com problemas.

### 2. Exibir logs

Esta opção permite exibir os logs do monitoramento anterior. Os logs são registrados no arquivo "log.txt" e incluem informações sobre o status de cada site e o horário em que foram verificados.

### 0. Sair do programa

Esta opção encerra o programa.


## Autor

Este programa foi desenvolvido por [Gabriel Tres](https://github.com/Gabetres) para fins de estudos disponibilizado pela [Alura](https://www.alura.com.br/) e está na versão 1.5.

# Website Monitoring

This is a simple Go program that allows you to monitor websites and record logs of their availability status. It provides the following features:

- Start monitoring websites.
- Display logs from previous monitoring sessions.
- Exit the program.

## Prerequisites

Before using the program, make sure you have Go installed on your system. You can download and install Go from [golang.org](https://golang.org/dl/).

## How to Use

1. Clone or download the repository to your computer.
2. Ensure that the "sites.txt" file is in the same directory as the program. This file should contain the list of websites you want to monitor, one per line.
3. Open a terminal and navigate to the directory where the program is located.
4. Run the program with the command `go run monitorar.go`.

## Features

### 1. Start Monitoring

This option allows you to start monitoring the websites listed in the "sites.txt" file. The program will make HTTP requests to the sites and record logs indicating whether the site is online or experiencing issues.

### 2. Display Logs

This option allows you to display logs from previous monitoring sessions. The logs are recorded in the "log.txt" file and include information about the status of each site and the time they were checked.

### 0. Exit the Program

This option exits the program.

## Author

This program was developed by [Gabriel Tres](https://github.com/Gabetres) for educational purposes and is made available by [Alura](https://www.alura.com.br/). It is currently in version 1.5.

