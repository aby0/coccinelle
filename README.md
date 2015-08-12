# coccinelle
Coccinelle is a program matching and transformation engine which provides the language SmPL (Semantic Patch Language) for specifying desired matches and transformations in C code. Coccinelle was initially targeted towards performing collateral evolutions in Linux. Such evolutions comprise the changes that are needed in client code in response to evolutions in library APIs, and may include modifications such as renaming a function, adding a function argument whose value is somehow context-dependent, and reorganizing a data structure. Beyond collateral evolutions, Coccinelle is successfully used (by us and others) for finding and fixing bugs in systems code.

This repository contains several semantic patches as well as cleanup patches which are accepted by linux Foundations.

A complete list of accepted patches can be seen [here.](https://git.kernel.org/cgit/linux/kernel/git/gregkh/staging.git/log/?h=staging-next&qt=author&q=somyaanand214%40gmail.com&showmsg=1) 
