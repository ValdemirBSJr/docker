# Bookworm tem compatibilidade melhor que o alpine (¬¬)
FROM node:22-bookworm

# Instala dependências básicas que o bot vai precisar (git, curl, utilitários de sistema)
RUN apt-get update && apt-get install -y \
    curl \
    git \
    iproute2 \
    && rm -rf /var/lib/apt/lists/*

# Instala o pacote globalmente. 
# O projeto levou uma piaba federal da Claude e já mudou o nome para 'moltbot', 
# mas o nome do pacote ainda é 'clawdbot' na maioria dos registros npm.
# Se falhar no futuro, é por que eles atualziaram tudo para 'moltbot'.
RUN npm install -g clawdbot@latest

# Define o diretório de trabalho
WORKDIR /root/clawd_workspace

# Define o comando padrão para iniciar o gateway (modo daemon)
CMD ["clawdbot", "gateway"]
