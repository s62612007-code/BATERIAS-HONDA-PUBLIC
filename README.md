# Baterías Honda – Cotizador Coéxito Cali

Aplicación web para consulta de compatibilidad, catálogo de precios y cotización de baterías (Bosch, MAC, Varta, Coéxito, Duncan, Willard).

## Características

- Búsqueda por marca, modelo y año del vehículo
- Catálogo con logos e imágenes por referencia
- Cotización con descarga en PDF
- **PilaBot**: asistente virtual con cálculo de domicilio y descuentos

## Domicilio (desde Carrera 54A #7-05, Cali)

| Zona | Radio | Precio |
|------|-------|--------|
| Cercana | hasta 1.5 km | $15.000 |
| Amplia | hasta 8 km | $25.000 |

## Promociones

- **Batería usada:** -$30.000 en la referencia elegida
- **Promoción Vecindad:** -$35.000 en la segunda pila

## Uso local

```bash
python3 -m http.server 8080
```

Abrir `http://localhost:8080`

## Estructura

```
├── config/     # precios.json, bot-biblioteca.json
├── css/        # estilos y bot
├── data/       # catálogo vehicular
├── images/     # logos y referencias
├── js/         # app.js, bot.js
└── index.html
```

**Baterías Honda** – *Energía confiable para tu camino.*
