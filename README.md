# goit-markup-hw-07
% -- шаблон ставим вместо селектора .
@extend -- разширение стилей 
$color -- переменная 
@mixin -- миксин ( пока не доганяю =D ) ( УРАА ! разобрался спустя 20 мин )

ПРИМЕР ================================
@mixin centeredFlex ($type) {
    display: $type;
    align-items: center;
    justify-content: center;
    
p {
   @include centeredFlex(flex);
 }
 
div {
   @include centerdFlex(flex);
}

biutton {
   @include centeredFlex(inline-flex);
}
======================================
