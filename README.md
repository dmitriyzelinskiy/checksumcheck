# checksumcheck
Checksum comparison bash script.

Usefull for a single file and a provided hash.

Uses [shasum](https://linux.die.net/man/1/shasum) - Print or Check SHA Checksums

## USE
checksumcheck *file* *checksum* [*ALGORITHM*]

*ALGORITHM*=[ 1 (default), 224, 256, 384, 512, 512224, 512256 ]

## EXAMPLE
```bash
checksumcheck ~/downloads/document.pdf 89b8ded93ebf6664c441ecc13e0df458de58cc85

>>> Checksum of a file matches provided checksum
>>> file checksum: 89b8ded93ebf6664c441ecc13e0df458de58cc85
>>> compare with:  89b8ded93ebf6664c441ecc13e0df458de58cc85
```
