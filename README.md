# Projeto Loteca 
Este é um projeto de simulador de loteria, 
onde o usuário digita 6 números e realiza um 
sorteio de outros 6 números, no final é verificado
quantos números ele acertou.

## Tecnologias utilizadas
- **HTML**: estrutura do site
- _CSS_: Estilização do site
- *_JS_*: funções do site
- ~~BottStrao~~: Não foi utilizado

### Melhorias Possiveis
1. [X] Subir para GitHubPages 
2. [ ] Alterar os Alerts
3. [ ] Utilizar o Bootstrap
4. [ ] deixar responsivo

### Disponibilizado em 
[GitBubPage](https://gabizaura.github.io/loteca_mat/)


### Prints da tela

| ID | Primeira tela | Segunda tela      | 
|----|---------------|-------------------|
| 1  | loteca Limpa  | loteca Preenchida |
| 2  | ![tela_loteca_não_preenchida](https://user-images.githubusercontent.com/100213062/161781963-12befac5-eb65-4e39-97d8-27c61dad2c52.png) | ![image](https://user-images.githubusercontent.com/100213062/161782746-4711ed3b-b0e9-48b5-ae42-1bb50a659540.png) |


#### Função Principal
```
function sorteio(){
        if(numEsco.length==6){
        var cont = 0
        numSort = []

    
            while(cont < 6){
      
                let num = Math.random() * 60
                num = Math.ceil(num)
                if(!numSort.includes(num)){
                    numSort[cont] = num
                    console.log(numSort)
                    cont++
                }   

            }
```

#### comando git 
para iniciar o projeto
```bash:
git init
```
