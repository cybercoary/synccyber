# AtlasModule
Como instalar:

```
bash <(wget -qO- https://raw.githubusercontent.com/cybercoary/synccyber/main/install.sh)
```

Instale o painel web Atlas normalmente, e sincronize sua VPS

Apos sincronizar sua VPS use o comando abaixo na VPS para substituir os modulos pelos modulos Dragon


```
rm atlasdata.sh || true && rm atlascreate.sh || true && rm atlasteste.sh || true && rm atlasremove.sh || true && rm delete.py || true && rm sincronizar.py || true && wget https://raw.githubusercontent.com/cybercoary/synccyber/main/atlascreate.sh && chmod 777 atlascreate.sh && wget https://raw.githubusercontent.com/cybercoary/synccyber/main/atlasteste.sh && chmod 777 atlasteste.sh && wget https://raw.githubusercontent.com/cybercoary/synccyber/main/atlasremove.sh && chmod 777 atlasremove.sh && wget https://raw.githubusercontent.com/cybercoary/synccyber/main/delete.py && wget https://raw.githubusercontent.com/cybercoary/synccyber/main/atlasdata.sh && chmod 777 atlasdata.sh && chmod 777 delete.py && wget https://raw.githubusercontent.com/cybercoary/synccyber/main/sincronizar.py && chmod 777 sincronizar.py > /dev/null 2>&1
```