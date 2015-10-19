#include <stdio.h>
#include <string.h>
#include <math.h>

void hitung_3gelang() {

	int G1=0, G2=0, G3=0;
	int N=0;
	char WARNA[20];

	for (N=1; N<=3; N++) {
		//N menunjukan gelang ke N
		printf("Masukan warna GELANG ke %d: ", N);
		scanf("%s", WARNA);

		// if (WARNA == "hitam") { // INI SALAH
		if ( strcmp(WARNA, "hitam") == 0 ) { //=0 berarti sama
			 switch (N) {
				case 1: G1 = 0; break;
				case 2: G2 = 0; break;
				case 3: G3 = 0; break;
			 }
		} else if ( strcmp(WARNA, "coklat") == 0 ) {
			 switch (N) {
				case 1: G1 = 1; break;
				case 2: G2 = 1; break;
				case 3: G3 = 1; break;
			 }
		} else if ( strcmp(WARNA, "merah") == 0 ) {
			 switch (N) {
				case 1: G1 = 2; break;
				case 2: G2 = 2; break;
				case 3: G3 = 2; break;
			 }
		} else if ( strcmp(WARNA, "orange") == 0 ) {
			 switch (N) {
				case 1: G1 = 3; break;
				case 2: G2 = 3; break;
				case 3: G3 = 3; break;
			 }
		} else if ( strcmp(WARNA, "kuning") == 0 ) {
			 switch (N) {
				case 1: G1 = 4; break;
				case 2: G2 = 4; break;
				case 3: G3 = 4; break;
			 }
		} else if ( strcmp(WARNA, "hijau") == 0 ) {
			 switch (N) {
				case 1: G1 = 5; break;
				case 2: G2 = 5; break;
				case 3: G3 = 5; break;
			 }
		} else if ( strcmp(WARNA, "biru") == 0 ) {
			 switch (N) {
				case 1: G1 = 6; break;
				case 2: G2 = 6; break;
				case 3: G3 = 6; break;
			 }
		} else if ( strcmp(WARNA, "ungu") == 0 ) {
			 switch (N) {
				case 1: G1 = 7; break;
				case 2: G2 = 7; break;
				case 3: G3 = 7; break;
			 }
		} else if ( strcmp(WARNA, "abu-abu") == 0 ) {
			 switch (N) {
				case 1: G1 = 8; break;
				case 2: G2 = 8; break;
				case 3: G3 = 8; break;
			 }
		} else if ( strcmp(WARNA, "putih") == 0 ) {
			 switch (N) {
				case 1: G1 = 9; break;
				case 2: G2 = 9; break;
				case 3: G3 = 9; break;
			 }
		} else if ( strcmp(WARNA, "emas") == 0 ) {
			 switch (N) {
				case 1: G1 = 0; break;
				case 2: G2 = 0; break;
				case 3: G3 = 0; break;
			 }
		} else if ( strcmp(WARNA, "perak") == 0 ) {
			 switch (N) {
				case 1: G1 = 0; break;
				case 2: G2 = 0; break;
				case 3: G3 = 0; break;
			 }
		} else if ( strcmp(WARNA, "tidak berwarna") == 0 ) {
			 switch (N) {
				case 1: G1 = 0; break;
				case 2: G2 = 0; break;
				case 3: G3 = 0; break;
			 }
		}
		// dibuat untuk 12 warna
	} // akhir loop N

	//G1 G2 G3 ?
  //(G1*10 + G2) * pow(10,G3); //
	//(G1*10 + G2) * exp(G3);

	N = (G1*10 + G2) * pow(10,G3);

	// printf("\nG1=%d , G2=%d, G3=%d \n", G1,G2,G3 );
	printf("\nNilai resistor R = %d ohm", N );

}
void hitung_4gelang() {

	int G1=0, G2=0, G3=0, G4=0;
	int N=0;
	char WARNA[20];
	char PERSEN = '%';

	for (N=1; N<=4; N++) {
		//N menunjukan gelang ke N
		//TAMPILKAN DAFTAR WARNA DI SINI
		printf("Masukan warna GELANG ke %d: ", N);
		scanf("%s", WARNA);

		// if (WARNA == "hitam") { // INI SALAH
		if ( strcmp(WARNA, "hitam") == 0 ) { //=0 berarti sama
			 switch (N) {
				case 1: G1 = 0; break;
				case 2: G2 = 0; break;
				case 3: G3 = 0; break;
				case 4: G4 = 1; break;
			 }
		} else if ( strcmp(WARNA, "coklat") == 0 ) {
			 switch (N) {
				case 1: G1 = 1; break;
				case 2: G2 = 1; break;
				case 3: G3 = 1; break;
				case 4: G4 = 2; break;  //toleransi coklat tidak ada
			 }
		} else if ( strcmp(WARNA, "merah") == 0 ) {
			 switch (N) {
				case 1: G1 = 2; break;
				case 2: G2 = 2; break;
				case 3: G3 = 2; break;
				case 4: G4 = 3; break;  //toleransi coklat tidak ada
			 }
		} else if ( strcmp(WARNA, "orange") == 0 ) {
			 switch (N) {
				case 1: G1 = 3; break;
				case 2: G2 = 3; break;
				case 3: G3 = 3; break;
				case 4: G4 = 4; break;  //toleransi coklat tidak ada
			 }
		}  else if ( strcmp(WARNA, "kuning") == 0 ) {
			 switch (N) {
				case 1: G1 = 4; break;
				case 2: G2 = 4; break;
				case 3: G3 = 4; break;
				case 4: G4 = 5; break;  //toleransi coklat tidak ada
			 }
		}  else if ( strcmp(WARNA, "hijau") == 0 ) {
			 switch (N) {
				case 1: G1 = 5; break;
				case 2: G2 = 5; break;
				case 3: G3 = 5; break;
				case 4: G4 = 6; break;  //toleransi coklat tidak ada
			 }
		}  else if ( strcmp(WARNA, "biru") == 0 ) {
			 switch (N) {
				case 1: G1 = 6; break;
				case 2: G2 = 6; break;
				case 3: G3 = 6; break;
				case 4: G4 = 7; break;  //toleransi coklat tidak ada
			 }
		}  else if ( strcmp(WARNA, "ungu") == 0 ) {
			 switch (N) {
				case 1: G1 = 7; break;
				case 2: G2 = 7; break;
				case 3: G3 = 7; break;
				case 4: G4 = 8; break;  //toleransi coklat tidak ada
			 }
		}  else if ( strcmp(WARNA, "abu-abu") == 0 ) {
			 switch (N) {
				case 1: G1 = 8; break;
				case 2: G2 = 8; break;
				case 3: G3 = 8; break;
				case 4: G4 = 9; break;  //toleransi coklat tidak ada
			 }
		}  else if ( strcmp(WARNA, "putih") == 0 ) {
			 switch (N) {
				case 1: G1 = 9; break;
				case 2: G2 = 9; break;
				case 3: G3 = 9; break;
				case 4: G4 = 10; break;  //toleransi coklat tidak ada
			 }
		}  else if ( strcmp(WARNA, "emas") == 0 ) {
			 switch (N) {
				case 4: G4 = 5; break;  //toleransi coklat tidak ada
			 }
		}  else if ( strcmp(WARNA, "perak") == 0 ) {
			 switch (N) {
				case 4: G4 = 10; break;  //toleransi coklat tidak ada
			 }
		}  else if ( strcmp(WARNA, "tidak berwarna") == 0 ) {
			 switch (N) {
				case 4: G4 = 20; break;  //toleransi coklat tidak ada
			 }
		}
		// dibuat untuk 12 warna
	} // akhir loop N

	//G1 G2 G3 ?
  //(G1*10 + G2) * pow(10,G3); //
	//(G1*10 + G2) * exp(G3);

	N = (G1*10 + G2) * pow(10,G3);

	// printf("\nG1=%d , G2=%d, G3=%d G4=%d \n", G1,G2,G3, G4 );
	printf("\nNilai resistor R = %d ohm", N );
	printf("\nNilai Toleransi = %d %c", G4, PERSEN );
}

void hitung_5gelang() {

	int G1=0, G2=0, G3=0, G4=0, G5=0;
	int N=0;
	char WARNA[20];
	char PERSEN = '%';


	for (N=1; N<=5; N++) {
		//N menunjukan gelang ke N
		//TAMPILKAN DAFTAR WARNA DI SINI
		printf("Masukan warna GELANG ke %d: ", N);
		scanf("%s", WARNA);

		// if (WARNA == "hitam") { // INI SALAH
		if ( strcmp(WARNA, "hitam") == 0 ) { //=0 berarti sama
			 switch (N) {
				case 1: G1 = 0; break;
				case 2: G2 = 0; break;
				case 3: G3 = 0; break;
				case 4: G4 = 0; break;
				case 5: G5 = 1; break;
			 }
		} else if ( strcmp(WARNA, "coklat") == 0 ) {
			 switch (N) {
				case 1: G1 = 1; break;
				case 2: G2 = 1; break;
				case 3: G3 = 1; break;
				case 4: G4 = 1; break;
				case 5: G5 = 2; break;  //toleransi coklat tidak ada
			 }
		} else if ( strcmp(WARNA, "merah") == 0 ) {
			 switch (N) {
				case 1: G1 = 2; break;
				case 2: G2 = 2; break;
				case 3: G3 = 2; break;
				case 4: G4 = 2; break;
				case 5: G5 = 3; break;  //toleransi coklat tidak ada
			 }
		} else if ( strcmp(WARNA, "orange") == 0 ) {
			 switch (N) {
				case 1: G1 = 3; break;
				case 2: G2 = 3; break;
				case 3: G3 = 3; break;
				case 4: G4 = 3; break;
				case 5: G5 = 4; break;  //toleransi coklat tidak ada
			 }
		}  else if ( strcmp(WARNA, "kuning") == 0 ) {
			 switch (N) {
				case 1: G1 = 4; break;
				case 2: G2 = 4; break;
				case 3: G3 = 4; break;
				case 4: G4 = 4; break;
				case 5: G5 = 5; break;  //toleransi coklat tidak ada
			 }
		}  else if ( strcmp(WARNA, "hijau") == 0 ) {
			 switch (N) {
				case 1: G1 = 5; break;
				case 2: G2 = 5; break;
				case 3: G3 = 5; break;
				case 4: G4 = 5; break;
				case 5: G5 = 0.5; break;  //toleransi coklat tidak ada
			 }
		}  else if ( strcmp(WARNA, "biru") == 0 ) {
			 switch (N) {
				case 1: G1 = 6; break;
				case 2: G2 = 6; break;
				case 3: G3 = 6; break;
				case 4: G4 = 6; break;
				case 5: G5 = 0.25; break;  //toleransi coklat tidak ada
			 }
		}  else if ( strcmp(WARNA, "ungu") == 0 ) {
			 switch (N) {
				case 1: G1 = 7; break;
				case 2: G2 = 7; break;
				case 3: G3 = 7; break;
				case 4: G4 = 7; break;
				case 5: G5 = 0.10; break;  //toleransi coklat tidak ada
			 }
		}  else if ( strcmp(WARNA, "abu-abu") == 0 ) {
			 switch (N) {
				case 1: G1 = 8; break;
				case 2: G2 = 8; break;
				case 3: G3 = 8; break;
				case 4: G4 = 8; break;
				case 5: G5 = 0.05; break;  //toleransi coklat tidak ada
			 }
		}  else if ( strcmp(WARNA, "putih") == 0 ) {
			 switch (N) {
				case 1: G1 = 9; break;
				case 2: G2 = 9; break;
				case 3: G3 = 9; break;
				case 4: G4 = 9; break;
				case 5: G5 = 0.025; break;  //toleransi coklat tidak ada
			 }
		}  else if ( strcmp(WARNA, "emas") == 0 ) {
			 switch (N) {
				case 5: G5 = 5; break;  //toleransi coklat tidak ada
			 }
		}  else if ( strcmp(WARNA, "perak") == 0 ) {
			 switch (N) {
				case 5: G5 = 10; break;  //toleransi coklat tidak ada
			 }
		}  else if ( strcmp(WARNA, "tidak berwarna") == 0 ) {
			 switch (N) {
				case 5: G5 = 20; break;  //toleransi coklat tidak ada
			 }
		}
		// dibuat untuk 12 warna
	} // akhir loop N

	//G1 G2 G3 ?
  //(G1*10 + G2) * pow(10,G3); //
	//(G1*10 + G2) * exp(G3);

	N = (G1*100 + G2 + G3) * pow(10,G4);

	// printf("\nG1=%d , G2=%d, G3=%d G4=%d \n", G1,G2,G3, G4 );
	printf("\nNilai resistor R = %d ohm", N );
	printf("\nNilai Toleransi = %d %c", G5, PERSEN );
  //ridho surya kusuma yeah

}

void hitung_6gelang() {

	int G1=0, G2=0, G3=0, G4=0, G5=0, G6=0;
	int N=0;
	char WARNA[20];
	char PERSEN = '%';

	for (N=1; N<=6; N++) {
		//N menunjukan gelang ke N
		//TAMPILKAN DAFTAR WARNA DI SINI
		printf("Masukan warna GELANG ke %d: ", N);
		scanf("%s", WARNA);

		// if (WARNA == "hitam") { // INI SALAH
		if ( strcmp(WARNA, "hitam") == 0 ) { //=0 berarti sama
			 switch (N) {
				case 1: G1 = 0; break;
				case 2: G2 = 0; break;
				case 3: G3 = 0; break;
				case 4: G4 = 0; break;
				case 5: G5 = 1; break;
				case 6: G6 = 100; break;
			 }
		} else if ( strcmp(WARNA, "coklat") == 0 ) {
			 switch (N) {
				case 1: G1 = 1; break;
				case 2: G2 = 1; break;
				case 3: G3 = 1; break;
				case 4: G4 = 1; break;
				case 5: G5 = 2; break;  //toleransi coklat tidak ada
				case 6: G6 = 50; break;
			 }
		} else if ( strcmp(WARNA, "merah") == 0 ) {
			 switch (N) {
				case 1: G1 = 2; break;
				case 2: G2 = 2; break;
				case 3: G3 = 2; break;
				case 4: G4 = 2; break;
				case 5: G5 = 3; break;  //toleransi coklat tidak ada
				case 6: G6 = 15; break;
			 }
		} else if ( strcmp(WARNA, "orange") == 0 ) {
			 switch (N) {
				case 1: G1 = 3; break;
				case 2: G2 = 3; break;
				case 3: G3 = 3; break;
				case 4: G4 = 3; break;
				case 5: G5 = 4; break;  //toleransi coklat tidak ada
				case 6: G6 = 25; break;
			 }
		}  else if ( strcmp(WARNA, "kuning") == 0 ) {
			 switch (N) {
				case 1: G1 = 4; break;
				case 2: G2 = 4; break;
				case 3: G3 = 4; break;
				case 4: G4 = 4; break;
				case 5: G5 = 5; break;  //toleransi coklat tidak ada
				case 6: G6 = 0; break;
			 }
		}  else if ( strcmp(WARNA, "hijau") == 0 ) {
			 switch (N) {
				case 1: G1 = 5; break;
				case 2: G2 = 5; break;
				case 3: G3 = 5; break;
				case 4: G4 = 5; break;
				case 5: G5 = 0.5; break;  //toleransi coklat tidak ada
				case 6: G6 = 0; break;
			 }
		}  else if ( strcmp(WARNA, "biru") == 0 ) {
			 switch (N) {
				case 1: G1 = 6; break;
				case 2: G2 = 6; break;
				case 3: G3 = 6; break;
				case 4: G4 = 6; break;
				case 5: G5 = 0.25; break;  //toleransi coklat tidak ada
				case 6: G6 = 0; break;
			 }
		}  else if ( strcmp(WARNA, "ungu") == 0 ) {
			 switch (N) {
				case 1: G1 = 7; break;
				case 2: G2 = 7; break;
				case 3: G3 = 7; break;
				case 4: G4 = 7; break;
				case 5: G5 = 0.10; break;  //toleransi coklat tidak ada
				case 6: G6 = 0; break;
			 }
		}  else if ( strcmp(WARNA, "abu-abu") == 0 ) {
			 switch (N) {
				case 1: G1 = 8; break;
				case 2: G2 = 8; break;
				case 3: G3 = 8; break;
				case 4: G4 = 8; break;
				case 5: G5 = 0.05; break;  //toleransi coklat tidak ada
				case 6: G6 = 0; break;
			 }
		}  else if ( strcmp(WARNA, "putih") == 0 ) {
			 switch (N) {
				case 1: G1 = 9; break;
				case 2: G2 = 9; break;
				case 3: G3 = 9; break;
				case 4: G4 = 9; break;
				case 5: G5 = 0.025; break;  //toleransi coklat tidak ada
				case 6: G6 = 0; break;
			 }
		}  else if ( strcmp(WARNA, "emas") == 0 ) {
			 switch (N) {
				case 5: G5 = 5; break;  //toleransi coklat tidak ada
				case 6: G6 = 0; break;
			 }
		}  else if ( strcmp(WARNA, "perak") == 0 ) {
			 switch (N) {
				case 5: G5 = 10; break;  //toleransi coklat tidak ada
				case 6: G6 = 0; break;
			 }
		}  else if ( strcmp(WARNA, "tidak berwarna") == 0 ) {
			 switch (N) {
				case 5: G5 = 20; break;  //toleransi coklat tidak ada
				case 6: G6 = 0; break;
			 }
		}
		// dibuat untuk 12 warna
	} // akhir loop N

	//G1 G2 G3 ?
  //(G1*10 + G2) * pow(10,G3); //
	//(G1*10 + G2) * exp(G3);

	N = (G1*100 + G2 + G3) * pow(10,G4);

	// printf("\nG1=%d , G2=%d, G3=%d G4=%d \n", G1,G2,G3, G4 );
	printf("\nNilai resistor R = %d ohm", N );
	printf("\nNilai Toleransi = %d %c", G5, PERSEN );
	printf("\nNilai Temperatur = %d ppm", G6);
}

int main() {

	//input JUMLAH GELANG
	int GELANG = 0;

	while ( (GELANG<3) || (GELANG>6) ) {  //pengulangan dampai data GELANG BETUL
		printf("Masukan jumlah gelang : ");
		scanf("%d", &GELANG ); //harus antara 3 s/d 6

		if ( (GELANG<3) || (GELANG>6) ) {
			printf("\n---------------------------");
			printf("\nNilai GELANG antara 3 s/d 6");
		  printf("\n---------------------------\n");
		}

		//Input WARNA GELANG

		if (GELANG == 3) {
			//di sini program menghitung 3 gelang
			hitung_3gelang();
		} else if (GELANG == 4) {
			//di sini program menghitung 4 gelang
			hitung_4gelang();
		} else if (GELANG == 5) {
			//di sini program menghitung 5 gelang
			hitung_5gelang();

		} else if (GELANG == 6) {
			//di sini program menghitung 6 gelang
			hitung_6gelang();
		}

		//cara kedua
		/*
		switch (GELANG) {
			case 3 : ; //di sini program menghitung 3 gelang
							break;
			case 4 : ; //di sini program menghitung 4 gelang
							break;
			case 5 : ; //di sini program menghitung 5 gelang
							break;
			case 6 : ; //di sini program menghitung 6 gelang
							break;
		}
		*/
	}

	return 0;
}
