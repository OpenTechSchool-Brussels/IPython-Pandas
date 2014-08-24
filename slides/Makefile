
all: Intro.slides.html

clean:
	rm *.slides.html

Intro.slides.html: ../notebooks/Intro.ipynb
	../venv/bin/ipython nbconvert --to slides ../notebooks/Intro.ipynb

