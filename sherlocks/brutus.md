# 🪓 Brutus — Sherlock (Very Easy)

🔗 Prova de conclusão:  
https://labs.hackthebox.com/achievement/sherlock/2578759/631

## 📝 Descrição

Sherlock focado em **análise forense de logs**, **investigação de incidentes** e identificação de atividades suspeitas em um ambiente Linux.

O desafio simulou um cenário de comprometimento através de ataques de força bruta contra SSH, onde foi necessário analisar evidências deixadas nos registros do sistema para reconstruir a linha do tempo do ataque.

## ✔ O que foi praticado

- Análise de logs forenses Linux (`auth.log` e `wtmp`)
- Investigação de tentativas de autenticação SSH
- Identificação de padrões de ataque de brute force
- Análise de endereços IP suspeitos em registros de acesso
- Extração de informações de login e logout utilizando arquivos de auditoria
- Reconstrução da linha do tempo de um incidente
- Identificação de acesso autorizado após tentativas consecutivas de login
- Investigação de alterações realizadas após o comprometimento
- Análise de eventos relacionados a criação de usuários e persistência
- Uso de comandos Linux para filtragem e correlação de evidências

## 🛠 Ferramentas utilizadas

- Linux
- grep
- sort
- uniq
- last
- análise manual de logs
- arquivos de auditoria (`auth.log` e `wtmp`)

## 🔎 Principais descobertas

Durante a investigação foram analisados registros de autenticação para identificar:

- Tentativas repetidas de login SSH
- Origem das conexões suspeitas
- Momento em que ocorreu o acesso bem-sucedido
- Eventos posteriores ao comprometimento do sistema

A investigação foi conduzida através da correlação de diferentes fontes de evidência, permitindo reconstruir a sequência dos eventos do ataque.

## 📚 Conhecimentos adquiridos

- Fundamentos de Digital Forensics
- Análise de logs em ambientes Linux
- Investigação de incidentes de segurança
- Identificação de ataques de força bruta
- Técnicas básicas de Incident Response
- Correlação de eventos para reconstrução de ataques

---

# 🔍 HTB Sherlocks — Investigação Forense e Análise de Incidentes

Os **Sherlocks do Hack The Box** são desafios focados em **forense digital**, **análise de logs**, **detecção de ataques**, **malware analysis** e **investigação pós-incidente**.

Eles simulam cenários reais de segurança onde o analista precisa coletar evidências, entender a cadeia de ataque e responder perguntas utilizando técnicas de Blue Team, Threat Hunting e Incident Response.
