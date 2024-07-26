

```markdown
# Projeto de API de Gerenciamento de Restaurante

Este projeto é uma API para gerenciamento de um restaurante, desenvolvida com o intuito de demonstrar habilidades em FastAPI.

## Funcionalidades

- **Cadastro de Clientes**: Adicione, edite e remova informações dos clientes.
- **Gerenciamento de Mesas**: Controle o estado das mesas (disponível, reservada, ocupada).
- **Cardápio**: Gerencie itens do cardápio, incluindo criação, atualização e remoção de pratos.
- **Pedidos**: Registre e acompanhe pedidos feitos pelos clientes.

## Tecnologias Utilizadas

- **Linguagem de Programação**: Python
- **Framework**: FastAPI

## Estrutura do Projeto

```plaintext
restaurante/
├── main.py
├── models/
│   ├── cliente.py
│   ├── mesa.py
│   ├── cardapio.py
│   ├── pedido.py
├── routers/
│   ├── cliente.py
│   ├── mesa.py
│   ├── cardapio.py
│   ├── pedido.py
└── README.md
```

### Arquivos e Diretórios

- `main.py`: Arquivo principal que inicia a aplicação FastAPI e define as rotas.
- `models/`: Diretório contendo os modelos de dados para clientes, mesas, cardápio e pedidos.
- `routers/`: Diretório contendo as rotas para cada funcionalidade.

## Instalação

1. Clone o repositório:
    ```bash
    git clone https://github.com/araujojv/restaurante.git
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd restaurante
    ```
3. Crie um ambiente virtual:
    ```bash
    python -m venv venv
    ```
4. Ative o ambiente virtual:
    - No Windows:
      ```bash
      venv\Scripts\activate
      ```
    - No Linux/MacOS:
      ```bash
      source venv/bin/activate
      ```
5. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

## Uso

Execute a aplicação FastAPI:
```bash
uvicorn main:app --reload
```
Acesse a documentação interativa da API no navegador em `http://127.0.0.1:8000/docs`.

## Contribuição

Contribuições são bem-vindas! Siga os passos abaixo para contribuir:

1. Faça um fork do repositório.
2. Crie um branch para sua feature ou correção de bug (`git checkout -b feature/nova-feature`).
3. Faça commit das suas alterações (`git commit -am 'Adiciona nova feature'`).
4. Faça push para o branch (`git push origin feature/nova-feature`).
5. Crie um novo Pull Request.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## Sobre Mim

Sou estudante de Ciência de Dados e Business Intelligence, com interesse em desenvolvimento de APIs. Este projeto faz parte do meu portfólio para demonstrar minhas habilidades e dedicação em construir uma carreira sólida na área de tecnologia.
```

Sinta-se à vontade para ajustar esse README conforme necessário para refletir mais detalhadamente as especificidades do seu projeto. Se precisar de mais alguma coisa, estou à disposição!
