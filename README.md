<h1 align="center">Patrones de Diseño con Python</h1>
<h3>Principio de responsabilidad única (SRP)</h3>

"Una clase debe tener una,y solo una, razon para cambiar". Robert C. Martin

- Una clase debe tener una única responsabilidad o función
   Una clase debe tener una sola funcion
- Una clase debe tener una, y una sola,razón para cambiar

<h4>Beneficios</h4>
- Mejor mantenimiento<br>
  Si un codigo tiene mucha responsabilidad es muy dificil de mantener incrementando el costo, por lo contrario si solo tiene un responsabilidad
  sera facil el mantenimiento y reducira el costo.
- Reusabilidad incrementada<br>
  Cuando se tiene componentes separados y responsabilidad unica es mucho mas facil reutilizarlos
- Facilidad para realizar pruebas unitarias<br>
  Las pruebas unitarias son el pilar para desarrollo de software.
- Escalabilidad del sistema<br>
  Es mucho mas facil que el sistema cresca ya que la modificacion es mas sencilla y rapida
- Reducción de la complejidad<br>

<h4>Cuando debo aplicar el principio de responsabilidad</h4>
  
- Cuando existe varias razones para cambiar una clase
- Cuando exite una alta complejidad y dificil de mantenimiento
- Cuando existe dificultad para realizar las pruebas unitarias
- Cuando existe duplicación de codigo
  
  
