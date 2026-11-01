# ☁️ Projeto — Servidor Web com Amazon EC2

**Serviços:** EC2 · Security Groups · EBS  
**Origem:** Escola da Nuvem  
**Status:** 🟢 Documentação inicial — revisar com evidências

---

## 🎯 Objetivo

Implantar um servidor web em uma instância EC2 e configurar regras de acesso.

## 🛠️ Serviços e tecnologias

| Tecnologia | Aplicação no projeto |
|---|---|
| EC2 | Componente do ambiente; conferir configuração específica nas evidências |
| Security Groups | Componente do ambiente; conferir configuração específica nas evidências |
| EBS | Componente do ambiente; conferir configuração específica nas evidências |

## 🏗️ Arquitetura da solução

> Diagrama conceitual para documentação. Confirme se corresponde ao ambiente realmente implementado.

```mermaid
flowchart TD
Internet --> SG[Security Group: HTTP/HTTPS] --> EC2[EC2: Linux + servidor web]
EC2 --> EBS[Volume EBS]
```

## 📋 Etapas de implementação

1. Criar instância EC2 e selecionar AMI
2. Configurar Security Group conforme portas realmente utilizadas
3. Instalar e iniciar servidor web
4. Testar acesso e registrar resultado

## 💻 Scripts e comandos

Adicione aqui **somente comandos realmente utilizados**, após remover senhas, chaves, IDs privados e outros dados sensíveis.

```bash
# Exemplo de espaço reservado — substitua pelos seus comandos reais
```

## 📸 Evidências

Envie imagens para a pasta [`evidencias/`](./evidencias/) e insira aqui as referências, por exemplo:

```markdown
![Instância EC2 configurada](./evidencias/instancia-ec2.png)
```

## ✅ Resultados e aprendizados

Descreva o resultado que você observou e os principais aprendizados, sem afirmar testes que não foram realizados.

## 🔐 Cuidados de segurança

Não publique chaves de acesso, credenciais, arquivos `.pem`, tokens, dados pessoais, identificadores sensíveis ou configurações internas de contas.
