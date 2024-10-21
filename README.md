# Sample Server Thing to connect to a WoT Directory service using DNS-SD.

## Description (en)

Sample Thing to connect to a WoT Directory service using DNS-SD.

It connects to the first service under _wot._tcp.local.

It also alerts its presence under esp32.local.

It has 2 GET endpoints with no authorization:

* /getThingDescription (self-explanatory)
* /doSomething (actually buzz a buzzer connect to pin 23).

## Description (pt)

Thing de exemplo para conectar para um WoT Directory usando DNS-DS.

Conecta para o primeiro serviço sob _wot._tcp.local.

Também alerta sua presença sob esp32.local.

Tem dois GET endpoints sem autorização:

* /getThingDescription (pega a Thing Description)
* /doSomething (apita um buzzer conectado ao pino 23).

# Setup 

**(en)** Using an Arduino or an ESP32, connect a led on pin 2, and a buzzer on pin 23. Also make sure to turn on a WoT Directory service under _wot._tcp.local, and make sure the Thing Description is uploaded observing the led.

**(pt)** Usando um Arduino ou uma ESP32, conecte uma led no pino 2, e um buzzer no pino 23. Tenha certeza de ligar um diretório sob _wot._tcp.local, e verifique se a Thing Description foi enviada observando o led.