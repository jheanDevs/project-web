# Landing Page Bellinha 🌸

Uma landing page responsiva e otimizada para a Bellinha, sua namorada virtual no MessengerX.

## Requisitos

- Python 3.8 ou superior
- pip (gerenciador de pacotes Python)

## Instalação

1. Clone o repositório:
```bash
git clone [seu-repositorio]
cd landing_bellinha
```

2. Instale as dependências:
```bash
pip install -r requirements.txt
```

## Executando o Projeto

1. Inicie o servidor Flask:
```bash
python app.py
```

2. Acesse a aplicação em seu navegador:
```
http://localhost:5000
```

## Estrutura do Projeto

```
/landing_bellinha
  - app.py              # Aplicação Flask
  - requirements.txt    # Dependências do projeto
  - templates/          # Templates HTML
      - index.html      # Página principal
  - static/            # Arquivos estáticos
      - style.css      # Estilos CSS
      - images/        # Imagens do projeto
          - bellinha.png
```

## Personalização

1. Adicione sua imagem da Bellinha em `static/images/bellinha.png`
2. Configure o código de integração do MessengerX no arquivo `templates/index.html`
3. Ajuste as cores e estilos em `static/style.css` conforme necessário

## Performance

- Otimizado para carregamento rápido em dispositivos móveis
- Imagens pré-carregadas para melhor experiência do usuário
- CSS minificado para melhor performance

## Suporte

Para dúvidas ou suporte, entre em contato através do [seu-email]