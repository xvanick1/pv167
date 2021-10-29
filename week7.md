1. singleton
- trieda spravujúca (vytvaranie, evidencia, rušenie) uživateľov v systéme
- trieda pre správu jednotlivých projektov v systéme, opäť vytvaranie, evidencia, rušenie

2. builder
- použitie pri vytváraní konfigúrácie jednotlivých analýz
- pre vytvorenie zložených metrík 

3. composite
- použite pre reprezentovanie štruktúry projetku repsektíve jeho verzíí 

4. adapter
- použitie pri platbe cez externú platobnu bránu resp. službu 
- pri prihalsovaní alebo registrácií použivateľa cez systém tretej strany

5. strategy
-  rôzne ceny za prémiový učet

------------

6. observer
- zmena statusu analýzi
- info/notifikacia uživateľom

7. abstract factory
- pre vytvaranie rôznych konfigurácií kvality
- pre vytvaranie reportov s požadovanými metrikami

8.flyweight
- strom struktura projektov resp. ich klasifikacie
- uzly: verzia, autor, programovaci jazyk 
- adept na flyweight zdielany objekt: programovaci jazyk alebo autor
- nevhodne pre zdielanie: verzia
