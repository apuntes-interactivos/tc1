!sudo apt update && sudo apt upgrade
!sudo apt install texlive-latex-base 
!sudo apt install texlive-pictures
!sudo apt install texlive-latex-extra
!sudo apt install imagemagick ghostscript
!sudo apt install libjs-mathjax
!sudo apt install fonts-mathjax
!pip3 install lcapy
!pip uninstall sympy -y
!pip install sympy

Entorno de ejecución--> reiniciar entonrno de ejecucións

---  
Vesion 2
!pip3 install lcapy
!sudo apt install ghostscript texlive-latex-extra

Para montar un directorio de google drive
~~~py
from google.colab import drive
drive.mount('/content/gdrive')
~~~