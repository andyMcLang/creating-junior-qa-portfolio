# QA-opiskelua

Tämä on QA-testauksen opiskelumateriaali- ja harjoituskansio.

## Sisältö

| Tiedosto | Kuvaus |
|----------|--------|
| `test_example.py` | Playwright-esimerkkitesti |
| `test_example_selitykset.txt` | Esimerkkitestin selitykset suomeksi |
| `linkkivinkkejä_opiskeluun_by_cG_17.1.2026.docx` | Opiskelulinkkejä ja resursseja |

## Vaatimukset

- Python 3.x
- pytest-playwright

## Asennus

```powershell
python -m pip install pytest-playwright
python -m playwright install
```

## Testien ajaminen

```powershell
# Aja kaikki testit
pytest

# Aja testit näkyvässä selaimessa
pytest --headed

# Aja yksittäinen testitiedosto
pytest test_example.py

# Aja yksittäinen testi
pytest test_example.py::test_has_title
```
