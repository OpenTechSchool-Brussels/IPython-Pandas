
all: Intro.slides.html

clean:
	rm *.slides.html

Intro.slides.html: ../notebooks/Intro.ipynb
	ipython nbconvert --to slides ../notebooks/Intro.ipynb

