# DRP -- Política de Còpies de Seguretat

## Muntatges i Serveis Tècnics SL

## 1) Dades objecte de còpia

### Servidor -- Ubuntu Server

  -----------------------------------------------------------------------
  Tipus de dades     Volum     Criticitat     Freqüència de còpia
  ------------------ --------- -------------- ---------------------------
  Documents de       300 GB    Crític         Diària (Incremental),
  projectes                                   Setmanal (Completa),
                                              Mensual (Completa)

  Bases de dades     20 GB     Molt crític    Cada 4 h (Incremental),
                                              Diària/Setmanal/Mensual
                                              (Completa)

  Carpetes personals 100 GB    Crític         Diària (Incremental),
                                              Setmanal (Completa)
  -----------------------------------------------------------------------

### Equips clients

  ------------------------------------------------------------------------
  Tipus de dades               Criticitat            Freqüència
  ---------------------------- --------------------- ---------------------
  Carpeta Documents            Mitjà/Crític          Diària (Incremental),
                                                     Setmanal (Completa)

  ------------------------------------------------------------------------

## 2) Cronograma setmanal

  Dia                  Dades   Tipus de còpia                   Mitjà
  -------------------- ------- -------------------------------- -------------------
  Dilluns              Totes   Incremental + BD Completa        NAS
  Dimarts--Divendres   Totes   Incremental                      NAS
  Dissabte             Totes   Completa setmanal                NAS + Disc extern
  Diumenge             Totes   Completa mensual (1r diumenge)   Cloud

## 3) Regla 3-2-1

### Mitjà 1: NAS intern (RAID 5)

### Mitjà 2: Disc dur extern

### Mitjà 3: Còpia Cloud

## 4) Estratègia RTO / RPO

-   **RPO:** 4 hores\
-   **RTO:** 4 hores
