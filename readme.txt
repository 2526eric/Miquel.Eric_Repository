<html>
# Portal AI - Projecte web

Projecte web sobre **Intel·ligència Artificial** creat per [Èric] i [Miquel].

## Estructura de carpetes

```
/ (arrel)
  |- index.html
  |- about.html
  |- models.html
  |- gallery.html
  |- nosaltres.html
  |- membre1.html
  |- membre2.html
  |- contact.html
  |- css/
      |- style.css
  |- img/
      |- gallery/
      |- membres/
  |- README.md
```

## Entrega
- Creeu un repositori privat a GitHub i pugeu tots els fitxers. 
- Afegiu els noms dels membres al `README.md` i concediu accés al professor.

---

<!-- FILE: index.html -->
<!DOCTYPE html>
<html lang="ca">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portal IA - Inici</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header class="site-header">
    <h1>Portal Intel·ligència Artificial</h1>
    <nav class="main-nav">
      <a href="index.html">Inici</a>
      <a href="about.html">Sobre la IA</a>
      <a href="models.html">Models</a>
      <a href="gallery.html">Galeria</a>
      <a href="nosaltres.html">Nosaltres</a>
      <a href="contact.html">Contacte</a>
    </nav>
  </header>

  <main>
    <section>
      <h2>Benvingut/da al portal sobre Intel·ligència Artificial</h2>
      <p>Aquest portal explica conceptes bàsics i exemples reals d'IA. Aquí trobaràs seccions amb informació, una galeria d'imatges, i fitxes d'alguns models destacats.</p>
      <ul>
        <li>Definició i història</li>
        <li>Models i aplicacions</li>
        <li>Galeria i recursos</li>
      </ul>
    </section>

    <section>
      <h3>Recurs recomanat</h3>
      <p>Aprèn les etiquetes HTML i CSS mentre llegeixes sobre IA amb els recursos suggerits al Moodle.</p>
      <p style="font-weight:bold;">Prova a navegar a la secció <a href="models.html">Models</a> per veure una llista estructurada.</p>
    </section>
  </main>

  <footer class="site-footer">
    <p>&copy; 2025 Portal IA. Creat per [Nom1] i [Nom2].</p>
  </footer>
</body>
</html>


<!-- FILE: about.html -->
<!DOCTYPE html>
<html lang="ca">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portal IA - Sobre la IA</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header class="site-header">
    <h1>Portal Intel·ligència Artificial</h1>
    <nav class="main-nav">
      <a href="index.html">Inici</a>
      <a href="about.html">Sobre la IA</a>
      <a href="models.html">Models</a>
      <a href="gallery.html">Galeria</a>
      <a href="nosaltres.html">Nosaltres</a>
      <a href="contact.html">Contacte</a>
    </nav>
  </header>

  <main>
    <article>
      <h2>Què és la Intel·ligència Artificial?</h2>
      <p>La intel·ligència artificial (IA) és la branca de la informàtica que es dedica a crear sistemes capaços de realitzar tasques que normalment requereixen intel·ligència humana.</p>

      <h3>Història breu</h3>
      <ol>
        <li>1950s — Naixement del concepte.</li>
        <li>1980s — Xarxes neuronals i aprenentatge.</li>
        <li>2010s — Aprenentatge profund i aplicacions comercials.</li>
      </ol>
    </article>
  </main>

  <footer class="site-footer">
    <p>&copy; 2025 Portal IA. Creat per [Nom1] i [Nom2].</p>
  </footer>
</body>
</html>


<!-- FILE: models.html -->
<!DOCTYPE html>
<html lang="ca">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portal IA - Models</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header class="site-header">
    <h1>Portal Intel·ligència Artificial</h1>
    <nav class="main-nav">
      <a href="index.html">Inici</a>
      <a href="about.html">Sobre la IA</a>
      <a href="models.html">Models</a>
      <a href="gallery.html">Galeria</a>
      <a href="nosaltres.html">Nosaltres</a>
      <a href="contact.html">Contacte</a>
    </nav>
  </header>

  <main>
    <h2>Models destacats</h2>

    <section>
      <h3>Taula de models</h3>
      <table>
        <thead>
          <tr>
            <th>Model</th>
            <th>Tipus</th>
            <th>Any</th>
            <th>Aplicacions</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Perceptró / Xarxa neuronal</td>
            <td>Classificació</td>
            <td>1950s</td>
            <td>Visió, reconeixement</td>
          </tr>
          <tr>
            <td>GPT (transformers)</td>
            <td>LLM / NLP</td>
            <td>2018+</td>
            <td>Generació de text, xatbots</td>
          </tr>
          <tr>
            <td>ResNet</td>
            <td>Visió per computador</td>
            <td>2015</td>
            <td>Classificació d'imatges</td>
          </tr>
        </tbody>
      </table>
    </section>

    <section>
      <h3>Llistat estructurat de models (exemple)</h3>
      <ul>
        <li>
          <strong>GPT-5</strong> — Model de llenguatge per a generació de text i assistència.
        </li>
        <li>
          <strong>Stable Diffusion</strong> — Generació d'imatges a partir de text.
        </li>
        <li>
          <strong>YOLO</strong> — Detecció d'objectes en temps real.
        </li>
      </ul>
    </section>
  </main>

  <footer class="site-footer">
    <p>&copy; 2025 Portal IA. Creat per [Nom1] i [Nom2].</p>
  </footer>
</body>
</html>


<!-- FILE: gallery.html -->
<!DOCTYPE html>
<html lang="ca">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portal IA - Galeria</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header class="site-header">
    <h1>Portal Intel·ligència Artificial</h1>
    <nav class="main-nav">
      <a href="index.html">Inici</a>
      <a href="about.html">Sobre la IA</a>
      <a href="models.html">Models</a>
      <a href="gallery.html">Galeria</a>
      <a href="nosaltres.html">Nosaltres</a>
      <a href="contact.html">Contacte</a>
    </nav>
  </header>

  <main>
    <h2>Galeria d'imatges</h2>
    <p>Imatges d'exemples d'IA (col·loca les imatges a `/img/gallery/`).</p>

    <div class="gallery">
      <figure>
        <img src="img/gallery/ai1.jpg" alt="Exemple IA 1">
        <figcaption>Generació d'imatges</figcaption>
      </figure>
      <figure>
        <img src="img/gallery/ai2.jpg" alt="Exemple IA 2">
        <figcaption>Xarxa neuronal</figcaption>
      </figure>
      <figure>
        <img src="img/gallery/ai3.jpg" alt="Exemple IA 3">
        <figcaption>Visualització de dades</figcaption>
      </figure>
    </div>
  </main>

  <footer class="site-footer">
    <p>&copy; 2025 Portal IA. Creat per [Nom1] i [Nom2].</p>
  </footer>
</body>
</html>


<!-- FILE: nosaltres.html -->
<!DOCTYPE html>
<html lang="ca">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portal IA - Nosaltres</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header class="site-header">
    <h1>Portal Intel·ligència Artificial</h1>
    <nav class="main-nav">
      <a href="index.html">Inici</a>
      <a href="about.html">Sobre la IA</a>
      <a href="models.html">Models</a>
      <a href="gallery.html">Galeria</a>
      <a href="nosaltres.html">Nosaltres</a>
      <a href="contact.html">Contacte</a>
    </nav>
  </header>

  <main>
    <h2>Equip</h2>
    <p>Aquesta secció conté enllaços a la pàgina individual de cada membre (cada membre crea la seva pàgina amb CV en taula).</p>

    <ul>
      <li><a href="membre1.html">[Nom1]</a></li>
      <li><a href="membre2.html">[Nom2]</a></li>
    </ul>
  </main>

  <footer class="site-footer">
    <p>&copy; 2025 Portal IA. Creat per [Nom1] i [Nom2].</p>
  </footer>
</body>
</html>


<!-- FILE: membre1.html -->
<!DOCTYPE html>
<html lang="ca">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portal IA - [Nom1]</title>
  <link rel="stylesheet" href="css/style.css">
  <style>
    /* estil intern requerit per a la pàgina del membre */
    .cv-table { width: 100%; border-collapse: collapse; }
    .cv-table th, .cv-table td { padding: 8px; border: 1px solid #ccc; }
  </style>
</head>
<body>
  <header class="site-header">
    <h1>Portal Intel·ligència Artificial</h1>
    <nav class="main-nav">
      <a href="index.html">Inici</a>
      <a href="about.html">Sobre la IA</a>
      <a href="models.html">Models</a>
      <a href="gallery.html">Galeria</a>
      <a href="nosaltres.html">Nosaltres</a>
      <a href="contact.html">Contacte</a>
    </nav>
  </header>

  <main>
    <h2>[Nom1] — CV</h2>

    <img src="img/membres/nom1.jpg" alt="Foto Nom1" style="width:150px; border-radius:8px;">

    <table class="cv-table">
      <tr>
        <th>Nom</th>
        <td>[Nom1]</td>
      </tr>
      <tr>
        <th>Data de naixement</th>
        <td>01/01/2006</td>
      </tr>
      <tr>
        <th>Estudis</th>
        <td>ESO / Batxillerat</td>
      </tr>
      <tr>
        <th>Habilitats</th>
        <td>HTML, CSS, interès en IA</td>
      </tr>
    </table>

    <p style="color: #555;">Breus comentaris personals sobre el projecte i la teva contribució.</p>
  </main>

  <footer class="site-footer">
    <p>&copy; 2025 Portal IA. Creat per [Nom1] i [Nom2].</p>
  </footer>
</body>
</html>


<!-- FILE: membre2.html -->
<!DOCTYPE html>
<html lang="ca">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portal IA - [Nom2]</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header class="site-header">
    <h1>Portal Intel·ligència Artificial</h1>
    <nav class="main-nav">
      <a href="index.html">Inici</a>
      <a href="about.html">Sobre la IA</a>
      <a href="models.html">Models</a>
      <a href="gallery.html">Galeria</a>
      <a href="nosaltres.html">Nosaltres</a>
      <a href="contact.html">Contacte</a>
    </nav>
  </header>

  <main>
    <h2>[Nom2] — CV</h2>

    <img src="img/membres/nom2.jpg" alt="Foto Nom2" style="width:150px; border-radius:8px;">

    <table class="cv-table">
      <tr>
        <th>Nom</th>
        <td>[Nom2]</td>
      </tr>
      <tr>
        <th>Data de naixement</th>
        <td>02/02/2006</td>
      </tr>
      <tr>
        <th>Estudis</th>
        <td>ESO / Batxillerat</td>
      </tr>
      <tr>
        <th>Habilitats</th>
        <td>HTML, CSS, investigació en IA</td>
      </tr>
    </table>

    <p style="color: #555;">Comentaris personals sobre el treball en equip i la secció que has preparat.</p>
  </main>

  <footer class="site-footer">
    <p>&copy; 2025 Portal IA. Creat per [Nom1] i [Nom2].</p>
  </footer>
</body>
</html>


<!-- FILE: contact.html -->
<!DOCTYPE html>
<html lang="ca">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portal IA - Contacte</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header class="site-header">
    <h1>Portal Intel·ligència Artificial</h1>
    <nav class="main-nav">
      <a href="index.html">Inici</a>
      <a href="about.html">Sobre la IA</a>
      <a href="models.html">Models</a>
      <a href="gallery.html">Galeria</a>
      <a href="nosaltres.html">Nosaltres</a>
      <a href="contact.html">Contacte</a>
    </nav>
  </header>

  <main>
    <h2>Contacte</h2>
    <p>Pàgina fictícia de contacte: podeu posar email o formulari (sense funcionar) si voleu.</p>

    <form>
      <label for="name">Nom:</label><br>
      <input type="text" id="name" name="name"><br>
      <label for="email">Email:</label><br>
      <input type="email" id="email" name="email"><br>
      <label for="message">Missatge:</label><br>
      <textarea id="message" name="message"></textarea><br>
      <input type="submit" value="Envia">
    </form>
  </main>

  <footer class="site-footer">
    <p>&copy; 2025 Portal IA. Creat per [Nom1] i [Nom2].</p>
  </footer>
</body>
</html>


<!-- FILE: css/style.css -->
/* CSS extern requerit */
* { box-sizing: border-box; }
body { font-family: Arial, Helvetica, sans-serif; margin:0; padding:0; background:#f7f7f7; color:#222; }
.site-header { background:#0b3d91; color:white; padding:12px 20px; }
.site-header h1 { margin:0; font-size:20px; }
.main-nav { margin-top:8px; }
.main-nav a { color:white; text-decoration:none; margin-right:12px; }
.main-nav a:hover { text-decoration:underline; }
main { padding:20px; max-width:1000px; margin:0 auto; background:white; }
.site-footer { text-align:center; padding:12px; background:#eaeaea; margin-top:12px; }

table { width:100%; border-collapse:collapse; margin-bottom:16px; }
th, td { padding:8px; border:1px solid #ddd; }

.gallery { display:flex; gap:12px; flex-wrap:wrap; }
.gallery figure { width:30%; background:#fff; padding:8px; border:1px solid #ddd; }
.gallery img { width:100%; height:auto; display:block; }

/* Estils interns i inline també s'han utilitzat a pàgines de membres */


<!-- FILE: .gitignore -->
node_modules/
.DS_Store

</