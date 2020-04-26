# python3

def make_car(manufacturer, model_name, **information):
	"""build a dictionary containing everything we know about a car. """
	car = { }
	car['maker'] = manufacturer
	car['type'] = model_name
	for key,value in information.items():
		car[key] = value
	return car
	
detail_of_car = make_car('toyota','camry',
									 colour = 'black',
									 year = 1993)
print(detail_of_car)

