# ☁️ Projeto — Gerenciamento de Acesso com IAM

**Serviços:** IAM · Users · Groups · Policies · MFA  
**Origem:** Escola da Nuvem  
**Status:** 🟢 Documentação inicial — revisar com evidências

---

## 🎯 Objetivo

Compreender o controle de acesso com identidades, grupos, permissões e autenticação.

## 🛠️ Serviços e tecnologias

| Tecnologia | Aplicação no projeto |
|---|---|
| IAM | Componente do ambiente; conferir configuração específica nas evidências |
| Users | Componente do ambiente; conferir configuração específica nas evidências |
| Groups | Componente do ambiente; conferir configuração específica nas evidências |
| Policies | Componente do ambiente; conferir configuração específica nas evidências |
| MFA | Componente do ambiente; conferir configuração específica nas evidências |

## 🏗️ Arquitetura da solução

> Diagrama conceitual para documentação. Confirme se corresponde ao ambiente realmente implementado.

```mermaid
flowchart TD
Admin[Administrador autorizado] --> IAM[IAM]
IAM --> USERS[Usuários e grupos]
IAM --> POL[Políticas de permissão]
USERS --> MFA[MFA]
```

## 📋 Etapas de implementação

1. Analisar usuários e grupos
2. Configurar ou revisar políticas conforme o exercício
3. Aplicar princípio do menor privilégio
4. Verificar boas práticas de MFA

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
