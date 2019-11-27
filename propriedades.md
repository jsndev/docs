---
description: >-
  Cada propriedade do arquivo JSON proposto será identificado de acordo com seu
  tipo e função.
---

# Propriedades

## SESSIONID

Contem o id da sessão ao qual aquela mensagem pertence.

```text
{
  "message": {
    "sessionID": |STRING|
  }
}

```

## ID

Contem a ordem em que a mensagem foi enviada naquela sessão.

> Cada mensagem enviada pertence a uma sessão única e seu identificador nada mais é que a ordem, que a mesma foi disparada dentro de uma sessão.

{% hint style="info" %}
Os identificadores são um auto incremente que deve iniciar em  1 \(um\).
{% endhint %}

```text
{
  "message": {
    "sessionID": |STRING|
    "id": |INT|
  }
}
```

