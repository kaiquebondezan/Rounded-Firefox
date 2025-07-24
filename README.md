# 🧩 Firefox Rounded + Custom Font Theme

A simple theme inspired by [Firefox-Rounded-Theme](https://github.com/imshinyu/Firefox-Rounded-Theme), which applies rounded corners to the Firefox UI and allows you to customize the default interface font via `userChrome.css`.

<img width="226" height="92" alt="image" src="https://github.com/user-attachments/assets/681cce61-cc41-4caf-87b7-42ef9aaab54f" />

[PT 🇧🇷](https://github.com/kaiquebondezan/Rounded-Firefox/edit/main/README.md#-em-portugu%C3%AAs) / [EN 🇺🇸](https://github.com/kaiquebondezan/Rounded-Firefox/edit/main/README.md#-in-english)

---

## 🇧🇷 Em português

### Como instalar

1. Acesse `about:config` na barra de endereços do Firefox.  
   Procure por `toolkit.legacyUserProfileCustomizations.stylesheets` e defina o valor como **true**.

2. Baixe o arquivo `.zip` com o código-fonte na seção de **Releases**.

3. Extraia o conteúdo do `.zip` e copie a **pasta `chrome`** para dentro da pasta do seu perfil do Firefox.

   Para encontrar a pasta do perfil:
   - Vá para `about:support` ou `about:profiles` no Firefox.
   - Localize o campo **Caminho da pasta do perfil** e clique em **Abrir pasta**.

4. Reinicie o navegador para aplicar as alterações.

### 💡 Como alterar a fonte da interface do navegador

Se desejar mudar a fonte da interface do Firefox, edite o arquivo `userChrome.css` localizado dentro da pasta `chrome` e edite o seguinte trecho com as propriedades da fonte desejada:

```css
* {
  font-family: "SF Pro Text", "San Francisco", system-ui, sans-serif !important;
}
```

Você pode substituir os nomes das fontes por qualquer fonte instalada no seu sistema.

---

## 🇺🇸 In English

### How to install

1. Go to `about:config` in the Firefox address bar.  
   Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and set it to **true**.

2. Download the `.zip` file from the **Releases** section.

3. Extract the contents of the `.zip` and copy the **`chrome` folder** into your Firefox profile folder.

   To find your profile folder:
   - Visit `about:support` or `about:profiles` in Firefox.
   - Locate the **Profile Folder Path** field and click **Open Folder**.

4. Restart Firefox to apply the changes.

### 💡 How to change the interface font

If you want to change Firefox's interface font, edit the `userChrome.css` file located inside the `chrome` folder and modify the following block with the desired font properties:

```css
* {
  font-family: "SF Pro Text", "San Francisco", system-ui, sans-serif !important;
}
```

You can replace the font names with any fonts installed on your system.
