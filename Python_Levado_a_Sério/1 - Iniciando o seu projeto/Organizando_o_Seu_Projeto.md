# Organizando o Seu Projeto
Navegar por uma hierarquia com vários níveis de profundidade pode ser um pesadelo enquanto uma hierarquia com poucos níeis tende a se tornar inflada.  
Armazene os testes dentro do diretório do pacote.  
O nome padrão de um script de instalação Python é setup.py. Ele é acompanhado por setup.cfg, que deve conter os detalhes de configuralçao do script de instalação.  
#### Tipos de Diretórios  
- **etc** para arquivos de configuração;
- **tools** para shell script ou ferramentas relacionadas;
- **bin** oara scripts binários;  
Organize seu código com base em funcionalidadesm e não com base em tipos.   
É uma péssima idéia criar um diretório de módulos que contem somentu um arquivo __init__.py, Se você criar um diretório, ele deverá contar vários outros arquivos Python pertencentes à categoria representada por esse diretório.  
Arquivos __init__.py deverão estar vazios na maior parte das vezes.  Python exige que um arquivo __init__.pyesteja presente para que o diretório seja considerado um submódulo.  
