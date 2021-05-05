# b3_mspr3_srv


## HOW TO SETUP

### Dans l'admin jenkins > outils :

JDK url
https://download.java.net/openjdk/jdk11/ri/openjdk-11+28_linux-x64_bin.tar.gz

MAVEN url
https://downloads.apache.org/maven/maven-3/3.8.1/binaries/apache-maven-3.8.1-bin.tar.gz

### admin jenkins > plugin :
tab "disponible" > search "maven"
check "maven intergration"
et install

Pour la création d'un job :

Project url
https://github.com/hugotms/b3_mspr_java/

commandes :

``` mvn clean install ```

``` java -jar target/b3_mspr_java-1.0-jar-with-dependencies.jar ```
