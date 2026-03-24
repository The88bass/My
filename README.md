import random

def brainstorm():
    # Drei Listen mit Bausteinen für eine Idee
    zielgruppe = ["für Katzen", "für vergessliche Studenten", "für Astronauten", "für Profi-Köche"]
    technologie = ["eine KI-App", "ein Roboter", "eine Webseite", "ein magisches Gadget"]
    funktion = ["die Socken sortiert", "schlechte Witze erzählt", "automatisch Pizza bestellt", "beim Sprachenlernen hilft"]

    # Zufällige Auswahl treffen
    wer = random.choice(zielgruppe)
    was = random.choice(technologie)
    tut = random.choice(funktion)

    print("\n--- DEINE KREATIVE IDEE ---")
    print(f"Bau {was} {zielgruppe[random.randint(0, len(zielgruppe)-1)]}, das {tut}!")
    print("---------------------------\n")

if __name__ == "__main__":
    brainstorm()
