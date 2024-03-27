#Lire les donnees du fichier Le fichier CreditBancaire.csv
Credit_data<-read.csv("CreditBancaire.csv")
View(Credit_data)
#Calculer la moyenne du credit
moyenne_Credit<-mean(Credit_data$Credit)
#Afficher la moyenne du credit
moyenne_Credit
# Calculer la moyenne du nombre de jours de retard de paiement par type de crédit
moyenne_retard <- tapply(Credit_data$Jours, Credit_data$Type  , mean)
#Afficher la moyenne du nombre de jours de retard de paiement par type de crédit
moyenne_retard
# Réaliser un graphique en bâton de la moyenne du nombre de jours de retard de paiement par type de crédit
barplot(moyenne_retard,main = "Graphique en baton")
