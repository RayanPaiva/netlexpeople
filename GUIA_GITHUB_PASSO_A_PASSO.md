# Guia Passo a Passo: Publicando no GitHub Pages 🐱🐙

Como é sua primeira vez, vamos fazer isso com calma em 3 etapas principais.

## ✅ Pré-requisitos
Antes de começar, certifique-se de que:
1. Você tem uma conta no [GitHub.com](https://github.com/).
2. Você tem o **Git** instalado no seu computador.
   - Para verificar, abra seu terminal e digite `git --version`. Se aparecer um número de versão, está tudo certo!

---

## Passo 1: Criar um Repositório no GitHub 🌐
1. Acesse sua conta no GitHub.
2. No canto superior direito, clique no ícone **+** e selecione **"New repository"**.
3. **Repository name**: Coloque um nome simples, ex: `netlex-landing-page`.
4. **Public/Private**: Escolha **Public** (necessário para o GitHub Pages gratuito).
5. **Não marque** nenhuma opção de "Initialize this repository with..." (sem README, sem .gitignore por enquanto).
6. Clique no botão verde **Create repository**.
7. **Importante:** Mantenha essa página aberta, vamos precisar do link que aparece nela (algo como `https://github.com/SEU_USUARIO/netlex-landing-page.git`).

---

## Passo 2: Configurar Seus Arquivos Localmente 💻
Vamos transformar sua pasta em um repositório Git.

1. Abra o Terminal (PowerShell ou CMD).
2. Navegue até a pasta do projeto (caso não esteja nela):
   ```powershell
   cd C:\Users\netlex\.gemini\antigravity\scratch\netlex-landing-page
   ```
3. Inicialize o Git:
   ```powershell
   git init
   ```
4. Adicione todos os arquivos:
   ```powershell
   git add .
   ```
5. Faça o primeiro "backup" (commit):
   ```powershell
   git commit -m "Primeira versao do site"
   ```
6. Renomeie a branch principal para 'main' (padrão moderno):
   ```powershell
   git branch -M main
   ```

---

## Passo 3: Conectar e Enviar para o GitHub 🚀
Agora vamos conectar seu computador ao GitHub.

1. Cole o comando abaixo no terminal (substitua pelo link que você copiou no Passo 1):
   ```powershell
   git remote add origin https://github.com/SEU_USUARIO_AQUI/netlex-landing-page.git
   ```
   *Se você não copiou o link antes, ele está na barra de endereço do navegador na página do repositório que você criou.*

2. Envie os arquivos:
   ```powershell
   git push -u origin main
   ```
   *Pode ser que o GitHub peça para você fazer login nessa etapa.*

---

## Passo 4: Ativar o Site (GitHub Pages) ✨
1. Volte para a página do seu repositório no GitHub.
2. No menu superior do repositório, clique em **Settings** (Configurações).
3. Na barra lateral esquerda, clique em **Pages**.
4. Em **Build and deployment** > **Branch**, clique no menu que diz "None" e selecione **main**.
5. Clique em **Save**.
6. Aguarde cerca de 1 a 2 minutos. Atualize a página e você verá uma barra no topo dizendo:
   "Your site is live at..." com o link do seu site!

🎉 **Parabéns! Seu site está online.**

## ?? Qual ser� o link do meu site?

Depois de configurar o GitHub Pages (nos passos acima), o link do seu site seguir� este padr�o:

https://SEU-NOMEDEUSUARIO.github.io/netlex-landing-page/

### Onde encontrar o link clic�vel:
1. No seu reposit�rio no GitHub, clique na aba **Settings** (Configura��es).
2. No menu lateral esquerdo, clique em **Pages**.
3. No topo dessa p�gina, voc� ver� uma caixa (geralmente verde) com a mensagem:
   **'Your site is live at...'** seguido do link.

Basta clicar nesse link para abrir sua landing page! ??
