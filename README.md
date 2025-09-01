# Uhuru
Proyecto Universitario. Aplicación de Escritorio para gestión y práctica de exámenes de certificación.


## Integrantes
+ Cao Carlos
+ Carios César
+ Ciavato Miguel
+ Homsany Jhonatan
+ Reis Erimar

# Enlaces
1. [ Modelos de Dominio. ](#modelo_dominio)
2. [ Modelos de Casos de Uso](#use_case)
3. [ Protipos de interfaz ](#prototipos)
4. [ Modelos de Análisis](#modelo_analisis)
5. [ Modelos de Diseño](#modelo_diseño)
6. [ Librerías](#lib)
7. [ Como usar](#guia)
8. [ Test](#modelo_test)
9. [ Cambio de Requisitos](#cambio_requisitos)

<a name="modelo_dominio"></a>
## Modelo del dominio
### Diagrama de clases

<p align="center">
  <img style="width:40%; heigth:300px" src="docs\scenariosView\domainModel\ClassDiagram.png">
</p>

### Diagrama de estado
<p align="center">
  <img style="width:60%; heigth:300px" src="docs\scenariosView\domainModel\StateDiagram.png">
</p>

<a name="use_case"></a>
## Modelo de Casos de Uso
## Diagrama de Casos de Uso
<p align="center">
  <img style="width:40%; heigth:300px" src="docs\scenariosView\useCaseModel\usecaseDiagram.png">
</p>

### Diagrama de Estados de los casos de uso
<p align="center">
  <img style="width:60%; heigth:300px" src="docs\scenariosView\useCaseModel\usecaseStateDiagram.png">
</p>

### Especificaciones de los casos de uso
<p align="center">
  <img style="width:60%; heigth:300px" src="docs\scenariosView\useCaseModel\CU1CrearExamen.png">
  <img style="width:60%; heigth:300px" src="docs\scenariosView\useCaseModel\CU2ResponderExamen.png">
  <img style="width:60%; heigth:300px" src="docs\scenariosView\useCaseModel\CU3ObtenerCertificado.png">
</p>

<a name="prototipos"></a>
## Prototipo de pantallas
### Flujo de Usuario
![Prototipos de Pantallas : Flujo Usuario](docs/prototype/Flujo-Usuario.png)
### Flujo de Administrador
![Prototipos de Pantallas : Flujo Usuario](docs/prototype/Flujo-Admin.png)      
### Enlaces 
- [Prototipo Interactivo en Figma](https://www.figma.com/file/dzXOa9yDAVZmEWpZJqrHQO/Prototipo-De-Interfaz?type=design&node-id=0%3A1&mode=design&t=nIYMdCu8Bfcdtu5P-1)
- [Pantallas](docs/prototype/INTERFACE.md)

<a name="modelo_analisis"></a>
## Modelo de Análisis
### Diagrama de clases de analisis
<p align="center">
  <img style="width:60%; heigth:300px" src="/docs/logicalView/analisysView/classAnalisys/analysisClassDiagram.png">
</p>

### Diagrama de clases de análisis y de colaboración de casos de uso prioritarios 

#### UC1 - Crear Examen
<p align="center">
  <img style="width:40%; heigth:300px" src="docs/logicalView/analisysView/usecaseAnalisys/analysisClassDiagramUC1.png">
  <img style="width:80%; heigth:300px" src="docs/logicalView/analisysView/usecaseAnalisys/collaborationDiagramUC1.png">
</p>

#### UC2 - Responder Examen
<p align="center">
  <img style="width:40%; heigth:300px" src="docs/logicalView/analisysView/usecaseAnalisys/analysisClassDiagramUC2.png">
  <img style="width:80%; heigth:300px" src="docs/logicalView/analisysView/usecaseAnalisys/collaborationDiagramUC2.png">
</p>

#### UC3 - Obtener Certificado
<p align="center">
  <img style="width:40%; heigth:300px" src="docs/logicalView/analisysView/usecaseAnalisys/analysisClassDiagramUC3.png">
  <img style="width:80%; heigth:300px" src="docs/logicalView/analisysView/usecaseAnalisys/collaborationDiagramUC3.png">
</p>

### Diagrama de paquetes de análisis
<p align="center">
  <img style="width:80%; heigth:300px" src="docs/logicalView/analisysView/packageAnalisys/packageDiagram.png">
</p>

<a name="modelo_diseño"></a>
## Modelo de Diseño
### Diagrama de clases
<p align="center">
  <img style="width:100%; heigth:300px" src="docs\logicalView\designView\usecaseDesign\designClasses.png">
</p>

### Diagrama de secuencia
<p align="center">
  <img style="width:60%; heigth:300px" src="docs\logicalView\designView\classDesing\sequenceDiagram.png">
</p>

### Diagrama de Traza
<p align="center">
  <img style="width:100%" src="docs\logicalView\designView\packageDesign\traceDiagram.png">
</p>

### Modelo de Despliegue
<p align="center">
  <img src="docs\physicalView\DeploymentDiagram.png">
</p>

<a name="lib"></a>
## Librerías
Las librerías de terceros usadas en el proyecto son:
Librería  | Versión | Uso
------------- | ------------- | -------------
ItextPdf  | 5.5.9  | Proporciona las clases necesarias para estructurar y generar el archivo PDF correspondiente al certificado del Curso Aprobado.
JsonSimple  | 1.1.1  | Proporciona las herramietnas necesarias para cargar, manipular y preservar la información de los modelos a traves de archivos JSON.
JUnit | 1.10.2  | Proporciona las herramietnas necesarias para ejecutar las pruebas unitarias del proyecto.

<a name="guia"></a>
## Cómo usar Uhuru
>[!WARNING]
>Luego de copiar y vincular el repositorio bastará con compilar el proyecto y ejecutar el archivo MAIN.JAVA disponible en la ruta /src/main.java

1. Inicia sesión con tu correo y contraseña registrados por el administrador
>[!TIP]
>Para realizar pruebas en el sistema puede acceder con las credenciales [correo:user clave:user] ó [correo:admin clave:admin]
<p align="center">
  <img style="width:60%; heigth:300px" src="docs\screenshots\login.png">
</p>

2. Selecciona uno de los cursos disponibles en la plataforma para poder acceder a los examenes asociados.
<p align="center">
  <img style="width:60%; heigth:300px" src="docs\screenshots\TestListView.png">
</p>

3. Una vez accedes al examen tendrás un tiempo limitado para responder todas las preguntas.
<p align="center">
  <img style="width:60%; heigth:300px" src="docs\screenshots\TestView.png">
</p>

4. Una vez aprobado todos los examenes de un curso podrás acceder a su certificado guardandolo en formato PDF.
<p align="center">
  <img style="width:60%; heigth:300px" src="docs\screenshots\GetCertificate.png">
</p>

6. Desde tu perfil podrás modificar datos básicos de tu usuario.

7. Podrás acceder a las preguntas frecuentes desde tu pantalla de inicio.

<a name="modelo_test"></a>
## Modelo de Pruebas
### - Prueba de Constructor de Test
El sujeto de la prueba es el constructor del modelo Test
### - Constructor de Question
El sujeto de la prueba es el constructor del modelo Question
### - Prueba de Constructor de Answer
El sujeto de la prueba es el constructor del modelo Answer
### - Prueba de Validación de Usuario
El sujeto de la prueba es ValidateUser de la clase LoginController

<a name="cambio_requisitos"></a>
## Cambio de Requisitos
>[!NOTE]
>Se solicitó añadir preguntas de selección múltiple e imágenes que acompañaran al enunciado

### Especificación de Casos de Uso 

CU1 - Crear Examen
<p align="center">
  <img style="width:60%; heigth:300px" src="docs\scenariosView\useCaseModel\CU1CrearExamenV2.png">
</p>

### Modelo de Diseño
Diagrama de Clases
<p align="center">
  <img style="width:100%; heigth:300px" src="docs\logicalView\designView\usecaseDesign\designClasses-changeOfRequirements.png">
</p>

## Prototipo de Pantalla
Create Tests
<p align="center">
  <img style="width:100%; heigth:300px" src="docs\prototype\screen\changeOfRequerimetsView\create-test-1.jpg">
   <img style="width:100%; heigth:300px" src="docs\prototype\screen\changeOfRequerimetsView\create-test-2.jpg">
</p>
