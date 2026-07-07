# 🐄 Rodeo Rodeio — Sistema de Gestão Ganadera

App web para controle de rebanho: inventário, parição, recria, sanidade e potreiros.

---

## 🚀 Como publicar no Vercel (passo a passo)

### Pré-requisitos (tudo gratuito)
- Conta no [GitHub](https://github.com) 
- Conta no [Vercel](https://vercel.com) (pode entrar com o GitHub)

---

### Passo 1 — Criar repositório no GitHub

1. Acesse [github.com](https://github.com) e faça login
2. Clique no **+** no canto superior direito → **New repository**
3. Nome: `rodeio-ganadero`
4. Deixe **Public** ou **Private** (tanto faz)
5. Clique **Create repository**

---

### Passo 2 — Subir os arquivos

#### Opção A — Pelo site do GitHub (mais fácil)
1. Na página do repositório recém criado, clique **uploading an existing file**
2. Arraste **todos os arquivos desta pasta** (incluindo a pasta `src/`)
3. Clique **Commit changes**

#### Opção B — Pelo terminal
```bash
cd rodeio-ganadero
git init
git add .
git commit -m "primeiro commit"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/rodeio-ganadero.git
git push -u origin main
```

---

### Passo 3 — Publicar no Vercel

1. Acesse [vercel.com](https://vercel.com) e faça login com o GitHub
2. Clique **Add New Project**
3. Selecione o repositório `rodeio-ganadero`
4. As configurações já estão corretas — clique **Deploy**
5. Em ~2 minutos o Vercel gera seu link, tipo:
   ```
   https://rodeio-ganadero.vercel.app
   ```

---

### ✅ Pronto!

O link funciona no **celular e computador**. Compartilhe com Jaciara e Claudio.

---

## 📱 Uso no celular

No iPhone/Android, abra o link no navegador e use **"Adicionar à tela de início"** para que funcione como um app nativo.

---

## 🔄 Como atualizar o app

Sempre que quiser adicionar funcionalidades, basta substituir o arquivo `src/App.jsx` no GitHub — o Vercel republica automaticamente em segundos.

---

## 📂 Estrutura do projeto

```
rodeio-ganadero/
├── index.html          ← página HTML base
├── package.json        ← dependências
├── vite.config.js      ← configuração do Vite
├── README.md           ← este arquivo
└── src/
    ├── main.jsx        ← entrada do React
    └── App.jsx         ← app completo (todos os módulos)
```
