# Menentukan Angka Ganjil dan Genap

```mermaid
flowchart TD;

strt((start))-->a[/Angka/];
a[/Angka/]-->dcs{hasil=0};
dcs{Angka%2=0?}--ya-->genap;
dcs{Angka%2=0?}--tidak-->ganjil;
genap-->stp(((stop)));
ganjil-->stp(((stop)));

```
