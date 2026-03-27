# datamining_master_degree_project

## Pré-requisitos

- Python 3.8 ou superior
- pip (gerenciador de pacotes do Python)

## Como rodar o projeto

### 1. Clonar o repositório

```bash
git clone <url-do-repositorio>
cd datamining_master_degree_project
```

### 2. Criar e ativar o ambiente virtual (venv)

#### Windows (CMD)

```cmd
python -m venv venv
venv\Scripts\activate
```

#### Windows (PowerShell)

```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
```

#### Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Instalar as dependências

Com o ambiente virtual ativado:

```bash
pip install -r requirements.txt
```

### 4. Instalar o Jupyter Notebook (caso não esteja instalado)

```bash
pip install notebook ipykernel
```

### 5. Registrar o kernel do ambiente virtual

```bash
python -m ipykernel install --user --name=venv --display-name "Python (venv)"
```

### 6. Executar o notebook

#### Via terminal

```bash
jupyter notebook crispdm_datamining.ipynb
```

#### Via VS Code

1. Abra o arquivo `crispdm_datamining.ipynb` no VS Code.
2. Instale a extensão **Jupyter** caso ainda não tenha.
3. No canto superior direito do notebook, clique em **Select Kernel**.
4. Escolha **Python Environments** → **Python (venv)** (ou o interpretador do seu `venv`).
5. Execute as células normalmente.

### 7. Desativar o ambiente virtual (quando terminar)

```bash
deactivate
```