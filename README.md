# 🚀 Servidor Linux na Prática

Este repositório acompanha o curso publicado no YouTube com foco em fundamentas os conhecimentos básicos em Linux simulando uma infraestrutura real, utilizando virtualbox como ambiente de virtualização. Aqui você encontrará materiais de apoio, comandos comentados, exercícios e documentação para cada etapa do projeto.

---

## 🎓 Proposta Pedagógica

**Objetivo Geral:**  
Capacitar alunos e entusiastas de tecnologia a instalar, configurar e administrar um servidor Linux completo, com aplicações reais como GLPI e sistemas de documentação técnica, seguindo boas práticas de segurança e gestão.

---

## 📚 Estrutura das Aulas

Cada módulo possui conteúdo explicativo e um exercício prático para reforçar o aprendizado.

---

### 1. 🧱 Preparação do Ambiente

- Introdução ao Proxmox e virtualização
- Verificação de recursos do host (CPU, RAM, disco)
- Download da ISO oficial do Ubuntu Server LTS
- Criação e configuração da VM com recursos mínimos
- Montagem da ISO e início da instalação

🎯 *Objetivo: preparar o terreno para a instalação do servidor.*

**🧪 Exercício 01:**
1. Instale o Proxmox em uma máquina ou VM.
2. Crie uma VM com 2 vCPU, 4GB RAM e 40GB de disco.
3. Monte a ISO do Ubuntu Server LTS e inicie a instalação.
4. Poste um print da tela de instalação no LinkedIn com a hashtag `#ServidorLinuxNaPrática`.

---

### 2. 🖥️ Instalação e Configuração do Ubuntu Server

- Instalação com SSH habilitado
- Atualização de pacotes e sistema
- Configuração de rede (IP fixo ou DHCP reservado)
- Instalação de ferramentas básicas para administração

🎯 *Objetivo: garantir um sistema operacional funcional e acessível remotamente.*

**🧪 Exercício 02:**
1. Instale o Ubuntu Server com SSH habilitado.
2. Configure IP fixo ou DHCP reservado.
3. Instale `curl`, `wget`, `net-tools`, `vim`.
4. Poste no LinkedIn o comando usado para configurar o IP e me marque!

---

### 3. 🌐 Configuração do Servidor Web

- Instalação do Apache, PHP e extensões
- Instalação do MariaDB/MySQL e phpMyAdmin
- Teste do ambiente com página PHP

🎯 *Objetivo: montar a base para aplicações web dinâmicas.*

**🧪 Exercício 03:**
1. Instale Apache, PHP e MariaDB.
2. Crie uma página PHP com `phpinfo()`.
3. Poste um print da página funcionando no LinkedIn com a hashtag `#ServidorLinuxNaPrática`.

---

### 4. 🧩 Instalação de Aplicações Reais

- Criação e configuração de banco de dados
- Instalação do GLPI (gestão de ativos e chamados)
- Instalação de sistema de documentação técnica (DokuWiki, BookStack ou outro)
- Configuração de backups automáticos

🎯 *Objetivo: aplicar o conhecimento em soluções reais de mercado.*

**🧪 Exercício 04:**
1. Instale o GLPI e configure o banco.
2. Escolha uma ferramenta de documentação e instale.
3. Configure um backup automático com `cron`.
4. Poste no LinkedIn qual ferramenta escolheu e por quê.

---

### 5. 🔐 Segurança e Acesso

- Configuração de firewall (ufw ou iptables)
- Criação de usuários com permissões específicas
- Acesso remoto seguro (SSH com chave, fail2ban)
- Criação de snapshot da VM

🎯 *Objetivo: proteger o servidor e garantir acesso seguro.*

**🧪 Exercício 05:**
1. Configure o `ufw` para permitir apenas portas essenciais.
2. Crie um usuário com acesso restrito.
3. Configure acesso SSH com chave pública.
4. Poste no LinkedIn um print do seu `ufw status`.

---

### 6. 📑 Documentação e Finalização

- Registro de configurações e credenciais
- Documentação de IP, hostname e serviços ativos
- Validação de acesso externo às aplicações
- Organização e controle de tarefas no Monday

🎯 *Objetivo: consolidar o projeto com documentação e controle.*

**🧪 Exercício 06:**
1. Crie um documento com IP, hostname e serviços ativos.
2. Teste o acesso externo às aplicações.
3. Poste no LinkedIn uma dica de documentação que você usou.

---

## 🎥 Metodologia no YouTube

- Aulas práticas e passo a passo
- Explicações acessíveis, mesmo para iniciantes
- Material complementar e comandos comentados
- Espaço para dúvidas e interação nos comentários

---

## 🏁 Resultado Esperado

Ao final do curso, o aluno terá um servidor Linux funcional, seguro e com aplicações reais instaladas, pronto para uso em ambientes corporativos, educacionais ou pessoais.

---

**Siga o projeto no LinkedIn e marque seus avanços com a hashtag `#ServidorLinuxNaPrática`!**
