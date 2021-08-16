# bc_key
_Bitcoin Private Key Extractor_

# changes
- This is a modified version of [bc_key](https://github.com/halfinney/bc_key.git) for windows.

# prerequisites:

- [openssl-1.0.2u](https://ftp.openssl.org/source/old/1.0.2/)
- [db-18.1.40](https://www.oracle.com/database/technologies/related/berkeleydb-downloads.html)
- [fmemopen_windows](https://github.com/Arryboom/fmemopen_windows.git)

All the required libs are included with project.
# compiling:

- Microsoft Visual Studio Community 2019 

# usage:
```
bc_key BITCOIN_ADDRESS /path/to/wallet.dat
bc_key ALL /path/to/wallet.dat
bc_key EVERYTHING /path/to/wallet.dat
```
