# Beverage Dispensers - Report November and December 2019

*(Business case : Training Quest - Wild Code School (in French))*

## Problématique

Le client gère des distributeurs de boissons sur des quais de gare. Un employé passe une fois par semaine recharger les machines. Cet employé indique régulièrement que la machine était vide, mais sans préciser quels produits sont vides. **Le client souhaiterait estimer le manque à gagner (lorsqu'il y a rupture de stock), et te demande une analyse détaillée. Il aimerait un conseil pour savoir s'il est rentable d'envoyer ou non l'employé pour recharger les machines deux fois par semaine plutôt qu'une seule fois.**

Pour cela, il te fournit l'extraction du journal automatique (le "log") des 4 distributeurs de boisson de la gare concernée. Chaque machine enregistre en effet chaque vente ou passage du technicien avec un horodatage.

Quelques compléments (tous les montants sont hors taxe, tu n'as donc pas à prendre en compte les taxes et/ou les impôts dans cette analyse) :

- Le déplacement d'un employé coûte 50 euros pour aller à la gare + 20 euros par machine. Les 4 machines sont dans la même gare.
- Le prix de vente des boissons est de : 1 euro le café ; 1,60 euros le soda ; 1,80 euros le nrj drink.
- Le coût de revient des boissons est de : 30 cts le café ; 60 cts le soda ; 80 cts le nrj drink.
- Chaque distributeur a une capacité maximale de : 280 doses de café ; 120 canettes de soda ; 60 bouteilles de nrj drink.
- La gare est fermée au public une partie de la nuit.
- Le coût de location de l'emplacement pour chaque machine est de 150 euros mensuels.
- Les frais d'entretien de chaque machine sont de 1200 euros annuels.

## Challenge

Effectue l'analyse demandée, avec des visualisations explicatives, et propose un conseil au client.

Tu trouveras le journal des ventes ici.

Nous te laissons libre d'y répondre à ta manière. La créativité, l'intuition, la faculté de s'imaginer à la place du client, sont des compétences très importantes dans nos métiers.

## Informations

Le journal contient les ventes de produits et les "refill" par l'employé. Chaque ligne correspond à une action (une vente d'une boisson ou un refill par l'employé). Il y a bien 4 machines.

Explore les données : les ventes sont-elles bien réparties par machine ? Par produit ? Par heure de la journée ? Y a-t-il des ventes quand la gare est fermée ? Entre quelles horaires la gare est-elle fermée ? Les ventes sont-elles différentes le week-end ? Vend-on plus de café le matin ou le soir ? Et les autres boissons ? Le remplissage (refill) de la machine est-il bien hebdomadaire ? Quel jour passe l'employé ? Etc... Détermine en moyenne à partir de quel jour de la semaine/heure il y a rupture de stock. Estime le manque à gagner par rapport à des jours de la semaine qui seraient similaires s'il y avait des stocks. Propose un conseil sur l'opportunité de faire un second passage pour recharger la machine.

## Results

### General Sales

![Sales](https://github.com/Laetitia-Deken/Beverage-Dispensers_Report-November-and-December-2019/blob/bb0b207dcc2c2463f8e01576eb74d7749eeed51a/Beverage%20Dispensers%20-%20Report%20November%20and%20December%202019%20(sales).png "Sales")

### Month

![Month](https://github.com/Laetitia-Deken/Beverage-Dispensers_Report-November-and-December-2019/blob/bb0b207dcc2c2463f8e01576eb74d7749eeed51a/Beverage%20Dispensers%20-%20Report%20November%20and%20December%202019%20(month).png "Month")

### Stockouts

![Stockouts](https://github.com/Laetitia-Deken/Beverage-Dispensers_Report-November-and-December-2019/blob/bb0b207dcc2c2463f8e01576eb74d7749eeed51a/Beverage%20Dispensers%20-%20Report%20November%20and%20December%202019%20(stockouts).png "Stockouts")

### Lost sales

![Lost Sales](https://github.com/Laetitia-Deken/Beverage-Dispensers_Report-November-and-December-2019/blob/bb0b207dcc2c2463f8e01576eb74d7749eeed51a/Beverage%20Dispensers%20-%20Report%20November%20and%20December%202019%20(lost%20sales).png "Lost Sales")

