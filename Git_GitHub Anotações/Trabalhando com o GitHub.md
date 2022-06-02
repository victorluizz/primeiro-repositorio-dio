# Trabalhando com o GitHub

- Links
    
    [Comandos básicos para um bom desempenho no terminal](https://www.notion.so/Comandos-b-sicos-para-um-bom-desempenho-no-terminal-40f48e0624054c329facff1768f46ce6) 
    
    [Iniciando o Git e criando um commit](https://www.notion.so/Iniciando-o-Git-e-criando-um-commit-c60a7ca6416b4afa800eb6bcf1ca37cf) 
    
    [Ciclo de vida dos arquivos no Git](https://www.notion.so/Ciclo-de-vida-dos-arquivos-no-Git-60ffcccbc37849a8b268db48cc94db86) 
    

## Criando um repositório no Git e upando os arquivos do Notebook

- **Passo a passo**
    1. Dar um “Git Bash Here” na pasta onde está os arquivos
    2. Pegar o link do repositório no GitHub
    3. No terminal: git remote add origin [git@github.com](mailto:git@github.com):victorluizz/livro-receitas.git
    4. No terminal: git remote -v
    5. No terminal: git push origin master
        - Após isso, será solicitado a senha que foi criada em SSH
- **Observações**
    - É bom criar o arquivo README e colocar ele como “md”.

## Clonando um repositório

- **Passo a passo**
    1. Ir no repositório e pegar o código SSH ou HTTPS
    2. Ir na pasta no computador e dar um “Git Bash Here’
    3. No terminal: git clone git clone [git@github.com](mailto:git@github.com):victorluizz/primeiro-repositorio-dio.git

## git remote -v

- Lista todos os repositórios remotos que você tem.