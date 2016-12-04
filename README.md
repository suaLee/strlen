# strlen

#include <stdio.h> 

int strlen(char *p){
	char *s = p;
	while (*p != 0) {
		p++;
	}
	return p - s;
}

int main() {

	char *strr = "hello";

	int len=strlen(strr);
	printf("%d", len);

	return 0;
}
