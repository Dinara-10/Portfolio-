Обязательные переменные:

1) money – стартовое количество денежных единиц ( 100 000 )
2) start – дата старта временного интервала ( 2018-1-1 )
3) finish – дата финиша временного интервала ( 2018-12-31 )
4) stop_loss – в процентах (5%)
5) fast_window – размер быстрого скользящего окна (30 торговых свечей)
6) slow_window – размер медленного скользящего окна (90 торговых свечей) в окнах считаем простое скользящее среднее

Используем часовые временные интервалы.

Исходные данные имеют вид Pandas DataFrame:

- индексы – объект дата/время
- колонки – Open, High, Low, Close

Обязательно использовать реальные часовые данные стоимости акций с бирж, например нью-йоркской или московской за 1 год.

Торговая система строится в НЕкоммерческой версии Vector bt https://vectorbt.dev
