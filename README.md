Descripció - Enunciat de Tasca S4.01 Introducció a Spring

Exercici 1

Aquest exercici introdueix al framework Spring i a l'ús de Maven com a gestor de dependències. També es treballarà amb el protocol HTTP, Postman i la gestió de dependències amb Maven i Gradle.

Fases de l'exercici:

Creació del projecte Spring Boot
Accedir a Spring Initializr i generar un projecte amb les següents característiques:
Gestor de dependències: Maven
Llenguatge: Java
Spring Boot: Darrera versió estable
Metadades del projecte:
Group: cat.itacademy.s04.t01.n01
Artifact/Name/Description: S04T01N01
Package name: cat.itacademy.s04.t01.n01
Packaging: Jar
Java: Mínim versió 11
Dependències:
Spring Boot DevTools
Spring Web
Importació a Eclipse
Importar el projecte com a Maven Project (File > Import > Existing Maven Project).
Configurar el port del servidor (server.port=9000) a l'arxiu application.properties.
Creació d’una API REST amb un controlador
Crear un subpackage controller dins el package principal.
Afegir la classe HelloWorldController amb dos mètodes:
saluda: Respon a una petició GET amb RequestParam (valor per defecte: “UNKNOWN”).
Exemples:
http://localhost:9000/HelloWorld
http://localhost:9000/HelloWorld?nom=El meu nom
saluda2: Respon a una petició GET amb PathVariable (paràmetre opcional).
Exemples:
http://localhost:9000/HelloWorld2
http://localhost:9000/HelloWorld2/elmeunom
Pràctica amb comandes bàsiques de Maven
Compilar el projecte: mvn compile
Empaquetar el projecte: mvn package
Netejar el projecte: mvn clean
Executar l'aplicació: mvn spring-boot:run
L’objectiu és aprendre a crear una aplicació Spring Boot, gestionar dependències amb Maven i fer servir API REST amb paràmetres.

Tecnologies Utilitzades

IntelliJ,  Spring boot, Git and GitHub

Requisits Nothing

Instal·lació Nothing

Execució Nothing

Desplegament Nothing

-Contribucions

Nothing
