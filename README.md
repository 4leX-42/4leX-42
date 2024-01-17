<h1 align="center">
  <b>Arbusto</b>
</h1>

¡Hola! Soy Arbusto, actualmente vivo en Numancia de la Sagra, España. Estoy preparándome para 
<a href="https://es.wikipedia.org/wiki/Tu_Examen">Tu Examen</a>, 
y aprendiendo programación a través de pequeños proyectos.

<br>

<p>
<div align="center">
  <img src="https://img.shields.io/badge/-HTML-c58545?style=for-the-badge&logo=html5&logoColor=c58545&labelColor=282828">
  <img src="https://img.shields.io/badge/-CSS-d1a01f?style=for-the-badge&logo=css3&logoColor=d1a01f&labelColor=282828">
  <img src="https://img.shields.io/badge/-Python-98b982?style=for-the-badge&logo=python&logoColor=98b982&labelColor=282828">
</div>
</p>

```python
class Arbusto():
    
  def __init__(self):
    self.name = "Arbusto";
    self.username = "arbusto";
    self.location = "Numancia de la Sagra, España";
    self.twitter = "@arbusto";
    self.web = "https://arbusto.dev";
  
  def __str__(self):
    return self.name

if __name__ == '__main__':
    me = Arbusto()
