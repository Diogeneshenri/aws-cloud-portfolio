# ☁️ Projeto — Investigação de Segurança com CloudTrail

**Serviços:** CloudTrail · EC2 · AWS CLI · Athena  
**Origem:** Escola da Nuvem  
**Status:** 🟢 Documentação inicial — revisar com evidências

---

## 🎯 Objetivo

Investigar eventos de auditoria e alterações suspeitas em um ambiente web de laboratório.

## 🛠️ Serviços e tecnologias

| Tecnologia | Aplicação no projeto |
|---|---|
| CloudTrail | Componente do ambiente; conferir configuração específica nas evidências |
| EC2 | Componente do ambiente; conferir configuração específica nas evidências |
| AWS CLI | Componente do ambiente; conferir configuração específica nas evidências |
| Athena | Componente do ambiente; conferir configuração específica nas evidências |

## 🏗️ Arquitetura da solução

> Diagrama conceitual para documentação. Confirme se corresponde ao ambiente realmente implementado.

```mermaid
flowchart TD
EVENT[Alteração em recurso AWS] --> TRAIL[CloudTrail]
TRAIL --> LOG[Registros de auditoria]
LOG --> ANALYSIS[Análise: CLI / Athena]
ANALYSIS --> FIND[Identificação do evento]
```

## 📋 Etapas de implementação

1. Criar/configurar trilha CloudTrail
2. Inspecionar eventos de alterações em Security Groups
3. Consultar logs e correlacionar ações
4. Documentar achados da simulação de incidente

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
