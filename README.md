# 🚀 Minecraft Server - GitHub Codespaces

Este repositório contém a infraestrutura para um servidor de Minecraft rodando via **Crafty Controller** dentro do GitHub Codespaces. 

---

## 🛠️ Como Iniciar o Servidor

Sempre que o Codespace for reiniciado, siga estes passos na ordem:

### 1. Iniciar o Painel de Controle (Crafty)
No terminal do VS Code, execute:
```bash
cd crafty-4
python3 main.py
```
Mantenha esta aba do terminal aberta para que o painel continue funcionando.

2. Acessar o Painel Web
Vá na aba PORTAS (ao lado do Terminal).

Procure a porta 8443.

Clique no ícone do Globo ("Abrir no Navegador").

Faça login com suas credenciais de administrador.

3. Iniciar o Túnel Público (Playit.gg)
Para que os jogadores consigam se conectar, abra uma nova aba de terminal e digite:

Bash
./playit
O IP e a porta de conexão serão exibidos no terminal ou no site do playit.gg.

🎮 Informações do Servidor
Tipo: Minecraft Bedrock

Versão: 1.21.132

Gerenciador: Crafty Controller 4.0

⚠️ Observações Importantes
Manutenção Online: O Codespaces entra em hibernação após 30-60 minutos de inatividade. Para manter o servidor online, mantenha a aba do navegador aberta.

Segurança: Nunca compartilhe sua senha de admin ou o arquivo default-creds.txt publicamente.

Limite de Horas: O uso consome o seu saldo de horas gratuitas do GitHub Codespaces. Verifique seu consumo regularmente no painel do GitHub.

📂 Estrutura de Pastas
/crafty-4: Pasta principal do painel de controle.

/crafty-4/app/servers: Local onde ficam os arquivos do mundo, plugins e configurações do Minecraft.
