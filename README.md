# Edwin_afinador

# Conceito

O projeto é fazer um afinador de guitarra/violão de seis cordas. Como entrada, o sinal de aúdio adquirido por um microfone, e a escolha do usuário de qual corda será tocada. Como saída, existe um display mostrando se a corda está afinada, uma indicação de o quão distante está para o afinamento e em que direção devemos afinar. Além disso, há 3 leds confirmando se aquele som está mais agudo, mais grave ou já afinado.

Por exemplo, suponhamos a frequência de 333,5Hz captada de um usuário que escolheu a corda Lá. O programa detecta a frequência do som é maior por 3,9 Hz do padrão da corda Lá (110Hz). A interface mostra Sharp (agudo) e diz se está perto ou longe da afinação dá certo por um indicador tipo velocímetro.

# Função

Afinar uma guitarra/violão utilizando a própria tela do notebook e o microfone do notebook, ou qualquer microfone conectado.


# Motivação

O trabalho envolve manipulação de sinais de áudio, vistos na cadeira de SSL, conceitos de programação do LabView, possível aplicação de conceitos de combinatória e, ainda, um pouco teoria musical. Além disso, é uma aplicação diária na vida de quem toca/trabalha com instrumentos.

# Interface Gráfica

A linguagem de programação LabView facilita a proposta, tornando tanto a programação quanto a interface gráfica integradas e simples. Logo abaixo, um exemplo do Front Painel.

![FrontPainel](https://user-images.githubusercontent.com/48916600/59400712-c145b200-8d6e-11e9-9de6-26cfb85cd2e0.png)

O usuário escolherá a corda em Choosing the string. Após tocá-la, os indicadores em LED afirmam se sua corda está frouxa ou não. Um indicador mais sensível acima (com ponteiro) servirá para atingir a afinação (TUNED). 

# Fluxograma




