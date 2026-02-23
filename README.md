# ÁlcoolCalc — PWA

Estimativa técnica de metabolização do álcool baseada no modelo matemático de Widmark.

## 🚀 Deploy no GitHub Pages

1. Crie um repositório público no GitHub
2. Faça upload de todos os arquivos deste projeto
3. Acesse **Settings → Pages → Source: main / root**
4. O app ficará disponível em `https://SEU_USUARIO.github.io/NOME_DO_REPO`

## 📲 Instalar como App (PWA)

### Android (Chrome)
- Abra o app no Chrome
- Toque no menu (⋮) → **"Adicionar à tela inicial"**
- O app será instalado como APK-like, funciona **offline**

### iOS (Safari)
- Abra no Safari
- Toque em **Compartilhar (□↑)** → **"Adicionar à Tela de Início"**

### Desktop
- O banner de instalação aparece automaticamente no Chrome/Edge

## 📁 Estrutura

```
├── index.html      # App principal (todo o código)
├── manifest.json   # Configuração PWA
├── sw.js           # Service Worker (cache offline)
├── icon-192.png    # Ícone PWA
└── icon-512.png    # Ícone PWA
```

## ⚙️ Funcionalidades

- ✅ Cálculo BAC pelo modelo de Widmark
- ✅ Perfil pessoal com localStorage
- ✅ Histórico de cálculos (50 entradas)
- ✅ Gráfico de curva de metabolização
- ✅ Funciona 100% offline (Service Worker)
- ✅ Instalável como app (PWA)
- ✅ Design mobile-first responsivo

## ⚠️ Aviso Legal

Estimativa matemática. Não use para decidir dirigir ou realizar atividades de risco. O metabolismo varia entre indivíduos.
