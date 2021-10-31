# PetreaVladut_IR1_gr5_sg8
Se folosesc operatori logici precum in c++. Fieacre propozitie trebuie sa contina atom(subiect logic), operator(din lista de mai sus) si sa fie incadrata in paranteze. Programul returneaza true daca input- ul este o propzitie logica corect formata si false in caz contrar.
operatori:
1. => - implicatie
2. ! - negatie
3. == - echivalenta
4. && - conjucntie
5. || - disjunctie
6. != - non-echivalenta/XOR
ex:
(!a) true
(a) false
(((P||Q)=>(!(P||Q)))&&(P||(!(!Q)))) true
((p&&q)=>(!q)) true
(p&&q)=>!q false



