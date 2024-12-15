### Hi there 👋, my name is H. E.
#### I am a cybersecurity enthusiast and Spanish developer
![I am cybersecurity enthusiast and Spanish developer](https://media.giphy.com/media/du3J3cXyzhj75IOgvA/giphy.gif)

---

### About Me 🚀

### JS
```javascript

function hello(name, languages) {
  console.log(`¡Hola! Soy ${name}, un desarrollador web, tengo amplia experiencia en los siguientes lenguajes:`);
  console.log('Mis lenguajes más usados son:');
  languages.forEach((language, index) => {
    console.log(`${index + 1}. ${language}`);
  });
}

hello('Devil Bit', ['PHP', 'Angular', '.NET']);

````

### PHP
````
<?php
function listarExperiencia($nombre, $experiencias) {
    echo "#### Mi experiencia incluye:\n\n";
    foreach ($experiencias as $experiencia) {
        echo "- $experiencia\n";
    }
}


listarExperiencia([
    'Especialista en soporte técnico - Grupo Sertracen - feb. 2021 - abr. 2021',
    'Desarrollador Full Stack - Rusty Chicken - sept. 2021 - ene. 2023',
    'Desarrollador de software - PLUGTHEM - mar. 2023 - jul. 2024',
    'Desarrollador Full Stack - RELATIVE ENGINE INNOVA - jul. 2024 - sept. 2024',
    'Desarrollador Full Stack - Provedatos del Ecuador SA - sept. 2024 - actualidad'
]);
?>
````

### .Net
````
using System;
using System.Collections.Generic;

class Program
{
    static void Main(string[] args)
    {
        MostrarLenguajesPorAprender("H. E.", new List<string>
        {
            "Phyton",
            "Kotlin",
        });
    }

    static void MostrarLenguajesPorAprender(List<string> lenguajes)
    {
        Console.WriteLine("estoy emocionado por aprender los siguientes lenguajes:");
        
        for (int i = 0; i < lenguajes.Count; i++)
        {
            Console.WriteLine($"{i + 1}. {lenguajes[i]}");
        }
    }
}
````
### TS
````
function listarHabilidadesExtras(nombre: string, habilidades: string[]): void {
    console.log('Además de desarrollar software, tengo habilidades extras en:');
    habilidades.forEach((habilidad, index) => {
        console.log(`${index + 1}. ${habilidad}`);
    });
}

// Llamada a la función con tus datos
listarHabilidadesExtras('H. E.', [
    'Docker',
    'Linux',
    'Git',
    'Administración de servidores',
    'Ciberseguridad'
]);

