hey: one two
	# Target name
	echo $@

	# All prerequisites newer than the target
	echo $?

	# Outputs all prerequisites
	echo $^

	# Outputs first prerequisite
	echo $<

	touch hey

one:
	touch one

two:
	touch two

clean:
	rm -f hey one two