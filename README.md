# DnnBase
Dnn Module

Para rodar este projeto é necessário alguns passos:

1º) Abra o Visual Studio e vá em Tools > Extension And Updates
2º) Clicando na aba Online, pesquise pro DNN
3º) Instale os templates do Dnn e reinicie o VS
4º) Para usar estes templates, é necessário criar um site no IIS.
5º) Ao abrir o VS e clicar em New Project, selecione o Template DNN desejado.
6º) Ele vai solicitar algumas informações, sendo a última delas o caminho do site criado no IIS. Informe o site sem o http://. Ex: localhost:1010

A partir daí já será possível editar o projeto.

Para realizar a publicação do Module:

1º) Deve-se compilar a aplicação no modo release.
2º) Acessar o Dnn como SuperUsuario
3º) Clicar no icone de Gear a esquerda da página e acessar o menu Extensions
4ª) Clicar em Install Module, no topo direto da barra
5º) Dentro da pasta do projeto, haverá uma pasta chamada "install". Dentro dela vão haver dois arquivos. Realize o upload do arquivo que tem o sufixo "_install.zip"
6º) Após o upload ser realizado, será feito um breve wizard de instalação. Next, Next, Next, Next, Accept, Next, Next ...
7º) Após a instalação, o módulo ficará disponível para instalação em qualquer página.




