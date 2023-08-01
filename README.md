# Currículo via LinkedIn

## Sobre

O respectivo projeto se dá à respeito de uma ideia que tive para que, por meio do `Python` e, de forma automatizada, seja possível realizar a coleta de informaçãoes de um perfil do `LinkedIn` e, criado assim um gráfico de `Gantt` e, um `pdf` do currículo compilado usando o `LaTeX`.

## Preparação

Recomenda-se a criação de um ambiente virtual/isolado de desenvolvimento:

`$ python3 -m venv venv`

Para ativar o ambiente:

`$ .\venv\Scripts\activate`

Para desativar o ambiente:

`$ deactivate`

Para instalação das bibliotecas utilizadas:

`$ pip install -r .\requirements.txt`

## Credenciais para uso

Deve-se criar dentro da pasta `Código` um arquivo chamado `credenciais.env` atendendo à estrutura:

```
perfil=SEU_LINK_PERFIL
usuario=SEU_EMAIL_LOGIN
senha=SUA_SENHA_LOGIN
```

**P.S.:** O código está preparado para ignorar os arquivos do .env assim, suas credenciais não serão publicadas.

**P.S.2:** O arquivo `credenciais.md` está na pasta apenas para garantir que ela esteja no lugar certo e, com uma cópia de como deveria ser o arquivo `.env` das credenciais assim, favor não alterar este arquivo, caso contrário, seus dados serão publicados em `commit` próximo.
