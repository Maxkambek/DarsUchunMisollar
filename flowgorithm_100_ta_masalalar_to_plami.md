# Flowgorithm Dasturida Ishlash Uchun 100 ta Masala va Topshiriqlar To'plami

Ushbu to'plam o'quvchilarda algoritmik fikrlashni shakllantirish va Flowgorithm dasturida blok-sxemalar tuzish ko'nikmalarini rivojlantirish uchun mo'ljallangan. Masalalar oddiydan murakkabga tamoyili asosida 4 ta asosiy bo'limga ajratilgan.

---

## I BO'LIM: Oddiy (Chiziqli) Algoritmlar (1–25)
*Bu bo'limda faqat `Declare` (e'lon qilish), `Input` (kiritish), `Assign` (o'zlashtirish) va `Output` (chiqarish) bloklaridan foydalaniladi.*

1. **Ikki son yig'indisi:** Kiritilgan ikkita $A$ va $B$ sonlarining yig'indisini toping.
2. **To'rtta amal:** Kiritilgan ikkita $A$ va $B$ sonlarining yig'indisi, ayirmasi, ko'paytmasi va bo'linmasini hisoblang.
3. **Kvadrat:** Tomoni $a$ ga teng bo'lgan kvadratning perimetri ($P = 4a$) va yuzasini ($S = a^2$) toping.
4. **To'g'ri to'rtburchak:** Tomonlari $a$ va $b$ bo'lgan to'g'ri to'rtburchakning yuzasi ($S = a \cdot b$) va perimetrini ($P = 2(a + b)$) hisoblang.
5. **Aylana uzunligi:** Diametri $d$ ga teng bo'lgan aylananing uzunligini toping ($L = \pi \cdot d$, $\pi = 3.14$).
6. **Doira yuzasi:** Radiusi $R$ bo'lgan doiraning uzunligi ($L = 2\pi R$) va yuzasini ($S = \pi R^2$) aniqlang.
7. **Kub:** Qirrasining uzunligi $a$ bo'lgan kubning hajmi ($V = a^3$) va to'la sirti yuzasini ($S = 6a^2$) toping.
8. **Parallelepiped:** Tomonlari $a, b, c$ bo'lgan to'g'ri burchakli parallelepipedning hajmi ($V = a \cdot b \cdot c$) va to'la sirtini ($S = 2(ab + bc + ac)$) hisoblang.
9. **O'rta arifmetik:** Kiritilgan ikkita $a$ va $b$ sonlarining o'rta arifmetigini toping: $\frac{a + b}{2}$.
10. **O'rta geometrik:** Ikkita manfiy bo'lmagan $a$ va $b$ sonlarining o'rta geometrigini toping: $\sqrt{a \cdot b}$ (Flowgorithm'da `Sqrt(a * b)`).
11. **Uchburchak gipotenuzasi:** To'g'ri burchakli uchburchakning katetlari $a$ va $b$ berilgan. Uning gipotenuzasi ($c = \sqrt{a^2 + b^2}$) va perimetrini ($P = a + b + c$) toping.
12. **Harorat (Selsiy -> Farengeyt):** Selsiy bo'yicha berilgan haroratni ($C$) Farengeytga ($F$) o'tkazing: $F = C \cdot 1.8 + 32$.
13. **Harorat (Farengeyt -> Selsiy):** Farengeyt bo'yicha berilgan haroratni ($F$) Selsiyga ($C$) o'tkazing: $C = (F - 32) / 1.8$.
14. **Valyuta konvertori:** So'mda kiritilgan pul miqdorini AQSh dollariga o'tkazing (kursni o'zingiz belgilang).
15. **Tezlik va masofa:** Avtomobilning tezligi ($v$ km/soat) va vaqti ($t$ soat) kiritiladi. Bosib o'tilgan masofani ($S = v \cdot t$) toping.
16. **O'lchov birliklari (Santimetr):** Santimetrda berilgan uzunlik ($L$) necha to'liq metrga teng ekanligini toping (butun bo'lish: `L / 100` yoki `Int(L / 100)`).
17. **O'lchov birliklari (Kilogramm):** Kilogrammda berilgan og'irlik ($M$) necha to'liq tonnaga teng ekanligini aniqlang.
18. **Vaqt hisobi:** Kun boshidan beri $N$ sekund o'tdi. Kun boshidan beri necha to'liq minut o'tganini aniqlang.
19. **Qiymat almashtirish:** $A$ va $B$ o'zgaruvchilarining qiymatlarini o'zaro almashtiring va ekranga chiqaring (yordamchi $C$ o'zgaruvchisidan foydalaning).
20. **Ikki xonali son raqamlari:** Kiritilgan ikki xonali sonning o'nliklar va birliklar xonasidagi raqamlarini alohida ekranga chiqaring.
21. **Ikki xonali son raqamlari yig'indisi:** Kiritilgan ikki xonali sonning raqamlari yig'indisi va ko'paytmasini toping.
22. **Raqamlar o'rnini almashtirish:** Kiritilgan ikki xonali sonning raqamlari o'rnini almashtirishdan hosil bo'lgan sonni toping (Masalan: 47 -> 74).
23. **Uch xonali sonning yuzliklari:** Kiritilgan uch xonali sonning yuzliklar xonasidagi raqamini aniqlang.
24. **Uch xonali son raqamlari yig'indisi:** Kiritilgan uch xonali sonning barcha raqamlari yig'indisini hisoblang.
25. **Chegirma hisoblash:** Mahsulot narxi $P$ va chegirma foizi $K$ kiritiladi. Chegirmadan keyingi to'lanadigan summani toping.

---

## II BO'LIM: Shart Operatorlari (`If` / `Else`) (26–55)
*Bu bo'limda shart tekshirish (`If`) va mantiqiy operatorlar (`&&` - VA, `||` - YOKI, `!` - EMAS) qo'llaniladi.*

26. **Musbat yoki manfiy:** Kiritilgan butun son musbat bo'lsa, unga 1 qo'shing, aks holda o'zgarishsiz qoldiring.
27. **Musbat, manfiy yoki nol:** Kiritilgan sonning musbat, manfiy yoki nolga teng ekanligini ekranga chiqaring.
28. **Juft yoki toq:** Kiritilgan butun sonning juft yoki toq ekanligini aniqlang (`n % 2 == 0`).
29. **Ikki sondan kattasi:** Kiritilgan ikkita sondan kattasini ekranga chiqaring.
30. **Ikki sondan kichigi:** Kiritilgan ikkita sondan avval kichigini, keyin kattasini ekranga chiqaring.
31. **Tenglikni tekshirish:** Kiritilgan ikkita son o'zaro teng bo'lsa "Teng", aks holda "Teng emas" yozuvini chiqaring.
32. **Uch sondan kattasi:** Kiritilgan uchta sondan eng kattasini toping.
33. **Uch sondan kichigi:** Kiritilgan uchta sondan eng kichigini toping.
34. **O'rtacha son:** Kiritilgan uchta sonning o'rtachasini (ya'ni eng kattasi ham, eng kichigi ham bo'lmagan sonni) toping.
35. **Musbat sonlar soni:** Kiritilgan uchta butun son orasida nechta musbat son borligini aniqlang.
36. **Juft sonlar soni:** Kiritilgan uchta son orasida nechta juft va nechta toq son borligini hisoblang.
37. **5 ga karralilik:** Kiritilgan son 5 ga qoldiqsiz bo'linishini tekshiring.
38. **3 va 5 ga karralilik:** Kiritilgan son ham 3 ga, ham 5 ga qoldiqsiz bo'linishini tekshiring.
39. **Oraliqqa tegishlilik:** Kiritilgan $X$ soni $[10, 50]$ oralig'iga tegishli ekanligini tekshiring.
40. **Voyaga yetganlik:** Foydalanuvchining yoshi kiritiladi. 18 yosh va undan katta bo'lsa "Ruxsat berildi", aks holda "Ruxsat berilmadi" deb chiqaring.
41. **Imtihon bahosi:** O'quvchi balli (0–100) kiritiladi: 86–100 "A'lo", 71–85 "Yaxshi", 55–70 "Qoniqarli", 55 dan past "Qoniqarsiz".
42. **Hafta kunlari:** 1 dan 7 gacha son kiritiladi. Mos ravishda hafta kunlari nomini ("Dushanba", "Seshanba"...) chiqaring.
43. **Yil fasllari:** Oy raqami (1–12) kiritiladi. Ushbu oy qaysi faslga ("Qish", "Bahor", "Yoz", "Kuz") tegishli ekanini aniqlang.
44. **Oydagi kunlar soni:** Oy raqami (1–12) kiritiladi (kabisa bo'lmagan yil uchun). Shu oyda nechta kun borligini chiqaring.
45. **Kabisa yili:** Kiritilgan yilning kabisa yili ekanligini aniqlang (4 ga karrali, lekin 100 ga karrali bo'lmagan yoki 400 ga karrali yillar).
46. **Uchburchak mavjudligi:** $a, b, c$ kesmalar berilgan. Ulardan uchburchak yasash mumkinmi? ($a+b>c$, $a+c>b$, $b+c>a$).
47. **Uchburchak turi:** Tomonlari $a, b, c$ bo'lgan uchburchak teng tomonli, teng yonli yoki turli tomonli ekanligini aniqlang.
48. **To'g'ri burchakli uchburchak:** Tomonlari $a, b, c$ bo'lgan uchburchak to'g'ri burchakli ekanligini Pifagor teoremasi orqali tekshiring.
49. **Kvadrat tenglama:** $ax^2 + bx + c = 0$ tenglamaning koeffitsiyentlari kiritiladi. Diskriminant ($D = b^2 - 4ac$) orqali tenglamaning nechta yechimi borligini aniqlang.
50. **Elektr energiyasi to'lovi:** Sarflangan elektr energiyasi (kVt) kiritiladi. 200 kVt gacha 450 so'mdan, 200 kVt dan oshgan qismi uchun 900 so'mdan hisoblang.
51. **Taksi narxi:** Bosib o'tilgan masofa (km) kiritiladi. Dastlabki 3 km uchun 10 000 so'm, undan keyingi har bir km uchun 2 000 so'mdan hisoblang.
52. **Parolni tekshirish:** Foydalanuvchi parol kiritadi. Agar parol `"12345"` ga teng bo'lsa "Xush kelibsiz", aks holda "Parol xato" xabarini chiqaring.
53. **Svetofor:** Svetofor rangi ("qizil", "sariq", "yashil") kiritiladi. Mos ravishda "To'xtang", "Tayyorlaning", "Harakatlaning" xabarini chiqaring.
54. **Eng katta ikkita son yig'indisi:** Kiritilgan uchta sondan eng katta ikkitasining yig'indisini toping.
55. **Oxirgi raqam:** Kiritilgan son 7 raqami bilan tugashini tekshiring (`n % 10 == 7`).

---

## III BO'LIM: Takrorlanish Operatorlari (`For`, `While`, `Do`) (56–85)
*Bu bo'limda sikl operatorlari yordamida bir xil amallarni ko'p marta bajarish masalalari berilgan.*

56. **Salomlashish:** Ekranga 10 marta "Salom, Flowgorithm!" yozuvini chiqaring.
57. **1 dan 10 gacha:** 1 dan 10 gacha bo'lgan barcha natural sonlarni ekranga chiqaring.
58. **Teskari sanoq:** 10 dan 1 gacha bo'lgan sonlarni kamayish tartibida chiqaring.
59. **1 dan N gacha:** Foydalanuvchi kiritgan $N$ sonigacha bo'lgan barcha natural sonlarni chiqaring.
60. **A dan B gacha:** Kiritilgan $A$ va $B$ ($A < B$) sonlari orasidagi barcha butun sonlarni ekranga chiqaring.
61. **Juft sonlar:** 1 dan 50 gacha bo'lgan barcha juft sonlarni ekranga chiqaring.
62. **Toq sonlar:** 1 dan $N$ gacha bo'lgan barcha toq sonlarni ekranga chiqaring.
63. **3 ga karrali sonlar:** 1 dan 100 gacha bo'lgan 3 ga qoldiqsiz bo'linadigan sonlarni chiqaring.
64. **Sonlar kvadrati:** 1 dan 10 gacha bo'lgan sonlarning kvadratlarini ekranga chiqaring.
65. **Karra jadvali (5 lik):** 5 sonining 1 dan 10 gacha bo'lgan karra jadvalini chiqaring (`5 x 1 = 5` ko'rinishida).
66. **Ixtiyoriy karra jadvali:** Foydalanuvchi kiritgan $K$ sonining karra jadvalini (1 dan 10 gacha) ekranga chiqaring.
67. **Konfet narxi:** 1 kg konfet narxi $P$ so'm. 1, 2, 3, ..., 10 kg konfet narxini ekranga chiqaring.
68. **1 dan N gacha yig'indi:** 1 dan $N$ gacha bo'lgan barcha natural sonlar yig'indisini toping ($S = 1 + 2 + \dots + N$).
69. **Juft sonlar yig'indisi:** 1 dan $N$ gacha bo'lgan faqat juft sonlarning yig'indisini hisoblang.
70. **Toq sonlar yig'indisi:** $A$ dan $B$ gacha bo'lgan toq sonlarning yig'indisini toping.
71. **Faktorial ($N!$):** Kiritilgan $N$ sonining faktorialini hisoblang ($1 \cdot 2 \cdot 3 \cdot \dots \cdot N$).
72. **Darajaga ko'tarish:** $A$ sonining $N$-darajasini ($A^N$) ko'paytirish sikli yordamida hisoblang.
73. **Kvadratlar yig'indisi:** $1^2 + 2^2 + 3^2 + \dots + N^2$ yig'indini hisoblang.
74. **Kasrlar yig'indisi:** $1 + \frac{1}{2} + \frac{1}{3} + \dots + \frac{1}{N}$ yig'indini hisoblang.
75. **O'rta arifmetik (N ta son):** Foydalanuvchi avval $N$ sonini, keyin $N$ ta ixtiyoriy son kiritadi. Shu sonlarning o'rta arifmetigini toping.
76. **N ta sondan kattasi:** Foydalanuvchi kiritgan $N$ ta son orasidan eng kattasini toping.
77. **N ta sondan kichigi:** Foydalanuvchi kiritgan $N$ ta son orasidan eng kichigini toping.
78. **Musbat sonlarni sanash:** Kiritilgan $N$ ta son orasida nechta musbat son borligini hisoblang.
79. **0 kiritilguncha yig'indi (`While`):** Foydalanuvchi ketma-ket sonlar kiritadi. 0 kiritilganda sikl to'xtasin va kiritilgan barcha sonlar yig'indisi chiqarilsin.
80. **Manfiy son kiritilguncha sanash:** Foydalanuvchi sonlar kiritadi. Manfiy son kiritilganda sikl to'xtasin va ungacha nechta musbat son kiritilgani chiqarilsin.
81. **Parolni qayta so'rash (`Do-While`):** Foydalanuvchi to'g'ri parolni (`"7777"`) kiritmaguncha undan parol so'rayveradigan dastur tuzing.
82. **Musbat son kiritishni talab qilish:** Foydalanuvchi 0 dan katta son kiritmaguncha qayta kiritishni so'rang.
83. **Sonning bo'luvchilari:** Kiritilgan $N$ natural sonining barcha bo'luvchilarini ekranga chiqaring.
84. **Bo'luvchilar soni:** Kiritilgan $N$ natural sonining nechta bo'luvchisi borligini aniqlang.
85. **Bo'luvchilar yig'indisi:** Kiritilgan $N$ natural sonining barcha bo'luvchilari yig'indisini toping.

---

## IV BO'LIM: Murakkabroq va Mantiqiy Masalalar (86–100)
*Bu bo'limda sikl va shart operatorlari birgalikda qo'llaniladigan algoritmik masalalar jamlangan.*

86. **Tub sonni aniqlash:** Kiritilgan $N$ ($N > 1$) sonining tub yoki murakkab ekanligini aniqlang (faqat 1 ga va o'ziga bo'linadigan son tub deyiladi).
87. **Mukammal son:** Kiritilgan $N$ soni mukammal ekanligini tekshiring (o'zidan boshqa bo'luvchilari yig'indisi o'ziga teng bo'lgan son, masalan: $6 = 1 + 2 + 3$).
88. **Raqamlar sonini topish:** Kiritilgan ixtiyoriy musbat butun son necha xonali ekanligini aniqlang (`n = n / 10` amali orqali).
89. **Raqamlar yig'indisi:** Kiritilgan ixtiyoriy musbat butun sonning raqamlari yig'indisini toping (Masalan: 452 -> $4 + 5 + 2 = 11$).
90. **Raqamlar ko'paytmasi:** Kiritilgan ixtiyoriy musbat butun sonning raqamlari ko'paytmasini toping.
91. **Sonni teskari yozish:** Kiritilgan ixtiyoriy natural sonni teskari tartibda hosil qiling (Masalan: 1234 -> 4321).
92. **Palindrom son:** Kiritilgan son palindrom ekanligini tekshiring (o'ngdan ham, chapdan ham bir xil o'qiladigan son, masalan: 1221, 545).
93. **Son tarkibidagi juft raqamlar:** Kiritilgan sonning raqamlari orasida nechta juft raqam borligini aniqlang.
94. **Eng katta raqam:** Kiritilgan ixtiyoriy natural sonning eng katta raqamini toping (Masalan: 3825 -> 8).
95. **Fibonachchi sonlari:** Dastlabki $N$ ta Fibonachchi sonlarini ekranga chiqaring ($1, 1, 2, 3, 5, 8, 13, \dots$).
96. **EKUB (Evklid algoritmi):** Kiritilgan ikkita $A$ va $B$ natural sonlarining eng katta umumiy bo'luvchisini (EKUB) toping.
97. **EKUK:** Kiritilgan ikkita $A$ va $B$ sonlarining eng kichik umumiy karralisini (EKUK) toping ($\text{EKUK} = \frac{A \cdot B}{\text{EKUB}}$).
98. **Faktoriallar yig'indisi:** $1! + 2! + 3! + \dots + N!$ yig'indini hisoblang.
99. **Bank omonati:** Bankka $S$ so'm pul yillik $P\%$ ustama bilan qo'yildi. Necha yildan keyin omonat miqdori dastlabki summadan 2 barobar oshishini hisoblang.
100. **"Sonni top" o'yini:** Kompyuter 1 dan 100 gacha tasodifiy son o'ylaydi (`Random(100) + 1`). Foydalanuvchi son kiritadi, dastur "Kattaroq son kiriting" yoki "Kichikroq son kiriting" deb yordam beradi. Topilganda necha urinishda topganini ekranga chiqaradi.