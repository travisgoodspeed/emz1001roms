all: check


rom20x.txt: rom20x.bmp rom20x.bmp.json
	maskromtool rom20x.bmp -a rom20x.txt -platform offscreen -e
rom20x.bin: rom20x.txt
	false
check: rom20x.bin
#	echo '32fbbd84168d3482956eb3c5051637f5  rom20x.bin' | md5sum -c
	false

clean:
	rm -f rom20x.txt rom20x.bin
