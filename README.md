# Data

The *Cosmos Nexus* universe data was provided by the course staff and **is not included in the repository**. To run the notebook, place these files where the notebook expects them (`/content/` in Colab):

| File | Contents | Used in |
|---|---|---|
| `corpus_conocimiento.zip` | `.txt` / `.pdf` documents (synopses, biographies, chronicles) | Vector database (ChromaDB) |
| `cosmos_nexus_db.db` | SQLite database with movies, characters, worlds, and artifacts | SQL module |
| `relaciones_universo.csv` | Entity relationships (`entidad1`, `relacion`, `entidad2`) | Graph database (Neo4j) |

This folder is ignored by Git (see `.gitignore`) except for this file.
