
Halong20: Halong20.occ nodes-test-include.occ
	kroc -lcourse Halong20.occ

cinema: Halong20
	./Halong20
	ffmpeg -i image%d.ppm cinema.mp4

clean:
	rm -f  image* cinem* Halong20


