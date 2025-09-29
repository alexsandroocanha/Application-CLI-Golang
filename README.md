<h1 align="center">Aplicação CLI em Go</h1>
<p align="center"> <i>Identificar e mostrar endereço IPs publico e DNS de sites</i></p>

## Visão Geral

```
Objetivo: Esta aplicação foi desenvolvida em meus estudos de aprofundamento
em Go (Golang). Ela é uma aplicação simples de CLI (Comand-Line Interface),
com a funcionalidade de achar e identificar IPs Publicos e DNS(Domain Name
Sistem) de sites.
``` 
**Repositório criado 23/09/2025**


## Requisitos 
* _Ter o compilador do Go instalado no pc (para compilar/rodar via go run)_
* _Para testes rápidos no Windows, há um executável pronto_

## Informações adicionais
> * Caso queira apenas baixar e testar a aplicação, sujiro baixar o arquivo "aplicacao.exe", pois ela é apenas um executavel e não necessitará de ter o compilador do Go
> * Após baixar o executavel do app, avance para o topico de "..."

# Maneira de executar
Se você baixou o repositorio como um todo, e viu como o codigo esta estruturado e queira executar no momento, você tera duas opções, compilar o codigo ou rodar sem compilar

## Compilando o codigo
Para compilar o codigo, você abrira o terminal dentro da pasta em que o arquivo "main.go" se encontra, e logo após executara o comando
```golang
go build
```
Caso queira apenas iniciar a aplicação sem precisar de compilar, execute o comando
```golang
go run main.go
```
## Rodando a Aplicação / Comandos
Para rodar a aplicação e usar de fato ela, você precisara abrir o terminal dentro do arquivo "linha-de-comando.exe"

Este primeiro comando serve para identificar o Endereço ip Publico do site, caso queira consultar um endereço especifico, só precisa subistituir o "google.com"
```bash
No windows:
.\linha-de-comando.exe ip --host google.com

No linux:
./linha-de-comando.exe ip --host google.com
```

Este segundo comando serve para identificar o Servidor DNS do site, caso queira consultar um endereço especifico, só precisa subistituir o "google.com"
```bash
No windows:
.\linha-de-comando.exe servidores --host google.com

No linux:
./linha-de-comando.exe servidores --host google.com
```

### Considerações Finais
Este é um app simples criado para consolidar meu aprendizado em Go. Se ele foi útil para você, já valeu a pena.

Tem sugestões, críticas ou encontrou um bug?
> * Abra uma issue no repositório (preferível)
> * Envie um PR com melhorias
> * Ou me escreva por e-mail (abaixo)


### Informações para Contato

[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alexsandro-ocanha-rodrigues-77149a35b/)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/alexsandro.pcap/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:alexsandroocanha@gmail.com)
