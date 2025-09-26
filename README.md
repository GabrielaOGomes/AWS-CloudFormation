# AWS CloudFormation
Esse projeto tem a finalidade de aplicar os conhecimentos adquirido através do Bootcamp Santander Code Girls 2025 - AWS cloud foundation - com a criação de recursos como pilha (staks) gerando instancias EC2 através de um template YAML.

## Evidências

### Criação das Pilhas  
As pilhas (stacks) são conjuntos de recursos que podem ser gerenciados como uma unidade (ex.: criar uma VPC, uma instância EC2 e um Security Group ao mesmo tempo). Os modelos de pilhas (templates) são arquivos YAML ou JSON que descrevem as configurações necessárias para criar esses recursos.  

🛠️ Como funciona  
Cria o template (YAML/JSON).  
Faz o deploy no CloudFormation.  
O CloudFormation cria uma stack, que nesse caso conterá apenas um recurso: o bucket S3.  
Se você excluir a stack, o bucket também é excluído (a menos que tenha sido configurado como Retain).  

<img width="1919" height="1079" alt="Captura de tela 2025-09-26 194319" src="https://github.com/user-attachments/assets/ad704ff6-8ca0-49c3-95a4-a0fb362c001c" />  

### Criação das instâncias EC2  
Instâncias criadas a partir das pilhas (stacks).
<img width="1919" height="1077" alt="Captura de tela 2025-09-26 193058" src="https://github.com/user-attachments/assets/6e7d2f9f-556e-4408-8c90-72534014cdf3" />
