# Actividad

1. para crear la base de datos se va a usar el comando:
    ```mongosh
    use <newDbName>
    ```
2. crear la collection
    ```mongosh
    db.<collectionName>.insert({properties});
    db.<collectionName>.insertOne({properties});
    db.<collectionName>.insertMany([{properties}, {properties},...]);
    ```
3. Insertar la data de scripts.mongodb
4. Operadores de comparacion.
    ~~~
    -  $eq: Compara si un campo es igual a un valor específico.
    -  $ne: Compara si un campo no es igual a un valor específico.
    -  $gt: Compara si un campo es mayor que un valor específico.
    -  $gte: Compara si un campo es mayor o igual que un valor específico.
    -  $lt: Compara si un campo es menor que un valor específico.
    -  $lte: Compara si un campo es menor o igual que un valor específico.
    -  $in: Compara si un campo está contenido en una lista de valores.
    -  $nin: Compara si un campo no está contenido en una lista de valores.
    -  $exists: Comprueba si un campo existe en un documento.
    -  $type: Comprueba el tipo de datos de un campo en un documento.
    ~~~
    adicionalmente tenemos estos que son menos comunes
    ~~~
    - $size: Comprueba si un campo de tipo array tiene un tamaño específico.
    - $all: Comprueba si un campo de tipo array contiene todos los valores de una lista dada.
    - $elemMatch: Busca documentos que contengan al menos un elemento que cumpla una condición específica en un campo de tipo array.
    - $not: Invierte el resultado de una expresión de consulta.
    - $regex: Realiza una búsqueda basada en una expresión regular en un campo de tipo string.
    - $text: Realiza búsquedas de texto completo en campos de tipo string.
    - $mod: Comprueba si un campo es divisible por un valor específico (utilizado en combinación con $mod).
    - $where: Permite ejecutar expresiones JavaScript personalizadas como parte de la consulta.
    ~~~