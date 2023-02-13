# Igazsabtablazat-generalasa-logikai-feladatok-gyakorlasahoz

<h1>Igazságtáblázat generálása magyarul</h1>
<h2>módosított verzió: Michael Rieppel</h2>
<h2>alapverzió: Michael Rieppel</h2>

<h2>Online tesztelhető verzió:</h2>
<a href="http://programozas.sterbinaroland.hu/igazsagtabla.html">demo</a>

Példák a program megfelelő működéséhez:

(/ jellel elválasztva különböző szimbólumó formulák tesztelhetőek!)
~p / ¬p
(p & q) / (p ∧ q)
(p > (q v ~r)) / (p ⊃ (q ∨ ¬r))
(p & (~q > r)) / (p ∧ (¬q ⊃ r))
{(p<>(qvr)), p, (~q>r)} / {(p≡(q∨r)), p, (¬q⊃r)}
