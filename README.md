# DZ-14  Задача "Распаковка":

def print_params(a = 2, b = 'строка', c = True):
     print(a, b, c)


values_list = [777, None, 'Текст']
values_dict = {'a':12.24, 'b':"Москва", 'c':False}
print_params(*values_list)
print_params(**values_dict)
values_list_2 = [54.32, 'Строка']
print_params(*values_list_2,42)

# Вывод на консоль:
#777 None Текст
#12.24 Москва False
#54.32 Строка 42
