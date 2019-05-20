---

copyright:

  years: 1994, 2019

lastupdated: "2019-05-16"

keywords: bandwidth pool, bandwidth usage, Add Servers list, optimizing badwidth 

subcollection: customer-portal 

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:new_window: target="_blank"}


# Optimisation de votre utilisation de la bande passante
{: #cp_manbdwpool}

Le trafic réseau public de données transférées en sortie à partir de centres de données IBM Cloud du monde entier constitue une charge de bande passante en sortie. Cette charge dépend de l'emplacement des ressources transférant les données, de la quantité de données en sortie et des allocations de bande passante dont peuvent bénéficier les produits IBM Cloud dont vous avez fait l'acquisition. 
{:shortdesc} 

Les clients peuvent optimiser l'utilisation de la bande passante en "regroupant en pool" toute la bande passante destinée aux serveurs dans un pool de bande passante. Les moyennes de bande passante pour les serveurs d'un pool sont considérées comme un seul élément, et elles sont calculées uniquement si la bande passante totale de tous les serveurs dépasse celle allouée à l'ensemble des serveurs et non mesurés à un niveau individuel. 

Les définitions de pool sont répertoriées dans le tableau suivant : 

| Pool      | Emplacement(s)          |
| ------------- |:-------------:|
| Etats-Unis    | DAL01<br/><br/>DAL02<br/><br/>DAL04<br/><br/>DAL07<br/><br/>DAL09<br/><br/>DAL10<br/><br/>DAL12<br/><br/>DAL13<br/><br/>HOU02<br/><br/>MON01<br/><br/>SEA01<br/><br/>SJC01<br/><br/>SJC03<br/><br/>SJC04<br/><br/>TOR01<br/><br/>WDC01<br/><br/>WDC04<br/><br/>WDC06<br/><br/>WDC07|
| Amsterdam & Londres | AMS01<br/><br/>AMS03<br/><br/>LON01<br/><br/>LON02<br/><br/>LON04<br/><br/>LON05<br/><br/>LON06<br/><br/>PAR01 |
| Australie | MEL01<br/><br/>SYD01<br/><br/>SYD04<br/><br/>SYD05 |
| Brésil | SAO01 |
| Francfort | FRA02<br/><br/>FRA04<br/><br/>FRA05 |
| Inde | CHE01 |
| Italie | MIL01 |
| Corée du Sud | SEO01 | 
| Mexique | MEX01 | 
| Norvège | OSL01 | 
| Singapour, Hong Kong & Tokyo | HKG02<br/><br/>SNG01<br/><br/>TOK02<br/><br/>TOK04<br/><br/>TOK05 |
{:caption="Tableau 1. Définition de regroupement en pool" caption-side="top"}


## Modification d'un pool de bande passante
{: #cp_modbdwpool}

Une fois qu'un pool de bande passante est créé, si vous faites partie des utilisateurs autorisés, vous pouvez accéder à tout moment à ce pool. Vous pouvez accéder au pool de bande passante pour afficher les équipements associés au pool, ajouter ou retirer des unités. Utilisez la procédure suivante pour accéder à un pool :

1. Connectez-vous au portail client à l'aide de vos données d'identification uniques.
2. Sélectionnez **Réseau** > **Bande passante** > **Pools** depuis le menu pour accéder à la fenêtre Pools de bande passante.
3. Cliquez sur le **Nom du pool** pour accéder au pool. Chaque équipement associé au pool est affiché.
4. Depuis l'onglet **Modifier**, vous pouvez renommer le pool, ajouter ou retirer une unité.
  * Pour renommer le pool, entrez le nouveau nom dans la zone contenant le nom actuel du pool.
  * Pour ajouter une unité au pool, depuis la liste **Ajouter serveurs**, sélectionnez le nom de l'unité et cliquez sur **Sélectionner**.
  * Pour retirer une unité du pool, dans la liste **Supprimer serveurs**, sélectionnez l'unité et cliquez sur **Sélectionner**.
5. Cliquez sur **Modifier rack**.
6. Cliquez sur le lien **Afficher tous les pools de bande passante** pour revenir à la fenêtre Pools de bande passante.
