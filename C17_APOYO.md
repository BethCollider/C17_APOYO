# Construir funcion de reinicio

`function reinicio () {`

​    `//Establecer el cambio de GS`

​    `GS = PLAY;`

​    `//Definir visibiliodad de mensajes`

​    `gameover.visible = false;`

​    `reset.visible = false;`

​    `//Establecer destruccion de obstaculos y nubes`

​    `obsGrup.destroyEach();`

​    `nubeGrup.destroyEach();`

​    `//Cambiar imagen trex`

​    `trex.changeAnimation("runner",trex_running);`

​    `//Puntacion 0`

​    `score = 0;`

`}`