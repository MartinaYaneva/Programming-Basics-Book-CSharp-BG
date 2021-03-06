#### Създаване на методите

За да създадем този метод, първо трябва да създадем три други метода с едно и също име и различни сигнатури. Първо създаваме метод, който ще сравнява цели числа.

![](/assets/chapter-10-images/18.Greater-of-two-values-01.png)

Следвайки логиката от предходния метод, създаваме такъв със същото име, който обаче ще сравнява символи.

![](/assets/chapter-10-images/18.Greater-of-two-values-02.png)

Следващият метод, който трябва да създадем, ще сравнява низове. Тук логиката ще е малко по-различна, тъй като стойностите от тип **`string`** не позволяват да бъдат сравнявани чрез операторите **`<`** и **`>`**. Ще използваме метода **`CompareTo(…)`**, който връща числова стойност: по-голяма от 0 (сравняваният обект е по-голям), по-малка от 0 (сравняваният обект е по-малък) и 0 (при два еднакви обекта).

![](/assets/chapter-10-images/18.Greater-of-two-values-03.png)
