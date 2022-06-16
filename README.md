# binary-tree
[echo "# binary-tree" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/direnyegen/binary-tree.git
git push -u origin main]
(https://app.patika.dev/diren)
ilk değer 7 root olarak seçilir
sırasıyla sonraki değerlerin root değerden büyük ya da küçük olmasına göre 7'nin sağına ya da soluna yazılır.
Buradan hareketle;
5<7 soluna yazılır
1<7 sola yazılır
8>7 sağa yazılır
3<7 sola yazılır
0<7 sola yazılır
6<7 sola yazılır
9>7 sağa yazılır
4<7 sola yazılır
2<7sola yazılır
Bu sola ve sağa yazılan ifadeler kendinden bir önceki elemana göre kendi içlerinde sola ya da sağa yazılacağına göre en sonda durum;
            7
       5          8
   1         6           9
0    3
    2  4
