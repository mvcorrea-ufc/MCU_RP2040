# Enviroment

## Pre-Requisitos
* [docker desktop](https://www.docker.com/get-started) instalado na máquina.

## Instalação do Ambiente de Desenvolvimento
```shell
git clone https://github.com/mvcorrea-ufc/MCU_RP2040.git            # MCU_RP2040 folder created 
cd MCU_RP2040 && cp enviroment/dockerfile.minideb ./Dockerfile      # copy the dockerfile
docker build -t="arm-env:1.0" .                                     # build the image
```