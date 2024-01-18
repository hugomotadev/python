# Python


### Criando ambiente virtual Python com "venv" dentro do seu projeto

1. No terminal, execute o seguinte comando:
```
python -m venv .venv
```
>[!NOTE]
>A execução desse comando cria o diretorio chamado "venv" e coloca todos os arquivos necessários para o ambiente virtual dentro. Além disso, Outro nome pode ser usado para este diretorio, mas por padrão é comumente chamado de ".venv".

Estrutura de diretorio em um Windows utilizando o Explorar do Visual Estudio Code:
![image](https://github.com/hugomotadev/python/assets/134611853/1b85a802-987e-4f76-8967-cf0018efd43c)

2. Execute o comando abaixo para ativar o ambiente virtual:
```
.venv/Scripts/activate.bat
```
>[!NOTE]
>Agora o nome do ambiente virtual aparecerá entre parênteses anter do texto do prompt:
>
>![image](https://github.com/hugomotadev/python/assets/134611853/513c8851-d588-485e-bd45-8eaffcfe811a)


> [!IMPORTANT]
> Se estiver usando o Visual Estudio Code no Windows utilize o cmd como terminal e substitua as barras do comando acima por barras invertidas para indicar o caminho do script activete.bat

3. Agora você pode instalar quaisque pacotes ou módulos de maneira isolado do ambiente "global".

 
#### Bibliografia

- https://code.visualstudio.com/docs/python/environments
