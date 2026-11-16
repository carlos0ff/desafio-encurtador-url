# Encurtador de URLs

**Status: planejamento — implementação ainda não iniciada.**

Repositório de estudo de [José Carlos](https://github.com/carlos0ff), organizado a partir da [seleção de desafios de Matheus Leandro](https://www.matheusleandro.com.br/desafios).

## Objetivo

Construir um serviço para criar endereços curtos e redirecionar seus visitantes ao destino original.

## Escopo do desafio

- Receber o endereço original por `POST /shorten-url`.
- Gerar identificadores alfanuméricos com 5 a 10 caracteres.
- Persistir o destino e a expiração; definir e documentar a duração.
- Redirecionar acessos ao identificador cadastrado.
- Responder com HTTP 404 quando o identificador não existir.

O contrato usa o campo `url` na entrada e na resposta de criação, com HTTP 200. Os endpoints são requisitos previstos, ainda indisponíveis.

## Critérios de conclusão

- [ ] Criar a API e a persistência.
- [ ] Evitar colisões entre identificadores.
- [ ] Documentar o comportamento após a expiração e para entradas inválidas.
- [ ] Testar criação, redirecionamento, ausência e expiração.
- [ ] Acrescentar instruções reproduzíveis de execução.

## Tecnologia planejada

Java e Spring Boot, conforme a categoria da plataforma. Banco, versões e ferramenta de build serão definidos na implementação.

## Como executar

Este repositório contém apenas a documentação inicial. Ainda não há aplicação, scripts de execução ou testes executáveis. Os comandos serão adicionados junto com a implementação.

## Referências e créditos

- [Enunciado na plataforma](https://www.matheusleandro.com.br/desafios/crie-um-encurtador-de-urls)
- [Referência original indicada pela plataforma](https://github.com/backend-br/desafios/blob/master/url-shortener/PROBLEM.md)

Este README resume a proposta e registra um plano de trabalho. Os créditos do enunciado pertencem aos autores das referências; a solução será desenvolvida neste repositório.
