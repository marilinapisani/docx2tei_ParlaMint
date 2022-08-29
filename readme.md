# **Codificación en TEI de un Corpus de Interacciones Parlamentarias con Python**

En los últimos años, por su disponibilidad, estructura y contenido, los estudios de corpus basados en la interacción parlamentaria se han vuelto numerosos (Truan and Romary, 2021). 
Dentro de estos estudios, el proyecto [ParlaMint](https://github.com/clarin-eric/ParlaMint) contribuye a la creación de corpus de sesiones parlamentarias comparables y uniformemente anotados (Erjavec, T., Ogrodniczuk, M., Osenova, P. et al, 2022).
Para obtener esta uniformidad, el proyecto ofrece esquemas RelaxNG y códigos XSLT de validación. 

Aquí se presenta un propuesta para automatizar en Python el etiquetado en TEI de documentos DOCX, que combina técnicas de análisis exploratorio de los datos y guías de etiquetado en TEI. 
Se toman como ejemplo de aplicación las transcripciones de las sesiones del Parlamento de Cataluña entre 2015 y 2020.

La guía detallada se desarrolla en un cuaderno de [Colab](https://bit.ly/3pRsxtS).

**Referencias**

Erjavec, T., Ogrodniczuk, M., Osenova, P., Ljubešić, N., Simov, K., Pančur, A., Rudolf, M., Kopp, M., Barkarson, S., Steingrímsson, S., Çöltekin, Ç., de Does, J., Agnoloni, T., Venturi, G., Pérez, M., de Macedo, L. D., Navarretta, C., Luxardo, G., & Fišer, D. (2022, February 2). The ParlaMint corpora of parliamentary proceedings. Language Resources and Evaluation. https://doi.org/10.1007/s10579-021-09574-0

Truan, N., & Romary, L. (2022, June 22). Building, Encoding, and Annotating a Corpus of Parliamentary Debates in TEI XML: A Cross-Linguistic Account. Journal of the Text Encoding Initiative, (14). https://doi.org/10.4000/jtei.4164
