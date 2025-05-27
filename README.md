# Badanie powiązania snu i głodu

Na początku 2025 roku zaprojektowałem i przeprowadziłem badanie mające na celu sprawdzenie związku między zaburzeniami snu a odczuwaniem głodu. Zebrałem odpowiedzi od 56 osób.

Samodzielnie przygotowałem kwestionariusz, oczyściłem dane oraz przeprowadziłem analizę.

# Wyniki

- Wyniki nie zostały opublikowane, ponieważ ostatecznie nie napisałem raportu z badania.  
- Analiza została przeprowadzona w skrypcie o nazwie `analysis.ipynb`.  
- W analizie wykazano, że istnieje różnica w odczuwaniu głodu związanym z sekrecją greliny u osób z zaburzeniami snu w porównaniu do osób bez takich zaburzeń.  

![Macierz korelacji pomiędzy istotnymi zmiennymi uwzględnionymi w badaniu](wyniki.png)

- `f1_sen` — czynnik odpowiadający osobom z zaburzeniami snu polegającymi na późnym zasypianiu  
- `f2_sen` — czynnik odpowiadający osobom bez zaburzeń snu  
- `f1_głód` — czynnik odpowiadający poziomowi leptyny (hormonu sytości)  
- `f2_głód` — czynnik odpowiadający poziomowi greliny (hormonu głodu)

Należy zwrócić uwagę na różnicę w korelacji między `f1_sen`, `f2_sen` a `f2_głód` (**p-value tej różnicy: 0,013**).

Macierz przedstawia również korelacje między deklarowanymi zaburzeniami snu a poziomem greliny. Nie należy jednak nadmiernie ufać tym wynikom, ponieważ bazują one wyłącznie na deklaracjach uczestników — należałoby skonstruować pytania, które rzetelnie mierzyłyby każdy z typów zaburzeń snu.

