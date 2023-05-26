# How_Edu-Desafio02
CDC com DMS-AWS
Desafio consiste em Caputrar as alterações do banco de dados RDS-AWS  através do DMS e popular o Bucket S3.
Criação dos Recursos:

 Bucket
![image](https://github.com/Rafaelcorreiasilva/How_Edu-Desafio02/assets/85971778/6e18350c-f840-4dad-9de3-13dbe210c743)

Bucket vazio
![image](https://github.com/Rafaelcorreiasilva/How_Edu-Desafio02/assets/85971778/6cdd4ed3-2ac3-450d-973b-d1238571b71e)

Criação Rds

![image](https://github.com/Rafaelcorreiasilva/How_Edu-Desafio02/assets/85971778/b26c19bb-7158-4b44-bd8c-378e48643573)

Mudando os parametros para ligar o CDC

![image](https://github.com/Rafaelcorreiasilva/How_Edu-Desafio02/assets/85971778/d4b55265-8e2e-45db-ad8a-e69367749987)


Instancia de Replicação

![image](https://github.com/Rafaelcorreiasilva/How_Edu-Desafio02/assets/85971778/3550cc8b-b7d3-4dd9-87e5-2c21edf23625)


Endpoints

![image](https://github.com/Rafaelcorreiasilva/How_Edu-Desafio02/assets/85971778/2c8ced57-da29-4464-a226-94074835e9d7)

teste de conexão do endpoint source

![image](https://github.com/Rafaelcorreiasilva/How_Edu-Desafio02/assets/85971778/f8aa0564-5c60-4e11-bf2f-9af844a0c25f)

teste de conexão do endpoint target

![image](https://github.com/Rafaelcorreiasilva/How_Edu-Desafio02/assets/85971778/651b42ee-d4d9-4174-8831-655ef8058e8a)

Database migration tasks pausado

![image](https://github.com/Rafaelcorreiasilva/How_Edu-Desafio02/assets/85971778/5e7a9273-9721-47c9-b125-8a8d7557ad79)

IAM para dar acesso aos serviços AWS

![image](https://github.com/Rafaelcorreiasilva/How_Edu-Desafio02/assets/85971778/83d29bab-c8fa-4711-9694-8e8d8431c9e1)

##Ligando o processo

Quantidade de linhas no banco de dados Postgree

![image](https://github.com/Rafaelcorreiasilva/How_Edu-Desafio02/assets/85971778/176d882e-4592-49e6-a0b3-945b31b22b5a)

DMS Reiniciando

![image](https://github.com/Rafaelcorreiasilva/How_Edu-Desafio02/assets/85971778/8d99cc9b-686d-4e16-ad76-cb741a77a699)

Task Dms replicando

![image](https://github.com/Rafaelcorreiasilva/How_Edu-Desafio02/assets/85971778/ea6ad91f-0a70-4802-9b30-ad06f4ce7405)

Linhas carregadas no DMS

![image](https://github.com/Rafaelcorreiasilva/How_Edu-Desafio02/assets/85971778/89099155-bb37-4d43-b716-c43ef1dd3e94)

Mostrando a data e hora que foi rodado o DMS

![image](https://github.com/Rafaelcorreiasilva/How_Edu-Desafio02/assets/85971778/140fa178-e1b1-49c7-a941-7f1cc0b8cba1)

Bucket populado

![image](https://github.com/Rafaelcorreiasilva/How_Edu-Desafio02/assets/85971778/1d38db42-5217-4c42-91ec-81390ab9e0cf)

![image](https://github.com/Rafaelcorreiasilva/How_Edu-Desafio02/assets/85971778/f8124bd9-12d9-4f54-8579-5e48c3a4a918)

![image](https://github.com/Rafaelcorreiasilva/How_Edu-Desafio02/assets/85971778/1ff43a3b-a5ff-4e8c-a6ce-466ac6344dd8)

Novos dados carregadas na tabela postgree

![image](https://github.com/Rafaelcorreiasilva/How_Edu-Desafio02/assets/85971778/bb16d56a-596b-4a0b-9497-0ac9ad3e7579)

DMS capturou as mudanças

![image](https://github.com/Rafaelcorreiasilva/How_Edu-Desafio02/assets/85971778/5d4467e5-99a3-4dab-9239-e46f2279d8f2)

![image](https://github.com/Rafaelcorreiasilva/How_Edu-Desafio02/assets/85971778/1fc45ed7-0268-47ac-8c70-2cc486bc2741)

Bucket recebeu as alterações e inserções capturadas pelo DMS

![image](https://github.com/Rafaelcorreiasilva/How_Edu-Desafio02/assets/85971778/b89daf79-5055-42a5-96d1-9a0d29c157a6)






