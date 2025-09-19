### 1. `git add`

- **O que faz:** Prepara arquivos que você alterou para serem salvos no histórico do projeto.
- **Como usar:**
    - Se você mudou um arquivo chamado `index.html`, rode:

```
git add index.html
```

    - Para preparar todos os arquivos alterados:

```
git add .
```

- **Quando usar:** Sempre que quiser registrar uma alteração antes de salvar de verdade com o `git commit`.[^3][^4]


### 2. `git config`

- **O que faz:** Configura informações do usuário (nome, e-mail) e preferências do Git no seu computador.
- **Como usar:**
    - Para definir seu nome:

```
git config --global user.name "Seu Nome"
```

    - Para definir seu e-mail:

```
git config --global user.email "seu@email.com"
```

- **Quando usar:** Normalmente, só na primeira vez que instala o Git, ou se quiser mudar alguma configuração pessoal.[^6][^3]


### 3. `git clone`

- **O que faz:** Copia um projeto inteiro de um repositório remoto (por exemplo, do GitHub) para o seu computador.
- **Como usar:**
    - Pegue a URL do repositório (exemplo: `https://github.com/usuario/projeto.git`) e rode:

```
git clone https://github.com/usuario/projeto.git
```

- **Quando usar:** Quando você quer começar a trabalhar em um projeto que já existe em outro lugar, ou fazer backup do seu próprio projeto.[^2][^5][^3]
