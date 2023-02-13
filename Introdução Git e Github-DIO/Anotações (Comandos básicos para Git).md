# Comandos básicos para Git

**Inicar repositório no Git:**

- git init

*Estamos, realmente,  criando um repositório!



**Verificar o status do arquivo**

- git status

*Conseguimos ver em que estágio nosso arquivo está



**Pré commit**

- git add {nome do arquivo}

*Preparamos o arquivo para "commitar" eles

*É possível utilizar * para pré commitar todos os arquivos

**Cancelar o pré commit**

- git restore --staged {nome do arquivo}



**Commitar o arquivo**

- git comit -m "{mensagem}"

*Upamos o arquivo e deixamos disponível para todos

*_Flags_*



## Git e Github

**Linkar o repositório local com o remoto**

- git remote add origin {link do repositório}

*Pegamos o link do repositório no Github



**Levar o repositório local para o remoto**

- git push origin master

*origin é o apelido do repositório remoto (serve p não ter que ficar digitando o link inteiro)



**Baixar um repositório remoto e mexer localmente**

- git clone {url do github}







##  **Flags**

- -a

  Mostra arquivos ocultos

- -m

  Colocar uma mensagem no commit

- -v 

  Aponta para onde estava o repositório anteriormente
