# CLICK_PADEL_MICROSERVICE
# Click Padel - Microservices Backend

Backend para la tienda de palas de pádel Click Padel, implementado con una arquitectura de microservicios.

## Servicios

- Auth Service: Gestión de usuarios y autenticación
- Product Service: Gestión de productos (palas)
- Order Service: Gestión de pedidos y carritos
- Gateway Service: API Gateway

## Tecnologías

- Python 3.9+
- FastAPI
- PostgreSQL
- Docker
- Redis

## Configuración del Entorno de Desarrollo

1. Clonar el repositorio:
```bash
git clone <repository-url>
cd CLICK_PADEL_MICROSERVICE
```

2. Crear y activar entorno virtual:
```bash
python -m venv venv
source venv/bin/activate  # En Windows: .\venv\Scripts\activate
```

3. Instalar dependencias:
```bash
pip install -r requirements.txt
```

4. Configurar variables de entorno:
```bash
cp .env.example .env
# Editar .env con tus configuraciones
```

5. Iniciar servicios:
```bash
docker-compose up -d
```

## Estructura del Proyecto

Explicación de la estructura de directorios y archivos principales.

## Contribución

Instrucciones para contribuir al proyecto.