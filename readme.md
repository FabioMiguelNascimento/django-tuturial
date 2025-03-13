# Aplicativo Django Todo

Uma aplicação Django simples para gerenciar itens de tarefas.

## Pré-requisitos

- Python 3.x
- Django 4.2.x

## Instalação

1. Clone este repositório:
```bash
git clone https://github.com/FabioMiguelNascimento/django-tuturial.git
cd django-tuturial/demo
```

2. Instale as dependências:
```bash
pip install django
```

3. Execute as migrações do banco de dados:
```bash
python manage.py migrate
```

4. Crie um superusuário (opcional - para acesso administrativo):
```bash
python manage.py createsuperuser
```

## Executando a Aplicação

1. Inicie o servidor de desenvolvimento:
```bash
python manage.py runserver
```

2. Abra seu navegador e acesse:
- Página inicial: http://127.0.0.1:8000/
- Lista de tarefas: http://127.0.0.1:8000/todos/
- Interface administrativa: http://127.0.0.1:8000/admin/

## Estrutura do Projeto

```
demo/
├── myapp/                  # Aplicação principal
│   ├── migrations/        # Migrações do banco de dados
│   ├── templates/        # Templates HTML
│   ├── admin.py         # Configuração do admin
│   ├── models.py        # Modelos de banco de dados
│   ├── views.py         # Funções de visualização
│   └── urls.py          # Roteamento de URLs
└── demo/                  # Configurações do projeto
    ├── settings.py      # Configuração do projeto
    └── urls.py          # Roteamento principal de URLs
```