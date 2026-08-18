| Hallazgo | Dónde estaba | Técnica de Git | Comando exacto | Referencia |
| :--- | :--- | :--- | :--- | :--- |
| FRAG-01 | commit f1b2297 | archivo anterior al borrado | git show f1b2297:bitacora/frag-01.txt > bitacora/frag-01.txt | f1b2297 |
| FRAG-02 | etiqueta pre-incidente | leer mensaje de tag | git show respaldo/pre-incidente | respaldo/pre-incidente |
| Glifo | etiqueta pre-incidente | extraer objeto blob | git show respaldo/pre-incidente:assets/sello.svg > assets/sello.svg | respaldo/pre-incidente |
