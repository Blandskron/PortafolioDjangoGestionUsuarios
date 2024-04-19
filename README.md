# PortafolioDjangoGestionUsuarios

## Clonar y Configurar el Proyecto

Sigue estos pasos para clonar y configurar el proyecto en tu máquina local:

### 1. Clonar el Repositorio

```
git clone <URL_del_repositorio>
```

### 2. Instalar Dependencias

```
cd nombre_del_proyecto
pip install -r requirements.txt
```

### 3. Realizar Migraciones

```
python manage.py migrate
```

### 4. Crear un Superusuario (Opcional)

Si deseas acceder al panel de administración de Django, puedes crear un superusuario con el siguiente comando:

```
python manage.py createsuperuser
```

### 5. Ejecutar el Servidor de Desarrollo

```
python manage.py runserver
```

El servidor se ejecutará en `http://localhost:8000/`. Puedes acceder a la aplicación a través de tu navegador web.
