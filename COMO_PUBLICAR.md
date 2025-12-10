# Como colocar sua Landing Page no ar 🚀

Existem várias formas gratuitas e rápidas de publicar seu site. Aqui estão as 3 opções mais recomendadas:

## Opção 1: Netlify Drop (Mais Fácil e Rápido) 🏆
Ideal se você não quer usar comandos e quer o site no ar em segundos.

1. Acesse [app.netlify.com/drop](https://app.netlify.com/drop).
2. Abra a pasta onde seus arquivos estão salvos no seu computador:
   `C:\Users\netlex\.gemini\antigravity\scratch\netlex-landing-page`
3. Arraste a pasta inteira **netlex-landing-page** para a área indicada na página do Netlify.
4. Aguarde alguns segundos e seu site estará online! O Netlify gerará um link automático para você.

## Opção 2: Vercel (Profissional)
A Vercel é excelente para performance.

1. Crie uma conta em [vercel.com](https://vercel.com).
2. Instale o Vercel CLI no seu terminal (se tiver Node.js):
   ```bash
   npm i -g vercel
   ```
3. No terminal, dentro da pasta do projeto, digite:
   ```bash
   vercel
   ```
4. Siga as instruções na tela (geralmente é só dar Enter em tudo).

## Opção 3: GitHub Pages (Para Desenvolvedores)
Se você usa Git, essa é a forma clássica.

1. Crie um repositório no GitHub.
2. No terminal, dentro da pasta do projeto:
   ```bash
   git init
   git add .
   git commit -m "Primeiro commit"
   git branch -M main
   git remote add origin SEU_LINK_DO_GITHUB
   git push -u origin main
   ```
3. No repositório do GitHub, vá em **Settings > Pages** e selecione a branch `main` para publicar.

---

**Dica:** Antes de publicar, verifique se todas as imagens na pasta `assets` estão carregando corretamente abrindo o `index.html` no seu navegador localmente.
