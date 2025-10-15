
DIFERENCIAS ENTRE CONDA, VENV Y PIP
venv es el creador de entornos virtuales que viene con Python. Sirve para aislar las librerias de un proyecto usando el Python que ya hay. No instala paquetes por si mismo, se usas junto con pip.

pip es el instalador de paquetes de Python. Instala, actualiza y desinstala librerias desde PyPI, dentro del entorno que estes usando, ya sea venv, conda o global. 

conda gestiona entornos y paquetes a la vez. Puede instalar paquetes precompilados y dependencias del sistema, no solo de Python, desde canales como conda forge.

COMO RECREAR EL ENTORNO EN OTRA COMPUTADORA.
1. Instalar Python 3.11
2. Abrir la terminal e instalar git usando: pip install git
3. Clonar el repositorio de https://github.com/luisntaboada1/programacionCienciaDatos
4. En el directorio donde se instalo el repositorio activar el entorno virtual.
5. Si no se instalaron junto con el repositorio, instalar las dependencias del requirements.txt