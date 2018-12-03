# lita
```
<programa> ::= miditra: <isa>
               torolalana: <torolalana>
               mivoaka: <rafitrisa>

<torolalana> ::= foana.
               | <voambolana> lasa <rafitrisa>.
               | raha <hevitra> dia <torolalana> ratszay <torolalana>.
               | ataovy <torolalana> rambola <hevitra>.
               | tapaho.
               | atomboy <torolalana> farano
               | <torolalana>. <torolalana>

<voambolana> ::= [a-z]+(\d|[a-z]|_)*

<rafitrisa> ::= -?\d+
              | fidirana[\d+]
              | <voambolana>
              | ( <rafitrisa> )
              | <rafitrisa> + <rafitrisa>
              | <rafitrisa> * <rafitrisa>
              | <rafitrisa> - <rafitrisa>
              | <rafitrisa> / <rafitrisa>

<hevitra> ::= marina
            | diso
            | <rafitrisa> <  <rafitrisa>
            | <rafitrisa> =  <rafitrisa>
            | ( <hevitra> )
            | <hevitra> na <hevitra>
            | <hevitra> sy <hevitra>
```
