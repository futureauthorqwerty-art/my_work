## MACE
The file ... is taken on the basic. 
I changed the reaction equasion. 
Spin is also zero like in methane.
Don't change the size of vacuum sphere due to it at least twice bigger than ethane.
Calculate the number of symmetries for ethan: three first order external asix and one third order C-C bond axis.
    In result 3 + 3 = 6 external symmetries and 3 internal => 18 in total.
Add C-C bond calculations in ethane. Excp value 1.512 was taken from pubchem
Changed coeficients in # 6. Reaction energetics:
Complete double check with Deepseek. 
Using Hess law recalculate table enthalpy for ethane.
### Analysis of the yielded data/ 
1) The calculated enthalpy is -1289.80 kJ/mol, whick in compare with Expt ref: -1560.7 kJ/mol has inaccuracy about 17%.
2) Relaxed Bond Lengths is accurate, exept one small mistake in O2, the difference is about 2.4

## MOPAC
The file ... is taken on the basis/
The correct file, which calculate FINAL HEAT OF FORMATION dHf(298.15 K) properly, was used.
I changed the reaction equasion
I changed the expexted meaning of the Relaxed bond lengths 
Add C-C bond calculations in ethane. Excp value 1.512 was taken from pubchem
Changed coeficients in # 6. Reaction energetics:
Using Hess law recalculate table enthalpy for ethane.

### Analys of the yielded data/ 
1) Initial enthalpy of formation is -1222.28 kJ/mol, which gived an error about 22% and O2 enthalpy of formation -38.37, while it is zero by definition. Taking into account this problem and correcting it, minusing the obtained value with the approppriate stoichiometricc coefficient we obtain deltafH_O2= 0 and
deltafH_C2H6 = -1356.59 kJ/mol. In this case innacuracy is about 13%.
2) Relaxed Bond Lengths is accurate, exept one inacuracy mistake in O2, the difference is about 5.7%


## NWchem
The file ... is taken on the basis/
Only 4 processors were used.
I changed the reaction equasion
I changed the expexted meaning of the Relaxed bond lengths
Add C-C bond calculations in ethane. Excp value 1.512 was taken from pubchem
Changed the rigid external rotational symmetry number(6 for ethane instead of 12 for methane).
Vibrations frequences are also fine? error is about 5%.

