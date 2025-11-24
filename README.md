# Impostor
Quien es el Impostor?

Este es un proyecto personal que armé para jugar con mis amigos y familia en reuniones. Es el típico juego de deducción (como el Among Us o Spyfall) donde todos reciben una palabra secreta menos uno: el Impostor. La gracia es descubrir quién está mintiendo.

# De qué trata?
Básicamente quería algo rápido para usar en el celular sin tener que bajar apps. Entras, pones tu nombre y listo.

La idea es que todos ven una palabra en su pantalla (ejemplo: "Playa"), pero el impostor solo ve que es el impostor. Nadie sabe quién es quién. Tienen que ir hablando o diciendo palabras relacionadas para sacarle la ficha al que no sabe nada.

# Cómo jugar?

Alguien crea la sala y pasa el código de 4 letras.

Todos entran y cuando estén listos, le dan a iniciar.

Deslizan su carta para ver su rol (nadie más debe ver tu pantalla).

A discutir y votar para encontrar al mentiroso.

Hecho por diversión. ¡Ojalá les sirva para pasar el rato!

# Lo que tiene el proyecto

Aunque es un proyecto sencillo, le metí cariño a varias cosas:

Multijugador real: Usé Firebase, así que si alguien entra a la sala, aparece al instante en la pantalla de todos.

Diseño bonito: Traté de que se viera moderno, con ese efecto de vidrio borroso ("glassmorphism") y un fondo animado.

El Swipe: Hice un gesto para el celular donde deslizas el dedo hacia arriba para ver tu carta en secreto, así el de al lado no te espía.

Todo en uno: Todo el código vive en un solo archivo para que sea fácil de mover o editar.

# Con qué lo hice?

Usé herramientas modernas pero manteniéndolo simple para no complicarme la vida:

React: Para manejar todo lo visual.

Firebase: Para que los jugadores se conecten entre sí.

Tailwind CSS: Para los estilos y que se vea bien en el móvil.

Canvas Confetti: Un efectito de celebración para cuando termina la ronda.

# Cómo se prueba?

Es súper fácil:

Descargas el código.

Abres el archivo index.html en tu navegador.

¡Y ya está!

(Ojo: Si quieres usarlo con tu propia base de datos, tendrías que cambiar mis credenciales de Firebase en el código, pero para probar así funciona).
