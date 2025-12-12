# 🐀 Nibbles — Starting Point (Easy)

🔗 Prova de conclusão:  
https://labs.hackthebox.com/achievement/machine/2578759/121

## ✔ O que foi praticado
- Enumeração inicial com Nmap, identificando portas 22 (SSH) e 80 (HTTP) abertas :contentReference[oaicite:0]{index=0}
- Enumeração web identificando aplicação *NibbleBlog* rodando na porta 80 :contentReference[oaicite:1]{index=1}
- Enumeração de diretórios e arquivos escondidos usando *gobuster/dirb* :contentReference[oaicite:2]{index=2}
- Descoberta do diretório admin e enumeração do login :contentReference[oaicite:3]{index=3}
- Obtenção de credenciais válidas (ex: admin / nibbles) para acessar painel administrativo :contentReference[oaicite:4]{index=4}
- Upload de **PHP reverse shell** através de vulnerabilidade no *NibbleBlog* :contentReference[oaicite:5]{index=5}
- Estabelecimento de **shell interativo no sistema da máquina** :contentReference[oaicite:6]{index=6}
- Transferência de **linEnum** para a máquina alvo para auxiliar em privesc :contentReference[oaicite:7]{index=7}
- Enumeração interna do sistema com linEnum para encontrar vetor de escalada :contentReference[oaicite:8]{index=8}
- Identificação de **falha de configuração sudo** permitindo execução de script com permissão root :contentReference[oaicite:9]{index=9}
- Exploração da configuração sudo para ganhar **acesso root** :contentReference[oaicite:10]{index=10}
- Captura da flag do sistema e conclusão da caixa
