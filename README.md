# Dars 22 — Uyga vazifa: Hosila va Gradient

Najot Ta'lim Machine Learning kursi, Dars 22 uy vazifasi. 12 ta topshiriqdan iborat bo'lib, hosila tushunchasidan tortib gradient descent va learning rate xatti-harakatigacha bo'lgan mavzularni mustahkamlaydi.

## Mundarija

1. Ta'rifni tushuntirish — hosila va limit
2. Power rule bilan qo'lda hisoblash
3. Hosila ishorasini o'qish (o'sish / kamayish / tekis nuqta)
4. Belgilash: Lagranj (`f'(x)`) va Leybnits (`df/dx`)
5. Numerik hosila funksiyasi (`hosila(f, x, h)`)
6. SymPy bilan analitik tekshirish
7. Qisman hosila (`∂f/∂x`, `∂f/∂y`)
8. Gradient vektori (`∇f`)
9. Minimum nuqtani topish (qo'lda + numerik tekshiruv)
10. Gradient descent sikli (`pastga_tush`)
11. Learning rate tajribasi (kichik / optimal / juda katta)
12. Gradient Ascent xatosini topish va tuzatish (debugging)

## Fayllar

| Fayl | Tavsif |
|---|---|
| `hosila_practice.ipynb` | Uy vazifasi — barcha 12 topshiriq, javoblar va kod |
| `requirements.txt` | Notebook'ni ishga tushirish uchun zarur kutubxonalar |

## Ishga tushirish

```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook hosila_practice.ipynb
```

## Talab qilinadigan kutubxonalar

- numpy
- sympy
- jupyter

## Muallif

Zaxro Madrimova — [github.com/madrimovazaxro](https://github.com/madrimovazaxro)
