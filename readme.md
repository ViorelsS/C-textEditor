# Custom text exitor in C

Following the guide on `https://viewsourcecode.org/snaptoken/kilo/index.html`

```Makefile
term: term.c
	$(CC) term.c -o term -Wall -Wextra -pedantic -std=c99
	# -Wall: Enable all warnings
	# -Wextra: Enable extra warnings
	# -pedantic: Enable extra warnings for non-standard code
	# -std=c99: Use the C99 standard
```
