# Documentações sobre o shield Ramps 1.6 Rearap e congigurações gerais usando Marlin 1.1.9



[RAMPS 1.6 - RepRap](https://reprap.org/wiki/RAMPS_1.6)

Atentar para o tópico Warning que alerta sobre um erro na placa que joga o pino de 5V para GND.

![Warning](https://reprap.org/mediawiki/images/d/d0/Shorted.png)


Para verificar o diagrama esquemático clique [aqui](https://github.com/bigtreetech/ramps-1.6/blob/master/Ramps1.6/hardware/R6Schematic%20diagram.pdf)

![JPG com o esquema de conectores da Ramp 1.6](https://reprap.org/mediawiki/images/5/55/RAMPS1-6connectors.jpg)



|  Jumper 1 | Jumper 2  | Jumper 3  |   Steps     |
|:---------:|:---------:|:---------:|------------:|
|    Não    |   Não     |   Não     |  Full step  |
|    Sim    |   Não     |   Não     |  Half step  |
|    Não    |   Sim     |   Sim     |   1/4 step  |
|    Sim    |   Sim     |   Não     |   1/8 step  |
|    Não    |   Não     |   Sim     |  1/16 step  |
|    Sim    |   Não     |   Sim     |  1/32 step  |
|    Sim    |   Sim     |   Sim     | 1/128 step  |

