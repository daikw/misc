files := file1 file2
others := f1 f2
some_files: $(files)
	echo "files are: " $(files)
	echo "others are: " ${others}
	touch some_file

file1:
	touch file1

file2:
	touch file2

clean:
	rm -f file1 file2 some_file

