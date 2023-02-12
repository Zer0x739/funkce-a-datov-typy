# Funkce a datové typy
##### Popis kodu 
Tento PHP kód vytváří třídu Conversion, která poskytuje metody pro konverzi mezi různými datovými typy. Konkrétně jsou vytvořeny konverzní metody pro kombinace datových typů int, string, float, bool a array.

Každá konverzní metoda je pojmenována ve tvaru ${value1}TO${value2}(), kde ${value1} a ${value2} představují dva různé datové typy. Každá metoda má na vstupu hodnotu typu $value1 a vrací hodnotu typu $value2.

Kromě toho jsou vypsány výsledky konverzních metod pro každou kombinaci datových typů a hodnotu ze seznamu $setValues. Výsledky jsou vypsány na standardní výstup pomocí funkce echo.

Nakonec je třída Conversion vypsána do souboru "vysledek.php" pomocí funkce file_put_contents().
