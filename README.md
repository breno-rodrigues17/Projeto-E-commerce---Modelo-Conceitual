# Projeto conceitual de Banco de dados - E-COMMERCE

Este repositorio contém o modelo conceitual de banco de dados para um sistema **E-COMMERCE"".
O projeto foi desenvolvido como parte de um desafio da dio 
___

## 🎯 Objetivo do Projeto
O desafio consiste em **refinar o modelo apresentado**, incluindo os seguintes pontos:

- **Cliente PJ e PF:** Uma conta pode ser **Pessoa Jurídica (PJ)** ou **Pessoa Física (PF)**, mas não pode ter as duas informações simultaneamente.  
- **Pagamento:** É possível cadastrar **mais de uma forma de pagamento** para uma conta.  
- **Entrega:** Cada entrega possui **status** e **código de rastreio** para acompanhamento.  

## 🛠️ Tecnologias Utilizadas
- **DBDesigner** ou ferramenta similar para criação do diagrama.
- **Git/GitHub** para versionamento e hospedagem do projeto.
- Conceitos de **modelagem conceitual**, **entidades**, **relacionamentos** e **integridade de dados**.


## 🔍 Visualização do Diagrama
O diagrama está disponível na pasta `![Diagrama Conceitual](https://raw.githubusercontent.com/breno-rodrigues17/Projeto-E-commerce---Modelo-Conceitual/main/Modelo%20conceitual%20ecommerce%20-%20dio.png)
` e pode ser visualizado diretamente no GitHub como imagem.  

> Dica: Clique na imagem para ampliar e analisar todos os relacionamentos entre entidades.

## 📝 Exemplo de Entidades e Relacionamentos
- **Cliente** → Pode ser PJ ou PF.  
- **Forma de Pagamento** → Relacionamento N:1 com Cliente (um cliente pode ter várias formas de pagamento).  
- **Entrega** → Possui atributos de `status` e `código de rastreio`.  

## 🚀 Como Contribuir
1. Faça um fork deste repositório.  
2. Crie sua branch: `git checkout -b minha-feature`.  
3. Adicione seu diagrama ou melhorias.  
4. Faça commit das alterações: `git commit -m "Adiciona diagrama atualizado"`.  
5. Envie para o GitHub: `git push origin minha-feature`.  
6. Abra um Pull Request.  

## 💡 Considerações Finais
Este projeto é uma excelente oportunidade para praticar **modelagem conceitual**, demonstrar conhecimento em **relacionamento entre entidades**, **integridade de dados** e boas práticas de documentação de projetos no GitHub.  

---
**Autor:** Breno Rodrigues





