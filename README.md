**TL;DR**

- Mira el número de página en `Propuestas_PDI_MUIA.pdf` de los TFMs que te interesan
- Los PDFs se nombran `pg[número de pagina en PDF]__[palabras clave]__[nombre del equipo].pdf`. Ejemplo `pg1__RedesGenerativasAstronomia__PacoPaulaPedro.pdf`. Lee los PDFs sobre TFMs que te interesen
- Si el equipo `[nombre del equipo]` ha rellenado [`00_notebook/candidates.csv`](00_notebook/candidates.csv), entonces puedes chekear sus stats con el notebook [`00_notebook/template.ipynb`](00_notebook/template.ipynb).
- Tanto los PDFs como el notebook te ayudarán a evitar rivales fuertes, y aplicar a TFMs que tal vez no te son tan interesantes, pero donde tú eres la competencia a batir.

### Motivación

El 15 de diciembre solo tenemos 1 bala, solo 1, si otro trío es "mejor" que el tuyo pues has perdido, da igual que pierdas por muy poco que por mucho, **has perdido**.

Y no solo has perdido ese TFM, sino que otros TFMs donde tu candidatura podría ser la mejor (si hubieras aplicado ahí) puede que se asignen y tampoco puedas optar más a ellos.

Lo ideal es saber quien aplica a cada TFM, así:
- Si mi candidatura es top, pues evito competir con otros, ya que no se arriesgarán a competir contra tops
- Y si mi candidatura es modesta, pues sabré donde aplican los tops, así les evito y tengo más opciones.

Es un win-win para ambos. Solo los tríos menos pro les hace esta estrategia perder. Ya que todo TFM interesante tendrá al menos una propuesta modesta (contra la que pierden).

Suponiendo que somos balanceados, es decir, hay tantos equipos tops como modestos como muy-modestos, pues el compartir información ayuda al 66%!

Incluso a los muy-modestos puede ayudar. Ya que si ven que sin escoger quedan solo TFMs que no quieren, pues invertirán energías en pensar propuestas propias.


### Uso de notebook


1. Clonar el repositorio
```sh
git clone https://github.com/juanMarinero/UNIR-MasterAI-TFM-applications-comparative.git
cd 00_notebook  
```

2. Abre con Google-Colab

Ó alternativamente:

2. Crear el entorno virtual
3. Instalar las dependencias (numpy, pandas, matplotlib,...)

```sh
pip install -r requirements.txt
```

4. Instala jupyterlab y ejecuta el notebook


### Demuestra que eres un top, evita a la competencia

#### PDF

Pull request de `pg[número de pagina en PDF]__[palabras clave]__[nombre del equipo].pdf`. Ejemplo `pg1__RedesGenerativasAstronomia__PacoPaulaPedro.pdf`.

El redactar este PDF también ayuda para cuando al presentar la candidatura destaques lo bueno que es tu equipo.

#### Dataset

Haz un pull request de [`00_notebook/candidates.csv`](00_notebook/candidates.csv) con los campos rellenados para tu equipo.

- Mismo `TeamName-unique` para todo el equipo
- Mismo `PDF_page` para todo el equipo. Ejemeplo para TFMs de astronomia por ejemplo valores solo 1, 3, 5 ó 53.
- Solo 1 candidatura por equipo. Si ves que otra candidatura posterior te supera en el mismo TFM y quieres editar el campo `PDF_page`, entonces haz un pull request con los cambios.

En columna comentarios de [`00_notebook/candidates_template.csv`](00_notebook/candidates_template.csv) se explica porque algunos campos tienen decimales. Ideal si cada registro con decimales también lo justifica.

Puedes poner los valores que querais, no voy a revisar nada excepto el campo `Bonus`.

Si no aportais un enlace a linkedin (o parecido), pues la credibilidad de cada registro es baja.
