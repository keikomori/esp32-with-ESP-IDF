<h6>Placa de desenvolvimento ESP32 (ESP8266) </h6>
<h1 align="center">Desenvolvendo no ESP32 com o SDK ESP-IDF</h1>
<h6 align="center">by Keiko Mori</h6>

Como desenvolver projetos utilizando RTOS no ESP32 com o SDK ESP-IDF.

<h4>Instalação do SDK-IDF v4.2</h4>

Acesse o site oficial da Spressif e faça o download do [esp-idf](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/get-started/windows-setup.html)

<h4> Comandos utilizados para Compilar, Gravar e Monitorar a Saída Serial do ESP32: </h4>

```python

# Configuração do projeto com o menuconfig
idf.py menuconfig
 
# Para compilar
idf.py build
 
# Compilar, gravar e abrir o terminal serial (monitor)
idf.py -p COMx flash monitor
 
# Apagar a memória Flash do ESP32
idf.py -p COMx erase_flash
 
# Apagar os objetos criados na última compilação
idf.py clean
 
# Abrir o terminal serial
idf.py -p COMx monitor
```

> Em algumas versões de placas é necessário acionar o botão de BOOT da placa para que sejam gravados os dados

<h4>em desenvolvimento ...</h4>


