# Comment installer Qiskit?

## Installer `conda`

La bibliothèque Qiskit se base sur le langage de programmation Python, il faut donc d'abord installer Python. Le plus pratique pour s'assurer que tout le monde a accès au même environnement est d'utiliser Anaconda. Suivez les instructions d'installation [ici](https://conda.io/projects/conda/en/latest/user-guide/install/index.html#regular-installation). Lorsque vous aurez le choix, préférez Miniconda à Anaconda.

## Se créer un nouvel environnement

Une fois `conda` installé avec succès, vous pourrez vous créer un environnement de travail. Dans votre terminal (ou l'Anaconda Prompt pour les utilisateurs Windows) tapez:

```bash
conda create -n fallfest python=3.9
```

Tapez `y` pour confirmer la création lorsque le programme vous le demandera.

## Activer le nouvel environnement

Avant de pouvoir travailler avec un nouvel environnement `conda`, il faut l'activer avec la commande `conda activate fallfest`. Vous pouvez à tout moment désactiver cet environnement en utilisant `conda deactivate`.

## Installer `qiskit`

Vérifiez que l'environnement `fallfest` a bien été activé, le cas échéant activez le avec `conda activate fallfest`. Ensuite, utilisez la commande suivante pour installer les paquets Python nécessaires:
```bash
python -m pip install qiskit jupyter jupyterlab
```

## Vérifier l'installation

L'installation peut être vérifiée en lançant la commande
```bash
python -c 'import qiskit; print("Success!")'
```
Si cette commande affiche "Success!" alors l'installation s'est déroulée correctement, sinon n'hésitez pas à venir demander de l'aide sur le canal Discord!
