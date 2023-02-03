## Project description
 
Change the sequence of strings after base64 encryption

## Install

```
pip install venus-py-tools
```

## Usage

```
from venus-py-tools import eds_un_re_index as eds2

enc_str = 'VmVudXM='

# rebuild_indexReplace A with Z(lowercase and so on) and 0 with 9...
re_enc_str = eds2.rebuild_index(enc_str) 

print(re_enc_str) # EnEfwCN=

```



This is a simple package. There are still many imperfections.

Please give us your advice. I wish you all the best.
