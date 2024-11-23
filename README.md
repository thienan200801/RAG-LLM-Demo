### 1. Install dependencies
```python
conda install onnxruntime -c conda-forge
```

### 2. Now run this command to install dependenies in the `requirements.txt` file. 

```python
pip install -r requirements.txt
```

### 3. Install markdown depenendies with: 

```python
pip install "unstructured[md]"
```

### 4. Create database

```python
python create_database.py
```

## Query the database

Query the Chroma DB.

```python
python query_data.py "How does Alice meet the Mad Hatter?"
```