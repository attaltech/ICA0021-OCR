# Replace this text with your name / Asendage see tekst oma nimega

## Ülesande Kirjeldus  
Fail `ocr-json.json` (asub kataloogis `files`) sisaldab andmeid saadud OCR-i abil, kasutades [Google Vision API](https://cloud.google.com/vision).  

Teie ülesandeks on täiendada funktsiooni `parseJson` failis `task.py`, et see tagastaks nimekirja ('list' formaadis) tuvastatud tähtedest failist `files/ocr-json.json`, mille usaldusväärsuse tase (confidence level) on vähemalt **0.1**.  

Vajadusel võid defineerida ja kutsuda täiendavaid abifunktsioone, kuid kogu teie kood peab jääma faili `task.py`.


## Task Description  
The file `ocr-json.json` (located in the `files` directory) contains data extracted using optical character recognition (OCR) with the [Google Vision API](https://cloud.google.com/vision).  

Your task is to update the `parseJson` function in `task.py` to return a list of recognized letters from `files/ocr-json.json` that have a confidence level of at least **0.1**.  

You may define and call additional helper functions if needed, but all your code must be contained within `task.py`.

This assignment is not graded
