# Como usar

## Acessar uma Branch Específica de Atividade

Para acessar uma branch específica de atividade no repositório, siga os seguintes passos:

### 1. Clone o repositório (se ainda não o fez):
``git clone https://github.com/seu-usuario/repositorio.git``
``cd repositorio``

### 2. Para mudar para uma branch específica, como a branch atividade02:
``git checkout atividade02``

## Criar e Subir uma Nova Branch de Atividade

Para criar e subir uma nova branch de atividade:

### 1. A partir da branch principal (ou de qualquer outra branch que você deseja usar como base):
``git checkout main``

### 2. Crie a nova branch, por exemplo atividade03:
``git checkout -b atividade03``

### 3. Após fazer as mudanças desejadas e commitar essas mudanças:
``git add .``
``git commit -m "Descreva as alterações feitas"``

### 4. Suba a nova branch para o repositório remoto:
``git push -u origin atividade03``
