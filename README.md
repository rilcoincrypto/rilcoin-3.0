# rilcoin-3.0 
(English readme click here https://github.com/rilcoincrypto/rilcoin-3.0/blob/main/EN-README.md)

Nueva versión de Rilcoin, más rápida, segura y sencilla

Creemos que rilcoin es una criptomoneda designada para facilitar la interacción comercial

Nuestro equipo se ha enfocado en crear la forma de pago más amigable

Rilcoin 3.0 brinda más seguridad y transparencia a nuestros usuarios

Además, solucionamos el problema energético, hemos sido más ecológicos, con nuestro consenso SPoW

SPoW (Subsecuente Proof of Work) reducirá la intensidad de la energía dedicada a extraer un bloque y mantendrá la red segura

Cada nodo y cada billetera tendrán la opción de minar y obtener recompensas basadas en transacciones, sin equipo dedicado

Rilcoin 3.0 está abierto para ser utilizado como forma de pago en cualquier desarrollo, es universal y no responde a ningún Gobierno o Entidad

Visítanos en https://rilcoin.org/

Empezando

1) Descarga la billetera basada en tu sistema operativo

-Abra su billetera y asegúrese de que su billetera esté conectada con un nodo. -Su billetera está conectada cuando vea el icono Conexiones de billetera en la esquina inferior derecha de su billetera.

2) Utilice las siguientes instrucciones para extraer un bloque.

-Cierre su billetera y cree el archivo rilcoin.conf en la carpeta “% APPDATA% \ rilcoin \”.

-Pega el siguiente texto en rilcoin.conf y guarda el archivo.

rpcuser=rpc_rilcoin

rpcpassword=50438c6bdd47af5d887e9fc81

rpcallowip=127.0.0.1

rpcport=26579

listen=1

server=1

addnode=ril.99usa.com

addnode=ril2.99usa.com

-Abre tu billetera.

-Cree un archivo .bat llamado mine.bat en la misma carpeta donde extrajo rilcoin-cli.exe y pegue el siguiente texto en mine.bat.

@echo off

set SCRIPT_PATH=%cd%

cd %SCRIPT_PATH%

echo Press [CTRL+C] to stop mining.

:begin

rilcoin-cli.exe generate 1

goto begin

-Guarda el archivo.

-Ejecutar mine.bat para comenzar a minar.

Le tomará alrededor de +/- 30 minutos extraer su primer bloque, dependiendo del hardware de su computadora.

Tenga en cuenta que sus bloques darán 0 recompensas, cuando lleguen las transacciones y se generen tx, las recompensas comenzarán a mostrarse, es aleatorio.
