# infodigital-clase-03
<!DOCTYPE html>
<html lang="es">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous" />
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Sans:ital,wght@0,300;0,400;0,600;1,400&display=swap" rel="stylesheet">
        <style>
            :root { --bs-font-sans-serif: 'IBM Plex Sans', sans-serif;}
            @media (min-width: 992px) { .container{max-width: 960px;} }
            h1,h2,h3{ letter-spacing: 0.1rem; }
            hr{ border: 1px solid solid; max-width: 10vh; margin: 2.5rem auto;}
        </style>
        <title>Reemplaza este título que se muestra en la ventana de tu navegador</title>
    </head>
    <body class="bg-dark text-white">
        <header class="container">
            <div class="row py-4">
                <div class="col-sm-11 col-md-10 col-lg-9 col-xl-8 col-xxl-7 mx-auto">
                    <h1 class="mb-3 mt-5 text-center">CLASE 3</h1>
                    <h2 class="mb-5 text-center text-uppercase fs-6 text-white-50">Olivia Bacigalupo & Manuela Munchmeyer</h2>
                    <p class="lead">Las gráficas en las infografías nos permiten acercarnos de una manera visual a la información y procesarla rápidamente.
                    Existen tres tipos de gráficas que se usan para representar la información y que veremos a continuación.</p>
                </div>
            </div>
        </header>
        <main class="container">
            <div class="row g-4 pb-5">
                <div class="col-sm-11 col-md-10 col-lg-9 col-xl-8 col-xxl-7 mx-auto">
                    <hr>
                    <h3 class="text-center my-5">GRÁFICA FIGURATIVA</h3>
                    <p>En la Gráfica figurativa se representan la información a través de imágenes, ilustraciones, simbolos, etc y permite entenderla y procesarla de una manera más simple, visual y rápida. "Gráficos figurativos son aquellos que representan fenómenos físicos; en ellos generalmente existe una cierta similitud entre lo representado y la forma visual" (Cairo, 2011:31).</p>
                </div>                
                <!--primera imagen-->
                <div class="col-12 col-sm-6">
                    <figure class="shadow bg-black">
                        <img loading="lazy" src="img/imagen-1.PNG" class="w-100" alt="describe lo que se ve en la imagen" />
                        <figcaption class="p-3 small text-white-50">"The Godfather at 50", 2022.</figcaption>
                    </figure>
                </div>
                <!--segunda imagen-->
                <div class="col-12 col-sm-6">
                    <figure class="shadow bg-black">
                        <img loading="lazy" src="img/imagen-2.jpg" class="w-100" alt="describe lo que se ve en la imagen" />
                        <figcaption class="p-3 small text-white-50">"Bamboo Curtains", 2022.</figcaption>
                    </figure>
                </div>
                <!--tercera imagen-->
                <div class="col-12 col-sm-6">
                    <figure class="shadow bg-black">
                        <img loading="lazy" src="img/imagen-3.jpg" class="w-100" alt="describe lo que se ve en la imagen" />
                        <figcaption class="p-3 small text-white-50">"Life in a shoe box", 2022.</figcaption>
                    </figure>
                </div>
                <!--cuarta imagen-->
                <div class="col-12 col-sm-6">
                    <figure class="shadow bg-black">
                        <img loading="lazy" src="img/imagen-4.jpg" class="w-100" alt="describe lo que se ve en la imagen" />
                        <figcaption class="p-3 small text-white-50">"Subdivided flat living", 2022.</figcaption>
                    </figure>
                </div>
                <!--no hay más imágenes-->
            </div>
            <div class="row g-4 pb-5">
                <div class="col-sm-11 col-md-10 col-lg-9 col-xl-8 col-xxl-7 mx-auto">
                    <hr>                    
                    <h3 class="text-center my-5">GRÁFICA MIXTA</h3>
                    <p>La Gráfica mixta combina la Gráfica figurativa y la Gráfica no figurativa, en dónde podemos ver mucha información y datos en gráficos que nos permite dimensionar la información junto a imágenes o ilustraciones para visualizar el contexto.</p>
                </div>
                <!--primera imagen-->
                <div class="col-12 col-sm-6">
                    <figure class="shadow bg-black">
                        <img loading="lazy" src="img/imagen-5.JPG" class="w-100" alt="describe lo que se ve en la imagen" />
                        <figcaption class="p-3 small text-white-50">"Pedal power", 2022.</figcaption>
                    </figure>
                </div>
                <!--segunda imagen-->
                <div class="col-12 col-sm-6">
                    <figure class="shadow bg-black">
                        <img loading="lazy" src="img/imagen-6.PNG" class="w-100" alt="describe lo que se ve en la imagen" />
                        <figcaption class="p-3 small text-white-50">"Ebola outbreaks", 2014.</figcaption>
                    </figure>
                </div>
                <!--no hay más imágenes-->
            </div>
            <div class="row g-4 pb-5">
                <div class="col-sm-11 col-md-10 col-lg-9 col-xl-8 col-xxl-7 mx-auto">
                    <hr>
                    <h3 class="text-center my-5">GRÁFICA NO FIGURATIVA</h3>
                    <p>La Gráfica no figurativa es capaz de abstraer datos e información y llevarlos a una configuración visual que muestra lo que en realidad no se puede ver, donde las estadísticas se logran visualizar, "Con los gráficos no figurativos se puede convertir la cantidad estadística en una cualidad visible" (Boehm, 2010, p.104).</p>                    
                </div>
                <!--solo un gráfico-->
                <div class="col-md-12 col-lg-11 col-xl-10 col-xxl-9 mx-auto">
                    <figure class="shadow bg-black">
                        <img loading="lazy" src="img/imagen-7.svg" class="w-100" alt="describe lo que se ve en la imagen" />
                        <figcaption class="p-3 small text-white-50">Gráfico de Población en cada Continente.</figcaption>
                    </figure>
                </div>
                <div class="col-sm-11 col-md-10 col-lg-9 col-xl-8 col-xxl-7 mx-auto">
                    <p class="small text-white-50 mb-5">La gráfica de arriba se despliega en la página como si se tratara de una imagen rasterizada, con el elemento <a href="https://developer.mozilla.org/es/docs/Web/HTML/Element/img" target="_blank">&lt;img&gt;</a>. Otros elementos de HTML podrían usarse para un mejor despliegue del SVG. Reviseramos tales elementos algunas clases más adelante, pero ya les conviene revisar <a href="https://css-tricks.com/using-svg/" target="_blank">Using SVG | CSS Trick</a>.</p>
                </div>
            </div>
        </main>
        <footer>
            <div class="container">
                <div class="row py-3">
                <div class="col-sm-11 col-md-10 col-lg-9 col-xl-8 col-xxl-7 mx-auto">
                        <p class="d-flex justify-content-between small p-1 m-0">
                            <a href="https://github.com/profesorfaco/dno075-2022-2/">Infografía Digital</a>
                            <a href="https://github.com/profesorfaco/dno075-2022-2/tree/main/clase-03">Lunes 22 de agosto, 2022</a>
                        </p>
                    </div>
                </div>
            </div>
        </footer>
        <script>
            var links = document.querySelectorAll('a');
            links.forEach(l => l.classList.add("link-light"));
            console.log("Esto es JavaScript");
        </script>
    </body>
</html>
