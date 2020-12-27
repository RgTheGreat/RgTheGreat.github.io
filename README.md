# RgTheGreat.github.io

## welcome to rgthegreat.github.io (blog)


### here are some things you can create using python

 ``py term``
 
 ## here is the code, it doesn't know real python commands but only calculation>>>


#### the input textarea and if the person types exit the app or code will close(not forever)
 ``while 1:
	x = input(">>> ")
	if x == 'exit':
		break		
``

## here is the rest>>>
``	try:
		y = eval(x)
		if y: print(y)
	except:
		try:
			exec(x)
		except Exception as e:
			print("Syntas or spelling error :( :", e)
	``
