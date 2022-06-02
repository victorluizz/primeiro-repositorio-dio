# Comandos básicos para um bom desempenho no terminal

- Links
    
    [Iniciando o Git e criando um commit](https://www.notion.so/Iniciando-o-Git-e-criando-um-commit-c60a7ca6416b4afa800eb6bcf1ca37cf) 
    
    [Ciclo de vida dos arquivos no Git](https://www.notion.so/Ciclo-de-vida-dos-arquivos-no-Git-60ffcccbc37849a8b268db48cc94db86) 
    
    [Trabalhando com o GitHub](https://www.notion.so/Trabalhando-com-o-GitHub-cd32352a3c1e499988932dce4c3f844a) 
    

# Comandos no terminal do Windows

## dir

- Serve para mostrar todos os diretórios da pasta na qual você está.

## cd

- Serve para ir diretamente a uma pasta específica.
- É igual em todos os sitemas operacionais.
    - **Ex:** C:\Users\victo>cd /
- **cd ..** - Serve para sair de um diretório
    - **Ex:** C:\workspace>cd ..

## cls

- Serve para limpar a tela do terminal.

## tab

- Completa o nome do diretório que está sendo digitado.

## mkdir

- Serve para criar um diretório novo.
- **Ex:** C:\>mkdir workspace

## echo

- Printa no terminal a palavra que foi digitada.
    - **Ex**
        - C:\workspace>echo ola
            
            ![Untitled](Comandos%20ba%CC%81sicos%20para%20um%20bom%20desempenho%20no%20termin%201467f81458bf41aeb20aa055234ea9eb/Untitled.png)
            
- Caso seja usado com um “>”, ele verifica se o arquivo citado já existe na pasta, caso não, ele mesmo o cria.
    - **Ex**
        - C:\workspace>echo hello > hello.txt
            
            ![Untitled](Comandos%20ba%CC%81sicos%20para%20um%20bom%20desempenho%20no%20termin%201467f81458bf41aeb20aa055234ea9eb/Untitled%201.png)
            

## del

- Serve para deletar arquivos.
- **Ex:** C:\>del workspace
    - Nesse exemplo, ele apagaria todos os arquivos que estão na pasta “workspace”.

## seta pra cima

- Navega entre o histórico de comandos que já foi utilizado no terminal.

## rmdir

- Deleta um repositório, assim como todos os arquivos dentro dele.
- **Ex:** C:\>rmdir workspace /S /Q