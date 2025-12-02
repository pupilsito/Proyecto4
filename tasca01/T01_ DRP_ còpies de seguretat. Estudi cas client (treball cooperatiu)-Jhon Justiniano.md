 **DRP: còpies de seguretat. ![][image1]Fase 2: Treball per parelles** 

Treballant per parelles: 

**1.Discussió i Consens: Comparen les seves respostes individuals (Fase 1\)** 

Després de comparar les nostres parts individuals en la fase 1, vam arribat als següents punts que tenim en comú: 

\-Les dades més crítiques són les bases de dades, després vindran els documents dels projectes i finalment serien les carpetes personals. 

\-No fa falta copiar tots i completament els equips dels clients, només seria la carpeta de documents, això ja que tota la informació crítica està en el servidor, per tant, el més important seria el que està en el servidor. 

\-Tenim en comú la combinació de les còpies incrementals, les completes i les diferencials, però sempre prioritzant la seguretat diària, setmanal i mensual. \-Tenim en comú com utilitzarem *NAS intern, discos externs i el* Cloud, tot això respectant la regla 3-2-1. 

**2.Elaboració d'una Proposta Unificada: Heu de consensuar i dissenyar el vostre propi Esquema 3-2-1 de Còpies (3 còpies, 2 mitjans, 1 fora de lloc) basat en els requisits del cas.** 

| Element  | Proposta de la parella  | Justificació |
| :---- | :---- | :---- |
| **Dades crítiques**  | \-La base de dades de comptabilitat i dels clients (20 GB)  \-Els documents dels projectes (300 GB)  \-Les carpetes personals dels usuaris (100 GB) \-Carpetes de documents dels equips clients. | Són les dades més importants i més essencials perquè l'empresa funcioni correctament cada dia, ja que els projectes, les carpetes personals i les base de dades són molt importants i imprescindibles per al treball dels treballadors de l'empresa i les dades dels clients només es copiaran de manera parcial per a evitar que es dupliquin. |
| **Periodicitat (bases de dades)** | \-Incremental cada 4 hores i seria de manera diària. \- Completa seria setmanal.  \-Completa seria mensual també. | Les bases de dades és la informació que és la més sensible de l'empresa, a més necessita restauració ràpida i punts freqüents de la restauració. |
| **Tipus de còpia (Bases de dades)** | \-Diària \- Incremental  \-Setmanal \- Completa | Tindrem còpies freqüents, diàries, setmanals i |

6/11  
 **DRP: còpies de seguretat. ![][image2]**

|  | \-Mensual \- Completa  | mensuals. La còpia completa seria per a poder garantir la integritat setmanal i mensual. |
| :---- | :---- | :---- |
| **Mitjà 1 (Local)**  | NAS intern per a les còpies diàries i setmanals. | Ens permetrà restauració ràpida i estaria sempre disponible en la xarxa interna. |
| **Mitjà 2 (Extern)**  | Disc dur extern per a còpies setmanals i mensuals fora de línia. | Afegirem una capa de protecció. |
| **Mitjà 3 (Fora de lloc)**  | Còpia en el Cloud, la qual cosa seria mensual. Una opció seria en el núvol. | Compleix la regla del 3-2-1 i ens assegura que sí o sí una còpia està fora de la ubicació física. |

**Fase 3: Treball en grup** 

**1.Debat i Selecció: Cada parella presenta el seu esquema. El grup debat els pros i contres de cada proposta (cost, temps de recuperació, seguretat, simplicitat).** 

**2.Disseny de la Política Final: El grup ha de redactar la Política de Còpies de Seguretat Definitiva que presentaran a l'empresa "Muntatges i Serveis Tècnics SL".** 

Després de debatre i posar-nos d'acord tots els presentem a continuació el document final. 

**Document Final (Fase 3\)** 

El grup ha de generar un document amb els següents punts resolts: **1\) Dades Objecte de Còpia** 

**Quines dades es copien i amb quina freqüència (separant Servidor/Clients i crítiques/no crítiques).** 

Dades del servidor d'arxius Ubuntu Server: 

| Tipus de dades  | Volum  | Criticitat  | Freqüència |
| :---- | :---- | :---- | :---- |
| **Documents de projectes (Plans, especificacions tècniques, etc.)** | 300 GB amb un creixement  moderat | Crític  | Diària:  Incremental  Setmanal:  Completa  Mensual: |

7/11  
 **DRP: còpies de seguretat. ![][image3]**

|  |  |  | Completa |
| :---- | :---- | :---- | :---- |
| **Base de dades (Compatibilitat i clients)** | 20 GB però amb canvis constants | Molt crític  | Cada 4 hores: Incremental  Diària: Completa Setmanal:  Completa  Mensual:  Completa |
| **Carpetes  personals dels usuaris (Per al treball diari)** | 100 GB  | Crític o mig crític  | Diària:  Incremental  Setmanal:  Completa |

Dades dels clients Windows 10/11 

Només es realitzen les còpies de: 

| Tipus de dades  | Criticitat  | Freqüència |
| :---- | :---- | :---- |
| **Carpeta de Documents dels usuaris** | Crític o mig crític  | Diària: Incremental  Setmanal: Completa |

Només fem còpies d'això i només diària i setmanal perquè els clients treballen directament amb dades que es troba en el servidor i només fa falta fer còpies de la carpeta de documents perquè alguns clients es guarden coses o arxius de manera temporal en la carpeta de documents. 

8/11  
 **DRP: còpies de seguretat. ![][image4]**

**2)Cronograma Setmanal Detallat** 

| Dia  | Dades (Ex: BD)  | Tipus de còpia  | Mitjà |
| :---- | :---- | :---- | :---- |
| **Dilluns**  | 1.Les bases de dades.  2.Els projectes i les carpetes.  3.Del personal i dels clients. | 1.Incrementals  cada 4 hores a més una completa tard de la nit tipus 23.00 h.  2.Incremental.  3.Incremental. | 1.NAS  2.NAS  3.NAS |
| **Dimarts**  | 1.Les bases de dades.  2.Les altres dades. | 1.Incrementals  cada 4 hores.  2.Incremental. | 1.NAS  2.NAS |
| **Dimecres**  | 1.Les bases de dades.  2.Les altres dades. | 1.Incrementals  cada 4 hores.  2.Incrementals. | 1.NAS  2.NAS |
| **Dijous**  | 1.Les bases de dades.  2.Les altres dades. | 1.Incrementals  cada 4 hores.  2.Incrementals. | 1.NAS  2.NAS |
| **Divendres**  | 1.Les bases de dades.  2.Les altres dades. | 1.Incrementals  cada 4 hores.  2.Incrementals. | 1.NAS  2.NAS |
| **Dissabte**  | 1.Les bases de dades.  2.Les altres dades. | 1.Completa  setmanal.  2.Completa  setmanal. | 1.NAS \+ Disc durs externs.  2.NAS \+ Disc durs externs. |
| **Diumenge**  | 1.Les bases de dades. | Si és el primer diumenge del mes hauria de ser | Cloud xifrades ja que així serien |

9/11  
 **DRP: còpies de seguretat. ![][image5]**

|  | 2.Les altres dades. | còpies completes mensuals. | còpies externes i segures. |
| :---- | :---- | :---- | :---- |

**3)Elecció de Mitjans i Ubicació (Regla 3-2-1)** 

**\*Mitjà 1 (Local): Quin mitjà concret (p. ex., Disc dur USB, NAS) s'utilitza.** 

**NAS intern amb un RAID 5**   
\-Estaria situat en el centre de processaments de dades de l'empresa. \-Estaria emmagatzemat totes les còpies incrementals com també les còpies completes setmanals. 

\-Tindria un accés ràpid per si fa falta fer restauracions ràpides.   
\-El RAID 5 és per si falla algun disc. 

**\*Mitjà 2 (Extern): Quin mitjà (p. ex., Cloud, LTO) i el proveïdor proposat (p. ex., Azure, Google Cloud, servei local).** 

**Disc dur extern amb USB**   
\-Estaria comentat només durant la realització de les còpies de seguretat setmanals i de les mensuals. 

\-Tindria una protecció per exemple contra les falles elèctriques, etc. \-Podem deixar-ho en una caixa forta dins del centre de processaments de dades o fora de l'empresa en algun lloc segur. 

**\*Ubicació Fora de Lloc: On es guarda la còpia externa (física o lògica) i qui és el responsable de la seva gestió.** 

**Cloud i estaria pujat en el núvol**   
\-Tindria una ubicació segura en el núvol.   
\-Tindria una còpia xifrada.   
\-El responsable seria el departament de IT de l'empresa i haurien de fer una validació mensual de la integritat. 

10/11  
 **DRP: còpies de seguretat. ![][image6]4)Estratègia de Recuperació (RTO/RPO)**   
**\*Com es garanteix que les dades de Comptabilitat/Clients compleixen amb el requisit de RPO (4 hores) i RTO (4 hores).** 

Primer que tot hem de deixar clar que el RPO no és el mateix que el RTO, el RPO és com un màxim de pèrdua de 4 hores i el RTO és la restauració completa en menys de 4 hores. 

Per a garantir el compliment de la base de dades de comptabilitat i dels clients que compleixin amb el requisit RPO i RTO farem el següent: 

**RPO \= Màxim de 4 hores de pèrdua.** 

Farem còpies de seguretat incrementals cada 4 hores de la base de dades i en cas d'un error sempre haurà d'haver-hi un punt de restauració menor a 4 hores. **RTO \= Restauració completa en menys de 4 hores.** 

Les còpies haurien de guardar-se en el NAS intern i hauria de tenir accés directe i amplada de banda interna una mica elevada. A més una restauració de la base de dades de 20 GB des del NAS. També hauria d'haver-hi un sistema de restauració automatitzat. 

**Alguns escenaris de recuperació:** 

\-Falla del servidor: Hauríem de fer una restauració des del NAS. \-Ransomware en el servidor: Si per algun cas no es pot usar el NAS hauríem de fer una restauració des de disc dur extern. 

\-Desastres físics: Hauríem de fer una restauració des del Cloud mensual que tardaria molt més o com les bases de dades tindran una còpia setmanal en el disc dur extern podríem fer la restauració des d'aquí. 

Solució en Github 

11/11

[image1]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACcAAAAgCAYAAACRpmGNAAAEHElEQVR4XtWY+09bZRjH9z/NXbxNp9FNo/EX4yVxXn/QxKjxkhhjor9MFxMT4y0DBmxlmt2HxCEUOlrkUtYBEyijQLkjsGoL9AZtT/v4fr/tqe05PbEFl8BDPgnnPed932/f93me9zlnj2zBMpmMIk3iiVW5szYqfwYHSGDdJ5vJcO4+nssYu5dte4wNVqZPFNsMyq3pBmnse53UOh6SavtBqbLvJ/i/3nFYmjxviXfuEsmKrVzk7haHQZOpuBJ0ltQ7HpGTrXsrosH5pIwtNElKS5ByzVKcvlLRjYA097+nJtlHznU9y+uzrqeIUYg1++T60GcEK1mOWYqDo4PGvjc4eOfoCZJIRSk6HF8mF7pfKCFkr/zc+Yz85HqaGO+1DHzIcf7Ldqe40fkrBIOdvv6oROIr5F+Dg2ekb/zHoolPtT8gPWPfSNsfn6jre3KYxbt930k6oxErsxQXWBsjGMjmPCpxFaVANy2dIi2DH/EZrCCYC/SKy/uFSYyRU233y/LqMLGKZJM4LZ2URDKqnDZC6hwPC5zZM3GSxDdDuXRiIzVqkvahT/Pb3H37a7FaLSP2Wx+TtPqRpWx3iVtZ9Yp3/rJoWpJc6H4+N1jWf7DFNucRJeo+4vZ9zzzY768jVUw5ZiGlqG0/RMLxJaMMmknc4JRNrt18J+9TTTfeNA1abT+gnjtNsNL+ZYcSei8xPlsOk0t2owyaSZzLe5zRuZFYJy0DHxQNhJXB9uqRthqdlTMdR0wTVgIivpTtLnHIT1Wt+5XvjZDWXKrQ6fSe4FYmtQ3y28D7bK9tf5DUqUIAoAAobjuULw6M4pwjx40yaCXFoYNv8Rr51fM2r+F7ABGMvDS+2EyylcgBWfjrBlmLzqvVnJGO4c9lNtBF1mLzEorMMAeCy73HtiYO24oOnokqcqnnJbVtj0kw7CewjeS6nO96juDZmraDStQcWQz2y8WeF+kaf4cnCAQjyJCCgH+prUhc2du6o8UNTp1hB/gWsHUclaHZc/kSCtxe+KVo8EJx2D7PZPZH6eLQhuScSMUIcmNh/7JTCYIAPtTc/y654n5FJdlY/n5K21Q+87KluPXYogzPnperqkrOr1xsQUZURezyfkn0fFhxEsbkV92vqa18nEyvOIvuQ7zxFCgUN3OnU/TjSxcXjPh50Bf2ARUfXztaHHxqaqVDCXyV4Ahje+6vb/wH0yRIJ/rZ+vvoV/l2+B64OVlDVyn+QapkCg2RsksmGATBiUFhG2h0Zyvj7dLr+1atmEasrKS4UhZPhAhShHGiSsGRuK0y3Wg7WlwoMk2q7Vsri1CwOtRrIdj2q6HR9Mir38LKNTifYOL+316qjVb4OQIFqR7NSKKIRFQyANUISnsUCSNzF8ld+xyh244WV2hZoXf/E9g/PqR5wKW6wIgAAAAASUVORK5CYII=>

[image2]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACcAAAAgCAYAAACRpmGNAAAEHElEQVR4XtWY+09bZRjH9z/NXbxNp9FNo/EX4yVxXn/QxKjxkhhjor9MFxMT4y0DBmxlmt2HxCEUOlrkUtYBEyijQLkjsGoL9AZtT/v4fr/tqe05PbEFl8BDPgnnPed932/f93me9zlnj2zBMpmMIk3iiVW5szYqfwYHSGDdJ5vJcO4+nssYu5dte4wNVqZPFNsMyq3pBmnse53UOh6SavtBqbLvJ/i/3nFYmjxviXfuEsmKrVzk7haHQZOpuBJ0ltQ7HpGTrXsrosH5pIwtNElKS5ByzVKcvlLRjYA097+nJtlHznU9y+uzrqeIUYg1++T60GcEK1mOWYqDo4PGvjc4eOfoCZJIRSk6HF8mF7pfKCFkr/zc+Yz85HqaGO+1DHzIcf7Ldqe40fkrBIOdvv6oROIr5F+Dg2ekb/zHoolPtT8gPWPfSNsfn6jre3KYxbt930k6oxErsxQXWBsjGMjmPCpxFaVANy2dIi2DH/EZrCCYC/SKy/uFSYyRU233y/LqMLGKZJM4LZ2URDKqnDZC6hwPC5zZM3GSxDdDuXRiIzVqkvahT/Pb3H37a7FaLSP2Wx+TtPqRpWx3iVtZ9Yp3/rJoWpJc6H4+N1jWf7DFNucRJeo+4vZ9zzzY768jVUw5ZiGlqG0/RMLxJaMMmknc4JRNrt18J+9TTTfeNA1abT+gnjtNsNL+ZYcSei8xPlsOk0t2owyaSZzLe5zRuZFYJy0DHxQNhJXB9uqRthqdlTMdR0wTVgIivpTtLnHIT1Wt+5XvjZDWXKrQ6fSe4FYmtQ3y28D7bK9tf5DUqUIAoAAobjuULw6M4pwjx40yaCXFoYNv8Rr51fM2r+F7ABGMvDS+2EyylcgBWfjrBlmLzqvVnJGO4c9lNtBF1mLzEorMMAeCy73HtiYO24oOnokqcqnnJbVtj0kw7CewjeS6nO96juDZmraDStQcWQz2y8WeF+kaf4cnCAQjyJCCgH+prUhc2du6o8UNTp1hB/gWsHUclaHZc/kSCtxe+KVo8EJx2D7PZPZH6eLQhuScSMUIcmNh/7JTCYIAPtTc/y654n5FJdlY/n5K21Q+87KluPXYogzPnperqkrOr1xsQUZURezyfkn0fFhxEsbkV92vqa18nEyvOIvuQ7zxFCgUN3OnU/TjSxcXjPh50Bf2ARUfXztaHHxqaqVDCXyV4Ahje+6vb/wH0yRIJ/rZ+vvoV/l2+B64OVlDVyn+QapkCg2RsksmGATBiUFhG2h0Zyvj7dLr+1atmEasrKS4UhZPhAhShHGiSsGRuK0y3Wg7WlwoMk2q7Vsri1CwOtRrIdj2q6HR9Mir38LKNTifYOL+316qjVb4OQIFqR7NSKKIRFQyANUISnsUCSNzF8ld+xyh244WV2hZoXf/E9g/PqR5wKW6wIgAAAAASUVORK5CYII=>

[image3]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACcAAAAgCAYAAACRpmGNAAAEHElEQVR4XtWY+09bZRjH9z/NXbxNp9FNo/EX4yVxXn/QxKjxkhhjor9MFxMT4y0DBmxlmt2HxCEUOlrkUtYBEyijQLkjsGoL9AZtT/v4fr/tqe05PbEFl8BDPgnnPed932/f93me9zlnj2zBMpmMIk3iiVW5szYqfwYHSGDdJ5vJcO4+nssYu5dte4wNVqZPFNsMyq3pBmnse53UOh6SavtBqbLvJ/i/3nFYmjxviXfuEsmKrVzk7haHQZOpuBJ0ltQ7HpGTrXsrosH5pIwtNElKS5ByzVKcvlLRjYA097+nJtlHznU9y+uzrqeIUYg1++T60GcEK1mOWYqDo4PGvjc4eOfoCZJIRSk6HF8mF7pfKCFkr/zc+Yz85HqaGO+1DHzIcf7Ldqe40fkrBIOdvv6oROIr5F+Dg2ekb/zHoolPtT8gPWPfSNsfn6jre3KYxbt930k6oxErsxQXWBsjGMjmPCpxFaVANy2dIi2DH/EZrCCYC/SKy/uFSYyRU233y/LqMLGKZJM4LZ2URDKqnDZC6hwPC5zZM3GSxDdDuXRiIzVqkvahT/Pb3H37a7FaLSP2Wx+TtPqRpWx3iVtZ9Yp3/rJoWpJc6H4+N1jWf7DFNucRJeo+4vZ9zzzY768jVUw5ZiGlqG0/RMLxJaMMmknc4JRNrt18J+9TTTfeNA1abT+gnjtNsNL+ZYcSei8xPlsOk0t2owyaSZzLe5zRuZFYJy0DHxQNhJXB9uqRthqdlTMdR0wTVgIivpTtLnHIT1Wt+5XvjZDWXKrQ6fSe4FYmtQ3y28D7bK9tf5DUqUIAoAAobjuULw6M4pwjx40yaCXFoYNv8Rr51fM2r+F7ABGMvDS+2EyylcgBWfjrBlmLzqvVnJGO4c9lNtBF1mLzEorMMAeCy73HtiYO24oOnokqcqnnJbVtj0kw7CewjeS6nO96juDZmraDStQcWQz2y8WeF+kaf4cnCAQjyJCCgH+prUhc2du6o8UNTp1hB/gWsHUclaHZc/kSCtxe+KVo8EJx2D7PZPZH6eLQhuScSMUIcmNh/7JTCYIAPtTc/y654n5FJdlY/n5K21Q+87KluPXYogzPnperqkrOr1xsQUZURezyfkn0fFhxEsbkV92vqa18nEyvOIvuQ7zxFCgUN3OnU/TjSxcXjPh50Bf2ARUfXztaHHxqaqVDCXyV4Ahje+6vb/wH0yRIJ/rZ+vvoV/l2+B64OVlDVyn+QapkCg2RsksmGATBiUFhG2h0Zyvj7dLr+1atmEasrKS4UhZPhAhShHGiSsGRuK0y3Wg7WlwoMk2q7Vsri1CwOtRrIdj2q6HR9Mir38LKNTifYOL+316qjVb4OQIFqR7NSKKIRFQyANUISnsUCSNzF8ld+xyh244WV2hZoXf/E9g/PqR5wKW6wIgAAAAASUVORK5CYII=>

[image4]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACcAAAAgCAYAAACRpmGNAAAEHElEQVR4XtWY+09bZRjH9z/NXbxNp9FNo/EX4yVxXn/QxKjxkhhjor9MFxMT4y0DBmxlmt2HxCEUOlrkUtYBEyijQLkjsGoL9AZtT/v4fr/tqe05PbEFl8BDPgnnPed932/f93me9zlnj2zBMpmMIk3iiVW5szYqfwYHSGDdJ5vJcO4+nssYu5dte4wNVqZPFNsMyq3pBmnse53UOh6SavtBqbLvJ/i/3nFYmjxviXfuEsmKrVzk7haHQZOpuBJ0ltQ7HpGTrXsrosH5pIwtNElKS5ByzVKcvlLRjYA097+nJtlHznU9y+uzrqeIUYg1++T60GcEK1mOWYqDo4PGvjc4eOfoCZJIRSk6HF8mF7pfKCFkr/zc+Yz85HqaGO+1DHzIcf7Ldqe40fkrBIOdvv6oROIr5F+Dg2ekb/zHoolPtT8gPWPfSNsfn6jre3KYxbt930k6oxErsxQXWBsjGMjmPCpxFaVANy2dIi2DH/EZrCCYC/SKy/uFSYyRU233y/LqMLGKZJM4LZ2URDKqnDZC6hwPC5zZM3GSxDdDuXRiIzVqkvahT/Pb3H37a7FaLSP2Wx+TtPqRpWx3iVtZ9Yp3/rJoWpJc6H4+N1jWf7DFNucRJeo+4vZ9zzzY768jVUw5ZiGlqG0/RMLxJaMMmknc4JRNrt18J+9TTTfeNA1abT+gnjtNsNL+ZYcSei8xPlsOk0t2owyaSZzLe5zRuZFYJy0DHxQNhJXB9uqRthqdlTMdR0wTVgIivpTtLnHIT1Wt+5XvjZDWXKrQ6fSe4FYmtQ3y28D7bK9tf5DUqUIAoAAobjuULw6M4pwjx40yaCXFoYNv8Rr51fM2r+F7ABGMvDS+2EyylcgBWfjrBlmLzqvVnJGO4c9lNtBF1mLzEorMMAeCy73HtiYO24oOnokqcqnnJbVtj0kw7CewjeS6nO96juDZmraDStQcWQz2y8WeF+kaf4cnCAQjyJCCgH+prUhc2du6o8UNTp1hB/gWsHUclaHZc/kSCtxe+KVo8EJx2D7PZPZH6eLQhuScSMUIcmNh/7JTCYIAPtTc/y654n5FJdlY/n5K21Q+87KluPXYogzPnperqkrOr1xsQUZURezyfkn0fFhxEsbkV92vqa18nEyvOIvuQ7zxFCgUN3OnU/TjSxcXjPh50Bf2ARUfXztaHHxqaqVDCXyV4Ahje+6vb/wH0yRIJ/rZ+vvoV/l2+B64OVlDVyn+QapkCg2RsksmGATBiUFhG2h0Zyvj7dLr+1atmEasrKS4UhZPhAhShHGiSsGRuK0y3Wg7WlwoMk2q7Vsri1CwOtRrIdj2q6HR9Mir38LKNTifYOL+316qjVb4OQIFqR7NSKKIRFQyANUISnsUCSNzF8ld+xyh244WV2hZoXf/E9g/PqR5wKW6wIgAAAAASUVORK5CYII=>

[image5]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACcAAAAgCAYAAACRpmGNAAAEHElEQVR4XtWY+09bZRjH9z/NXbxNp9FNo/EX4yVxXn/QxKjxkhhjor9MFxMT4y0DBmxlmt2HxCEUOlrkUtYBEyijQLkjsGoL9AZtT/v4fr/tqe05PbEFl8BDPgnnPed932/f93me9zlnj2zBMpmMIk3iiVW5szYqfwYHSGDdJ5vJcO4+nssYu5dte4wNVqZPFNsMyq3pBmnse53UOh6SavtBqbLvJ/i/3nFYmjxviXfuEsmKrVzk7haHQZOpuBJ0ltQ7HpGTrXsrosH5pIwtNElKS5ByzVKcvlLRjYA097+nJtlHznU9y+uzrqeIUYg1++T60GcEK1mOWYqDo4PGvjc4eOfoCZJIRSk6HF8mF7pfKCFkr/zc+Yz85HqaGO+1DHzIcf7Ldqe40fkrBIOdvv6oROIr5F+Dg2ekb/zHoolPtT8gPWPfSNsfn6jre3KYxbt930k6oxErsxQXWBsjGMjmPCpxFaVANy2dIi2DH/EZrCCYC/SKy/uFSYyRU233y/LqMLGKZJM4LZ2URDKqnDZC6hwPC5zZM3GSxDdDuXRiIzVqkvahT/Pb3H37a7FaLSP2Wx+TtPqRpWx3iVtZ9Yp3/rJoWpJc6H4+N1jWf7DFNucRJeo+4vZ9zzzY768jVUw5ZiGlqG0/RMLxJaMMmknc4JRNrt18J+9TTTfeNA1abT+gnjtNsNL+ZYcSei8xPlsOk0t2owyaSZzLe5zRuZFYJy0DHxQNhJXB9uqRthqdlTMdR0wTVgIivpTtLnHIT1Wt+5XvjZDWXKrQ6fSe4FYmtQ3y28D7bK9tf5DUqUIAoAAobjuULw6M4pwjx40yaCXFoYNv8Rr51fM2r+F7ABGMvDS+2EyylcgBWfjrBlmLzqvVnJGO4c9lNtBF1mLzEorMMAeCy73HtiYO24oOnokqcqnnJbVtj0kw7CewjeS6nO96juDZmraDStQcWQz2y8WeF+kaf4cnCAQjyJCCgH+prUhc2du6o8UNTp1hB/gWsHUclaHZc/kSCtxe+KVo8EJx2D7PZPZH6eLQhuScSMUIcmNh/7JTCYIAPtTc/y654n5FJdlY/n5K21Q+87KluPXYogzPnperqkrOr1xsQUZURezyfkn0fFhxEsbkV92vqa18nEyvOIvuQ7zxFCgUN3OnU/TjSxcXjPh50Bf2ARUfXztaHHxqaqVDCXyV4Ahje+6vb/wH0yRIJ/rZ+vvoV/l2+B64OVlDVyn+QapkCg2RsksmGATBiUFhG2h0Zyvj7dLr+1atmEasrKS4UhZPhAhShHGiSsGRuK0y3Wg7WlwoMk2q7Vsri1CwOtRrIdj2q6HR9Mir38LKNTifYOL+316qjVb4OQIFqR7NSKKIRFQyANUISnsUCSNzF8ld+xyh244WV2hZoXf/E9g/PqR5wKW6wIgAAAAASUVORK5CYII=>

[image6]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACcAAAAgCAYAAACRpmGNAAAEHElEQVR4XtWY+09bZRjH9z/NXbxNp9FNo/EX4yVxXn/QxKjxkhhjor9MFxMT4y0DBmxlmt2HxCEUOlrkUtYBEyijQLkjsGoL9AZtT/v4fr/tqe05PbEFl8BDPgnnPed932/f93me9zlnj2zBMpmMIk3iiVW5szYqfwYHSGDdJ5vJcO4+nssYu5dte4wNVqZPFNsMyq3pBmnse53UOh6SavtBqbLvJ/i/3nFYmjxviXfuEsmKrVzk7haHQZOpuBJ0ltQ7HpGTrXsrosH5pIwtNElKS5ByzVKcvlLRjYA097+nJtlHznU9y+uzrqeIUYg1++T60GcEK1mOWYqDo4PGvjc4eOfoCZJIRSk6HF8mF7pfKCFkr/zc+Yz85HqaGO+1DHzIcf7Ldqe40fkrBIOdvv6oROIr5F+Dg2ekb/zHoolPtT8gPWPfSNsfn6jre3KYxbt930k6oxErsxQXWBsjGMjmPCpxFaVANy2dIi2DH/EZrCCYC/SKy/uFSYyRU233y/LqMLGKZJM4LZ2URDKqnDZC6hwPC5zZM3GSxDdDuXRiIzVqkvahT/Pb3H37a7FaLSP2Wx+TtPqRpWx3iVtZ9Yp3/rJoWpJc6H4+N1jWf7DFNucRJeo+4vZ9zzzY768jVUw5ZiGlqG0/RMLxJaMMmknc4JRNrt18J+9TTTfeNA1abT+gnjtNsNL+ZYcSei8xPlsOk0t2owyaSZzLe5zRuZFYJy0DHxQNhJXB9uqRthqdlTMdR0wTVgIivpTtLnHIT1Wt+5XvjZDWXKrQ6fSe4FYmtQ3y28D7bK9tf5DUqUIAoAAobjuULw6M4pwjx40yaCXFoYNv8Rr51fM2r+F7ABGMvDS+2EyylcgBWfjrBlmLzqvVnJGO4c9lNtBF1mLzEorMMAeCy73HtiYO24oOnokqcqnnJbVtj0kw7CewjeS6nO96juDZmraDStQcWQz2y8WeF+kaf4cnCAQjyJCCgH+prUhc2du6o8UNTp1hB/gWsHUclaHZc/kSCtxe+KVo8EJx2D7PZPZH6eLQhuScSMUIcmNh/7JTCYIAPtTc/y654n5FJdlY/n5K21Q+87KluPXYogzPnperqkrOr1xsQUZURezyfkn0fFhxEsbkV92vqa18nEyvOIvuQ7zxFCgUN3OnU/TjSxcXjPh50Bf2ARUfXztaHHxqaqVDCXyV4Ahje+6vb/wH0yRIJ/rZ+vvoV/l2+B64OVlDVyn+QapkCg2RsksmGATBiUFhG2h0Zyvj7dLr+1atmEasrKS4UhZPhAhShHGiSsGRuK0y3Wg7WlwoMk2q7Vsri1CwOtRrIdj2q6HR9Mir38LKNTifYOL+316qjVb4OQIFqR7NSKKIRFQyANUISnsUCSNzF8ld+xyh244WV2hZoXf/E9g/PqR5wKW6wIgAAAAASUVORK5CYII=>