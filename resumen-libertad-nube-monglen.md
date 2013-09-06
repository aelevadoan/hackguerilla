# Libertad en la nube, Libertad del Software, Privacidad y Seguridad para la Web 2.0 y Computación en la Nube
## Eben Monglen


Y obtenés servicio de correo electrónico gratuitamente y algo de almacenamiento que vale exactamente una moneda y media al precio actual de almacenamiento y obtenés espionaje permanente.

Y gratis también.

Y tu agenda está en la web y todos pueden ver si tenés una cita el viernes a la noche y tenés un estado (“buscando”) y obtenés un servicio gratis, de publicidad (“soltero: buscando”). Espionaje gratis incluido. Y todo esto apareció así en un parpadeo y aquí estamos (...)


Entonces tenemos que volver un poco y pensar en qué punto estamos y cómo llegamos aquí y probablemente algo más importante, si podemos salir y si podemos, ¿cómo? Y no es una linda historia, para nada (...)

Empieza por supuesto con la Internet, la elaboración teórica de una red de par-a-par llamada “Internet” diseñada como una red de pares sin ninguna necesidad intrínseca de control jerarquizado o estructurado y asumiendo que cada punto de la Red es una entidad independiente y libre cuya voluntad es equivalente a la voluntad de los seres humanos que la quieren controlar.


Por supuesto, nunca trabajó realmente de esa manera. No había nada en el diseño técnico para prevenirlo. Es un simple problema de software y tiene un simple nombre de tres sílabas. El nombre es Microsoft. El software que empezó a ocupar la red estaba construido sobre una idea muy clara que no tenía nada que ver con pares. Se llamó “arquitectura cliente-servidor”.

De hecho, si lo piensan, fue peor que eso. La cosa llamada “Windows” era una versión degenerada de una llamada “X Windows”. Esta también pensó el mundo como una arquitectura cliente-servidor, pero lo que ahora diríamos al revés de como la conocemos. El servidor era la cosa del lado del ser humano. Esa era la concepción básica del mundo de X Windows. Servía comunicaciones con seres humanos en los puntos finales de la red a procesos ubicados en lugares arbitrarios cerca del centro, en la mitad, o en los bordes de la Red. Fue la gran idea de Windows en una forma extraña crear un arquetipo político en la red que redujo el ser humano al cliente y produjo una gran y centralizada computadora que podríamos llamar un servidor, que ahora proveía cosas al ser humano en términos de tómalo-o-déjalo.

Eran términos, por supuesto, bastante tómalo-o-déjalo y desafortunadamente, todos lo tomaron porque no sabían dejarlo una vez que entraron. Ahora la red estaba hecha de servidores en el centro y clientes en el borde. Los clientes tenían bastante poco poder y los servidores tenían mucho. Mientras el almacenamiento se abarata, mientras el procesamiento se abarata, y mientras los servicios complejos que sólo escalan en formas en que es díficil usar computadoras pequeñas -o en cualquier caso, estas colecciones agregadas de computadoras- para ello, siendo el más importante de todos la búsqueda. Mientras los servicios empezaban a poblar la red, la naturaleza jerárquica de la red empezó a verse como pensada para que así fuera. La red estaba hecha de servidores y clientes y los clientes eran los tipos en el borde representando humanos y los servidores eran las cosas en el medio con montones de poder y montones de datos.

Ahora, una cosa más ocurrió alrededor de ese momento. No ocurrió en las computadoras de Microsoft Windows aunque sí ocurrió en los servidores de Microsoft Windows y también en SOs más sensibles como Unix y BSD entre otros. Es decir, los servidores mantenían registros. Es una cosa muy buena de hacer. Las computadoras deben mantener registros. Fue una decisión muy sabia la de mantener registros, cuando se crea software para sistemas operativos. Ayuda en la inspección, hace realizables los rendimientos, hace posible estudiar las operaciones de las computadoras en el mundo real. Es una muy buena idea.

Pero si tenés un sistema que centraliza servidores y los servidores centralizan los registros, entonces estás creando vastos repositorios de datos jerárquicamente organizados sobre gente en los bordes de la red, sobre el que estos no tienen control y, a menos que tengan experiencia en la operación de servidores, no comprenderán su extensión, su significado, no entenderán su agregabilidad.

Esto fue una receta para el desastre

“Nube” significa que ha ocurrido la virtualización de los servidores. Entonces “nube” significa que los servidores han ganado libertad, libertad de moverse, libertad de danzar, libertad de combinarse y separarse y volverse a agregar y hacer toda clase de trucos. Los servidores ganaron libertad. Los clientes no ganaron nada. Bienvenidos a la nube.

Entonces esta es la arquitectura de la catástrofe. Si lo piensan, cada paso en esa revolución arquitectónica: de una red hecha de pares a servidores que sirven comunicaciones con humanos, a clientes que son programas corriendo sobre metal macizo, a clientes que son computadoras que la gente usa en un estado bastante desempoderado y servidores con una alta concentración de poder en la Red, a servidores como procesos virtuales corriendo en nubes de metal en el centro de una galaxia cada vez más caliente con clientes que están por ahí en los brazos de espiral polvorientos.

Todas esas decisiones arquitecturales fueron hechas sin ninguna discusión sobre sus consecuencias sociales a largo plazo, parte de nuestra dificultad general para hablar de las consecuencias sociales de la tecnología durante el gran período de invención de Internet hecho por científicos informáticos que no estaban terriblemente interesados en sociología, psicología social o, con algunas excepciones brillantes, la libertad. Entonces obtuvimos una arquitectura que estaba bastante sujeta al abuso. Estaba pidiendo que la abusen y ahora estamos teniendo el abuso que creamos. Porque alivianamos los clientes más y más y más. En efecto, los hicimos móviles. Los pusimos en nuestros bolsillos y empezamos a pasear con ellos.

De hecho, lo que tenemos son cosas que llamamos plataformas. La palabra “plataforma” como la palabra “nube” no tiene un significado inherente. Se tira mucho en lenguaje de negocios. Pero, básicamente, lo que significa plataforma es lugar que no podés dejar. Cosas a las que estás clavado. Cosas que no te dejan. Esas son plataformas. Y la Red, una vez que se convirtió en una zona arquitecturada jerárquicamente con servidores en el centro y clientes cada vez más desempoderados en el borde, se convierte en la zona de plataformas y fabricar plataformas se convierte en la orden del día.

Entonces tenemos un montón de gestores de plataformas en una red organizada jerárquicamente y empezamos a desarrollar servicios. “Servicios” es una palabra complicada. No carece para nada de sentido pero es engañoso describirla. La usamos para un montón de cosas distintas. Necesitamos desesperadamente una taxonomía analítica de “servicios”. Las taxonomías de los “servicios” incluyen preguntas acerca de simplicidad, complejidad, escala y control.

Pero esa es la parte inocente de la historia y no nos quedamos en la parte inocente de la historia por una variedad de temas.

Ahora, donde llegamos es a descubrir que todo esto hubiera sido mejor si tuvieran los registros de todo porque una vez que tenés los registros de todo entonces cualquier servicio se convierte en una mina de oro esperando y la jodimos porque la arquitectura de la Red puso los registros en el lugar equivocado. Pusieron los registros donde la inocencia se tentaría. Pusieron los registros donde el estado fallido de los seres humanos implicaba malos problemas y los obtuvimos.

La nube significa que ya ni siquiera podemos apuntar en la dirección del servidor y porque no podemos apuntar en la dirección del servidor no tenemos ningún medio extra técnico o no técnico confiable para controlar este desastre en cámara lenta. Pueden hacer una regla sobre los registros o flujos de datos o preservación o control o acceso o publicación pero sus leyes son humanas y ocupan un territorio particular y el servidor está en la nube y eso significa que el servidor siempre está un paso adelante de cualquier regla que hagas o dos o tres o seis o ¡puf! Me acabo de dar cuenta que estoy sujeto a regulación, creo que me voy a Oceanía.

Lo que significa es que en efecto, perdimos la habilidad para usar regulación legal o cualquier otra cosa sobre la arquitectura física de la red para interferir en el proceso de caída de la inocencia que era ahora inevitable en la etapa de la que hablo, que podríamos llamar Google tardío etapa 1.

Aquí es donde, por supuesto, entra el Sr. Zuckerberg (creador de Facebook)

La raza humana es susceptible al daño pero el Sr. Zuckerberg ha alcanzado un récord envidiable: ha hecho más daño a la raza humana que cualquier otro de su edad.

Todos necesitan acostarse con alguien y él convirtió esto en una estructura para degenerar la integridad de la personalidad humana y hasta una extensión remarcable tuvo éxito con un trato bastante pobre. Es decir, “te voy a dar alojamiento web gratis y algunos pendorchos PHP y también obtenés espionaje gratis todo el tiempo”. Y funciona.

Esa es la parte triste, funciona.

¿Cómo pudo pasar esto?

No había una razón arquitectural, en verdad. No había una razón arquitectural. Facebook es la Web con “Me voy a quedar todos los registros, ¿cómo te sentís sobre eso?” Es un terrario de cómo se siente vivir en un panóptico construido de partes web.

Y no debería permitirse. Se reduce a eso. No debería permitirse. Es una manera muy pobre de entregar esos servicios. Están groseramente sobrevaluados para “espionaje todo el tiempo”. No son técnicamente innovadores. Dependen de una arquitectura sujeta al abuso y el modelo de negocio que lo sostiene es abuso. No hay ningún otro modelo de negocio para ellos. Esto es malo.

No estoy sugiriendo que deba ser ilegal. Tendría que ser obsoleto.

Cuando le digo a mis estudiantes, “por qué dejan que otra gente lea sus correos?”, me responden “pero nadie está leyendo mi correo, ningún ser humano lo ha tocado. Eso me horrorizaría, me asustaría que los tipos de Google estén leyendo mi correo. Pero no está pasando así que no tengo problema.”

Ahora, no podemos decir esto de Facebook. En efecto, ellos saben demasiado sobre Facebook si se permitieran saberlo realmente. Ustedes leyeron y saben. Los trabajadores de Facebook saben quién va a tener un amorío antes que la gente porque pueden ver que X revisa obsesivamente la página en Facebook de Y. Hay algunas investigaciones muy buenas hechas un par de años atrás por estudiantes del MIT que no voy a nombrar porque no respetaron los términos de servicio de Facebook durante su investigación. Sólo estaban revolviendo el contenido de algunas páginas, pero el propósito de esto era demostrar que podían encontrar homosexuales no declarados en Facebook.

No dicen nada sobre su orientación sexual. Sus amigos están declarados, sus intereses son los intereses de sus amigos declarados. Sus fotos están etiquetadas con sus amigos declarados y ellos están declarados sólo que no. Sólo están declarados en Facebook si alguien mira, que seguramente no es lo que tenían en mente y seguramente no es lo que teníamos en mente sobre ellos. En efecto, el grado potencial de desigualdad informacional y la alteración y dificultad que surgen de un malentendido, un error heurístico, en las mentes de los seres humanos acerca de qué es y qué no es descubrible acerca de ellos no es nuestro mayor problema con la privacidad.

Se piensa todavía en la privacidad como “el gran secreto que no quiero que se revele” y ese no es el problema. Su problema es todo el resto que forma el relleno, los datos que rellenan la vida, que no piensan de ninguna manera como un secreto pero que se agrega a lo que no quieren que nadie sepa. Lo que se agrega, en efecto, no sólo a lo que no quieren que otros sepan sino también a modelos predictivos sobre ellos de los que se horrorizarían si supieran que existen. La simplicidad con la que podés desanonimizar datos teóricamente anónimos, la facilidad con la que, de múltiples fuentes disponibles a través de terceras o cuartas partes, se puede ensamblar información, hacer mapas de la vida de la gente. La facilidad con la que empezás a juntar, con las pocas cosas que sabés de la gente, los datos que están disponibles para inferir inmensidad de cosas más.

Mi amigo y colega Bradly Kuhn que trabaja en el Centro Legal del Software Libre (SFLC) es uno de esos seres humanos arcaicos que cree que su número de seguridad social es una cosa privada. Y se toma grandes molestias para asegurarse que su número de seguridad social no sea revelada, lo cual es su derecho bajo nuestra ley, aunque suene raro. Pero, tratá de obtener seguro médico o una caja de depósitos segura, o de hecho, operar en negocios siquiera. A veces hacemos malabares con nuestros asuntos porque el número de seguridad social de Bradly es un secreto. Un día le dije “sabés, ya está, Google ya conoce tu número de seguridad social”. Él dijo, “no, no lo saben, nunca se lo dije a nadie”. Yo dije, “si pero conocen los números de seguridad social de todos los demás que nacieron en Baltimore ese año. El tuyo es el que falta”.

Y como ustedes saben, es verdad. Los datos que inferimos son los datos en los agujeros entre los datos que ya conocemos, si sabemos lo suficiente.

Así que el lugar donde vivimos se ha convertido en un lugar del que sería muy poco inteligente decir que no hay nada que no se sepa. Si sos bastante bien conocido en la Red, y cada uno de nosotros por una razón u otra es bastante bien conocido en la Red. Queremos vivir ahí. Es nuestro vecindario. Lo que no queremos es vivir con una cámara en cada árbol y un micrófono en cada arbusto y un minero de datos bajo nuestros pies mientras caminamos y la Red es así ahora. Este no es un juicio estético del ’95 sobre cómo el vecindario se llenó de gente que no comparte nuestro etnocentrismo tecnogeek. No estoy lamentando el progreso de alguna forma democratizante. Al contrario, lamento el progreso hostil a la libertad humana. Todos sabemos lo que es hostil a la libertad humana. Todos comprendemos las posibilidades despóticas gracias a las distopías en que es fértil la ciencia ficción que leímos cuando éramos chicos. La Guerra Fría fue fértil en la invención fantástica de cómo vivimos ahora y es difícil aceptarlo aunque sea verdad. Afortunadamente, por supuesto, no es propiedad del gobierno. Bueno, lo es. Es afortunado. Es verdad. Es afortunado que sea propiedad de gente a la que podemos sobornar no importa quién seas. Si sos el gobierno hay formas muy fáciles de hacerlo. Llenás un formulario de citación (subpoena) y lo mandás por correo.

Tenemos que avivarnos si somos los que nos preocupamos por la libertad, el juego empezó hace tiempo y estamos atrasados. Hicimos muchas cosas buenas y tenemos un montón de herramientas dando vueltas que construimos durante los últimos 25 años. Esas herramientas estén por ahí pero tenemos que admitir que no las hemos usado para proteger la libertad porque la libertad está decayendo.

Lo que necesitamos es hacer algo tan grasoso que no haya otra plataforma de red social nunca más. ¿Podemos hacerlo? Si, absolutamente. Está bien a nuestro alcance.

¿Vamos a hacerlo antes que el IPO de Facebook? ¿O vamos a esperar hasta después? ¿Realmente? ¿Honestamente? Seriamente. El problema que tiene la ley muy a menudo en el mundo en que vivimos y practicamos y trabajamos, el problema que la ley tiene muy a menudo, es el problema que la tecnología puede solucionar. Y el problema que la tecnología puede solucionar es el lugar al que vamos a la ley. Ese es el movimiento del software libre. Está el hacking de software por acá y está el hacking legal por allá y cuando juntás ambos el todo es superior a la suma de las partes. Entonces, no es que tenemos que vivir en la catástrofe. No es que empezar a revertir la catástrofe es difícil para nosotros. Necesitamos rearquitecturar los servicios en la Red. Necesitamos redistribuir los servicios de vuelta hacia los bordes. Necesitamos devirtualizar los servidores donde nuestra vida está almacenada y necesitamos recuperar alguna autonomía para vos como el dueño del servidor.

Este es un desafío técnico por una razón social. Es una frontera por explorar de la gente técnica. Hay un enorme retorno social por hacerlo.

Ahora les digo a mis estudiantes “¿pueden encontrar un lugar donde no haya cámaras?” Ahora, lo que pasó en ese proceso fue que creamos inmensos auxiliares cognitivos para el Estado -enormes máquinas para escuchar. Estamos rodeados de datos explotables.

Adaptación de **Libertad en la nube, Libertad del Software, Privacidad y Seguridad para la Web 2.0 y Computación en la Nube
Eben Monglen **

Para ver versión completa ir a  http://endefensadelsl.org/freedom_in_the_cloud.html
