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

Diferenças entre atquivos: `diff cidades.txt estados.txt`
```bash
--- cidades.txt
+++ estados.txt
@@ -1,3 +1,5 @@
 PE Pernambuco
 PB Paraiba
 RN Rio Grande do Norte
+AL Alagoas
+SE Sergipe
```

Adicionando dados no arquivo: `patch -p0 cidades.txt estados.txt`

Mostra uma lista de users criados: `cat /etc/passwd` 

Mostra uma lista de grupos criados: `cat /etc/group`

Caminhos da variável $PATH: `echo $PATH`

Adicionar caminho a variável PATH: `PATH=/root/backup`

Saber o nome do host: `hostname`

Saber o endereço IP: `ifconfig` ou `ip addr show`

Comando ping: `ping www.google.com.bkr`

Ver informações de um dominio: `nslookup www.sportrecife.com.br`

Traçar caminho até um dominio: `traceroute www.sportrecife.com.br`

Rastrear as portas utilizadas: `netstat -s`

Tabela de roteamento: `netstast -rn`

Testar comunicação: `telnet 0.0.0.0 90`