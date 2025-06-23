📲 Projeto: WhatsApp Chatbot Automatizado (Prototipagem / Estudo)
🏛️ Descrição
Este projeto é um Chatbot para WhatsApp, desenvolvido em Node.js utilizando a biblioteca whatsapp-web.js.

O bot responde automaticamente a mensagens recebidas, simulando um funil de atendimento com envio de mensagens de texto, delays e simulação de digitação.

⚠️ Importante:
Este projeto utiliza uma API não oficial do WhatsApp. Não é recomendado para uso em produção. O uso indevido pode violar os termos de serviço da Meta, podendo resultar em bloqueio ou banimento do número.

🎯 Funcionalidades
Leitura de QR Code para autenticação no WhatsApp Web.

Simulação de digitação antes de cada mensagem (via chat.sendStateTyping()).

Delay programado entre as mensagens para humanizar a interação.

Menu de opções com respostas automáticas para os seguintes comandos numéricos:

Opção	Resposta
1	Como funciona o serviço
2	Valores dos planos
3	Benefícios
4	Como aderir
5	Outras perguntas / Contato

Reconhecimento de palavras-chave como: "menu", "oi", "olá", "bom dia", "boa tarde", etc.

🛠️ Tecnologias Utilizadas
Node.js

whatsapp-web.js

qrcode-terminal

📋 Pré-requisitos
Node.js instalado (versão recomendada: LTS)

Uma conta ativa do WhatsApp (⚠️ Preferencialmente um número secundário)

Terminal com suporte a leitura de QR Code (ex: CMD, PowerShell, Terminal Linux)

🚀 Instalação e Execução
Clone o repositório:

bash
Copiar
Editar
git clone (https://github.com/Romulomrs/wppbot.git)
cd seu-repo
Instale as dependências:

bash
Copiar
Editar
npm install whatsapp-web.js qrcode-terminal
Execute o bot:

bash
Copiar
Editar
node index.js
Escaneie o QR Code com o WhatsApp.

🚧 Estrutura Atual do Projeto
bash
Copiar
Editar
├── CHATBOT.js          # Arquivo principal com o código do bot
├── package.json             # Gerenciador de dependências
├── node_modules

⚠️ Aviso Ético e Técnico
Uso experimental apenas!
Este projeto não deve ser usado em ambientes comerciais ou de produção.

Se quiser uma solução robusta, segura e dentro das boas práticas de mercado, considere migrar para a API Oficial do WhatsApp Business (Meta).

📌 Melhorias Futuras (recomendadas)
✔️ Separar lógica de negócios em módulos (ex: utils.js, respostas.js)
✔️ Usar arquivos de configuração externa para os textos de respostas
✔️ Implementar logs de erro e reconexão automática
✔️ Migrar para API oficial se for para produção

📖 Licença
Este projeto é de uso educacional. Sem garantias de funcionamento ou suporte.
