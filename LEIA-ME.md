# Mobile Screen Test

Simulador de celular para o Chrome. Este repositório tem só a extensão pronta para carregar.

## Instalar (uma vez)

Precisa do [Git](https://git-scm.com/downloads) ou do [GitHub Desktop](https://desktop.github.com/).

**Pelo terminal:**

```bash
git clone --branch extensao --single-branch https://github.com/gabriieljoao/mobile-screen-test.git ~/extensoes/mobile-screen-test
```

**Pelo GitHub Desktop:** File → Clone repository → URL `https://github.com/gabriieljoao/mobile-screen-test`, escolha uma pasta fixa (por exemplo `Documentos/extensoes/mobile-screen-test`).

Em seguida, no Chrome:

1. Abra `chrome://extensions`.
2. Ligue **Modo do desenvolvedor** (canto superior direito).
3. Clique em **Carregar sem compactação** e escolha a pasta clonada (a que tem o `manifest.json`).
4. No ícone de quebra-cabeça da barra, **fixe** o Mobile Screen Test.

Não apague nem mova a pasta: o Chrome lê a extensão dela.

## Atualizar

1. Na pasta: `git pull` (ou **Fetch origin** → **Pull origin** no GitHub Desktop).
2. Em `chrome://extensions`, clique em **Recarregar** (seta circular) no cartão da extensão.
3. Recarregue as abas que estavam com o simulador ligado.

Favoritos e preferências continuam: ficam no Chrome, não na pasta.

## Uso

Abra um site `http://` ou `https://` e clique no ícone, ou use `Alt+Shift+M`. `Alt+Shift+R` gira o aparelho e `Alt+Shift+S` captura a tela. Para trocar os atalhos: `chrome://extensions/shortcuts`.

## Avisos

- O Chrome pode mostrar "extensões no modo do desenvolvedor" ao abrir. É esperado; feche o aviso.
- Não use o simulador em abas de banco, e-mail ou painéis sensíveis. Limites: botão **Ajuda e limites** nas Configurações do simulador.
- Janelas anônimas: em `chrome://extensions` → **Detalhes** → **Permitir no modo anônimo**.
