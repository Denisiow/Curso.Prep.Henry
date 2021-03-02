# Explicaciones

## Objetos
Los objetos son parecidos a los arrays, pueden contener multiples elementos en un mismo lugar para acceder a ellos más fácilmente. Los elementos dentro de los objetos se llaman propiedades. Los objetos usan un par llamado Key:Value para contener elementos. Key es un valor único dentro del objeto, que a su vez contiene un value dentro de ella, que puede repetirse y no ser unico.
Nos dan la posibiilidad de acceder a datos de una manera mas ordenada.

## Propiedades
Son los elementos que van dentro del objeto (los Keys), que a su vez contiene los valores dentro (los values)

## Métodos
Se le llama Método a una función (function) cuando se encuentra dentro de un objeto.

## For ... in
For... in es un bucle, igual que "for". Como no se puede usar el bucle "for" con un objeto (porque no tiene un indice numerico), se debe usar este tipo de bucle para buscar dentro del objeto.

## Notación de puntos vs notación de corchetes
En general la notación de corchetes (brackets) es mas flexible y permite usar variables o ingresar a propiedades que empiecen con numeros o que lleven espacios. La notación de puntos (dot) es mas rapida y simple pero no puede hacer lo mismo que la de corchetes. Por ejemplo, "objeto.123propiedad" no seria valido, mientras que "objeto["123propiedad"]" si lo seria.