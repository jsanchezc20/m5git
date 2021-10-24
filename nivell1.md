## Java (llenguatge de programació)
El **Java** és un [llenguatge de programació][langProg] dissenyat el 1990 per [_James Gosling_][Gosling] amb altres companys de [**Sun Microsystems**][Sun] a partir del _llenguatge C_.

[langProg]:https://ca.wikipedia.org/wiki/Llenguatge_de_programaci%C3%B3
[Gosling]:https://ca.wikipedia.org/w/index.php?title=James_Gosling&action=edit&redlink=1
[Sun]:https://ca.wikipedia.org/wiki/Sun_Microsystems

### Projectes i eines relacionades
* Proves unitàries: **JUnit**.
* Projectes **Jakarta**:
	* **Tomcat**: servidor de **servlets**.
	* **Apache**: servidor de pàgines web.
	* Escriptura de diari-registre de successos: **Log4j**
* Mapeig del domini orientat a objectes al domini relacional: **Hibernate**.
* Mesura de rendiment: **JMeter**.

### Passos per crear un programa amb Java
* Crear un arxiu amb el codi del programa amb extensió .java.

| **_elmeuprograma.java_**  |
|-|


* Compilar el programa per crear l'arxiu executable (arxiu de bytecodes ) que tindrà l'extensió .class.

>javac elmeuprograma.java

* Si es produeixen errors corregir-los.
* Executar el programa amb l'intèrpret de bytecode (JVM).

>java elmeuprograma

* Si el programa no funciona utilitzar el depurador per executar el programa pas a pas.

### Programa d'exemple
```JAVA
class HolaMon {
    public static void main (String args[]) {
        System.out.print("Hola, món!");
    }
}
```