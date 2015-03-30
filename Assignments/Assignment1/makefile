READ = evince
COMP = pdflatex
NUM  = 1

ass$(NUM).pdf: ass$(NUM).tex unswmaths.cls unswshortcuts.sty
	$(COMP) $<

	
read: ass$(NUM).pdf
	$(READ) $^

spell: ass$(NUM).tex
	ispell $<

ques: assignment$(NUM).pdf
	$(READ) $<

clean:
	rm -f *.log *.aux *~

tea:	
	@echo "Earl Grey. Hot."
