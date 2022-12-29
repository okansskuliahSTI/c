#include <stdio.h>
using namespace std;
int main(void)
{
	char nama[100], npm[100], jurusan[100],ttl[100];
	
	printf("Nama : ");
    gets(nama);
    printf("NPM : ");
    gets(npm);
    printf("Jurusan : ");
    gets(jurusan);
    printf("Tempat & Tanggal Lahir : ");
    gets(ttl);
    printf("\nOUTPUT\n");
    printf("Nama : %s\n", nama);
     printf("NPM : %s\n", npm);
      printf("Jurusan : %s\n", jurusan);
       printf("Tempat & Tanggal Lahir : %s\n", ttl);
	return 0;
}
