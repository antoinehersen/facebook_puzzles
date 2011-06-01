all:
	ghc -O3 --make Main.hs -o meepmeep

clean:
	rm -f *.hi *.o meepmeep *.tar

tar: clean
	tar -cf meepmeep.tar *