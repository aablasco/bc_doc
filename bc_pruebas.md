# Pruebas de Business Central

## Cajas
He intentando hacer una simulación de cajas pero para poder hacer cambios en el registro
se necesitaría que las opciones de la tabla 81 se sustituyeran por `enum`.

En la parte de `C/AL` ya están añadidos las siguientes propiedades
para poder hacer esos cambios:

 * Extensible : por defecto No
 * EnumTypeId : identificación del `enum`
 * EnumTypeName : se recuperará el nombre cuando se asigne el id

---

 # Resultados de las pruebas

 En `app.json` se tiene que indicar el rango de la licencia.
 ```
 "idRange": {
    "from": 7049685,
    "to": 7052184
  },
 ```

 