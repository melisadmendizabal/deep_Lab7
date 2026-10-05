### Instalar dependencias
```bash
py -3.11 -m venv venv
venv\Scripts\activate
python -m pip install --upgrade pip
pip install torch --index-url https://download.pytorch.org/whl/cu128
pip install numpy pandas matplotlib tqdm datasets gensim scikit-learn joblib spacy nltk ipykernel
python -m ipykernel install --user --name lab7 --display-name "Python (lab7)"
python -c "import torch; print(torch.cuda.is_available(), torch.cuda.get_device_name(0))"
```
