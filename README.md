# Local GC content variation in *S. coelicolor*

Project investigating the local GC content of the
*Streptomyces coelicolor* A3(2) genome.

Download the genome using ``curl``.

```
$ curl --location --output Sco.dna http://bit.ly/1Q8eKWT
```

Generate ``local_gc_content.csv`` file from ``Sco.dna`` file.

```
$ python dna2csv.py
```

Generate ``local_gc_content.png`` file from ``local_gc_content.csv`` file.

```
$ Rscript csv2png.R
```
