# ☁️ Projeto — Armazenamento com Amazon S3

**Serviços:** S3 · Buckets · Storage Classes  
**Origem:** Escola da Nuvem  
**Status:** 🟢 Documentação inicial — revisar com evidências

---

## 🎯 Objetivo

Explorar armazenamento de objetos, classes de armazenamento e controles de acesso no S3.

## 🛠️ Serviços e tecnologias

| Tecnologia | Aplicação no projeto |
|---|---|
| S3 | Componente do ambiente; conferir configuração específica nas evidências |
| Buckets | Componente do ambiente; conferir configuração específica nas evidências |
| Storage Classes | Componente do ambiente; conferir configuração específica nas evidências |

## 🏗️ Arquitetura da solução

> Diagrama conceitual para documentação. Confirme se corresponde ao ambiente realmente implementado.

```mermaid
flowchart TD
USER[Usuário autorizado] --> IAM[IAM] --> S3[Bucket S3]
S3 --> OBJ[Objetos]
S3 --> CLASSES[Classes de armazenamento]
```

## 📋 Etapas de implementação

1. Criar ou inspecionar bucket
2. Enviar e consultar objetos de teste
3. Comparar classes de armazenamento
4. Revisar permissões e bloqueio de acesso público

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
