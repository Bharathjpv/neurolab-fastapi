# FastApi

## Run the application
### Step 1: Clone the repository

```bash
git clone https://github.com/Bharathjpv/neurolab-fastapi.git
```

### Step 2- Create a conda environment

```bash
conda create -p venv python==3.9 -y
```

### Step 3- Activate
```bash
conda activate venv
```

### Step 3 - Install the requirements

```bash
pip install -r requirements.txt
```

### Step 5 - Run the application server

```bash
uvicorn app:app  --reload
```
### Step 6. Test the server

home route

```bash
http://localhost:8000
```
items route
```bash
http://localhost:8000/items/78?q=myquery
```