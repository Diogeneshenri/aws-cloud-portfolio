☁️ Projeto — Servidor Web com Amazon EC2

![AWS](https://img.shields.io/badge/AWS-EC2-orange?style=for-the-badge)
![Apache](https://img.shields.io/badge/APACHE-HTTP_SERVER-red?style=for-the-badge)
![Linux](https://img.shields.io/badge/LINUX-AMAZON_LINUX-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/STATUS-CONCLU%C3%8DDO-brightgreen?style=for-the-badge)

---

 🎯 Objetivo

Implantar um servidor web em uma instância EC2 e configurar regras de acesso.

 🛠️ Serviços e tecnologias

| Tecnologia | Aplicação no projeto |
|---|---|
| EC2 | Componente do ambiente; conferir configuração específica nas evidências |
| Security Groups | Componente do ambiente; conferir configuração específica nas evidências |
| EBS | Componente do ambiente; conferir configuração específica nas evidências |

🏗️ Arquitetura da solução

> Diagrama conceitual para documentação. Confirme se corresponde ao ambiente realmente implementado.

```mermaid
flowchart TD
Internet --> SG[Security Group: HTTP/HTTPS] --> EC2[EC2: Linux + servidor web]
EC2 --> EBS[Volume EBS]
```

 📋 Etapas de implementação

1. Criar instância EC2 e selecionar AMI
2. Configurar Security Group conforme portas realmente utilizadas
3. Instalar e iniciar servidor web
4. Testar acesso e registrar resultado


💻 Script User Data

```bash
#!/bin/bash
yum install -y httpd
systemctl enable httpd
systemctl start httpd
echo '<html><h1>Meu primeiro servidor web AWS!</h1></html>' > /var/www/html/index.html
```

 📸 Evidências
🖥️ Servidor Web EC2 em funcionamento

<p align="center">
  <img src="./evidencias/ec2-servidor.jfif" alt="Evidência do servidor web AWS EC2" width="100%">
</p>
✅ Resultados e aprendizados

💡 Aprendizados
✅ Processo de criação e configuração de uma instância EC2
✅ Uso do User Data para automatizar a instalação de serviços no boot
✅ Papel dos Security Groups no controle de acesso à instância
✅ Importância do Amazon EBS como armazenamento persistente
✅ Como redimensionar tipo de instância e volume de armazenamento
✅ Proteção contra término acidental de instâncias em produção

