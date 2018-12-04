# lita
```
<programa> ::= miditra: \d+
               baiko: <baiko>
               mivoaka: <rafitrisa>

<baiko> ::= foana.
          | <voambolana> avadio <rafitrisa>.
          | raha <vina> dia <baiko> ratszay <baiko>.
          | ataovy <baiko> rambola <vina>.
          | tapaho.
          | atomboy <baiko> farano
          | <baiko>. <baiko>

<voambolana> ::= [a-z]+(\d|[a-z]|_)*

<rafitrisa> ::= -?\d+
              | fidirana[\d+]
              | <voambolana>
              | ( <rafitrisa> )
              | <rafitrisa> + <rafitrisa>
              | <rafitrisa> * <rafitrisa>
              | <rafitrisa> - <rafitrisa>
              | <rafitrisa> / <rafitrisa>

<vina> ::= marina
         | diso
         | <rafitrisa> <  <rafitrisa>
         | <rafitrisa> =  <rafitrisa>
         | ( <vina> )
         | <vina> na <vina>
         | <vina> sy <vina>
```
