#### Filosofía y conceptos de Linux ####

#### Objetivos de aprendizaje ####

Al final de este capítulo, usted debería ser capaz de:
- Discutir la historia y la filosofía de Linux.
- Describir la comunidad Linux.
- Definir los términos comunes asociados con Linux.
- Discutir los componentes de una distribución de Linux.

#### Introducción ####

Linux es un sistema operativo de computadora de código abierto, inicialmente desarrollado para computadoras personales basadas en **Intel x86**. Posteriormente se ha migrado a muchas otras plataformas de hardware.

En esta sección, se familiarizará con cómo Linux evolucionó de un proyecto de estudiante a un esfuerzo masivo con un enorme impacto en el mundo de hoy.

#### Historia de Linux ####

Linus Torvalds estudió en Helsinki, Finlandia, en 1991, cuando comenzó un proyecto: escribir su propio **kernel** de sistema operativo. También reunió y/o desarrolló los otros ingredientes esenciales necesarios para construir un **sistema operativo** completo con su núcleo en el centro. Pronto, esto se hizo conocido como el kernel de **Linux**.

En 1992, Linux autorizó nuevamente la utilización de la **General Public License (GPL)** por GNU (un proyecto de la Free Software Foundation o FSF, que promueve el software disponible gratuitamente), lo que permitió construir una comunidad mundial de desarrolladores. Al combinar el núcleo con otros componentes del sistema del proyecto GNU, muchos otros desarrolladores crearon sistemas completos llamados **distribuciones de Linux** a mediados de los 90.

#### Más sobre la historia de Linux ####

Las distribuciones de Linux creadas a mediados de los años 90 proporcionaron la base para una informática totalmente gratuita y se convirtieron en una fuerza motriz en el movimiento del software de código abierto. En 1998, importantes compañías como **IBM** y **Oracle** anunciaron su apoyo a la plataforma Linux y también comenzaron importantes esfuerzos de desarrollo.

Hoy, Linux alimenta a más de la mitad de los servidores en Internet, la mayoría de los teléfonos inteligentes (a través del sistema **Android**, que está construido sobre Linux) y casi todos los supercomputadores más poderosos del mundo.

#### Knowledge Check ####

When did Linus Torvalds start writing the Linux kernel?

- [ ] 1952
- [x]1991
- [ ] 2002
- [ ] 2010

#### Introducción ####

Cada organización o proyecto tiene una filosofía que funciona como una guía al enmarcar sus objetivos y delinear su camino de crecimiento. Esta sección contiene una descripción de la filosofía de Linux y cómo esta filosofía ha impactado su desarrollo.

Linux es constantemente mejorado y mantenido por una red de desarrolladores de todo el mundo que colaboran a través de Internet, con Linus Torvalds a la cabeza. La habilidad técnica y el deseo de contribuir son los únicos requisitos para participar.

### Filosofía de Linux ####

Linux toma prestado mucho del sistema operativo **UNIX** porque fue escrito para ser una versión de fuente abierta y gratuita de **UNIX**. Los archivos se almacenan en un sistema de archivos jerárquico, con el nodo superior del sistema como raíz o simplemente "/". Siempre que sea posible, Linux hace que sus componentes estén disponibles a través de archivos u objetos que se parecen a los archivos. Los procesos, los dispositivos y los sockets de red están representados por objetos similares a archivos y, a menudo, se puede trabajar utilizando las mismas utilidades que se usan para los archivos normales.

Linux es una **multitarea** completa (es decir, múltiples subprocesos de ejecución se realizan simultáneamente), sistema operativo **multiusuario**, con una red incorporada y procesos de servicio conocidos como **demonios** en el mundo **UNIX**.

#### Knowledge Check ####

- [x] Linux was written to be a free and open source version of UNIX.
- [ ] Linux makes its components available via its servers.
- [x] Processes, devices, and network sockets are all represented by file-like objects, and can often be worked with using the same utilities used for regular files.
- [x] In Linux all files are stored in one united directory tree, starting at "/", the system's root directory.

That's correct!

Linux borrows heavily from the UNIX operating system because it was written to be a free and open source version of UNIX. Files are stored in a hierarchical filesystem, with the top node of the system being root directory or simply "/". Whenever possible, Linux makes its components available via files. Processes, devices, and network sockets are all files, and can often be worked with using the same utilities used for regular files.

What are the qualifications required for participating in Linux kernel development?

- [x] Technical skills
- [x] A desire to contribute
- [ ] Citizen of the U.S.
- [ ] University degree in computer science

#### Introducción a la Comunidad ####

Supongamos que, como parte de su trabajo, necesita configurar un servidor de archivos Linux y se encuentra con algunas dificultades. Si no puede averiguar la respuesta usted mismo u obtener ayuda de un compañero de trabajo, ¡la comunidad Linux podría salvar el día! Hay muchas maneras de interactuar con la comunidad Linux: puede publicar consultas en foros de discusión relevantes, suscribirse a hilos de discusión e incluso unirse a grupos locales de Linux que se encuentran en su área.

#### La comunidad de Linux ####

#### Más sobre la comunidad de Linux ####

La comunidad Linux es un ecosistema de gran alcance que consiste en desarrolladores, administradores de sistemas, usuarios y proveedores, que usan muchos foros diferentes para conectarse entre sí. Entre los más populares están:

- Grupos de usuarios de Linux (tanto locales como en línea)
- **I**nternet **R**elay **C**hat (**IRC**) software (como **Pidgin** y **XChat**)
- Comunidades en línea y paneles de discusión
- Grupos de noticias y listas de correo, incluyendo la **Lista de Correo del Kernel de Linux**
- Eventos de la comunidad (como las **Cumbres de código abierto** y las **Conferencias de Linux integradas**)

Una de las comunidades de usuarios en línea más poderosas es linux.com. Este sitio está alojado por la Fundación Linux y sirve a más de un millón de visitantes únicos cada mes. Tiene secciones activas en:

- Noticias
- Temas de discusión de la comunidad
- Tutoriales gratuitos y consejos para el usuario.

En este curso, nos referiremos varias veces a artículos relevantes o tutoriales en este sitio.

#### Knowledge Check ####

Which of the following communication channels does the Linux community use to communicate?

- [ ] cnn.com
- [x] IRC Channels
- [x] Mailing Lists
- [x] Community Events

#### Introducción ####

Cuando comiences a explorar Linux, pronto encontrarás términos desconocidos, como distribución, gestor de arranque, entorno de escritorio, etc. Por lo tanto, antes de seguir adelante, detengámonos y echemos un vistazo a la terminología básica utilizada en Linux para ayudarte a obtener hasta la velocidad.

#### Terminología de Linux ####

#### Knowledge Check ####

What is a kernel?

- [] The glue between hardware and applications.
- [] A collection of software making up a Linux-based Operating System.
- [] A program that runs as a background process.
- [] A graphical subsystem on nearly all Linux systems.

What is a desktop environment?

- [] A collection of software making up a Linux-based Operating System.
- [] A program that runs as a background process.
- [] A graphical subsystem on nearly all Linux systems.
- [] A graphical user interface on top of the Operating System.

What is a command line?

- [] A collection of software making up a Linux-based Operating system.
- [] A program that runs as a background process.
- [] An interface for typing commands for the Operating System to execute.
- [] A list of commands requested to be run in the order presented.

#### Introducción ####

Supongamos que se le ha asignado un proyecto para construir un producto para una plataforma Linux. Los requisitos del proyecto incluyen asegurarse de que el proyecto funcione correctamente en las distribuciones de Linux más utilizadas. Para lograr esto, debe aprender sobre los diferentes componentes, servicios y configuraciones asociados con cada distribución. Estamos a punto de ver cómo harías exactamente eso.

#### Linux Distributions ####
Entonces, ¿qué es una distribución de Linux y cómo se relaciona con el kernel de Linux?

Como se ilustró anteriormente, el kernel de Linux es el núcleo de un sistema operativo de computadora. Una **distribución completa de Linux** consiste en kernel más una serie de otras herramientas de software para operaciones relacionadas con archivos, administración de usuarios y administración de paquetes de software. Cada una de estas herramientas proporciona una pequeña parte del sistema completo. Cada herramienta es a menudo su propio proyecto separado, con sus propios desarrolladores trabajando para perfeccionar esa parte del sistema.

Anotar

#### Más sobre las distribuciones de Linux ####

Como se mencionó anteriormente, el kernel de Linux actual, junto con los núcleos de Linux anteriores (así como versiones de versiones anteriores) se pueden encontrar en el sitio web www.kernel.org. Las diversas distribuciones de Linux pueden basarse en diferentes versiones de kernel. Por ejemplo, la muy popular distribución **RHEL 7** se basa en la versión 3.10 del kernel de Linux, que no es nueva, pero es extremadamente estable. Otras distribuciones pueden moverse más rápidamente al adoptar las últimas versiones del kernel. Es importante tener en cuenta que el kernel no es una proposición de todo o nada, por ejemplo, **RHEL 7** y **CentOS 7** han incorporado muchas de las mejoras más recientes al kernel en su versión de 3.10, al igual que **Ubuntu 16.04** y **openSUSE-Leap-42.2** y SLES-12 **SP2** en sus respectivas versiones del kernel 4.4.

Los ejemplos de otras herramientas e ingredientes esenciales proporcionados por las distribuciones incluyen el compilador **C/C++**, el depurador **gdb**, las aplicaciones de las bibliotecas del sistema central para enlazar con el fin de ejecutar, la interfaz de bajo nivel para dibujar gráficos en la pantalla, así como el entorno de escritorio de nivel superior y el sistema para instalar y actualizar los diversos componentes, incluido el kernel mismo.

#### Servicios asociados con distribuciones ####

La gran variedad de distribuciones de Linux está diseñada para atender a muchas audiencias y organizaciones diferentes, de acuerdo con sus necesidades y gustos específicos. Sin embargo, las grandes organizaciones, como las empresas y las instituciones gubernamentales y otras entidades, tienden a elegir las principales distribuciones comercialmente compatibles de **Red Hat**, **SUSE** y **Canonical (Ubuntu)**.

**CentOS** es una popular alternativa gratuita a **Red Hat Enterprise Linux (RHEL)** y, a menudo, es utilizada por organizaciones que se sienten cómodas al operar sin soporte técnico pagado. **Ubuntu** y **Fedora** son populares en el ámbito educativo. **Scientific Linux** es favorecido por la comunidad de investigación científica por su compatibilidad con paquetes de software matemáticos y científicos. Tanto **CentOS** como **Scientific Linux** son compatibles con Binary **RHEL**; es decir, los paquetes de software binario en la mayoría de los casos se instalarán correctamente en todas las distribuciones.

Muchos distribuidores comerciales, incluidos **Red Hat**, **Ubuntu**, **SUSE** y **Oracle**, brindan soporte a largo plazo basado en tarifas para sus distribuciones, así como certificación de hardware y software. Todos los distribuidores principales brindan servicios de actualización para mantener su sistema preparado con las últimas mejoras de seguridad y corrección de errores, y mejoras de rendimiento, así como también proporcionar recursos de soporte en línea.

#### Knowledge Check ####

In addition to the kernel, what are some of the purposes of the other software tools required for developing a full Linux distribution?

- [] Performing file-related operations
- [] Catering to different audiences
- [] Maintaining user management
- [] Taking care of software package management

Which of the following are binary-compatible Linux distributions which are free alternatives to Red Hat Enterprise Linux (RHEL)? Choose all that apply.

- [] CentOS
- [] Ubuntu
- [] Scientific Linux
- [] openSUSE

#### Resumen ####

Has completado este capítulo. Vamos a resumir los conceptos clave cubiertos:

- Linux toma mucho del sistema operativo **UNIX**, con el cual sus creadores estaban bien versados.
- Linux accede a muchas características y servicios a través de archivos y objetos similares a archivos.
- Linux es un sistema operativo multitarea y multiusuario, con una red integrada y procesos de servicio conocidos como daemons.
- Linux es desarrollado por una confederación de desarrolladores de todo el mundo, colaborando a través de Internet, con Linus Torvalds a la cabeza. La habilidad técnica y el deseo de contribuir son los únicos requisitos para participar.
- La comunidad Linux es un ecosistema de desarrolladores, proveedores y usuarios de gran alcance que respalda y adelanta el sistema operativo Linux.
- Algunos de los términos comunes utilizados en Linux son: núcleo, distribución, gestor de arranque, servicio, sistema de archivos, sistema de ventanas X, entorno de escritorio y línea de comandos.
- Una distribución completa de Linux consiste en kernel más una serie de otras herramientas de software para operaciones relacionadas con archivos, administración de usuarios y administración de paquetes de software.
