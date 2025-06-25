# 🔧 Setup de Ambiente de Desenvolvimento e Segurança no Ubuntu

Este script automatiza a instalação e configuração de um ambiente completo de **desenvolvimento** e **segurança ofensiva/defensiva** em sistemas **Ubuntu-based**. Ele instala ferramentas essenciais como VSCode, Docker, pyenv, nvm, Wireshark, firewall UFW, rkhunter, auditd, e muito mais.

---

## 🚀 Funcionalidades

O script realiza as seguintes operações:

### ✅ Atualizações e Ferramentas Essenciais
- Atualiza o sistema (`apt update && upgrade`)
- Instala `curl`, `git`, `build-essential`

### 👨‍💻 Desenvolvimento
- **VSCode** (com repositório oficial)
- **pyenv** (gerenciador de versões do Python)
- **nvm** (gerenciador de versões do Node.js)
- **Docker** (com grupo de usuários e repositório oficial)
- **Zsh** com **Oh My Zsh**

### 🛡️ Segurança e Monitoramento
- **Wireshark** (analisador de pacotes)
- **Ferramentas de rede**: `net-tools`, `iproute2`, `iftop`, `nethogs`
- **rkhunter** (verificador de rootkits)
- **UFW** (firewall com regra SSH configurada)
- **Fail2Ban** (proteção contra brute force)
- **auditd** (auditoria de eventos de segurança)

---

## 🧾 Pré-requisitos

- Sistema baseado em **Ubuntu** (20.04 ou superior recomendado)
- Permissões de **sudo**
- Conexão com a internet

---

## 📦 Instalação

1. Clone o repositório:

```bash
git clone https://github.com/EuMaxsuelPiana/Desenvolvimento-e-Seguran-a-Ubuntu.git
cd Desenvolvimento-e-Seguran-a-Ubuntu
