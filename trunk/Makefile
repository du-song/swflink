swflink: swflink.c
	gcc -g -c -DHAVE_CONFIG_H -I${SWFTOOLS}/src -fPIC -Wparentheses -Wimplicit -Wreturn-type -O -fomit-frame-pointer swflink.c -o swflink.o
	gcc -g -DHAVE_CONFIG_H swflink.o -o swflink ${SWFTOOLS}/lib/librfxswf.a ${SWFTOOLS}/lib/libbase.a -lz -lm 

clean:
	rm -f swflink.o swflink
