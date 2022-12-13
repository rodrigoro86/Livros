# Numeração de Versões 
PEP 440 define a expressão regular no formato a seguir para a numeração de versões:   
N[.N]+{{a|b|c|rc}N][.postN][.devN]}  
- Verções N.[N]+ são conideradas finais.  
- Vesões baseadas em datasm são invalidas. 
- N[.N]+aN (por exemplo, 1,2a1): representa uma versão alfa, é uma versçao que pode estar instável ou dunionalidades faltando.  
- N[.N]+bN; (por exemplo, 1,2b1): representa uma versão beta, uma versão que pode ter todas as funionalidades, mas ainda contém bugs.  
- N[.N]+cN ou N[.N]+rcN; (por exemplo, 1,2rc1): representa uma candidata a lançamento (release), uma versão que poderá ser lançada como definitiva, a menos que surjam bugs significativos.
