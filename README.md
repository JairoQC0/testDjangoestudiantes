### 📌 Endpoints de la API - App `core`

#### 1. **Lista de recetas**

-   **Método:** `GET`
    
-   **URL:** `/api/recetas/`
    
-   **Descripción:** Devuelve un listado de todas las recetas disponibles.
    
-   **Respuesta:** JSON con la lista de recetas.
    

#### 2. **Crear receta**

-   **Método:** `POST`
    
-   **URL:** `/api/recetas/`
    
-   **Descripción:** Crea una nueva receta con los datos enviados.
    
-   **Body esperado:** JSON con campos como `nombre`, `ingredientes`, `preparacion`, etc.
    
-   **Respuesta:** JSON con la receta creada y su ID.
    

#### 3. **Detalle de una receta**

-   **Método:** `GET`
    
-   **URL:** `/api/recetas/<id>/`
    
-   **Descripción:** Devuelve los detalles de una receta específica por su ID.
    
-   **Respuesta:** JSON con los datos de la receta.
    

#### 4. **Actualizar receta**

-   **Método:** `PUT` o `PATCH`
    
-   **URL:** `/api/recetas/<id>/`
    
-   **Descripción:** Actualiza una receta existente.
    
-   **Body esperado:** JSON con los campos a modificar.
    
-   **Respuesta:** JSON con la receta actualizada.
    

#### 5. **Eliminar receta**

-   **Método:** `DELETE`
    
-   **URL:** `/api/recetas/<id>/`
    
-   **Descripción:** Elimina la receta especificada por su ID.
    
-   **Respuesta:** Código de estado `204 No Content` si se elimina con éxito.
    

#### 6. **Endpoint raíz (opcional)**

-   **Método:** `GET`
    
-   **URL:** `/`
    
-   **Descripción:** Página principal o respuesta simple para probar si el servidor está activo.
