# Monopoly game simulator

## Run the project
(MacOSX environment)

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python main.py
```

## Config files 

`config.py` allows dynamic variable loading  
It is more versitle than `.env` files

example:
```python
log = True # disables override logs if False (default True)
```

## Watching changes

Powershell:  
`get-content log.txt -wait -tail 30`

Bash:  
`tail log.txt -f`