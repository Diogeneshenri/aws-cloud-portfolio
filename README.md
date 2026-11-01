# ☁️ Portfólio de Laboratórios AWS

Projetos de estudo em **Cloud Computing, Infraestrutura e Segurança na AWS**, com documentação, arquiteturas conceituais e espaço para evidências.

> **Transparência:** os projetos abaixo são documentação inicial baseada nos estudos relatados. Revise os detalhes e inclua prints antes de afirmar que cada implementação foi concluída.

## 📁 Projetos

| # | Projeto | Serviços | Status | Origem |
|---|---|---|---|---|
| 01 | [Servidor Web com Amazon EC2](./projetos/01-servidor-web-ec2/) | EC2 · Security Groups · EBS | 📝 Revisar evidências | Escola da Nuvem |
| 02 | [VPC, Servidor Web e Acesso SSH](./projetos/02-vpc-redes/) | VPC · Subnets · IGW · Route Tables · SSH | 📝 Revisar evidências | Escola da Nuvem |
| 03 | [AWS CLI e Linux em EC2 Red Hat](./projetos/03-aws-cli-red-hat/) | EC2 · AWS CLI · SSH · Linux | 📝 Revisar evidências | Prática AWS |
| 04 | [Gerenciamento de Acesso com IAM](./projetos/04-iam/) | IAM · Users · Groups · Policies · MFA | 📝 Revisar evidências | Escola da Nuvem |
| 05 | [Armazenamento com Amazon S3](./projetos/05-s3/) | S3 · Buckets · Storage Classes | 📝 Revisar evidências | Escola da Nuvem |
| 06 | [Gerenciamento de Instâncias com Systems Manager](./projetos/06-systems-manager/) | SSM · Session Manager · Run Command · Parameter Store | 📝 Revisar evidências | Escola da Nuvem |
| 07 | [Investigação de Segurança com CloudTrail](./projetos/07-cloudtrail-seguranca/) | CloudTrail · EC2 · AWS CLI · Athena | 📝 Revisar evidências | Escola da Nuvem |
| 08 | [Administração Linux em Amazon EC2](./projetos/08-linux-ec2/) | EC2 · Linux · SSH · EBS | 📝 Revisar evidências | Prática AWS |

## 🧩 Projetos adicionais — confirmar execução

Os modelos abaixo são **rascunhos**, não comprovam que o laboratório foi realizado.

| # | Projeto | Serviços | Status |
|---|---|---|---|
| 09 | [Infraestrutura como Código com CloudFormation](./projetos/09-cloudformation/) | CloudFormation · AWS | 🟡 A confirmar |
| 10 | [Monitoramento e Alertas com CloudWatch](./projetos/10-cloudwatch-sns/) | CloudWatch · SNS · EC2 | 🟡 A confirmar |
| 11 | [Implantação com Elastic Beanstalk](./projetos/11-elastic-beanstalk/) | Elastic Beanstalk · EC2 | 🟡 A confirmar |
| 12 | [Banco de Dados com Amazon RDS](./projetos/12-rds/) | RDS · VPC · Security Groups | 🟡 A confirmar |
| 13 | [Alta Disponibilidade com Auto Scaling](./projetos/13-auto-scaling/) | EC2 · Auto Scaling · Load Balancer | 🟡 A confirmar |
| 14 | [Roteamento e Disponibilidade com Route 53](./projetos/14-route53/) | Route 53 · Health Checks | 🟡 A confirmar |

## 📌 Como usar

1. Abra cada pasta em `projetos/` e revise o README.
2. Confirme o que foi realmente executado e substitua os textos genéricos por seus resultados.
3. Envie prints reais para `evidencias/`, ocultando dados sensíveis.
4. O GitHub renderiza automaticamente os diagramas Mermaid no README.
5. Depois de verificar cada projeto, altere o status para `✅ Concluído`.

## 🔐 Segurança

Nunca envie credenciais, chaves AWS, tokens, arquivos `.pem`, segredos ou dados pessoais para repositórios públicos.
