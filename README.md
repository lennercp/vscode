# Como baixar o vscode
Acesse esse [site](https://code.visualstudio.com/download#) para fazer o download do vscode, e clique na opção **.tar.gz x64**

Abra o terminal e vá para pasta downloads
```shell
cd downloads
```

Copie esse comando e ao final aperte **TAB** para completar o nome do arquivo, depois aperte ENTER
```shell
tar -zxvf code-stable-x64
```

Após a instalação ser concluída, rode esses comandos
```shell
cd VSCode
pwd
```
Copie o caminho e agora vamos criar um atalho
```shell
vim ~/.bashrc
```

dentro do arquivo coloque isso, no lugar de "caminho" colar o que foi copiado na etapa anterior
```shell
alias code='"caminho"/code'
```

aperte **:** **wq**

agora iremos atualizar o bashrc com esse comando
```shell
source ~/.bashrc
```

agora so rodar o comando 
```shell
code
```
e o vscode irá abrir



