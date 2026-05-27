# 🚀 Como Publicar seu Projeto Gratuitamente na Vercel

Este guia prático ensina o passo a passo detalhado para colocar a sua jornada interativa do avião de origami no ar através da **Vercel**, permitindo que qualquer pessoa acesse o projeto através de um link público e gratuito!

Como o projeto é construído em um **arquivo único de tecnologia web pura (`index.html`)**, a Vercel identificará e hospedará tudo de forma instantânea e com **configuração zero**.

---

## 📋 Pré-requisitos
1. Ter o código enviado para o seu repositório no GitHub (já concluído com sucesso em [github.com/SaturnoAbreu/presente](https://github.com/SaturnoAbreu/presente)).
2. Ter uma conta criada na **[Vercel](https://vercel.com)** (você pode se cadastrar gratuitamente usando sua própria conta do GitHub).

---

## 🛠️ Passo a Passo para a Implantação

### Passo 1: Fazer login na Vercel com o GitHub
1. Acesse o site oficial da Vercel: **[vercel.com](https://vercel.com)**.
2. Clique em **"Sign Up"** (ou **"Log In"** se já tiver conta).
3. Selecione a opção **"Continue with GitHub"**.
4. Autorize a integração caso seja solicitado. Isso conectará a Vercel diretamente aos seus repositórios públicos e privados.

---

### Passo 2: Importar o Repositório do Projeto
1. Assim que entrar no painel de controle (Dashboard) da Vercel, clique no botão azul **"Add New..."** no canto superior direito e selecione **"Project"**.
2. Na seção **"Import Git Repository"**, você verá uma lista dos seus repositórios do GitHub.
3. Procure pelo repositório chamado **`presente`** (da conta `SaturnoAbreu`).
4. Clique no botão **"Import"** ao lado dele.

> ✨ *Dica: Se o repositório não aparecer na lista inicial, você pode pesquisar por "presente" na barra de buscas ou clicar em "Configure GitHub App" para dar permissão de leitura ao repositório específico.*

---

### Passo 3: Configurar e Colocar no Ar (Deployment)
Como o nosso projeto é composto por apenas um arquivo estático puro (`index.html`), **nenhuma configuração complexa é necessária**:

1. **Project Name**: Pode deixar como `presente` (ou escolher outro nome que fará parte do seu link final).
2. **Framework Preset**: Deixe como **"Other"** (a Vercel detectará automaticamente que é um site HTML estático).
3. **Root Directory**: Mantenha como `./` (diretório raiz).
4. **Build and Development Settings**: Não mexa em nada (deixe em branco/padrão).
5. **Environment Variables**: Não é necessário configurar nenhuma variável.
6. Clique no botão azul **"Deploy"** na parte inferior!

---

### Passo 4: Celebração! 🎉
1. Aguarde cerca de 10 a 20 segundos enquanto a Vercel lê o arquivo `index.html` e o propaga nos servidores mundiais.
2. Uma tela de confetes aparecerá com uma prévia visual do seu site!
3. Clique sobre a imagem de prévia ou no botão **"Visit"** para abrir o seu site publicado.
4. O link terá um formato profissional e limpo, como: `https://presente-xxx.vercel.app` (onde `xxx` é um sufixo gerado ou o nome personalizado do projeto).

---

## 🔄 Atualizações Automáticas (CI/CD)

Uma das maiores vantagens de usar a Vercel integrada ao GitHub é o deploy contínuo:
* Sempre que você ou eu fizermos qualquer alteração no código do arquivo `index.html` e dermos um `git push` para a branch `main`, **a Vercel identificará a alteração e atualizará o site automaticamente em menos de 10 segundos!**
* Você nunca precisará fazer o processo de deploy manualmente de novo.

---

## 📱 Dica de Ouro: QR Code para Acessar no Celular
Como o site é focado em uma experiência afetiva, ele fica incrivelmente fofo e interativo em dispositivos móveis (com os toques na tela e as nuvens passando). 
1. Pegue o link gerado pela Vercel (ex: `https://presente.vercel.app`).
2. Acesse um gerador de QR Code gratuito (como o *qrcode-generator.de*).
3. Gere o QR Code do link do site e imprima ou envie junto com uma cartinha física. 
4. Quando a pessoa escanear com a câmera do celular, ela abrirá a animação 3D diretamente na palma da mão! ❤️
