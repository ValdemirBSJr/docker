![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

# Moltbot como Agente Pessoal de IA
==========================

## Descrição
O Moltbot é uma ferramenta de IA que visa ser um agente pessoal de última geração, capaz de gerenciar vários serviços ao mesmo tempo. Este projeto visa subir o Moltbot como um container no WSL para explorar suas funcionalidades.

## Principais Conceitos
* O Moltbot pode integrar com mais de 50 serviços, incluindo e-mails, Spotify, Slack, Obsidian e muito mais.
* A ferramenta pode ser configurada para usar diferentes provedores de IA, como o OpenRouter.
* O Moltbot pode ser acessado via interface web ou linha de comando.

## Como usar
1. Clone o repositório e navegue até a pasta do projeto.
2. Construa a imagem do Docker com o comando `docker compose build`.
3. Execute o assistente em modo de configuração com o comando `docker compose run --rm moltbot clawdbot onboard`.
4. Configure o Moltbot de acordo com as instruções na interface web ou linha de comando.
5. Acesse o Moltbot via interface web ou linha de comando para usar suas funcionalidades.

## Configuração
* Certifique-se de ter o Docker e o WSL instalados em sua máquina.
* Edite o arquivo `docker-compose.yml` para configurar as variáveis de ambiente, como a chave de API do OpenRouter.
* Edite o arquivo `clawdbot.json` para configurar o roteamento e outras opções do Moltbot.

## Contato
Se você tiver alguma dúvida ou precisar de ajuda, por favor, não hesite em entrar em contato comigo. Você pode abrir uma issue neste repositório ou me contatar diretamente.

* **Valdemir Bezerra de Souza Júnior**
* Analista Infraestrutura | Devops | SRE | Cloud | Oracle Cloud | Linux | Docker | Kubernets | Python | Go | Rust | Lua | N8N | No Code
* [Linkedin](https://www.linkedin.com/in/valdemirbezerra/)

## Observações
* O Moltbot é uma ferramenta ainda em desenvolvimento, portanto, é recomendável usar com cautela.
* Certifique-se de ler as instruções cuidadosamente antes de usar o Moltbot.
* O uso do Moltbot é por sua conta e risco.

## Artigo original demonstrando o uso:
[https://www.linkedin.com/pulse/como-parei-de-criar-readmes-manualmente-usando-python-valdemir-rdycc](https://www.linkedin.com/pulse/moltbot-clawdbot-docker-wsl-como-criei-um-agente-de-valdemir-fktqf)
