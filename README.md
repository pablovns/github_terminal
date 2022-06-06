# Usando o GitHub pelo terminal

- O primeiro passo é clonar (baixar) o repositório já existente no GitHub (crie ele se necessário):  
    - `git clone <link do repositório>`  
    
    Exemplo:
    - `git clone https://github.com/pablovns/exemplo.git` 

    **Certifique-se de que o link tenha o `.git` no final**.
  
<br>  

- Preparas as mudanças feitas nos arquivos (+ do VS Code):  
    - Caso você queira adicionar todos os arquivos do diretório atual no terminal:
        - `git add .`
    - Caso você queira adicionar arquivos individualmente: 
        - `git add <nome do arquivo>`  

        Exemplo:
        - `git add index.html`
  
<br>  

- Ver quais mudanças estão preparadas (verde = arquivo adicionado):  
    - `git status`
  
<br>  

- Dar commit nas mudanças (commit para o Git, não para o GitHub):  
    - `git commit -m 'mensagem'`  

    Exemplo:  
    - `git commit -m 'Mudanças iniciais'`
  
<br>  

- Selecionar a branch (ramificação) main (principal):
    - `git branch -M main`

- Dar push (enviar para o GitHub) no que foi dado commit:  
    - `git push -u origin main`  

<br>

### OBS: Talvez seja necessário configurar o seu usuário e e-mail com os seguintes comandos:
- usuário:  
    - `git config user.name "seu-nome-aqui"`
- email:  
    - `git config user.email "seu-email@exemplo.com"`