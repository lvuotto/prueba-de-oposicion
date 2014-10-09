#FIGS=halfadder.pdf fulladder.pdf halfadder-nand.pdf fulladder-nand.pdf
FIGS=sumador-simple.pdf \
     sumador-completo.pdf sumador-completo-1.pdf sumador-completo-2.pdf \
     sumador-completo-nand.pdf sumador-completo-nand-1.pdf \
     sumador-completo-nand-2.pdf sumador-completo-nand-opt.pdf

po.pdf: po.tex $(FIGS)
	pdflatex $<

po-entregable.pdf: po-entregable.tex $(FIGS)
	pdflatex $<
