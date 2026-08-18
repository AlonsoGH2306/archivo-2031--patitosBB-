| Hallazgo | Dónde estaba | Técnica de Git | Comando exacto | Referencia |
|---|---|---|---|---|
| FRAG-01 | Commit f1b2297 de la rama principal | Recuperación desde commit histórico | `git show f1b2297:bitacora/frag-01.txt` | f1b2297 |
| FRAG-02 | Tag respaldo/pre-incidente | Lectura de referencia tag | `git tag -n99` | respaldo/pre-incidente |
| Glifo sello | Tag respaldo/pre-incidente | Checkout de archivo desde tag | `git checkout respaldo/pre-incidente -- assets/sello.svg` | respaldo/pre-incidente |