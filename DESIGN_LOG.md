Manejo de estados de carga y feedback.

Los estados de carga se manejan principalmente con toasts informativos y spinners visibles que le indican al usuario que el sistema está trabajando. Por ejemplo, al guardar un punto, calcular una ruta o detectar la ubicación del usuario, se muestra un indicador visual inmediato que bloquea y evita que el usuario repita acciones innecesarias.

Para los estados de error, se muestran por mensajes claros y directos que explican qué pasó y qué puede hacer el usuario después. Cuando falla el cálculo de la ruta o la geolocalización, la UI responde mostrando un toast de error y, cuando es posible, ofrece una alternativa visual para que el usuario no se quede sin retroalimentación visual. En acciones críticas, como guardar un punto, se permite reintentar sin perder el contexto.

En general, el enfoque fue priorizar la continuidad de uso, incluso cuando ocurre un error, la aplicación sigue siendo funcional y predecible.
