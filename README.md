# Correccion-tp-haskell


##
  areaTriangulo :: Float -> Float -> Float
  areaTriangulo b h = (b*h)/ 2.0



  esBisiesto :: Int -> Bool
  esBisisesto x = mod x 400 == 0 || (mod x 4 == 0 && mod x 100 /= 0)


  potencia :: Integer -> Integer -> Integer
  potencia  _ 0 = 1
  potencia numero exp = numero * potencia numero (exp - 1)
