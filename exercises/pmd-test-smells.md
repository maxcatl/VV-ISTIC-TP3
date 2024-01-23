# Detecting test smells with PMD

In folder [`pmd-documentation`](../pmd-documentation) you will find the documentation of a selection of PMD rules designed to catch test smells.
Identify which of the test smells discussed in classes are implemented by these rules.

Use one of the rules to detect a test smell in one of the following projects:

- [Apache Commons Collections](https://github.com/apache/commons-collections)
- [Apache Commons CLI](https://github.com/apache/commons-cli)
- [Apache Commons Math](https://github.com/apache/commons-math)
- [Apache Commons Lang](https://github.com/apache/commons-lang)

Discuss the test smell you found with the help of PMD and propose here an improvement.
Include the improved test code in this file.

## Answer

## TODO partie 1

On exécute pmd sur Apache Commons Collections avec la règle `UseAssertTrueInsteadOfAssertEquals`. J'obtiens le résultat suivant.
## TODO rajouter image


On choisie le premier smell et on remplace ensuite la méthode `assertEquals(false)` par `assertFalse`:

test présent dans le package collections d'Apache :
## TODO ajouter image test avant changement

test modifié pour que le smell n'apparaisse plus :
## TODO ajouter image test après changement

Résultats pmd après changement du test (le premier smell (ligne 191) n'apparait plus) :
## TODO rajouter image pmd après changement
