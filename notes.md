### Miguel Cabrera - Building Data Pipelines with Python - TrustYou @Berlin

* Un poco lo mismo de Daniel Moreno, pero con Luigi.
* JODER, en realidad deberiamos usar esto para el end-to-end data challenge en DESI.
* `import luigi` 

### Daniel Moreno - Airflow to manage workflows.

* `github.com/apacha/incubator-airflow`
* `pip instal airflow`, `pip install airflow[mysql]`
* IDEA: Cual seria la posibilidad de usar airflow para mover/procesar datos de DESI?
* demorenoc.github.io/slides/pycon-co-2017/airflow

### Manuel Kauffman (Genio!)

* Como hacer preguntas inteligentes de Eric Raymond.
* TODO: buscar, definitivamente todo lo que el ha hecho en python argentina,
  especialmente lo del viaje por el pais.
* IDEA: Unir todo lo de astro4dev con la COMUNIDAD python que ya esta haciendo
  cosas con comunidad.xs
* IDEA: Repensar el metodo de Django Girls para actividades de astro3dev.
* IDEA: comprar muchas raspberry pys para hacer talleres de programacion en lugares
  donde es dificil acceder a laptops.
* IDEA: Hablar con la Python Software Foundation para unir esfuerzos con la OAD.
* MOTTO: Siempre hablar de astronomia en cualquier lugar que nos encontremos.

### Peder - Data Science.

* Lab vs. Factory  
* Analysis vs. Building. Stats vs Code. Static vs. Live.  
* Data Science is Hard: Data + technical prblems, skill set, machine learning ops.  
* margingoodson ten ways your data project is going to fail.  
* github.com/ianozsvald/data_science_delivered  
* good cultures: data democratizations, clear objectives.
* raw data -> clean data -> strategic insight -> real world scoring
* Spark, Luigi, Airflow, Dask. Herramientas para dataflow.
* How to deploy a model. Jupyter, yhat, domino, palladium, azure, flask microservice
* Zinkevich rules for deploying ML models.
* www.peadarcoyle.com
* LIME para reducir la complejidad de resultados de ML y hacerlo entendible para humanos.


### Hacking my car with python (Ariel Nunez, Barranquilla)

* DeepDrive Universe: youtube video to see how a neural network plays
  grandtheftauto.  
* A cellphone could run the neural network, but the current implementation
  uses an nvidia card.  
* Their company is called PiensaLabs.  

### Image Processing and computer vision. Jorge Martinez (also working at PiensaLabs, Barranquilla).

* Trabaja en la parte de mapas, indexacion de capas.
* Imagenes->caracteristicas->modelo. Ahora la cosa cambias con deep learning,
  todo esta mas enredado.
* informacion metrica-> crear modelo 3D a partir de la imagen.
* informacion semantica -> interpretar infomarcion en la imagen.
* En python tenemos: OpenCV, SimpleCV, scikit-image.
* Para reconocer caracteres: pytesseract.
* Para false coloring: cv2.applyColorMap. Para darle color real: tambien se puede con neural networks!
* para hacer imaging captioning: github:karpathy/neuraltalk
* github:jcjohnson/neural-style 
* pytorch -> libreria de redes convlucionales liberada por facebook para reconocimiento y style transfer
* yolo tracking -> youtube video doing recognition YOLO: You Only Learn Once
* style transfer facebook -> youtube video.

### Lennin Suescun (PiensaLabs)

* AI vs. AI two chatbots talking to each other -> youtube things.
* Machine Learning Tipico.
  Supervisado (que perro es? etiquetamos nosotros antes),
  No Supervisado (Se da informacion de algunas clases y otras no, para ver si logra ver la diferencia)
  Reinforcement Learning (Se le da feedback sobre los resultados. Si juega algo, le decimos si al final perdio o gano)
* No es magia: son muchos datos de entrenamiento con un contexto adecuado.
* Training, validation, testing.
* vatic->herramienta para hacer anotaciones en imagenes.
* 15000 frames anotados de videos para udacity.  


### Christian Garcia - Introduction to deep learning with Tensorflow 

* Neuralab.  
* Genial intro a machine learning y redes neuronales.  
* Buscar el MNIST de udacity en tensorflow.
* Buscar el ejemplo del cartpole



==
BUSCAR: zenhub
