#############################################################################################
######################### Herramientas para Esteganografía en Linux #########################
#############################################################################################

Listado de herramientas:

- Matroschka
    Toda la info y descarga en el Github de su creador: https://github.com/fgrimme/Matroschka
    
- Steghide
    Toda la info en la web oficial: http://steghide.sourceforge.net/
    Instalación: sudo apt-get install steghide
    Uso:  OCULTAR => "steghide embed -ef [archivo a ocultar] -cf [archivo que servirá de camuflaje] -sf [nombre del nuevo archivo a crear]"
          DESCUBRIR => "steghide extract -sf [archivo que contiene aquello que está oculto) -xf [archivo nuevo a crear con lo extraído]"
    Añadiendo "-p [contraseña]" tanto para ocultar como para descubrir permite especificar la contraseña a usar

- SteganographyStudio
    Toda la info en la web oficial: http://stegstudio.sourceforge.net/
    Archivo java ejecutable disponible en este repositorio

- StegoLSB
    Toda la info en el Github de su creador: https://github.com/D14M4NT3/StegoLSB.py
    Archivo py disponible en este repositorio

- xstegsecret
    Info en la página de su creador: http://stegsecret.sourceforge.net/indexS.html
    Archivo para descarga tanto en la página oficial como en este respositorio
