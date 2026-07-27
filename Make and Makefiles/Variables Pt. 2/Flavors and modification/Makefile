# Recursive variable. This will print "later" below
one = one ${later_variable}
# Expands only stuff thats defined now basically
# Simply expanded variable. This will not print "later" below
two := two ${later_variable}

later_variable = later

all: 
	echo $(one)
	echo $(two)