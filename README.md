# Cod reducere Dr. Max — fetch automat de pe shopilo.ro

Modul Python pentru fetch automat de **coduri de reducere Dr. Max** de pe [shopilo.ro](https://shopilo.ro/magazin/drmax.ro). Returneaza **cupoane Dr. Max** active in format JSON, gata de integrat intr-un bot Telegram, extensie de browser sau orice alt tool.

**Pagina live:** [shopilo-ro.github.io/cod-reducere-dr-max](https://shopilo-ro.github.io/cod-reducere-dr-max/)

![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue) ![License MIT](https://img.shields.io/badge/license-MIT-green)

## Instalare

```bash
pip install requests beautifulsoup4
git clone https://github.com/shopilo-ro/cod-reducere-dr-max
cd cod-reducere-dr-max
python fetch.py
```

## Output exemplu

```json
[
  {
    "store": "Dr. Max",
    "code": "SHOPILO10",
    "discount": "10%",
    "description": "10% reducere la prima comanda in aplicatie",
    "expires": "2026-10-02",
    "source": "https://shopilo.ro/magazin/drmax.ro"
  }
]
```

## Cupoane Dr. Max disponibile

| Reducere | Descriere | Sursa |
|----------|-----------|-------|
| 10% | 10% reducere la prima comanda in aplicatie | [shopilo.ro](https://shopilo.ro/magazin/drmax.ro) |

Codurile active: **[shopilo.ro/magazin/drmax.ro](https://shopilo.ro/magazin/drmax.ro)**

## Intrebari frecvente

### Cum folosesc un cod de reducere Dr. Max?
Copiaza codul din tabelul de mai sus sau de pe [shopilo.ro](https://shopilo.ro/magazin/drmax.ro), adauga produsele in cos pe Dr. Max, si introdu codul la checkout in campul dedicat.

### Cat timp sunt valabile cupoanele Dr. Max?
Fiecare cupon are data de expirare afisata in coloana "Expira". Scriptul fetch.py returneaza doar cupoanele active la momentul rularii.

### Unde gasesc cele mai noi voucher-uri Dr. Max?
Pagina [shopilo.ro/magazin/drmax.ro](https://shopilo.ro/magazin/drmax.ro) este actualizata zilnic cu cele mai noi cod reducere Dr. Max, voucher Dr. Max si cupon promotional Dr. Max.

### Codul nu functioneaza. Ce fac?
Verifica data de expirare si conditiile (valoare minima cos, produse eligibile). Unele coduri sunt valabile doar in aplicatia mobila sau pentru prima comanda.

## Despre Dr. Max

Dr. Max este unul dintre magazinele online populare. Gasesti pe [shopilo.ro](https://shopilo.ro/magazin/drmax.ro) cele mai bune cod reducere Dr. Max, cupoane Dr. Max verificate si voucher Dr. Max active, actualizate zilnic.

## Instalare npm

```bash
npm install cod-reducere-dr-max
```

```javascript
const { fetchCoupons } = require('cod-reducere-dr-max');
fetchCoupons().then(data => console.log(data));
```

## Licenta

MIT — date sursa de pe [shopilo.ro](https://shopilo.ro)
