# decimal_random

Проверка рандомности чисел генерируемых блокчейном.

Берем два блока, берем хэши, вычисляем суммарный хэш, из него делаем BigInteger, 
BigInteger делим по модулю на 12 и считаем сколько раз выпало число от 0 до 11б

