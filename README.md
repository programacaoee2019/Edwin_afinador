# Edwin_afinador

Conceito

Um microfone adquriria um sinal de aúdio e retornaria a frequência do tom de maior amplitude, isto é, a frequência fundamental da corda tocada. Como saída, seria um display mostrando a frequência do tom tocado e o nome da corda mais próxima a esse som, com uma indicação do quão distante está em semitons.

Por exemplo, suponhamos a frequência de 333,5Hz. A corda mais perto dessa frequência é a corda 1, maior que ela 3,9 Hz. Transferiríamos esse valor para semitons. Além disso, para tornar a interface melhor, colocáriamos um indicador dizendo se está muito grave ou agudo o som, facilitando o usuário a afinar rapidamente. 

Uma forma de desenvolver ainda mais isso, seria não especificar o instrumento a ser afinado. Acredito que iria envolver bastante combinatória para encontrar o instrumento apartir da manipulação do sinal de áudio.


Função

Afinar uma guitarra/violão utilizando o MyRio conectado a um display e um microfone, ou utilizando a própria tela do notebook e o microfone do notebook.


Motivação

O trabalho envolve manipulação de sinais de áudio, vistos na cadeira de SSL, conceitos de programação do LabView, possível aplicação de conceitos de combinatória e, ainda, um pouco teoria musical. Além disso, é uma aplicação diária na vida de quem toca/trabalha com instrumentos.

Interface Gráfica

A linguagem de programação LabView facilita a proposta, tornando tanto a programação quanto a interface gráfica integradas e simples. Logo abaixo, um exemplo do Front Painel.

![FrontPainel](https://user-images.githubusercontent.com/48916600/59400712-c145b200-8d6e-11e9-9de6-26cfb85cd2e0.png)

O usuário escolherá a corda em Choosing the string, conseguirá ver os sinais, tanto o recebido quanto o padrão daquela corda, e suas transformadas de fourier nos espaços para gráficos mostrados. Por fim, os indicadores em LED afirmam se sua corda está frouxa ou não. Um indicador mais sensível acima (com ponteiro) servirá para atingir a afinação (TUNED). 


