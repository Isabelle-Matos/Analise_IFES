# Instruções de Execução

Este repositório contém os arquivos necessários para a **Atividade Prática 4 - Ferramentas para Data Science (UFSJ)**.

## Como Executar o Projeto

Siga os passos abaixo no terminal para criar o ambiente virtual com o **Conda** e executar o projeto:

### 1. Criar o ambiente virtual a partir do arquivo
No terminal, execute o comando na raiz da pasta do projeto:

```bash
conda env create -f environment.yml
```

### 2. Ativar o ambiente virtual
```bash
conda activate ifes-env
```

### 3. Registrar o Kernel no Jupyter
Para que o ambiente fique disponível na lista de kernels do Jupyter:

```bash
python -m ipykernel install --user --name=ifes-env --display-name "Python (ifes-env)"
```

### 4. Iniciar o Jupyter Lab / Notebook
```bash
jupyter lab
```

Ao abrir o notebook `ifes.ipynb`, certifique-se de selecionar o kernel **`Python (ifes-env)`**.