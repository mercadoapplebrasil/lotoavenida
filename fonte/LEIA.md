# Fontes do site

O `index.html` é montado por script. Para remontar numa sessão nova:

```
mkdir -p /home/claude/scripts && tar -xzf fonte/fonte.tar.gz -C /home/claude/scripts
python3 /home/claude/scripts/la_melhorar.py
```

Para só atualizar bolões, cotas ou resultados não precisa remontar: basta editar o `dados.json` (quando houver).
