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

## Licença

* **[Licença MIT](https://github.com/murilochaves/curriculo-linkedin/blob/main/LICENSE)**

<p align='center'>
    <b>
        Direitos autorais (c) 2023 Murilo Chaves Jayme
    </b>
</p>

<p align='justify'>
    A permissão é concedida, gratuitamente, a qualquer pessoa que obtenha uma cópia deste software e dos arquivos de documentação associados (o "Software"), para lidar com o Software sem restrições, incluindo, sem limitação, os direitos de usar, copiar, modificar, mesclar, publicar, distribuir, sublicenciar e/ou vender cópias do Software, e permitir que as pessoas para quem o Software é fornecido façam o mesmo, sujeito às seguintes condições:
</p>

<p align='justify'>
    O aviso de direitos autorais acima e este aviso de permissão devem ser incluídos em todas as cópias ou partes substanciais do Software.
</p>

<p align='justify'>
    O SOFTWARE É FORNECIDO "COMO ESTÁ", SEM GARANTIA DE QUALQUER TIPO, EXPRESSA OU IMPLÍCITA, INCLUINDO, MAS NÃO SE LIMITANDO A GARANTIAS DE COMERCIALIZAÇÃO, ADEQUAÇÃO A UMA FINALIDADE ESPECÍFICA E NÃO VIOLAÇÃO. EM NENHUMA HIPÓTESE OS AUTORES OU TITULARES DE DIREITOS AUTORAIS SERÃO RESPONSÁVEIS POR QUALQUER RECLAMAÇÃO, DANOS OU OUTRA RESPONSABILIDADE, SEJA EM UMA AÇÃO DE CONTRATO, DELITO OU DE OUTRA FORMA, DECORRENTE DE, OU EM CONEXÃO COM O SOFTWARE OU O USO OU OUTRAS NEGOCIAÇÕES NO SOFTWARE.
</p>

<p align='center'>
    <b>
        Ou seja, pode ser usado para qualquer finalidade desde que atribuído a autoria!
    </b>
</p>