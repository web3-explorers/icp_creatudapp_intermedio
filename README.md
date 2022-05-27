# Crea tu dApp con ICP - Intermedio

Este repositorio contiene las presentaciones y códigos usados en el curso Crea tu dApp con ICP - Intermedio.

La presentación está disponible en: [Presentación](https://github.com/web3-explorers/icp_creatudapp_intermedio/blob/main/Crea%20una%20dApp%20con%20ICP%20-%20intermedio.pdf)

El curso está disponible en: https://youtube.com/playlist?list=PLu4f2kXcjVZYNdwUWF72MpB7uq7ipJaHS

## Pasos de ejecución

1. Primero, debes clonar este repositorio:
```sh
git clone https://github.com/web3-explorers/icp_creatudapp_intermedio.git
```

2. Luego, modifica los archivos de acuerdo a lo visto en el curso: https://youtube.com/playlist?list=PLu4f2kXcjVZYNdwUWF72MpB7uq7ipJaHS

3. A continuación, instala el DFinity Canister SDK (en una máquina tipo Linux):

```sh
sudo sh -ci "$(curl -fsSL https://smartcontracts.org/install.sh)"
```

4. En la misma máquina Linux, en la ruta raíz del proyecto ejecuta los siguientes pasos:

```sh
sudo dfx start --background
sudo npm install
sudo dfx deploy
```

5. En un navegador, explora la url: **http://<dominio/ip de la máquina>:8080**
