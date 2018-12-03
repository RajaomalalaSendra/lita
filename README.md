# lita
```
<programa> ::= fototra(fidirana) {
                 <torolalana>
                 avohay <isa>; 
               }

<torolalana> ::= ;
               | <voambolana> <- <rafitrisa>;
               | raha <valimpanontaniana> dia <torolalana> rtzany <torolalana>;
               | ataovy <torolalana> rmbola <valimpanontaniana>;
               | tapaho;
               | <torolalana> ; <torolalana>

<voambolana> ::= [a-z]+(\d|[a-z]|_)*

<rafitrisa> ::= -?\d+
              | fidirana[\d+]
              | <voambolana>
              | <rafitrisa> + <rafitrisa>
              | <rafitrisa> * <rafitrisa>
              | <rafitrisa> - <rafitrisa>
              | <rafitrisa> / <rafitrisa>

<valimpanontaniana> ::= marina
                      | diso
                      | <rafitrisa> <  <rafitrisa>
                      | <rafitrisa> =  <rafitrisa>
                      | <rafitrisa> na <rafitrisa>
                      | <rafitrisa> sy <rafitrisa>
```
