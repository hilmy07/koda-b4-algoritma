# Menentukan Angka Ganjil dan Genap

```mermaid
flowchart TD;

strt((start))-->a[/Angka/];
a[/Angka/]-->Angka%2;
Angka%2-->dcs{hasil=0};
dcs{hasil=0}--ya-->genap;
dcs{hasil=0}--tidak-->ganjil;
genap-->stp(((stop)));
ganjil-->stp(((stop)));

```
