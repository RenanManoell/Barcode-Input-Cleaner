# 🚀 Barcode Input Cleaner

Um script JavaScript (UserScript) para limpar automaticamente o valor de um input de código de barras, removendo tudo após o primeiro espaço ao pressionar **Enter**. Ideal para sistemas WMS (Warehouse Management Systems) que exigem leituras precisas de códigos de barras.

---

## 🛠️ Funcionalidades

- **Limpeza automática:** Remove tudo após o primeiro espaço no input de código de barras.
- **Integração contínua:** Funciona mesmo após múltiplas leituras ou recarregamentos do input.
- **Destaque visual:** O campo de input é destacado em verde para fácil identificação.
- **Compatibilidade:** Desenvolvido para funcionar em sistemas WMS específicos.

---

## ⚙️ Como Usar

1. **Instale uma extensão de UserScript:**  
   - Recomendamos o [Tampermonkey](https://www.tampermonkey.net/) (disponível para Chrome, Firefox, Edge e outros navegadores).

2. **Adicione o script:**  
   - Copie o código do arquivo `barcode-input-cleaner.js` e cole-o no painel do Tampermonkey.

3. **Acesse o sistema WMS:**  
   - Navegue até o sistema onde o script deve ser executado (URL configurada no script).

4. **Use o input de código de barras:**  
   - Ao digitar ou escanear um código de barras e pressionar **Enter**, o script limpará automaticamente o valor, removendo tudo após o primeiro espaço.

---

## 🖥️ Tecnologias Utilizadas

- **JavaScript:** Linguagem principal do script.
- **UserScript:** Compatível com extensões como Tampermonkey ou Greasemonkey.
- **MutationObserver:** Para monitorar alterações no DOM e garantir que o script funcione mesmo após recarregamentos do input.

---

## 📂 Estrutura do Código

O script é composto por três funções principais:

1. **`cleanBarcodeInput(input)`:**  
   Remove tudo após o primeiro espaço no valor do input.

2. **`setupInputListener(input)`:**  
   Configura o listener para o evento `onkeydown` e destaca o input em verde.

3. **`observeInput()`:**  
   Observa alterações no DOM para garantir que o script funcione mesmo que o input seja recriado.

---

## 🚨 Requisitos

- Navegador com suporte a UserScripts (Chrome, Firefox, Edge, etc.).
- Extensão Tampermonkey ou Greasemonkey instalada.
- Acesso ao sistema WMS configurado no script.

---

## 📝 Licença

Este projeto está licenciado sob a **MIT License**. Sinta-se à vontade para usar, modificar e distribuir conforme necessário.

---

## 👤 Autor

**Renan Manoel**  
Desenvolvedor e entusiasta de automação.  
[🔗 LinkedIn](#) | [🐙 GitHub](#)

---

## 💡 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir **issues** ou **pull requests** para melhorar o projeto.

---

✨ **Dúvidas ou sugestões?** Entre em contato ou abra uma issue no repositório!
