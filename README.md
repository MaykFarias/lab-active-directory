# 🖥️ Lab - Active Directory com Windows Server 2022

Laboratório prático de Active Directory montado em ambiente virtualizado com VirtualBox, simulando um ambiente corporativo real.

## 🛠️ Ambiente
- **Hypervisor:** Oracle VirtualBox
- **Servidor:** Windows Server 2022 Standard Evaluation
- **Cliente:** Windows 11 Pro
- **Domínio:** lab.local

## 🏗️ Estrutura do Domínio
- **OU Funcionarios** — usuários do setor de TI
- **OU Financeiro** — usuários do setor financeiro
- **Grupo TI** — agrupa os usuários joao.silva, maria.santos e carlos.oliveira

## 👥 Usuários criados
| Usuário | OU |
|---|---|
| joao.silva | Funcionarios |
| maria.santos | Funcionarios |
| carlos.oliveira | Funcionarios |
| ana.costa | Financeiro |

## 🔒 Políticas de Segurança via GPO
- **Bloquear Painel de Controle** — impede acesso ao Painel de Controle e Configurações do PC
- **Bloquear USB** — nega acesso a dispositivos de armazenamento removível
- **Bloquear Instalação de Programas** — restringe instalação de software pelos usuários
- **Senha Bloqueio de Tela** — bloqueia tela após 15 minutos e exige troca de senha a cada 30 dias

## ✅ Testes realizados
- Windows 11 Pro ingressado no domínio lab.local
- Login com usuário do domínio (lab\joao.silva) no PC cliente
- GPO de bloqueio do Painel de Controle validada e funcionando

## 📚 Referências
- [Microsoft Learn - Active Directory Domain Services](https://learn.microsoft.com/pt-br/training/paths/active-directory-domain-services/)

## 📸 Prints do Laboratório
![Active Directory](Active%20Directory%20Users%20and%20Computers.png)
![GPO](Group%20Policy%20Management.png)
![Bloqueio](Operacao%20Cancelada.png)
