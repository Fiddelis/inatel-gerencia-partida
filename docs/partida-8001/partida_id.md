# localhost:8001/partida/{id}

!!! note
    Utilizado somente pelo Front-end.

## PUT
==Indica o fim da partida==

```json
{
    "usuario_id": "long",
    "descricao": ["perdeu", "caiu", "anti-cheat"] // somente um
}
```

**Possiveis retorno:**  
200
```json
{
    "usuarios":[
        {"id": "long", "nome": "str", "novoRank": long},
        {"id": "long", "nome": "str", "novoRrank": long}
    ]
}
```