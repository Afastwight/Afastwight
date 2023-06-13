### Hi there 👋

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.2/css/all.min.css" integrity="sha512-1sCRPdkRXhBV2PBLUdRb4tMg1w2YPf37qatUFeS7zlBy7jJI8Lf4VHwWfZZfpXtYSLy85pkm9GaYVYMfw5BC1A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <title>Portfolio</title>
    <link rel="shortcut icon" href="icon.jpg" type="image/x-icon">
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <!-- MENU ENCABEZADO -->
    <div class="contenedor-header">
        <header>
            <div class="logo">
                <a href="#">Antonio</a>
            </div>
            <nav id="nav">
                <ul>
                    <li><a href="#inicio" onclick="seleccionar()">INICIO</a></li>
                    <li><a href="#sobremi" onclick="seleccionar()">SOBRE MI</a></li>
                    <li><a href="#skills" onclick="seleccionar()">SKILLS</a></li>
                    <li><a href="#curriculum" onclick="seleccionar()">CURRICULUM</a></li>
                    <li><a href="#portfolio" onclick="seleccionar()">PORTFOLIO</a></li>
                    <li><a href="#contacto" onclick="seleccionar()">CONTACTO</a></li>
                </ul>
            </nav>
            <div class="nav-responsive" onclick="mostrarOcultarMenu()">
                <i class="fa-solid fa-bars"></i>
            </div>
        </header>
    </div>

    <!-- SECCION INICIO -->
    <section id="inicio" class="inicio">
        <div class="contenido-banner">
            <div class="contenedor-img">
                <img src="fotohero.jpeg" alt="">
            </div>
            <h1>Antonio Tapia</h1>
            <h2>Ing.Sistema de la informacion - Programador junior</h2>
            <div class="redes">
                <a href="#"><i class="fa-brands fa-facebook-f"></i></a>
                <a href="#"><i class="fa-brands fa-twitter"></i></a>
                <a href="#"><i class="fa-brands fa-skype"></i></a>
                <a href="#"><i class="fa-brands fa-linkedin-in"></i></a>
                <a href="#"><i class="fa-solid fa-rss"></i></a>
            </div>
        </div>
    </section>

    <!-- SECCION SOBRE MI -->
    <section id="sobremi" class="sobremi">
        <div class="contenido-seccion">
            <h2>Sobre Mí</h2>
            <p><span>Hola, soy Antonio Tapia.</span> Programador independiente, emprededor y autodidacta dia tras dia. Actualmente cursando la carrera de Ingenieria en Sistema de la Informacion en la Facultad de Ing.Industrial. Motivado y encantado si puedo entrar a formar parte de su equipo de trabajo y poder aplicar todos los conocimientos y, al mismo tiempo, que me brinda la oportunidad de desarrollarme profesionalmente. </p>

            <div class="fila">
                <!-- datos personales -->
                <div class="col">
                    <h3>Datos Personales</h3>
                    <ul>
                        <li>
                            <strong>Cumpleaños</strong>
                            01-06-2003
                        </li>
                        <li>
                            <strong>Teléfono</strong>
                            0997963005
                        </li>
                        <li>
                            <strong>Email</strong>
                            antoniotapiaalvarez@gmail.com
                        </li>
                        <li>
                            <strong>linkedin</strong>
                            https://www.linkedin.com/in/antonio-tapia-0aab6820b/
                        </li>
                        <li>
                            <strong>Dirección</strong>
                            Av.Narcisa de Jesus,   Ecuador, Guayas
                        </li>
                        <li>
                            <strong>Cargo</strong>
                            <span>FREELANCE</span>
                        </li>
                    </ul>
                </div>

                <!-- intereses -->
                <div class="col">
                    <h3>Intereses</h3>
                    <div class="contenedor-intereses">
                        <div class="interes">
                            <i class="fa-solid fa-gamepad"></i>
                            <span>JUEGOS</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-headphones"></i>
                            <span>MUSICA</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-plane"></i>
                            <span>VIAJAR</span>
                        </div>
                        <div class="interes">
                            <i class="fa-brands fa-android"></i>
                            <span>ANDORID</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-futbol"></i>
                            <span>DEPORTE</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-book"></i>
                            <span>LIBROS</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-car"></i>
                            <span>AUTOS</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-camera"></i>
                            <span>FOTOS</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-chess-king"></i>
                            <samp>AJEDRES</samp>
                        </div>
                        
                    </div>
                </div>
            </div>
            <button>
                Descargar CV <i class="fa-solid fa-download"></i>
                <span class="overlay"></span>
            </button>
        </div>
    </section>

    <!-- SECCION SKILLS -->
    <section class="skills" id="skills">
        <div class="contenido-seccion">
            <h2>Skills</h2>
            <div class="fila">
                <!-- Technical Skill -->
                <div class="col">
                    <h3>Technical Skills</h3>
                    <div class="skill">
                        <span>Javascript</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>75%</span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>HTML & CSS</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>89%</span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Python</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>95%</span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Java</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>81%</span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Unity</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>55%</span>
                            </div>
                        </div>
                    </div>
                </div>
                <!-- Professional Skills -->
                <div class="col">
                    <h3>Professional Skills</h3>
                    <div class="skill">
                        <span>Comunicación</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>80%</span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Trabajo en Equipo</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>70%</span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Creatividad</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>99%</span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Dedicación</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>65%</span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Líder</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>94%</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- SECCION CURRICULUM -->
    <section id="curriculum" class="curriculum">
        <div class="contenido-seccion">
            <h2>Curriculum</h2>
            <div class="fila">
                <div class="col izquierda">
                    <h3>Educación</h3>
                    <div class="item izq">
                        <h4>Colegio</h4>
                        <span class="casa">Dr.Alfredor Raul Vera Vera</span>
                        <span class="fecha">2008 - 2021</span>
                        <p>Entre a la edad de los 5 años a primero de basico, Curse toda la escuela y a los 15 entre al colegio. Graduandome de bachiller en ciencia en el 2021 a la edad de 18 años.</p>
                        <div class="conectori">
                            <div class="circuloi"></div>
                        </div>
                    </div>
                    <div class="item izq">
                        <h4>Universidad Estatal de Guayaquil</h4>
                        <span class="casa">Facultad de Ingenieria en Sistema de la Informacion</span>
                        <span class="fecha">2021 - Actualidad</span>
                        <p>Durante la pandemia que empezo a finales del 2020 transcurrio mi prueba de seneci, la aceptacion y el ingreso a la universidad. Mi carrera tiene 8 semestre que equivale a 4 años. Actualmente estoy en mi 4 semestre. </p>
                        <div class="conectori">
                            <div class="circuloi"></div>
                        </div>
                    </div>
                    <div class="item izq">
                        <h4>Cursos</h4>
                        <span class="casa">Cursos Online</span>
                        <span class="fecha">2020 - Actualidad</span>
                        <p>Durante la cuarentena participe en varios curso de programacion en los temas de paginas web y creacion de aplicaciones donde tenemos: Html,Css,JavaScript - Python,Java,Unity. </p>
                        <div class="conectori">
                            <div class="circuloi"></div>
                        </div>
                    </div>
                </div>

                <div class="col derecha">
                    <h3>Proyectos</h3>
                    <div class="item der">
                        <h4>Python</h4>
                        <span class="casa">Shooter</span>
                        <span class="fecha">2022</span>
                        <p>Es un videojuego creado en python, utilizando las librerias tkinter, pygame y json. En donde el jugador es una nave espacial y dispara los meteorios que salen aletoriamente en la pantalla. El objetivo del juego es evitar que la nave choque con el meteoro.</p>
                        <div class="conectord">
                            <div class="circulod"></div>
                        </div>
                    </div>
                    <div class="item der">
                        <h4>Html Css Javascript</h4>
                        <span class="casa">Curriculum CV</span>
                        <span class="fecha">2023</span>
                        <p>Pagina Web diseñado con html,css y javascript. Que ofrece un curriculum CV donde explico mis habilidades, mi linea de formacion, mis proyectos, cursos y  donde cuento un poco sobre mi.</p>
                        <div class="conectord">
                            <div class="circulod"></div>
                        </div>
                    </div>
                    <div class="item der">
                        <h4>Java</h4>
                        <span class="casa">Whatsapp</span>
                        <span class="fecha">2022</span>
                        <p>Este proyecto nacio como nota final del semestre en la materia de programacion. Esta seria una similitud con Whatsapp en donde nosotros creariamos una interfaz grafica con javafx y que para guardar los usuarios, es decir los contactos conectariamos con postgresql para guardar los datos mas mensajes.</p>
                        <div class="conectord">
                            <div class="circulod"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- SECCION PORTFOLIO -->
    <section id="portfolio" class="portfolio">
        <div class="contenido-seccion">
            <h2>PORTFOLIO</h2>
            <div class="galeria">
                <div class="proyecto">
                    <img src="img/p1.jpg" alt="">
                    <div class="overlay">
                        <h3>Diseño Creativo</h3>
                        <p>Fotografía</p>
                    </div>
                </div>
                <div class="proyecto">
                    <img src="img/p2.jpg" alt="">
                    <div class="overlay">
                        <h3>Diseño Creativo</h3>
                        <p>Fotografía</p>
                    </div>
                </div>
                <div class="proyecto">
                    <img src="img/p3.jpg" alt="">
                    <div class="overlay">
                        <h3>Diseño Creativo</h3>
                        <p>Fotografía</p>
                    </div>
                </div>
                <div class="proyecto">
                    <img src="img/p4.jpg" alt="">
                    <div class="overlay">
                        <h3>Diseño Creativo</h3>
                        <p>Fotografía</p>
                    </div>
                </div>
                <div class="proyecto">
                    <img src="img/p5.jpg" alt="">
                    <div class="overlay">
                        <h3>Diseño Creativo</h3>
                        <p>Fotografía</p>
                    </div>
                </div>
                <div class="proyecto">
                    <img src="img/p6.jpg" alt="">
                    <div class="overlay">
                        <h3>Diseño Creativo</h3>
                        <p>Fotografía</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- SECCION CONTACTO -->
    <section id="contacto" class="contacto">
        <div class="contenido-seccion">
            <h2>CONTACTO</h2>
            <div class="fila">
                <!-- Formulario -->
                <div class="col">
                    <input type="text" placeholder="Tú Nombre">
                    <input type="text" placeholder="Número telefónico">
                    <input type="text" placeholder="Dirección de correo">
                    <input type="text" placeholder="Tema">
                    <textarea name="" id="" cols="30" rows="10" placeholder="Mensaje"></textarea>
                    <button>
                        Enviar Mensaje<i class="fa-solid fa-paper-plane"></i>
                        <span class="overlay"></span>
                    </button>
                </div>
                <!-- Mapa -->
                <div class="col">
                    <img src="direccion.png" alt="">
                    <div class="info">
                        <ul>
                            <li>
                                <i class="fa-solid fa-location-dot"></i>
                                Ecuador, Guayaquil, Cdla del rio
                            </li>
                            <li>
                                <i class="fa-solid fa-mobile-screen"></i>
                                Llamanos: 0997963005
                            </li>
                            <li>
                                <i class="fa-solid fa-envelope"></i>
                                Email: antoniotapiaalvarez@gmail.com
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- footer -->
    <footer>
        <a href="#inicio" class="arriba">
            <i class="fa-solid fa-angles-up"></i>
        </a>
        <div class="redes">
            <a href="#"><i class="fa-brands fa-facebook-f"></i></a>
            <a href="#"><i class="fa-brands fa-twitter"></i></a>
            <a href="#"><i class="fa-brands fa-skype"></i></a>
            <a href="#"><i class="fa-brands fa-linkedin-in"></i></a>
            <a href="#"><i class="fa-solid fa-rss"></i></a>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
