# `DEV` Cavalo de Tróia

Esse projeto se destina a demonstrar o quão eficaz, eficiente e efetivo fazer testes automatizados

O grande problema das empresas é perder tempo fazendo trabalhos cujos resultados são baixos a curto e longo prazo

A demonstração aqui une verificação e validação em um único trabalho

Além disso, esses testes baseiam-se nos dados, não dependendo de análises parciais das páginas `Web` retonardas

A diferença dele está em validar a partir das regras de teste interna e propagação da ação de validação

> **regras de teste interna**: regras que descrevem como o domínio deve se comportar, servindo como um descritor do domínio e servindo para validar serviços

> **propagação da ação de validação**: é avaliados os impactos causados no banco de dados, arquivos e logs

# Troia

Projeto utilizado como exemplo

Implemente o caso de uso `Presentear` o `Rei de Tróia`

## User stories

- Eu como rei quero gerenciar os presentes que recebo
    - Devo poder ver a lista de presentes
    - Devo poder ver os detalhes do presente
    - Devo poder rejeitar um presente

- Eu como rei quero ver um e-mail quando alguém cadastrar um presente
  - Devo saber o vulgo de quem está enviando
  - Devo saber o nome do presente
  - Devo saber até quando será enviado
  - Devo saber qual o valor estimado
  - Devo saber se oferece risco para minha cidade

- Eu como alguém quero enviar presente para o rei


## Branchs

Em ambos os branchs, seria disparados os serviços de validação do `Grego`, afim de identificar falhas

## main

Utilizado para publicar em produção

Nesse contexto, seria disparados os serviços de validação, afim de identificar falhas

## master

Utilizado para publicar no ambiente de homologação
