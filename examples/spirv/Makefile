rebuild:
	rm -rf SPIRV.html
	wget https://www.khronos.org/registry/spir-v/specs/unified1/SPIRV.html
	dashing build
	tar --exclude='Makefile' --exclude='.DS_Store' -cvzf SPIRV.tgz spirv.docset

