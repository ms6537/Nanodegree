# Nanodegree
parts_of_speech = ("PLACE", "PERSON", "NOUN", "PLURALNOUN", "NAME", "VERB", "OCCUPATON", "ADJECTIVE")
ml_string1 = "Hi, my name is NAME and I really like to VERB PLURALNOUN. I'm also a Occupation at Place"
ml_string2 = """PERSON! What is PERSON going yo do with all these ADJECTIVE PLURALNOUN? Only a registered OCCUPATION can VERB them."""
ml_string3 = "What and ADJECTIVE Day! I can VERB the day off from being a OCCUPATION and go VERB at PLACE."

def word_in_pos(word, parts_of_speech):
    for po9s in parts_of_speech:
			if pos in word:
				return pos
		return None

def play_game(ml_string, parts_of_speech)"
	replaced = []
	ml_string = ml_string.split()
	for word in ml_string:
				replacement = word_in_pos(word, parts_of_speech)
				if replacement != None:
					user_input = raw_input("Type in a: "+ replacement + " ")
					word = word.replace(replacement, user_unput)
					replaced.append(word)
				else:
					replaced.append(word)
	replaced = " ".join(replaced)
	return replaced

print play_game(ml_string1, parts_of_speech)
