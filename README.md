# WhatsApp Link Generator

Este projeto é uma aplicação simples baseada em HTML, CSS (via Bootstrap) e JavaScript que permite aos usuários gerar links personalizados para números de telefone no WhatsApp. O formulário suporta seleção de código de país com bandeiras, aplicação de máscara para números de telefone e estilização responsiva.

## Funcionalidades

- Seleção de código de país com bandeiras (padrão: Brasil).
- Entrada de número de telefone com máscara no formato brasileiro.
- Geração de link dinâmico para o WhatsApp no formato `https://wa.me/`.
- Layout responsivo utilizando Bootstrap.
- Interface centralizada e estilizada com as cores do WhatsApp.

## Tecnologias Utilizadas

- **HTML5**: Estrutura do documento.
- **CSS (via Bootstrap)**: Estilização e responsividade.
- **JavaScript/jQuery**: Funcionalidade dinâmica, incluindo aplicação de máscara de entrada.
- **jQuery Mask Plugin**: Aplicação de máscaras para o campo de telefone.

## Como Usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/EricSantosdm/WhatsLink
   ```
2. Abra o arquivo `index.html` no navegador.
3. Selecione o país desejado no menu suspenso.
4. Digite o número de telefone (com DDD).
5. Clique no botão "Gerar Link" para criar o link do WhatsApp.
6. O link gerado será exibido abaixo do formulário e poderá ser clicado para abrir o WhatsApp.

## Pré-visualização

A interface centralizada e estilizada com paleta de cores do WhatsApp:



## Estrutura do Projeto

```
/
├── index.html       # Arquivo principal
├── README.md        # Documentação do projeto
└── assets/          # Imagens e outros recursos
```

## Personalização

- Para adicionar ou modificar códigos de país, edite a seção `<select>` no arquivo HTML, adicionando as opções desejadas com a bandeira e o código correspondente.

```html
<option value="1"><img src="https://flagcdn.com/w40/us.png" alt="US"> Estados Unidos (+1)</option>
```

## Contribuindo

Sinta-se à vontade para contribuir com melhorias no projeto! Faça um fork, crie uma branch para suas alterações e envie um pull request.

## Licença

Este projeto está sob a licença MIT. Consulte o arquivo LICENSE para mais informações.

