# dvmn-py_basics-02
from transliterate import get_available_language_codes
from transliterate import translit
from num2words import num2words
print(get_available_language_codes ())
print(translit("Ladies and gentlemen, I'm 78 years old and I finally got 15 minutes", 'ru'))
print(translit("of fame once in a lifetime and I guess that this is mine.", 'ru'))
print(translit("People have also told me to make these next few minutes", 'ru'))
print(translit("escruciatingly embarrassing and to take vengeance of my enemies", 'ru'))
print(translit("Neither will happen.", 'ru'))
print()
print(translit("More than 3 years ago I moved to Novo-Novsk, but worked on new Magnetic", 'ru'))
print(translit("Storage for last 40. When I was 8...", 'ru'))
print(num2words(42))
print(num2words(42, to='ordinal'))
print(num2words(42, lang='fr'))
print("78-" , end=" ")
print(translit(num2words(78), 'ru'))
print("15-" , end=" ")
print(translit(num2words(15), 'ru'))
print("3-", end=" ")
print(translit(num2words(3), 'ru'))
print("40-", end=" ")
print(translit(num2words(40), 'ru'))
print("8-", end=" ")
print(translit(num2words(8), 'ru'))	
