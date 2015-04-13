# js_dictionary

Dictionary for JS primitive obfuscation.

## Building Blocks ###

* ***stringify object (not always works)*** ''+*object*
* **true** !''
* **false** ![]
* **NaN** !''+''['']
* **undefined** ''['']
* **"[object Object]"** ({}+'')
* **null** 
* **Infinity** (!''|!{})/(![]|!{})

### Characters ###

* **a** (''+(!''+''['']))[!''|!{}]
* b
* c
* d
* **e** (''+!'')[(!''|!{})+(!''|!{})+(!''|!{})]
* f
* g
* h
* i
* j
* k
* l
* m
* n
* o
* p
* q
* **r** (''+!'')[!''|!{}]
* s
* **t** (''+!'')[![]|!{}]
* **u** (''+!'')[(!''|!{})+(!''|!{})]
* v
* w
* x
* y
* z
* A
* B
* C
* D
* E
* F
* G
* H
* I
* J
* K
* L
* M
* **N** (''+(!''+''['']))[![]|!{}]
* O
* P
* Q
* R
* S
* T
* U
* V
* W
* X
* Y
* Z
* **[** ({}+'')[![]|!{}]
* **]** ({}+[])[(((!''|!{})+(!''|!{})+(!''|!{}))*((!''|!{})+(!''|!{}))+(!''|!{}))*((!''|!{})+(!''|!{}))]

### Numbers ###

* **0** ![]|!{}
* **1** !''|!{}
* **2** (!''|!{})+(!''|!{})
* **3** (!''|!{})+(!''|!{})+(!''|!{})
* **4** ((!''|!{})+(!''|!{}))*((!''|!{})+(!''|!{}))
* **5** ((!''|!{})+(!''|!{})+(!''|!{}))*((!''|!{})+(!''|!{}))-(!''|!{})
* **6** ((!''|!{})+(!''|!{})+(!''|!{}))*((!''|!{})+(!''|!{}))
* **7** ((!''|!{})+(!''|!{})+(!''|!{}))*((!''|!{})+(!''|!{}))+(!''|!{})
* **8** (!''|!{})<<((!''|!{})+(!''|!{})+(!''|!{}))
* **9** ((!''|!{})+(!''|!{})+(!''|!{}))*((!''|!{})+(!''|!{})+(!''|!{}))
* 10
* 11
* 12
* 13
* **14** (((!''|!{})+(!''|!{})+(!''|!{}))*((!''|!{})+(!''|!{}))+(!''|!{}))*((!''|!{})+(!''|!{}))
* 15
* 16
* 17
* 18
* 19
* 20
