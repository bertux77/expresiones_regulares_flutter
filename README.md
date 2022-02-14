# expresiones regulares para aplicaciones desarroladas en flutter
Expresion regular para validar emails.

String pattern = r'^(([^<>()[\]\\.,;:\s@\"]+(\.[^<>()[\]\\.,;:\s@\"]+)*)|(\".+\"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$';
 
RegExp regExp  = new RegExp(pattern);

----------------------------------------------------

Expresion regular para validar que solo se puedan escribir numeros con dos decimales (x.yy)

FilteringTextInputFormatter.allow(RegExp(r'^(\d+)?\.?\d{0,2}'))

Escrito por Alberto Carrion de Precursor Sinaptico. Desarrollador freelance Full Stack.
