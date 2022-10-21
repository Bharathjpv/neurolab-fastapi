# FastApi

![image](https://user-images.githubusercontent.com/115451707/196919992-edcfea8b-e3f6-4f35-9398-43be66b5622d.png)

### Step 1 - Install the requirements
```bash
pip install -r requirements.txt
```

### Step 2 - Run the application server

```bash
uvicorn app:app  --reload
```
### Step 3. Test the server

<b>Home route </b>

```bash
http://localhost:8000
```
<b>Items route</b>
```bash
http://localhost:8000/items/78?q=myquery
```