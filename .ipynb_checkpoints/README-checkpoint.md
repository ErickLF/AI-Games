## AI-Games

Este proyecto consiste en que nuestra computadora aprenda a jugar videojuegos clasicos del atari.
Para ello descargaremos todo lo que necesitamos directamente desde [aquí](https://github.com/openai/baselines).

Nosotros tomaremos como referencia [este proyecto](https://github.com/dgriff777/rl_a3c_pytorch) 

### Instalación

```
git clone https://github.com/openai/baselines.git
cd baselines
pip install -e .
```
Algunos errores que pudieras obtener son que no tienes:
* mpi4py:

  Para solucionarlo realiza estos pasos:      
      ```
      sudo apt install libopenmpi-dev
      sudo pip install mpi4py
      ```
  
* atari-py
    Para solucionarlo haz esto:
        ```
        sudo apt-get install libz-dev
        ```
### JPruebas

Realizaremos diferentes pruebas con diferentes metodos de aprendizaje entre ellos se encuentran:

* Actor Critico
* Deep Q Learning
* Politicas 

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
