# 👻 PhantomRing — Sherlock (Very Easy)

🔗 Prova de conclusão:  
https://labs.hackthebox.com/achievement/sherlock/2578759/1296

## 📝 Descrição

Sherlock focado em **análise de malware**, **engenharia reversa** e investigação do comportamento de um agente Linux suspeito.

O desafio envolveu a análise estática de um binário ELF para identificar funcionalidades implementadas pelo malware, incluindo enumeração de usuários, mecanismos de evasão e ações de persistência/destruição.

## ✔ O que foi praticado

- Análise estática de binários ELF Linux
- Engenharia reversa utilizando Radare2 e Ghidra
- Identificação de funções e handlers de comandos dentro do binário
- Análise de strings e referências cruzadas (`XREFs`)
- Investigação de chamadas relacionadas ao sistema operacional Linux
- Análise de mecanismos de enumeração de usuários ativos
- Identificação de técnicas de descoberta de ambiente
- Análise de mecanismos de evasão envolvendo ferramentas de segurança
- Investigação de funcionalidades de privilégio e persistência
- Compreensão de comunicação baseada em comandos entre agente e servidor

## 🛠 Ferramentas utilizadas

- Radare2
- Ghidra
- Linux ELF Analysis
- Strings
- Procfs (`/proc`)

## 🔎 Principais descobertas

Durante a análise foram identificadas funcionalidades relacionadas a:

- Enumeração de usuários conectados no sistema
- Consulta de informações do processo em execução
- Busca por possíveis mecanismos de monitoramento
- Rotinas de privilégio e destruição do próprio agente

A investigação foi realizada através da análise de:

- Funções internas do binário
- Strings presentes no executável
- Fluxo de execução dos comandos
- Referências cruzadas no código desassemblado

## 📚 Conhecimentos adquiridos

- Fluxo de análise de malware Linux
- Interpretação de assembly x86-64
- Uso de ferramentas de reverse engineering
- Identificação de comportamento malicioso sem execução do malware
- Técnicas utilizadas em análise de ameaças e threat hunting

---

# 🔍 HTB Sherlocks — Investigação Forense e Análise de Incidentes

Os **Sherlocks do Hack The Box** são desafios focados em **forense digital**, **análise de logs**, **malware analysis**, **detecção de ataques** e **investigação pós-incidente**.

Eles simulam cenários reais onde o analista precisa coletar evidências, entender o comportamento de ameaças e reconstruir eventos utilizando técnicas de Blue Team, Threat Hunting e Incident Response.
