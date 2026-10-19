# Caso 01 — O objeto de outro cliente

**Tipo:** exercício de mesa, dados e cenário sintéticos. Não exige instalação nem contato com serviços reais.

## Situação

A aplicação fictícia possui usuários de dois tenants. Uma rota recebe o identificador do objeto, mas o exercício questiona se a decisão de autorização valida também o tenant. Nenhum alvo ou endpoint real é utilizado.

## Sua missão

1. Escreva a política de acesso por usuário, objeto, tenant e ação.
2. Descreva um teste permitido dentro do tenant e um negado entre tenants.
3. Considere IDs existentes, inexistentes e sessões sem autenticação.
4. Registre a regressão necessária para preservar a política em futuras mudanças.

## Entrega

Preencha a [ficha](../templates/ficha.md), citando o trecho ou identificador que sustenta cada conclusão. Se faltar uma informação, registre a lacuna em vez de inventar um resultado.

<details>
<summary>Comentário e critério de aceite</summary>

A matriz demonstra autorização no servidor por objeto e contexto, sem depender apenas de esconder botões.

A avaliação é qualitativa e exige revisão humana. Este exercício não mede eficácia em um ambiente real.

</details>

[Guia](../docs/COMECE-AQUI.md) · [Início](../README.md)
