Либо сдаем усложненное ДЗ 8 семинара - телефонный справочник в виде ТГ-бот / ГУИ / SQL.

Либо выбираете любой датасет, который вам интересен, и полностью его анализируете, с графиками.

Либо выполняем задачу 44.

Задача 44: В ячейке ниже представлен код генерирующий DataFrame, которая состоит всего из 1 столбца. Ваша задача перевести его в one hot вид. Надо сделать это без get_dummies.

import random
lst = ['robot'] * 10
lst += ['human'] * 10
random.shuffle(lst)
data = pd.DataFrame({'whoAmI':lst})
data.head()
