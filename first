joueur1 = int(input("Entrer un nombre entier entre 1 et 100")) #Utilisateur tape un nombre
if 1 <= joueur1 <= 100: #vérifier si la valeur est entre 1 ou égal à 1 et 100 ou égal à 100
    result1 = int(joueur1) #variable result1 == valeur de joueur1
    joueur2 = True
else:
    print("Le nombre n'est pas compris entre 1 et 100") #si la valeur n'est pas comprise entre 1 et 100

tentative = 0

while joueur2 == True:

        joueur2input = int(input("Entre un nombre entier entre 1 et 100")) #Utilisateur 2 tape un nombre

        if 1 <= joueur2input <= 100: #vérifier si la valeur est entre 1 ou égal à 1 et 100 ou égal à 100
            tentative = tentative + 1 #ajoute 1 au nombre de tentative
            if(joueur2input == result1):
                print("Bravo ! Vous avez fait", tentative, "essaie(s) pour y arriver !")
                joueur2 = False
            elif joueur1 <= joueur2input: #si la valeur de l'utilisateur 2 est trop grande
                    print("Plus petit")
            elif joueur1 >= joueur2input: #si la valeur de l'utilisateur 2 est trop petite
                    print("Plus grand")
            else:
                print("Inconnu") #si la valeur de l'utilisateur 2 est inconnu
        else:
            print("Le nombre n'est pas compris entre 1 et 100")  # si la valeur n'est pas comprise entre 1 et 100
else:
    print("Fin du jeux") #si le jeux est fini
