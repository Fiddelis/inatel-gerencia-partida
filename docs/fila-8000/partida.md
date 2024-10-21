# localhost:8000/fila/partida

!!! note
    Uso interno.

## POST (Serviço de partida avisa o serviço de Fila que foi criado uma partida)
```json
{
    "partida_id": "long",
    "usuarios":[
        {"id": "long", "nome": "str", "rank": long},
        {"id": "long", "nome": "str", "rank": long}
    ]
}
```