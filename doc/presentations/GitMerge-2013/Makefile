all: html

html: talk.html

talk.html: talk.rst
	rst2s5 --theme=small-white --stylesheet=html4css1.css,override.css --current-slide $< $@
	#sed '//' ui/small-white/slides.js

clean:
	rm -fr talk.html ui/small-white/
