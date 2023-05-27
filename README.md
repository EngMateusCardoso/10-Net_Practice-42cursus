# 10-Net_Practice

Overlap: No contexto de redes e roteamento, "overlap" significa que duas ou mais redes possuem faixas de endereços IP que se sobrepõem, causando problemas de conectividade e roteamento. Isso ocorre quando endereços IP em comum são usados em diferentes redes, levando a conflitos e dificuldades na determinação da rota correta para os pacotes. É importante evitar a sobreposição de redes planejando cuidadosamente a atribuição de endereços IP para cada rede e garantindo que não haja conflitos.

| Binário | Decimal |
| ------- | ------- |
|10000000|128|
|11000000|192|
|11100000|224|
|11110000|240|
|11111000|248|
|11111100|252|
|11111110|254|
|11111111|255|

Classes

| Classe | intervalo do 1º octeto | Atribuída a host | qtt de endereços | Mascara |
| --- | --- | --- | --- | --- |
| Classe A | 0-127 | Sim | 16.777.216 | 255.0.0.0 |
| Classe B | 128-191 | Sim | 65.536 | 255.255.0.0 |
| Classe C | 192-223 | Sim | 256 | 255.255.255.0 |
| Classe D | 224-239 | Não | Multicast | - |
| Classe E | 240-255 | Não | Novas tecnologias | - |

|nom|send menssage |
| --- | --- |
| Unicast | único |
| Multicast | Vários |
| Broadcast | Todos (da mesma rede)|
| Anycast | O mais próximo |

IPs restritos (RFC 1918)
Redes Internas
- 10.0.0.0/8
- 172.16.0.0/12
- 192.168.0.0/16

IPs reservados
- 127.0.0.0/8 - loopback
- 196.254.0.0/16 - APIPA: IP atomático
- 0.0.0.0 IP de inicialização
- 255.255.255.255 broadcast geral
