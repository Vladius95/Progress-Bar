This is an example for using. The first argument determines a message that is output in the console. The second argument is the list that is passed to a function. One execution of function is one iteration.

def test(par):
	#doing
	import time
	time.sleep(1.5)

for i in ProgressBar('Something is doing', [i for i in range(56)]):
	test(i)

#console: Something is doing [####------] 42.86%
