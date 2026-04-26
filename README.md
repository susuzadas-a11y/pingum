<div id="top">

<p align="center">

<picture>

</p>

<p align="center">
  <em>Pensado e realizado em prol da comunidade de FreeFire, por PinguimSS.</em>
</p>



</div>

<img src="https://i.imgur.com/NnWf7Fm.png" alt="line break" width="100%" height="3px">


## Introdução

PinguimSS é um scanner para dispositivos Android que tem o objetivo de reunir logs e arquivos suspeitos em questão de segundos de utilização.

**Por que usar o PinguimSS?**

O projeto tem como principal função facilitar o trabalho dos analistas em suas telagens, que contem várias funções, como:

* **🔵 Automação:** O scanner faz todo o trabalho pesado por você, poupando seu tempo.
* **⚫️ Logs suspeitas:** Reune log's de todos possíves bypass para você automaticamente.
* **🟣 Facilidade:** O scanner roda utilizando `Termux`, e com alguns simples comandos você já vai estar rodando ele sem problemas.


## Como utilizar?



#### <img width="2%" src="https://simpleicons.org/icons/diagramsdotnet.svg">  Faça o download do Termux:


| Aplicativo                  | Descrição                |
|----------------------------|---------------------------|
| [Termux](https://f-droid.org/repo/com.termux_1022.apk) | Terminal utilizado para rodar o scanner   |
| [Tutorial](https://www.youtube.com/watch?v=RF7O1MHThsE&t=8s) | Tutorial ensinando a como utilizar   |


#### <img width="2%" src="https://simpleicons.org/icons/termius.svg">  Após abrir o Termux, utilize a opção de Parear Dispositivo e siga o passo a passo.

```sh
pkg update -y && pkg install curl android-tools -y && rm -f PinguimSS && curl -L -o PinguimSS https://raw.githubusercontent.com/kellerzz/KellerSS-Android/main/KellerSS && chmod +x PinguimSS && ./PinguimSS
