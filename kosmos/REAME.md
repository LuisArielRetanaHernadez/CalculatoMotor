# Notas de la pruba.

# Fecha de primer emplo

Cuando se ingresa un argumento de tipo Date para el parametro fechaPrimerEmpleo pero el formato es Date("30/12/1993")
Da error de dato invalido por el tipo de formato. Para poder ingresar ese tipo de formato en el parametro fechaPrimerEmpleo tendria que ser de tipo String para recibir el formato "30/12/1993" y despues cambiar el formato para pueda ser de tipo Date o otra opcion es crear una funcion para cambiar el formato de la fecha y que retorno el resultado en tipo Date y asi el parametro podra ser de tipo Date recibiendo el formato valido desde la funcion conversora.

Por el momento el parametro fechaPrimerEmpleo tiene que reciber la fecha en este formato Date("YYYY/MM/DD") -> new Date("2019/01/15")
