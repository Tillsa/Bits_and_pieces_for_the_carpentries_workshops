pdf:
	pandoc \
          --pdf-engine xelatex \
	  --variable mainfont="DejaVu Sans" \
	  --variable sansfont="DejaVu Sans" \
          -V geometry:"top=3cm, bottom=3cm, left=3.2cm, right=3.2cm" \
	  -V fontsize=11pt \
          -V papersize:a4 \
	  -o python_de.pdf \
	  python_de.md

clean:
	rm -f *pdf *~
