# Datos

Los datos del universo *Cosmos Nexus* fueron provistos por la cátedra y **no se incluyen en el repositorio**. Para ejecutar el notebook, ubicá estos archivos donde el notebook los espera (`/content/` en Colab):

| Archivo | Contenido | Se usa en |
|---|---|---|
| `corpus_conocimiento.zip` | Documentos `.txt` / `.pdf` (sinopsis, biografías, crónicas) | Base vectorial (ChromaDB) |
| `cosmos_nexus_db.db` | Base SQLite con películas, personajes, mundos y artefactos | Módulo SQL |
| `relaciones_universo.csv` | Relaciones entre entidades (`entidad1`, `relacion`, `entidad2`) | Base de grafos (Neo4j) |

Esta carpeta está ignorada por Git (ver `.gitignore`) salvo este archivo.
