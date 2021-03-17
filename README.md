[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/kristianfougner/enkeltoppsett)

Dette er et eksempel på oppsett av et Java-prosjekt.

Har brukt Maven sin quickstart archetype i oppsettet, se https://maven.apache.org/archetypes/maven-archetype-quickstart/. Denne kommer i 
utgangspunktet med JUnit4, men her er det endret til Junit5. Har også fjernet en god del av pluginsa og satt inn de vi til å begynne med absolutt
MÅ ha - kompilator og surefire (for kjøring av tester). Vi har konfigurert prosjektet (både i pom og gitpod-konfigurasjonsfiler) til å bruke Java 14.

Prosjektet er også "gitpodifisert".
