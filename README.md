# goit-markup-hw-07
% -- шаблон ставим вместо селектора .
@extend -- разширение стилей 
$color -- переменная 
@mixin -- миксин ( пока не доганяю =D ) ( УРАА ! разобрался спустя 20 мин )

ПРИМЕР ================================
@mixin centeredFlex ($type: flex ) {     ---- (флекс по умолчанию )
    display: $type;
    align-items: center;
    justify-content: center;
    
p {
   @include centeredFlex(flex);
 }
 
div {
   @include centerdFlex(flex);
}

button {
   @include centeredFlex(inline-flex);
}
======================================
https://viacheslavsosnovskiy.github.io/goit-markup-hw-07/
