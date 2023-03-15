# Projeto ERC 2981
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/marciogsantana/hackathon_celo/blob/main/LICENCE) 

# Sobre o projeto

Este projeto tem o objetivo de implementar um contrato
ERC 721 e o ERC2981 para adicionar Royalties ao contrato 
utilizado para fazer o mint dos NFTs 


### Funcionamento

O usuário pode usar a plataforma para fazer o mint dos NFTS,
quando este NFT for vendido a plataforma recebe 10% do valor
de venda do NFT a titulo de serviço.



## Layout Front End
![Front1](https://github.com/marciogsantana/imagens/blob/main/imagem_trofeu.png) ![Front 2](https://github.com/marciogsantana/imagens/blob/main/imagem_front_nft_2.png)


## NFT na plataforma Harible
![harible](https://github.com/marciogsantana/imagens/blob/main/imagem_royaltes_taxa.png)  

## Visualização  do percentual de Royaltie,
![harible_](https://github.com/marciogsantana/imagens/blob/main/imagem_royaltes_taxa_2.png)  

## Imagem IPFS,
![IPFS Imaggem](https://github.com/marciogsantana/imagens/blob/main/Metadados.png)  


# Tecnologias utilizadas
## Back end
- Javascript
- NodeJs
- Solidity
- Truffle
- Ganache (testes rápidos)
- Pinata
- Alchemy
- Redes de testes Goerli
- Plataformas de testes Opensea e Rarible
## Front end
- HTML / CSS / JS / TypeScript
- ReactJS
- React Native
## Iniciar o projeto

# clonar repositório
git clone https://github.com/marciogsantana/Projeto_IEP2981.git

```bash

# alterar o arqvuivo .env
inserir as chaves para autenticação

# Na raiz do projeto

# instalar dependências
npm install

# fazer deploy do contrato na rede de testes Goerli
truffle migrate --network goerli --reset

# acessar pasta SRC
# cd src
# executar o comando abaixo
npm start
Acesse http://localhost:3000 para visualizar a página no browser
```

# Autor

Márcio Gomes de Santana

https://www.linkedin.com/in/marcio-gomes-de-santana-05347198/
