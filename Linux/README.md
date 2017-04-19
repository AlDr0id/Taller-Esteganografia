**Herramientas para Esteganografía en Linux**

Listado de herramientas:

- **Matroschka**<br>
    Toda la info y descarga en el Github de su creador: https://github.com/fgrimme/Matroschka
    
- **Steghide**<br>
    Toda la info en la web oficial: http://steghide.sourceforge.net/ <br>
    Instalación: sudo apt-get install steghide<br>
    Uso:  OCULTAR => "steghide embed -ef [archivo a ocultar] -cf [archivo que servirá de camuflaje] -sf [nombre del nuevo archivo a crear]"<br>
          DESCUBRIR => "steghide extract -sf [archivo que contiene aquello que está oculto) -xf [archivo nuevo a crear con lo extraído]" <br>
    Añadiendo "-p [contraseña]" tanto para ocultar como para descubrir permite especificar la contraseña a usar

- **SteganographyStudio**<br>
    Toda la info en la web oficial: http://stegstudio.sourceforge.net/<br>
    Archivo java ejecutable disponible en este repositorio

- **StegoLSB**<br>
    Toda la info en el Github de su creador: https://github.com/D14M4NT3/StegoLSB.py<br>
    Archivo python disponible en este repositorio

- **xstegsecret**<br>
    Info en la página de su creador: http://stegsecret.sourceforge.net/indexS.html<br>
    Archivo para descarga tanto en la página oficial como en este respositorio
