# Especificaciones de Casos de Uso

## UC-1 Registrar usuario
Un usuario no registrado puede registrarse en la aplicación proporcionando su información personal. El usuario solicita registrarse y el sistema pide la información requerida para el registro. El usuario completa los campos requeridos, como su nombre completo, nombre de usuario, fecha de nacimiento, dirección de correo electrónico y contraseña. El sistema valida los datos y crea un usuario si los datos son correctos. Si los datos presentan algún error, dado que todos los campos son obligatorios y debe de respetarse el formato del correo, la unicidad del nombre de usuario y validación de contraseña, el sistema niega el registro y muestra un mensaje de error.

## UC-2 Iniciar Sesión
Un usuario registrado puede iniciar sesión proporcionando su correo electrónico y contraseña. El usuario ingresa sus credenciales en el formulario de inicio de sesión, y el sistema las valida. Si las credenciales son correctas, el usuario accede a su cuenta. En caso contrario, el sistema muestra un mensaje de error indicando los campos que debe corregir o completar. 

## UC-3 Recuperar Contraseña
Un usuario que olvidó su contraseña puede solicitar restablecerla proporcionando al sistema su correo registrado. El sistema verifica que dicho correo esté registrado y se comunica con el usuario para proceder con el restablecimiento de la contraseña. De lo contrario, muestra un mensaje de error. 

## UC-4 Cerrar Sesión
Un usuario autenticado puede cerrar su sesión. El usuario solicita cerrar su sesión, y el sistema finaliza la sesión activa. Una vez cerrada la sesión, el usuario podrá volver a iniciar sesión si lo desea.

## UC-5 Buscar Evento
Un usuario autenticado puede buscar un evento proporcionando palabras clave o términos relacionados. El sistema busca los eventos asociados a esos términos y muestra una lista con los resultados encontrados. Adicionalmente, el usuario puede refinar su búsqueda aplicando filtros basados en las categorías del evento. En consecuencia, el sistema actualizará la búsqueda para incluir aquellos eventos que coincidan con las categorías seleccionadas. Si no se encuentran eventos que coincidan con los criterios de búsqueda, el sistema notificará al usuario con un mensaje. 

## UC-6 Publicar Evento
Un usuario autenticado puede publicar la información de un evento proporcionando información básica, como una imagen (mínimo una), descripción, fecha, hora,  categoría, música y ubicación del evento. El sistema valida que la información requerida sea correcta y completa. Si la validación es exitosa, el evento se publica y queda visible para otros usuarios. Si hay errores en los datos ingresados, el sistema notifica al usuario para que los corrija antes de intentar nuevamente. 

## UC-7 Editar Evento
Un usuario autenticado puede modificar un evento que creó previamente, actualizando la información básica, como la imagen, descripción, fecha, hora, categoría, música y ubicación. El sistema valida que los nuevos datos sean correctos y estén completos. Si la validación es exitosa, los cambios se guardan y se actualiza la información del evento visible para otros usuarios. En caso de errores en los datos ingresados, el sistema notifica al usuario para que realice las correcciones necesarias.

## UC-8 Ver Detalles del Evento
Un usuario autenticado puede ver la información completa de un evento. El usuario solicita ver los detalles de un evento, y el sistema muestra detalles del mismo como la descripción, fecha, ubicación, y otros datos relevantes. Si ocurre un error en la carga de la información del evento, se informa al usuario.

## UC-9 Subir Imagen al Evento
Un usuario puede agregar una imagen al evento, ya sea cargándola desde la galería de su dispositivo o tomando una foto con la cámara. El sistema valida que el archivo sea compatible y carga la imagen. Si ocurre un error, como problemas de formato, permisos denegados o fallas en la red, el sistema notifica al usuario y ofrece opciones para intentar nuevamente. 

## UC-10 Subir Música al Evento
Un usuario puede agregar música a un evento seleccionando un archivo desde su dispositivo o grabando un audio. El sistema verifica que el archivo sea compatible y carga la música. En caso de error, como problemas de formato, permisos denegados o fallas en la red, el sistema notifica al usuario y le permite intentar nuevamente o continuar sin agregar música.

## UC-11 Agregar Ubicación al Evento
Un usuario puede agregar una ubicación a un evento, ya sea seleccionándola en un mapa o usando la detección automática del dispositivo. Si el sistema no puede obtener la ubicación debido a permisos denegados o problemas de red, se notifica al usuario y se le permite reintentar o continuar sin agregar una ubicación.

## UC-12 Editar Imagen del Evento
Un usuario autenticado puede editar las imagenes asociada a un evento que haya creado previamente. El sistema verifica que al menos una imagen quede registrada para el evento después de la edición. En caso de error, el sistema notifica al usuario y ofrece opciones para reintentar.

## UC-13 Eliminar Música del Evento
Un usuario autenticado puede eliminar la música asociada a un evento que haya creado previamente. En caso de errores (problemas de formato, permisos denegados o fallas en la red), el sistema notifica al usuario y permite intentar nuevamente.

## UC-14 Eliminar Ubicación del Evento
Un usuario autenticado puede eliminar la ubicación asociada a un evento que haya creado previamente. En caso de errores (permisos denegados o problemas de red), el sistema notifica al usuario y ofrece opciones para reintentar.

## UC-15 Seguir a un Usuario
Un usuario autenticado puede seguir a otro usuario. Al visitar el perfil de alguien que no sigue, el usuario puede solicitar seguir al otro usuario. El sistema registra esta acción y actualiza la información para representar la acción realizada.

## UC-16 Dejar de Seguir a un Usuario
Un usuario autenticado puede dejar de seguir a otro usuario que ya sigue. El sistema elimina la relación entre ambos usuarios, y el usuario deja de recibir actualizaciones del usuario objetivo. Si el usuario no está autenticado o no sigue al usuario objetivo, la acción no puede completarse.

## UC-17 Ver Notificaciones
Un usuario autenticado puede consultar un listado con todas sus notificaciones. El sistema presenta las notificaciones ordenadas cronológicamente. Si no hay notificaciones disponibles, el sistema informa al usuario que no tiene notificaciones en ese momento.

## UC-18 Buscar Perfil de Usuario
Un usuario autenticado puede buscar a otro usuario proporcionando su nombre o bien, nombre de usuario. El sistema busca los usuarios registrados que coincidan con la búsqueda y muestra un listado con los resultados encontrados. Si no hay usuarios que coincidan con los criterios de búsqueda, el sistema notificará al usuario con un mensaje.

## UC-19 Dar "Me gusta" a un Evento
Un usuario autenticado puede indicar que le gusta un evento. El sistema registra esta acción y actualiza la información para reflejar que al usuario le ha gustado el evento. Si ocurre un error, se informa al usuario.

## UC-20 Quitar "Me gusta" a un Evento
Un usuario autenticado puede quitar que le gusta un evento. El sistema registra esta acción y actualiza la información para reflejar que al usuario ya no le gusta el evento. Si ocurre un error, se informa al usuario.

## UC-21 Compartir un Evento
Un usuario autenticado puede compartir un evento. Al solicitar compartir el evento, el sistema muestra las opciones disponibles para compartir. El usuario elige una opción, y el sistema generará el contenido adecuado para compartirlo. Si el proceso falla, se muestra un mensaje de error.

## UC-22 Comentar Evento
Un usuario autenticado puede comentar al ingresar un texto sobre un evento especifico y enviarlo. El sistema valida que el comentario no esté vacío, guarda el comentario y lo muestra en la lista de comentarios del evento. Si ocurre un error al guardar el comentario, se informa al usuario.

## UC-23 Ver Perfil de Usuario
Un usuario autenticado puede visualizar el perfil de un usuario. El usuario solicita ver la información disponible del perfil y el sistema muestra la información disponible asociada dicho perfil de usuario. 

## UC-24 Editar Perfil
Un usuario autenticado puede editar la información de su perfil, como su nombre, imagen de perfil y biografía. El sistema muestra un formulario con la información actual del usuario, permitiéndole realizar modificaciones. Una vez realizados los cambios, el usuario guarda la nueva información. El sistema valida los cambios y actualiza el perfil del usuario. Si todo es correcto, los cambios se guardan correctamente. En caso de error, como datos incorrectos o problemas al guardar la información, el sistema notifica al usuario y le permite corregir los errores o intentar nuevamente.

## UC-25 Cambiar Idioma
Un usuario autenticado puede cambiar el idioma en que visualiza la aplicación. El usuario solicita cambiar el idioma y el sistema muestra los idiomas disponibles. Así, el usuario indica el idioma de su preferencia y el sistema actualiza la interfaz al idioma correspondiente, guardando esta preferencia para futuras sesiones. Si hay algún problema con el cambio, el sistema notificará al usuario y le permitirá intentarlo nuevamente.

## UC-26 Cambiar Contraseña
Un usuario autenticado puede cambiar su contraseña proporcionando al sistema su contraseña actual y su nueva contraseña. El sistema valida que su contraseña actual coincida con la ingresada y que cumpla con los requisitos mínimos. Si la contraseña es válida, el sistema confirma el cambio y desconecta al usuario, solicitándole que inicie sesión nuevamente con la nueva contraseña. Si la contraseña ingresada es incorrecta o no cumple con los requisitos mínimos, el sistema muestra un mensaje de error y permite al usuario corregirla o abandonar el proceso. 

## UC-27 Ver Lista de Seguidos
Un usuario autenticado puede ver un listado con los usuarios que sigue. El usuario solicita ver los usuarios que sigue y el sistema muestra un listado con todos los usuarios seguidos en orden alfabético u orden cronológico. Si el usuario no sigue a nadie, el sistema le informa que no tiene usuarios seguidos en ese momento.

## UC-28 Ver Lista de Seguidores
Un usuario autenticado puede ver un listado con los usuarios que lo siguen. El usuario solicita ver los usuarios que lo siguen y el sistema muestra un listado con sus seguidores ordenados en orden alfabético u orden cronológico. Si el usuario no tiene seguidores, el sistema le informa que no tiene seguidores en ese momento.
