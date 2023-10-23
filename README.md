<p align="center">
   <h1 align="center">libft</h1>
</p>

<p align="center">
   Implementación de algunas de las funciones de la librería estándar de C y otras funciones útiles para el resto de proyectos del Cursus
</p>

---

<p align="center">
   <h3 align="center">Funciones</h3>
</p>

<table align="center">
  <tr>
    <th>Función</th>
    <th>Descripción</th>
  </tr>
  <tr>
    <td align="center">ft_isalpha</td>
    <td align="center">Devuelve <b>1</b> si el carácter introducido es una letra</td>
  </tr>
  <tr>
    <td align="center">ft_isdigit</td>
    <td align="center">Devuelve <b>1</b> si el carácter introducido es un número</td>
  </tr>
  <tr>
    <td align="center">ft_isalnum</td>
    <td align="center">Devuelve <b>1</b> si el carácter introducido es una letra o un número</td>
  </tr>
  <tr>
    <td align="center">ft_isascii</td>
    <td align="center">Devuelve <b>1</b> si el carácter introducido pertenece al código ASCII</td>
  </tr>
  <tr>
    <td align="center">ft_print</td>
    <td align="center">Devuelve <b>1</b> si el carácter introducido pertenece al código ASCII y es imprimible</td>
  </tr>
  <tr>
    <td align="center">ft_strlen</td>
    <td align="center">Devuelve el número de caracteres de una cadena</td>
  </tr>
  <tr>
    <td align="center">ft_memset</td>
    <td align="center">Sustituye el contenido de posiciones de memoria adyacentes por el mismo carácter</td>
  </tr>
  <tr>
    <td align="center">ft_bzero</td>
    <td align="center">Vacía el número indicado de posiciones de memoria</td>
  </tr>
  <tr>
    <td align="center">ft_memcpy</td>
    <td align="center">Copia el número indicado de caracteres de una posición de memoria a otra</td>
  </tr>
  <tr>
    <td align="center">ft_memmove</td>
    <td align="center">Copia el número indicado de caracteres de una posición de memoria a otra manteniendo la integridad de los datos</td>
  </tr>
  <tr>
    <td align="center">ft_strlcpy</td>
    <td align="center">Copia el número indicado de caracteres de una cadena a otra</td>
  </tr>
  <tr>
    <td align="center">ft_strlcat</td>
    <td align="center">Une dos cadenas de caracteres</td>
  </tr>
  <tr>
    <td align="center">ft_toupper</td>
    <td align="center">Devuelve el carácter indicado en mayúscula</td>
  </tr>
  <tr>
    <td align="center">ft_tolower</td>
    <td align="center">Devuelve el carácter indicado en minúscula</td>
  </tr>
  <tr>
    <td align="center">ft_strchr</td>
    <td align="center">Devuelve la primera posición de una cadena donde se encuentra el carácter indicado</td>
  </tr>
  <tr>
    <td align="center">ft_strrchr</td>
    <td align="center">Devuelve la última posición de una cadena donde se encuentra el carácter indicado</td>
  </tr>
  <tr>
    <td align="center">ft_strncmp</td>
    <td align="center">Devuelve la diferencia entre dos cadenas de caracteres</td>
  </tr>
  <tr>
    <td align="center">ft_memchr</td>
    <td align="center">Devuelve la primera posición donde se encuentra el carácter indicado</td>
  </tr>
  <tr>
    <td align="center">ft_memcmp</td>
    <td align="center">Devuelve la diferencia entre dos regiones de memoria</td>
  </tr>
  <tr>
    <td align="center">ft_strnstr</td>
    <td align="center">Devuelve la primera posición de una cadena donde se encuentra la secuencia de caracteres indicada</td>
  </tr>
  <tr>
    <td align="center">ft_atoi</td>
    <td align="center">Convierte una cadena de dígitos en un número entero</td>
  </tr>
  <tr>
    <td align="center">ft_calloc</td>
    <td align="center">Reserva la cantidad de memoria indicada y la vacía</td>
  </tr>
  <tr>
    <td align="center">ft_strdup</td>
    <td align="center">Reserva memoria para la cadena de caracteres indicada</td>
  </tr>
  <tr>
    <td align="center">ft_substr</td>
    <td align="center">Reserva memoria para una cadena que se encuentra incluida en otra</td>
  </tr>
  <tr>
    <td align="center">ft_strjoin</td>
    <td align="center">Reserva memoria para la unión de dos cadenas de caracteres</td>
  </tr>
  <tr>
    <td align="center">ft_strtrim</td>
    <td align="center">Reserva memoria para una cadena recortada por delante y por detrás en función de una secuencia de caracteres</td>
  </tr>
  <tr>
    <td align="center">ft_split</td>
    <td align="center">Reserva memoria para un array de cadenas pertenecientes a una cadena original separada por un carácter indicado</td>
  </tr>
  <tr>
    <td align="center">ft_itoa</td>
    <td align="center">Reserva memoria para una cadena de caracteres equivalente a un número entero</td>
  </tr>
  <tr>
    <td align="center">ft_strmapi</td>
    <td align="center">Reserva memoria para almacenar el resultado de aplicar una función a todos los caracteres de una cadena</td>
  </tr>
  <tr>
    <td align="center">ft_striteri</td>
    <td align="center">Aplica una función a cada una de las posiciones de memoria de los caracteres de una cadena</td>
  </tr>
  <tr>
    <td align="center">ft_putchar_fd</td>
    <td align="center">Envía un carácter al descriptor de archivo indicado</td>
  </tr>
  <tr>
    <td align="center">ft_putstr_fd</td>
    <td align="center">Envía una cadena de caracteres al descriptor de archivo indicado</td>
  </tr>
  <tr>
    <td align="center">ft_putendl_fd</td>
    <td align="center">Envía una cadena de caracteres al descriptor de archivo indicado y añade al final un salto de línea</td>
  </tr>
  <tr>
    <td align="center">ft_putnbr_fd</td>
    <td align="center">Envía una número al descriptor de archivo indicado</td>
  </tr>
  <tr>
    <td align="center">ft_lstnew</td>
    <td align="center">Crea un nodo de lista con el contenido indicado</td>
  </tr>
  <tr>
    <td align="center">ft_lstadd_front</td>
    <td align="center">Añade un nodo al principio de una lista</td>
  </tr>
  <tr>
    <td align="center">ft_lstsize</td>
    <td align="center">Devuelve la longitud de una lista</td>
  </tr>
  <tr>
    <td align="center">ft_lstlast</td>
    <td align="center">Devuelve el último nodo de una lista</td>
  </tr>
  <tr>
    <td align="center">ft_lstadd_back</td>
    <td align="center">Añade un nodo al final de una lista</td>
  </tr>
  <tr>
    <td align="center">ft_lstdelone</td>
    <td align="center">Libera la memoria reservada para un nodo de lista</td>
  </tr>
  <tr>
    <td align="center">ft_lstclear</td>
    <td align="center">Libera la memoria reservada para todos los nodos de una lista</td>
  </tr>
  <tr>
    <td align="center">ft_lstiter</td>
    <td align="center">Aplica una función al contenido de cada nodo de una lista</td>
  </tr>
  <tr>
    <td align="center">ft_lstmap</td>
    <td align="center">Devuelve una lista resultante de aplicar una función al contenido de cada nodo de otra lista</td>
  </tr>
</table>
