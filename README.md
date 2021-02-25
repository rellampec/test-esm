**Tesging ESM Loader**

## test-esm

  * This repo only purpose is to have a basic example on how to load ES Modules.

## Installation

```
~/tmp$ mkdir test-ems && cd test-esm
~/tmp/test-esm$ git clone https://github.com/rellampec/test-esm.git .
~/tmp/test-esm$ npm install
```

You will need to download at least one Hunspell dictionary. Besides the one in the example, you can check links to other dictioanries in [FreeOffice Dictionaries](https://www.freeoffice.com/en/download/dictionaries).

```
~/tmp/test-esm$
~/tmp/test-esm$ mkdir dictionaries && cd dictionaries
~/tmp/test-esm/dictionaries$ curl https://www.softmaker.net/down/hunspell/softmaker-hunspell-english-nz-101.sox > en_NZ.sox
~/tmp/test-esm/dictionaries$ unzip en_NZ.sox en_NZ.aff en_NZ.dic
```
