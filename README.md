### Criar venv
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### Instalar as dependencias
```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### Adicionar as dependencias no requirments
```bash
pip freeze > requirements.txt
```