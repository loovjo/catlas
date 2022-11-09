# catlas - coral & awagga transport layer in APL succinctly

requires dfns in root.

structure:
* common utilities (`foldl`, `scanl`, `xor`) in root
* `aes/` aes stuff

## how 2 run:

```apl
]LINK.Create catlas APL/catlas -source=dir -watch=both
⎕CY'dfns'

⎕←'meow'
⍝ TODO: this doesn't work lmao
⎕←#.hex(16⍴0)#.catlas.aes.aes(16⍴0)
```
