# localhost:8000/fila/busca

!!! note
    Utilizado somente pelo Front-end.


## POST (1° pedido de fila)
```json
{
    "usuario_id": "long"
}
```
**Possiveis retornos:**  
201
```json
{}
```

---

## GET (Verificar fila)
```json
{
    "usuario_id": "long"
}
```
**Possiveis retornos:**

201
```json
{}
```

200
```json
{
    "partida_id": "long",
    "link_partida": "str",
    "usuarios":[
        {"id": "long", "nome": "str", "rank": long},
        {"id": "long", "nome": "str", "rank": long}
    ]
}
```

---

## DELETE (Sair da fila)
```json
{
    "usuario_id": "long",
}
```
**Possiveis retornos:**  
201
```json
{}
```