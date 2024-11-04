# Actividad1-c2
Actividad a1c2 - Ejercicios de clase de Fundamentos de JavaScript
CODIGO DE LOS EJERCICIOS REALIZADOS EN EL VIDEO:

//Adonys de Jesus Amaya Diaz 
console.log("Bienvenidos!!")

//palabra reservada let 
let contador = 0;
contador = contador +1;
contador = contador +1;
console.log(contador);

//const
const contador2 =1;

if(true) {
  const contador2 =5;
  console.log(contador2);
}
console.log(contador2);

//const persona 
const persona = {
  nombre : "Adonys",
  apellido : "Diaz"
}
persona.nombre = "Nino";
console.log(persona.nombre);

// objetos literales y Optional chaining
const frutas = ["pera", "manzana","sandia"];
console.log (frutas[2]);

//objetos literales, no indexados 
const animal = {
  color : "naranja",
  nombre : "simba",
  rugiendo : true,
  favoritos : {
    dia : {
      ok: true,
    },
     noche : {ok : false}     
  } 
}
console.log( "este Leon es de color : " + animal.color);
console.log("este Leon se llama  : " + animal.nombre);
console.log(animal["rugiendo"]);
console.log(animal.favoritos?.luna?.ok);
const tareas = {
  "3938474833jdjdj-dd" : { 
  title : "Tarea 1"
  }
}
console.log(tareas["3938474833jdjdj-dd"].title);
