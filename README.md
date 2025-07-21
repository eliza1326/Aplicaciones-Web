# Aplicaciones-Web
2025 UEA
Semana 8
Index.htlm:
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Handeli Perfumería Artesanal</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header class="bg-light py-3">
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container">
                <a class="navbar-brand" href="#">Handeli Perfumería</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ms-auto">
                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="#">Inicio</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#productos">Nuestros Perfumes</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#catalogo-completo">Catálogo Completo</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#ofertas">Recargas y Ofertas</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#experiencia">Experiencia Handeli</a> </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#contacto">Contacto</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#nosotros">Sobre Nosotros</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <main class="container my-5">
        <section id="carousel-section" class="mb-5">
            <h2 class="text-center mb-4">Descubre Nuestras Fragancias Exclusivas</h2>
            <div id="handeliCarousel" class="carousel slide" data-bs-ride="carousel">
                <div class="carousel-indicators">
                    <button type="button" data-bs-target="#handeliCarousel" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                    <button type="button" data-bs-target="#handeliCarousel" data-bs-slide-to="1" aria-label="Slide 2"></button>
                    <button type="button" data-bs-target="#handeliCarousel" data-bs-slide-to="2" aria-label="Slide 3"></button>
                </div>
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img src="https://via.placeholder.com/1200x400/FFDDC1/800000?text=Ultramale+Perfume+Handeli" class="d-block w-100" alt="Perfume Ultramale">
                        <div class="carousel-caption d-none d-md-block">
                            <h5>Ultramale - Jean Paul Gaultier</h5>
                            <p>Una fragancia audaz y carismática.</p>
                        </div>
                    </div>
                    <div class="carousel-item">
                        <img src="https://via.placeholder.com/1200x400/C1FFDD/008000?text=212+Perfume+Handeli" class="d-block w-100" alt="Perfume 212">
                        <div class="carousel-caption d-none d-md-block">
                            <h5>212 - Carolina Herrera</h5>
                            <p>La esencia de la ciudad moderna y vibrante.</p>
                        </div>
                    </div>
                    <div class="carousel-item">
                        <img src="https://via.placeholder.com/1200x400/DDC1FF/4B0082?text=Perfume+Arabe+Handeli" class="d-block w-100" alt="Perfume Árabe">
                        <div class="carousel-caption d-none d-md-block">
                            <h5>OUD Esencia - Perfume Árabe</h5>
                            <p>Profundidad y misterio en un aroma oriental.</p>
                        </div>
                    </div>
                </div>
                <button class="carousel-control-prev" type="button" data-bs-target="#handeliCarousel" data-bs-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Previous</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#handeliCarousel" data-bs-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Next</span>
                </button>
            </div>
        </section>

        <section class="text-center my-4">
            <button id="alertBtn" class="btn btn-info btn-lg">¡Descubre Novedades Handeli!</button>
        </section>

        <section id="productos" class="mb-5">
            <h2 class="text-center mb-4">Nuestros Perfumes de Diseñador Destacados</h2>
            <div class="table-responsive">
                <table class="table table-striped table-hover align-middle">
                    <thead class="table-dark">
                        <tr>
                            <th scope="col">Perfume</th>
                            <th scope="col">Marca/Tipo</th>
                            <th scope="col">Tamaño</th>
                            <th scope="col">Precio</th>
                            <th scope="col">Oferta Especial</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>Ultramale</td>
                            <td>Jean Paul Gaultier</td>
                            <td>30ml</td>
                            <td>$10.00</td>
                            <td>-</td>
                        </tr>
                        <tr>
                            <td>Ultramale</td>
                            <td>Jean Paul Gaultier</td>
                            <td>50ml</td>
                            <td>$15.00</td>
                            <td>Porta perfumero de regalo</td>
                        </tr>
                        <tr>
                            <td>Ultramale</td>
                            <td>Jean Paul Gaultier</td>
                            <td>100ml</td>
                            <td>$25.00</td>
                            <td>Crema hidratante 70gr de regalo (mismo olor o a escoger)</td>
                        </tr>
                        <tr>
                            <td>212</td>
                            <td>Carolina Herrera</td>
                            <td>30ml</td>
                            <td>$10.00</td>
                            <td>-</td>
                        </tr>
                        <tr>
                            <td>212</td>
                            <td>Carolina Herrera</td>
                            <td>50ml</td>
                            <td>$15.00</td>
                            <td>Porta perfumero de regalo</td>
                        </tr>
                        <tr>
                            <td>212</td>
                            <td>Carolina Herrera</td>
                            <td>100ml</td>
                            <td>$25.00</td>
                            <td>Crema hidratante 70gr de regalo (mismo olor o a escoger)</td>
                        </tr>
                        <tr>
                            <td>OUD Esencia</td>
                            <td>Perfume Árabe</td>
                            <td>30ml</td>
                            <td>$10.00</td>
                            <td>-</td>
                        </tr>
                        <tr>
                            <td>OUD Esencia</td>
                            <td>Perfume Árabe</td>
                            <td>50ml</td>
                            <td>$15.00</td>
                            <td>Porta perfumero de regalo</td>
                        </tr>
                        <tr>
                            <td>OUD Esencia</td>
                            <td>Perfume Árabe</td>
                            <td>100ml</td>
                            <td>$25.00</td>
                            <td>Crema hidratante 70gr de regalo (mismo olor o a escoger)</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </section>

        <section id="catalogo-completo" class="mb-5 bg-light p-4 rounded">
            <h2 class="text-center mb-4">Descubre Nuestro Amplio Catálogo de Fragancias</h2>
            <p class="lead text-center mb-4">Contamos con una extensa colección de perfumes de diseñador y árabes para satisfacer todos los gustos y ocasiones. ¡Explora la diversidad de aromas que Handeli tiene para ti!</p>
            <p class="text-center mb-5">Actualmente, disponemos de *más de 51 fragancias femeninas, 51 esencias masculinas y 25 perfumes árabes*.</p>

            <div class="row">
                <div class="col-md-4 mb-4">
                    <h4 class="text-primary">Fragancias Masculinas</h4>
                    <ul class="list-group">
                        <li class="list-group-item">Si Giorgio Armani</li>
                        <li class="list-group-item">Acqua di Gio Giorgio Armani</li>
                        <li class="list-group-item">Hugo Red Hugo Boss</li>
                        <li class="list-group-item">Homme Dior</li>
                        <li class="list-group-item">1 Million Lucky Paco Rabanne</li>
                        <li class="list-group-item">Invictus Paco Rabanne</li>
                        <li class="list-group-item">Eros Versace</li>
                        <li class="list-group-item">Phantom Paco Rabanne</li>
                        <li class="list-group-item">Sauvage Dior</li>
                        <li class="list-group-item">212 Men CH</li>
                        <li class="list-group-item">XS Black Paco Rabanne</li>
                    </ul>
                </div>
                <div class="col-md-4 mb-4">
                    <h4 class="text-primary">Fragancias Femeninas</h4>
                    <ul class="list-group">
                        <li class="list-group-item">Katy Perry's Meow</li>
                        <li class="list-group-item">Ariana Grande Cloud Pink</li>
                        <li class="list-group-item">Allure Homme Sport (Chanel)</li>
                        <li class="list-group-item">Good Girl Blush Carolina Herrera</li>
                        <li class="list-group-item">So Scandal! Jean Paul Gaultier</li>
                        <li class="list-group-item">De Ma L'Elixir Jean Paul Gaultier</li>
                        <li class="list-group-item">Fantasy Britney Spears</li>
                        <li class="list-group-item">Very Good Girl CH</li>
                        <li class="list-group-item">Coconut Passion</li>
                        <li class="list-group-item">Can Can Paris Hilton</li>
                        <li class="list-group-item">Yes I Am Cacharel</li>
                        <li class="list-group-item">Miss Dior Dior</li>
                        <li class="list-group-item">Lolita Lempicka</li>
                        <li class="list-group-item">La Vie Est Belle</li>
                    </ul>
                </div>
                <div class="col-md-4 mb-4">
                    <h4 class="text-primary">Perfumes Árabes y Especiales</h4>
                    <ul class="list-group">
                        <li class="list-group-item">Amber Oud Gold Al Haramain</li>
                        <li class="list-group-item">Khamrah Lattafa</li>
                        <li class="list-group-item">Acqua Media Cologne (Club de Nuit Armaf)</li>
                        <li class="list-group-item">Baccarat Rouge 540</li>
                        <li class="list-group-item">Angel Mugler</li>
                        <li class="list-group-item">CR7 Cristiano Ronaldo</li>
                        <li class="list-group-item">Odyssey Mandarine Sky Armani Code</li>
                    </ul>
                </div>
            </div>
            <p class="text-center mt-4">¡Visítanos para descubrir el catálogo completo y encontrar tu fragancia ideal!</p>
        </section>

        <section id="ofertas" class="mb-5 bg-light p-4 rounded">
            <h2 class="text-center mb-4">Recargas y Descuentos Especiales</h2>
            <div class="row">
                <div class="col-md-6 mb-4">
                    <div class="card h-100">
                        <div class="card-body">
                            <h5 class="card-title text-center text-primary">¡Reutiliza tu Envase! - Precios de Recarga</h5>
                            <ul class="list-group list-group-flush">
                                <li class="list-group-item d-flex justify-content-between align-items-center">
                                    Recarga 30ml
                                    <span class="badge bg-success rounded-pill">$7.00</span>
                                </li>
                                <li class="list-group-item d-flex justify-content-between align-items-center">
                                    Recarga 50ml
                                    <span class="badge bg-success rounded-pill">$10.00</span>
                                </li>
                                <li class="list-group-item d-flex justify-content-between align-items-center">
                                    Recarga 100ml
                                    <span class="badge bg-success rounded-pill">$15.00</span>
                                </li>
                            </ul>
                            <p class="card-text mt-3 text-muted text-center">Ayudamos al planeta y a tu bolsillo.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 mb-4">
                    <div class="card h-100">
                        <div class="card-body">
                            <h5 class="card-title text-center text-primary">Oferta por Volumen: ¡Tu Tercer Perfume con Regalo!</h5>
                            <p class="card-text">
                                Al realizar la compra de *3 perfumes* (ya sean de 50ml o 100ml), te obsequiamos una fragancia de *30ml completamente gratis*.
                            </p>
                            <p class="card-text text-center mt-3"><small class="text-muted">Combina tus aromas favoritos y lleva un regalo.</small></p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="experiencia" class="mb-5">
            <h2 class="text-center mb-4">Experiencia Handeli: Cuidado en Cada Detalle</h2>
            <p class="lead text-center mb-5">Cada entrega de Handeli es una experiencia cuidadosamente empaquetada, diseñada para deleitar. Mira cómo preparamos tu fragancia.</p>
            <div class="row g-4">
                <div class="col-md-6 col-lg-4">
                    <div class="card h-100 shadow-sm">
                        <img src="http://googleusercontent.com/file_content/0" class="card-img-top" alt="Perfume con crema hidratante de regalo">
                        <div class="card-body text-center">
                            <h5 class="card-title">Tu Perfume y Regalo Especial</h5>
                            <p class="card-text">Nuestras fragancias de 100ml vienen con una crema hidratante de 70gr, ¡el complemento perfecto!</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-lg-4">
                    <div class="card h-100 shadow-sm">
                        <img src="http://googleusercontent.com/file_content/1" class="card-img-top" alt="Perfume con porta perfumero de regalo">
                        <div class="card-body text-center">
                            <h5 class="card-title">Practicidad y Elegancia</h5>
                            <p class="card-text">Las compras de 50ml incluyen un práctico porta perfumero para llevar tu aroma a todas partes.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-lg-4">
                    <div class="card h-100 shadow-sm">
                        <img src="http://googleusercontent.com/file_content/2" class="card-img-top" alt="Ultramale con crema y empaque">
                        <div class="card-body text-center">
                            <h5 class="card-title">El Toque Distintivo de Diseñador</h5>
                            <p class="card-text">Perfumes icónicos como Ultramale, presentados con su crema correspondiente y empaque premium.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-lg-4">
                    <div class="card h-100 shadow-sm">
                        <img src="http://googleusercontent.com/file_content/3" class="card-img-top" alt="Perfume Phantom con empaque">
                        <div class="card-body text-center">
                            <h5 class="card-title">Envases Exclusivos</h5>
                            <p class="card-text">Cada fragancia de diseñador es entregada con el cuidado y la presentación que merece.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-lg-4">
                    <div class="card h-100 shadow-sm">
                        <img src="http://googleusercontent.com/file_content/4" class="card-img-top" alt="Jean Paul Gaultier Le Male con empaque">
                        <div class="card-body text-center">
                            <h5 class="card-title">Autenticidad y Calidad</h5>
                            <p class="card-text">Garantizamos la originalidad y la excelencia en cada perfume que adquieres.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-lg-4">
                    <div class="card h-100 shadow-sm">
                        <img src="http://googleusercontent.com/file_content/5" class="card-img-top" alt="Perfumes de recarga y muestra">
                        <div class="card-body text-center">
                            <h5 class="card-title">Recargas y Muestras Personalizadas</h5>
                            <p class="card-text">Tu perfume favorito, siempre contigo. Opción de recarga y muestras para explorar.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>


        <section id="contacto" class="mb-5">
            <h2 class="text-center mb-4">Contáctanos</h2>
            <div class="row justify-content-center">
                <div class="col-md-8 col-lg-6">
                    <form id="contactForm" novalidate>
                        <div class="mb-3">
                            <label for="nombre" class="form-label">Nombre completo</label>
                            <input type="text" class="form-control" id="nombre" required>
                            <div class="invalid-feedback">
                                Por favor, ingresa tu nombre.
                            </div>
                        </div>
                        <div class="mb-3">
                            <label for="email" class="form-label">Correo Electrónico</label>
                            <input type="email" class="form-control" id="email" required>
                            <div class="invalid-feedback">
                                Por favor, ingresa un correo electrónico válido.
                            </div>
                        </div>
                        <div class="mb-3">
                            <label for="mensaje" class="form-label">Mensaje</label>
                            <textarea class="form-control" id="mensaje" rows="5" required></textarea>
                            <div class="invalid-feedback">
                                Por favor, escribe tu mensaje.
                            </div>
                        </div>
                        <button type="submit" class="btn btn-primary w-100">Enviar Mensaje</button>
                    </form>
                </div>
            </div>
        </section>

        <section id="nosotros" class="my-5">
            <h2 class="text-center mb-4">Sobre Handeli Perfumería</h2>
            <p class="lead text-center">En Handeli, somos especialistas en *perfumes de diseñador* y *fragancias árabes, ofreciendo una cuidada selección de más de **51 fragancias femeninas, 51 esencias masculinas y 25 perfumes árabes. Contamos con aromas icónicos como **Ultramale de Jean Paul Gaultier* y *212 de Carolina Herrera*, entre muchos otros exclusivos. Creamos fragancias artesanales únicas y recargables, inspiradas en la naturaleza y la pasión por los aromas. Cada perfume es una obra de arte, cuidadosamente elaborada para despertar tus sentidos, ofreciendo calidad, exclusividad y sostenibilidad.</p>
        </section>

    </main>

    <footer class="bg-dark text-white text-center py-4">
        <div class="container">
            <p>&copy; 2025 Handeli Perfumería Artesanal. Todos los derechos reservados.</p>
            <p>Contacto: info@handeli.com | Síguenos en:
                <a href="#" class="text-white mx-2"><i class="fab fa-facebook-f"></i></a>
                <a href="#" class="text-white mx-2"><i class="fab fa-instagram"></i></a>
                <a href="#" class="text-white mx-2"><i class="fab fa-twitter"></i></a>
            </p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
    <script src="script.js"></script>

