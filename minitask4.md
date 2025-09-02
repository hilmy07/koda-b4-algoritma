# Menentukan Angka Ganjil dan Genap

```mermaid
flowchart TD;

strt((start))-->a[/Angka/];
a[/Angka/]-->dcs{hasil=0};
dcs{Angka%2=0?}--ya-->gnp[/"genap"/];
dcs{Angka%2=0?}--tidak-->gan[/"ganjil"/];
gnp[/"genap"/]-->stp(((stop)));
gan[/"ganjil"/]-->stp(((stop)));

```
