
all: Intro.slides.html \
    Pandas.slides.html

clean:
	rm *.slides.html

Intro.slides.html: ../notebooks/Intro.ipynb
	../venv/bin/ipython nbconvert --to slides ../notebooks/Intro.ipynb

Pandas.slides.html: ../notebooks/Pandas.ipynb
	../venv/bin/ipython nbconvert --to slides ../notebooks/Pandas.ipynb
