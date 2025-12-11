# T02: Copias de Seguridad en Windows 11 con Duplicati

### Ahora configuraremos las copias de seguridad en Windows 11 con Duplicati utilizando un disco duro adicional de 10 GB.
<img src="img/1.png">

---

## 1. Creación y formato del disco

### Aceptamos formateal el disco con esquema **GPT**.

<img src="img/2.png">

### Creem un **Volum simple** per preparar el disc.

<img src="img/4.png">

### Seguiremos con los pasos que nos diga la instalación con son de deducción

<img src="img/5.png">
<img src="img/6.png">
<img src="img/7.png">
<img src="img/8.png">

### Una vez creado ya nos aparece cuando abrimos el explorador de arvhivos

<img src="img/9.png">

---

## 2. Instal·lació de Duplicati

### Instalamos la aplicación desde la web oficial para evitar riesgos de seguirdad

### Para la instalación seguimos los siguientes pasos:

<img src="img/10.png">
<img src="img/11.png">
<img src="img/12.png">
<img src="img/13.png">

### Seleccionamos la opción instalar **Instal·lar**.

<img src="img/15.png">

---

## 3. Configuración inicial

### Cuando abramos Duplicati nos pedriá que asignemos una  **contraseña de administración**.

<img src="img/14.png">

### Hecho esto ya podemos hacer copias de seguridad

---

## 4. Creación de una copia de seguridad local

### Vamos a **Backups → Add**.

<img src="img/15.png">

### Seleccionamos **New Backup**.

<img src="img/16.png">

### Asignamos un nombre y una contraseña.

<img src="img/17.png">

### Configuramos el destino de la copia de seguridad.

<img src="img/18.png">

### Seleccionamos la carpeta que queremos copiar, en nuestro caso **Documents**.

<img src="img/19.png">

### Programamos la copia de seguridad para que se ejecutra **cada hora cada dia**.

<img src="img/20.png">

Configuramos que se guarden **todas les versiones**.

<img src="img/21.png">

### Configuracióm completada.

<img src="img/22.png">

---

## 5. Prueba de copia local

### A la carpeta Documents y un archivo **proba.txt**.

<img src="img/23.png">

### Ejecutamos la copia de forma manual con **Start**.

<img src="img/24.png">

### Borramos el documentos que hemos creado para hacer la prueba de restauración.

<img src="img/25.png">

---

## 6. Restauración local

### Accedemos a **Restores → Start**.

<img src="img/26.png">

### Seleccionamos la copia y hacemos click a **Restore**.

<img src="img/27.png">

### Seleccionamos la carpeta que queremos recuperar.

<img src="img/28.png">

### Lo restauramos a la ubicación original.

<img src="img/29.png">

### Comprobamos que la restauración se ha hecho con exito.

<img src="img/30.png">

---

## 7. Copia de seguridad a Google Drive

### Ahora crearemos una copia al Google Drive, programada cada dia para las 18:00.

<img src="img/31.png">

### Comencem configurant la còpia. El destí serà **Google Drive**.

<img src="img/32.png">

### Ponemos de ruta la copia de la carpeta **Documentos** y hacemos clic a **AuthID** para vincular nuestra cuenta.

<img src="img/33.png">

### Al hacer clic en **AuthID** se abre una pestaña para vincular nuestra cuenta.

<img src="img/34.png">


### Copa el codigo en la caja de  **código de autorización**.

<img src="img/35.png">

### Seleccionamos donde sera la ruta.

<img src="img/36.png">

### Programamos la copia cada dia a las **18:00 cada dia**.

<img src="img/37.png">

### Iniciamos la primera copia con el botón **Start**.

<img src="img/39.png">


### Borramos el docuemnt **prova.txt** para hacer la prueba de restauración.

<img src="img/41.png">

---

## 8. Restauración desde el Google Drive

### Para iniciar la restauración vamos a **Restores → Start**.

<img src="img/42.png">

### Seleccionamos la copia de seguridad de **Còpia Google Drive** y hacemos clic a **Restore**.

<img src="img/43.png">

### Comprbamos que la restauración se ha hecho con exito.

<img src="img/44.png">
