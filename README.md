# Angel's Notebooks

Repositorio personal de práctica con Jupyter Notebooks y Python.

## Estructura

### Notebooks sueltos
- [Diccionarios.ipynb](Diccionarios.ipynb) - Práctica con diccionarios en Python
- [for_recuento_palabras.ipynb](for_recuento_palabras.ipynb) - Ejercicios de conteo de palabras
- [for_repaso_general.ipynb](for_repaso_general.ipynb) - Repaso general de bucles for
- [metodos_str.ipynb](metodos_str.ipynb) - Métodos de strings en Python
- [pokeapi_apis .ipynb](pokeapi_apis%20.ipynb) - Consumo de la API de Pokémon

### Proyectos con carpetas

#### [shopify-api-customer/](shopify-api-customer/)
Extracción de información de clientes desde la API de Shopify.
- **Endpoint**: `/customers.json`
- **Objetivo**: Obtener datos de clientes (nombres, emails, direcciones)

#### [shopify-api-pedidos/](shopify-api-pedidos/)
Análisis completo de pedidos de Shopify.
- **Endpoint**: `/orders.json`
- **Objetivo**: Extraer y procesar pedidos, productos y clientes
- **Features**: Análisis exploratorio, múltiples tablas relacionadas

## Configuración

### Requisitos
```bash
pip install -r requirements.txt
```

### Variables de entorno
Los proyectos de Shopify requieren un archivo `.env` con:
```
SHOP_NAME=tu-tienda
SHOPIFY_API_TOKEN=shpat_xxxxx
```

Usa los archivos `.env.example` como plantilla.

## Uso

1. Clona el repositorio
2. Instala dependencias
3. Configura tus credenciales (si aplica)
4. Abre los notebooks con Jupyter o VSCode
