# MarketCloud-Atualizado
Fiz uma atualização nesse código devido a um conflito que estava tendo devido a atualização do Framework ionic se esta dando o mesmo problema com você essa solução pode ser útil.


Quando der esse erro: "rename it to ionic.consfig.json, or your project directory will not be detected"


Solução 1 - Acho que sua primeira máquina possui uma versão iônica <2.0.0, a outra> = 2.0.0

Se você encontrou o arquivo chamado  ionic.project renomear para ionic.config.json

Espero que isso o ajude.



Salução 2 - Crie um arquivo ionic.config.json manualmente na pasta do projeto. Copie o código abaixo mencionado neste arquivo:

{"nome": "Substituir pelo nome do seu projeto", "app_id": "", "v2": true, "typecript": true}

execute uma "instalação npm" para garantir que todos os módulos node_modules sejam atualizados. Isso funcionou para mim
