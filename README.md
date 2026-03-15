print("Ciao! 👋")
print("Questo programma ti aiuta a capire il significato di alcune parole meme di Internet.")
print("Scrivi una parola in MAIUSCOLO per vedere cosa significa.\n")

meme_dict = {
    "CRINGE": "Qualcosa di eccezionalmente strano o imbarazzante",
    "LOL": "Una risposta comune a qualcosa di divertente",
    "ROFL": "Ride così tanto da rotolarsi per terra",
    "SUS": "Qualcosa o qualcuno sospetto",
    "GG": "Good Game, usato per dire che la partita è stata bella",
    "NOOB": "Una persona inesperta in un gioco",
    "AFK": "Away From Keyboard, cioè lontano dal computer",
}

parola = input("Scrivi una parola che non capisci (usa solo lettere maiuscole!): ")

if parola in meme_dict.keys():
    print("Significato:", meme_dict[parola])
else:
    print("Mi dispiace, questa parola non è nel dizionario.")
