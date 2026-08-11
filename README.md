# README.me
 Portfólio Flask

Site de portfólio pessoal desenvolvido com **Python** e **Flask**, criado para apresentar informações profissionais, projetos, habilidades e formas de contato.

## 📋 Sobre o projeto

Este projeto consiste em um site de portfólio pessoal desenvolvido utilizando o framework **Flask**, permitindo apresentar de forma organizada informações sobre o desenvolvedor, seus projetos e suas principais competências.

O objetivo é criar uma presença profissional na web, com uma estrutura simples, leve e de fácil manutenção.

## ✨ Funcionalidades

* 🏠 Página inicial
* 👤 Apresentação pessoal
* 💻 Exibição de projetos
* 🛠️ Apresentação de habilidades e tecnologias
* 📄 Informações profissionais
* 📬 Área de contato
* 📱 Layout responsivo

## 🛠️ Tecnologias utilizadas

* **Python**
* **Flask**
* **HTML5**
* **CSS3**
* **JavaScript**

## 📁 Estrutura do projeto

```text
portfolio-flask/
├── app.py
├── requirements.txt
├── README.md
├── templates/
│   ├── index.html
│   └── ...
├── static/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   └── images/
└── ...
```

## 🚀 Instalação

### 1. Clone o repositório

```bash
git clone [URL_DO_REPOSITORIO]
```

### 2. Entre na pasta do projeto

```bash
cd portfolio-flask
```

### 3. Crie um ambiente virtual

No Windows:

```bash
python -m venv venv
```

Ative o ambiente virtual:

```bash
venv\Scripts\activate
```

No Linux/macOS:

```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Instale as dependências

```bash
pip install -r requirements.txt
```

## ▶️ Executando o projeto

Execute a aplicação com:

```bash
python app.py
```

Depois, acesse no navegador:

```text
http://127.0.0.1:5000
```

## 📦 Dependências

As dependências do projeto estão especificadas no arquivo `requirements.txt`.

Exemplo:

```text
Flask
```

Para instalar todas as dependências:

```bash
pip install -r requirements.txt
```

## ⚙️ Configuração

Caso o projeto utilize variáveis de ambiente, crie um arquivo `.env` na raiz:

```env
FLASK_APP=app.py
FLASK_ENV=development
SECRET_KEY=sua_chave_secreta
```

> Não compartilhe chaves secretas ou outras informações sensíveis no repositório.

## 🖥️ Desenvolvimento

Durante o desenvolvimento, o Flask pode ser executado em modo de debug:

```bash
flask --app app run --debug
```

Isso permite que alterações no código sejam recarregadas automaticamente durante o desenvolvimento.

## 🌐 Deploy

Para publicar o portfólio em produção, é recomendado utilizar um servidor WSGI apropriado para aplicações Flask, juntamente com uma plataforma de hospedagem compatível com Python.

Antes do deploy:

* Desative o modo `debug`.
* Configure as variáveis de ambiente.
* Proteja a `SECRET_KEY`.
* Configure corretamente o servidor.
* Verifique os arquivos estáticos.
* Teste todas as páginas e funcionalidades.

## 🗺️ Roadmap

* [x] Criar estrutura inicial do projeto
* [x] Configurar Flask
* [ ] Finalizar página inicial
* [ ] Adicionar seção de projetos
* [ ] Adicionar seção de habilidades
* [ ] Criar formulário de contato
* [ ] Melhorar responsividade
* [ ] Adicionar animações
* [ ] Publicar o projeto

## 📄 Licença

Este projeto está disponível para fins pessoais e profissionais.

Caso seja utilizada uma licença específica, adicione o arquivo `LICENSE` e atualize esta seção.

## 👨‍💻 Autor

**[JÚLIO RICARDO]**

GitHub: `[https://github.com/05julioricardo-stack]`

---

<p align="center">
  Desenvolvido com ❤️ usando Python + Flask.
</p>
