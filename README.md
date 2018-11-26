def get_summ(one, two, delimiter='&'):
	return str(one) + str (delimiter) + str(two)
	
	
sum_string = get_summ('Learn', 'python')
print(sum_string.upper())


def format_price(price):
	a = int(price)
	return 'Цена: ' + str(a) + ' руб.'
	
	
display_price = format_price(56.24)
print(display_price)
