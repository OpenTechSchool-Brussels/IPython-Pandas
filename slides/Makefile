
all: Intro.slides.html Pandas.slides.html Intro.html Pandas.html

clean:
	rm *.slides.html
	rm *.html

Intro.slides.html: ../notebooks/Intro.ipynb
	../venv/bin/ipython nbconvert --to slides ../notebooks/Intro.ipynb

Pandas.slides.html: ../notebooks/Pandas.ipynb
	../venv/bin/ipython nbconvert --to slides ../notebooks/Pandas.ipynb

Intro.html: ../notebooks/Intro.ipynb
	../venv/bin/ipython nbconvert --to html ../notebooks/Intro.ipynb

Pandas.html: ../notebooks/Pandas.ipynb
	../venv/bin/ipython nbconvert --to html ../notebooks/Pandas.ipynb
