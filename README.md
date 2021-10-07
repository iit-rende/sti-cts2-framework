



# Servizio Terminologico Integrato (CTS2 Framework) 

### Nome del modulo: cts2-framework-1.2.0.FINAL



## Modulo maven contenente i sorgenti del framework CTS2





### Descrizione

CTS2 Framework è l'implementazione di uno standard per la gestione organizzata di un sistema terminologico 

Al seguente link il repository del progetto originale con tutti i riferimenti : https://github.com/cts2/cts2-framework





### Descrizione Repository

Il repository contiene un progetto maven con tutti i moduli relativi ai sorgenti del framework



## Prerequisiti

Prima di procedere al download dei sorgenti per il corretto funzionamento occorre installare le seguenti.
Per l'installazione degli applicativi si demanda alla documentazione ufficiale

- SO AlmaLinuxOS [https://almalinux.org/it/]

- JDK 1.8 [https://www.oracle.com/it/java/technologies/javase/javase8-archive-downloads.html]

- liferay-portal-6.2-ce-ga6 [https://sourceforge.net/projects/lportal/files/Liferay%20Portal/6.2.5%20GA6/]

  



## Installazione 

Per procedere alla corretta installazione dei moduli del presente repository è necessario prima scaricare configurare e deployare i moduli dei repository[liferay-portal-6.2-ce-ga6]
Per l'installazione degli applicativi [AlmaLinuxOS, JDK 1.8, liferay-portal-6.2-ce-ga6] si rimanda alla documentazione ufficiale.



## Build

Per la build del modulo è necessario scaricare e installare - Maven 3.6.3 [https://maven.apache.org/docs/3.6.3/release-notes.html] o superiore

A questo punto si considera un ambiente configurato e con liferay correttamente avviato. 
Per la build i comandi da lanciare sono i seguenti (scaricare i sorgenti, entrare nella folder del progetto e lanciare il comando seguente per generale la build). La build è possibile lanciarla anche su uno solo dei sotto moduli (Portlet)

```sh
git clone https://...
cd cts2-framework-1.2.0.FINAL
mvn clean install
```





## Deploy

una volta buildato i modulo bisognerà deployare la webapp generata sotto il tomcat di Liferay (**...liferay/tomcat/webapp**) e se tutto è andato bene la console web del framework sarà disponibile all'indirizzo http://HOST/cts2framework/ 



![home](screenshot/home.png)



per accedere alla console di default l'account è [admin/admin]



di seguito le istruzioni per modificare la password:

- dopo aver fatto l'accesso alla console entrare nel tab "Configuration"
- selezionare "Apache Felix OSGi Management Console"
- dalla finestra che viene mostrata impostare la username e la password e salvare 



![](screenshot/cambio_pass_1.png)

![](screenshot/cambio_pass_2.png)







## Copyright ©

 [TODO]

## Maintainer

 [TODO]


## License 

 [TODO]
**http://www.apache.org/licenses/LICENSE-2.0**



