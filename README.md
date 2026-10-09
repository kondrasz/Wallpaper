# 🌐 AMACDOG_OS // Personal Desktop Environment

> *“Live keep forcing cruel choices.”* — P. Auguste Renoir

Bem-vindo ao repositório do meu ambiente de desktop pessoal customizado com temática Cyberpunk / Retro-Terminal. Este projeto utiliza HTML e CSS puro para simular uma interface de sistema operacional analógica/distópica.

---
## 🖼️ Como Alterar ou Substituir as Imagens

O processo para atualizar qualquer imagem exibida nas janelas do sistema é direto e envolve apenas dois passos: adicionar o novo arquivo na pasta raiz do projeto e atualizar a referência no código.

### Passo 1: Adicionar a nova imagem na pasta
1. Salve o seu novo arquivo de imagem (recomenda-se formatos como `.jpg`, `.png` ou `.webp`) dentro da pasta principal do repositório.
2. Certifique-se de dar um nome simples e sem espaços para o arquivo (ex: `nova-foto.jpg`).

### Passo 2: Atualizar a referência no arquivo `index.html`
Abra o arquivo `index.html` em qualquer editor de código (como o VS Code) e localize a tag `<img>` correspondente à imagem que você deseja substituir. 

Por exemplo, para trocar a foto de perfil do usuário (`me.png`), localize o trecho:

```html
<div class="user-auth-window">
    <div class="auth-title">USER_ID</div>
    <div class="auth-content">
        <div class="avatar-border">
            <!-- Altere o valor de 'src' para o nome da sua nova imagem -->
            <img src="me.png" alt="Cass">
        </div>
        <div class="auth-status">
            [[ <span style="color: #fff;">CASS</span> ]]
            <br>
            <span style="font-size: 10px; color: #00ff00;">AUTHORIZED</span>
        </div>
    </div>
</div>
```
Basta alterar o atributo src="me.png" para o nome do seu novo arquivo (ex: src="nova-foto.jpg").

---

### 📂 Mapeamento dos Blocos de Imagem no Código

Para facilitar a localização de cada elemento visual no `index.html`, utilize o guia abaixo:

| Janela / Elemento | Nome do Arquivo Atual | Onde encontrar no `index.html` |
| :--- | :--- | :--- |
| **Avatar de Usuário** | `me.png` | Bloco `.user-auth-window` |
| **Player de Música** | `Samurai.webp` | Bloco `AUDIO_PLAYER.EXE` |
| **Pôster Cyberpunk** | `cyberpunk.jpg` | Bloco `.cyberpunk-poster-window` |
| **Arquivo de Arte (Renoir)** | `Renoir.jpg` | Bloco `.renoir-archive` |
| **Mapa Tático (Arasaka)** | `arasaka.jpg` | Bloco `.arasaka-popup` |
| **Alerta Deadlock** | `seven.jpg` | Bloco `.seven-data-window` |
| **Alvo Wanted (Johnny)** | `johnny.JPG` | Bloco `.johnny-wanted-box` |
| **Visualizador Tático (ASCII)** | `ASCII.jpg` | Bloco `.skull-window` |

---
## 🚀 Como Executar Localmente
Basta clonar este repositório e abrir o arquivo `index.html` diretamente no seu navegador favorito:

```bash
git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)
```
----
### IMPORTANTEEEEEEEE
Outra coisa, vc roda o codigo abre no navegador e NAO TIRA PRINTTTTT, vc clica em algum botão ai no seu computador que vc exporta a pagina como PDF, ai vc baixa o pdf e converte para png,jpeg ou seu formato de arquivo favorito
Iriei aqui explicar o PORQUE vc nao pode tirar print: qualidade muito ruim, fica horrível como wallpaper
