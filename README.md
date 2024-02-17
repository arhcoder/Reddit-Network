# 📚 DATOS MASIVOS II
## 💻 Instituto de Investigaciones en Matemáticas Aplicadas y en Sistemas
## 🏫 Universidad Nacional Autónoma de México

<hr>

### 🤖 Reddit Comunities
### 🟠 Enlaces entre SubReddits
#### 👨‍👩‍👧‍👦 Análisis de Redes Sociales

<br>

#### Realizado por:
#### Iván Alejadro Ramos Herrera
#### 💜 [@arhcoder](https://github.com/arhcoder)


# 📓 Dataset

## Reddit - Subreddits - Relations
### Fuente: https://snap.stanford.edu/data/soc-RedditHyperlinks.html
### Información del dataset:

> La red de hipervínculos representa las conexiones dirigidas entre dos subreddits (un subreddit es una comunidad en Reddit). También proporciona embeddings de subreddit. La red se extrae de datos de Reddit disponibles públicamente de 2.5 años desde enero de 2014 hasta abril de 2017.

> **Red de hipervínculos de subreddit:** la red de hipervínculos de subreddit a subreddit se extrae de las publicaciones que crean hipervínculos de un subreddit a otro. Decimos que un hipervínculo se origina en una publicación en la comunidad de origen y se vincula a una publicación en la comunidad de destino. Cada hipervínculo está anotado con tres propiedades: la marca de tiempo, el sentimiento de la publicación de la comunidad de origen hacia la publicación de la comunidad de destino y el vector de propiedad de texto de la publicación de origen. La red es dirigida, firmada, temporal y atribuida.

> Tenga en cuenta que cada publicación tiene un título y un cuerpo. El hipervínculo puede estar presente en el título de la publicación o en el cuerpo. Por lo tanto, proporcionamos un archivo de red para cada uno.

> **Embeddings de subreddit:** también proporcionamos vectores de incrustación que representan cada subreddit. Estos se pueden encontrar en el enlace de este conjunto de datos: subreddit incrustando conjunto de datos. Tenga en cuenta que no se pudieron generar algunas incrustaciones de subreddit, por lo que este archivo tiene 51,278 incrustaciones.

> **Sitio web del proyecto:** estos archivos se generaron como parte del proyecto de investigación sobre cómo los subreddits se atacan entre sí. Los detalles del proyecto se pueden encontrar aquí.

**Dataset statistics**

|  |  |
| ------------------ | - |
| Number of nodes (subreddits) |	55,863 |
| Number of edges (hyperlink between subreddits) |	858,490 |
| Edge weights (label of hyperlink) | 	-1 or +1 |
| Edge attributes | Text property vectors |
| Timespan | Jan 2014 - April 2017 |