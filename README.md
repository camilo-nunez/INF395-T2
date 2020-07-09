<center>
    <img src="http://sct.inf.utfsm.cl/wp-content/uploads/2020/04/logo_di.png" style="width:60%">
    <h1> INF-395/477 Redes Neuronales Artificiales I-2020 </h1>
    <h3>  Tarea 2 - Redes Neuronales Convolucionales y Recurrentes  </h3>
</center>

Nombres: Leonardo Astudillo Villalon  & Camilo Nunez Fernandez

Roles: 201573598-0 &201573573-5

Correos:
leonardo.astudillov@sansano.usm.cl & camilo.nunezf@sansano.usm.cl
<hr style="height:2px;border:none"/>


**Temas**  

* Entrenamiento de Redes Neuronales Profundas. 
* Modelos de Auto-Encoder
* Redes Convolucionales y Recurrentes. 

<hr style="height:2px;border:none"/>

# Antes de ejecutar
##  Parte 1
* Esta todo listo, para llegar y ejecutar el código de esta parte.

## Parte 2
* Para ejecutar el word embeddinng se debe descomprimir el binario `twitter_w2v.bin` desde `.zip` del sigueinte [link](https://drive.google.com/file/d/10XFm40ELVhPILxiP9DvjOnQlyhcLlyo9/view?usp=sharing), en la raíz donde se encuentra el notebook.
* Se debe cambiar el path principal en la variable `main_path`.
* Para variar la cantidad de arcos, se debe modificar la la variable `data_child_array = truncate_list(data_child_array,x)` con `x` la cantidad de arcos necesarios, en su defecto, si se queire tener todos los arcos (ojo con la memoria), solo basta con comentar la linea.
