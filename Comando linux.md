## En la siguiente sesión podremos ver los comandos linux mas importantes

### cambiar de directorios
- cd 

### crear carpetas
- mkdir

### Eliminar archivos y directorios
- rm -rf


### Listar los archivos y carpetas
ls -lhtra

### Donde:
- ls -> Lista los directorios .
- l -> Ver detalle de los directorios y archivos.
- h -> Ver el peso de los archivos de una manera entendible.
- S -> Ordernar por peso de los archivos.
- t -> Ordenados por la fecha de edición (por defecto esta de la manera acendente)
- r -> Listar de manera desendente.
- a -> Visualizar los archivos ocultos

### crear archivos
- touch

### Mover archivos o carpetas
- mv (mover, renombrar)

### Comando de espacio para particiones
 - df -h
 
 ### Uso de disco
 - du -h (Se puede ver todos los archivos y directorios)
 - du -sh (Se ve el total del directorio)
 - du -sh * | sort -h (Ver el peso de todos los archivos y directorios, pero ordenado de menor a mayor)
 
 ### Crear enlace o link
 - ln (Enlace duro, para archivos o directorios)
 - Ejemplo: ln .bashrc .bash_profile
 
 - ln -s (Enlace simbolico, para directorios) - Recomendado
 - Ejempplo: ln -s etc /etc/
 
 
 ### Copiar archivos
 - cp archivo.txt archivo2.txt
 
 ### Copiar directorios
 - cp -r carpera carpera_copy (Es necesario que se indique -r)
 
 
 
