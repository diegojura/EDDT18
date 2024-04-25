# Explicación de los Merges en el Árbol de Git

1. **Primer Commit**
   - Todo comienza con el primer commit, marcado como `primer commit`.
   - Es la base de donde se derivarán todas las demás ramas y commits.

2. **Rama Develop**
   - Se crea una rama llamada `develop` a partir del commit inicial.
   - Esta rama sirve como base para el desarrollo e integración de características.

3. **Ramas de Características**
   - Se crean tres ramas de características (`feature1`, `feature2`, `feature2.2`) a partir de `develop`.
   - Estas ramas se utilizan para desarrollar nuevas características de forma independiente.

4. **Rama Hotfix**
   - Se crea una rama llamada `hotfix` a partir del commit inicial para hacer correcciones urgentes.
   - Luego se fusiona de nuevo en `develop`, asegurando que las correcciones se incluyan en los futuros desarrollos.

5. **Rama Develop 2**
   - La rama llamada `develop` se actualiza fusionando `feature2.2` en ella.

6. **Ramas de Lanzamiento**
   - Se crea una rama de lanzamiento llamada `release` a partir de `develop` para preparar un lanzamiento de producción.
   - Luego se fusiona en `main`, marcando un lanzamiento oficial.

7. **Main con Release 2**
   - La rama 'main' ahora contiene todas las actualizaciones hechas en 'release', indicando que se ha lanzado otra actualización o versión oficial.
