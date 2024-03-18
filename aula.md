### Comandos

Links: `ln backup.txt backup_link.txt`
```bash
/home/kleber # cat backup.txt
Arquivo backup
/home/kleber # cat backup_link.txt
Arquivo backup
```
Recuperar caracteres de uma frase: `echo "Kleber Alves" | cut -c 1-6`
```bash
Kleber
```
Recuperar dentro de um arquivo somente as siglas: `cat cidades.txt | cut -c 1-2`
```bash
PE
PB
RN
```

Recuperar dentro de um arquivo todo o conteudo(nesse caso): `cat cidades.txt | cut -c 1-25`
```bash
PE Pernambuco
PB Paraiba
RN Rio Grande do Norte
```