rebuild:
	rm -rf *.html chunked.*
	rm -rf vulkan.docset
	rm -rf Vulkan.tgz
	wget --recursive --no-parent --no-directories https://renderdoc.org/vkspec_chunked/index.html
	dashing build
	tar --exclude='Makefile' --exclude='.DS_Store' -cvzf Vulkan.tgz vulkan.docset

