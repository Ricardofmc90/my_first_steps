1 - https://github.com/Ricardofmc90/my_first_steps

2 - Naveguei pelo git bash (utilizando o cd e ls) até o local onde queria criar a pasta. Dei um mkdir, naveguei para dentro dela e usei o git init.
Fui ao github, peguei o endereço do repositório e voltei ao git bash para dar:
git remote add origin https://github.com/Ricardofmc90/my_first_steps.git

3 - Para criar o arquivo:
echo > ola_mundo.txt Lovelace
Para adicioná-lo:
git add ola-mundo.txt
git commit -m ‘Primeiro commit’
git push -u origin main

4 - echo > .gitignore
echo > serei_ignorado.txt Ignorar tudo!
vim .gitignore
Coloquei o nome do arquivo (serer_ignorado.txt) dentro do .gitignore e salvei;


