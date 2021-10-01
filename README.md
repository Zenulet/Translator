import goggletrans import Translator  
import microsoft import Translator


#print (goggletrans.LANGUAGES)


text1 = ""

text2 = ""

text3 = ""

translator = Translator()


print(translator.detect (text1))
print(translator.detect (text2))
print(translator.detect (text3))

print("Translate EN to RO: ", translator.translate(textl, src="en dest="ro"))
