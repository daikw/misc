hey: one two three
	echo $@ # hey
	echo $? # prerequisites, newer than the target
	echo $^ # all prerequisites
	touch hey

one:
	touch one
two:
	touch two
three:
	touch three

clean:
	rm -f one two three hey

