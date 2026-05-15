# 🖥️ Lab - Active Directory com Windows Server 2022

Laboratório prático de Active Directory montado em ambiente virtualizado com VirtualBox.

## 🛠️ Ambiente
- **Hypervisor:** Oracle VirtualBox
- **Sistema Operacional:** Windows Server 2022 Standard Evaluation
- **Domínio:** lab.local

## ✅ O que foi praticado

### Unidades Organizacionais (OU)
- Criação das OUs `Funcionarios` e `Financeiro` para organizar usuários por setor

### Usuários
- Criação de usuários (joao.silva, maria.santos, carlos.oliveira, ana.costa)
- Reset de senha de usuário
- Configuração de políticas de senha

### Grupos
- Criação do grupo `TI`
- Adição de membros ao grupo

### GPO (Group Policy Object)
- Criação de GPO `Bloquear Painel de Controle`
- Aplicação de política para bloquear acesso ao Painel de Controle e Configurações do PC para usuários da OU Funcionarios

## 📚 Referências
- [Microsoft Learn - Active Directory Domain Services](https://learn.microsoft.com/pt-br/training/paths/active-directory-domain-services/)
