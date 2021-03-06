# Permutation Subgroup Generator
This script calculates the subgroup generated by the permutation (generator) that you enter.

## Motivation
This script has been developed to fulfill a practical work of the subject Criptography I, part of the UBA's Information Security career. It is for academic purposes.

## Installation
There is not any prerequisites needed to run the script.

## Usage
To run the script, just execute the following command in the directory where you downloaded this repository.
```
python generate_subgroup.py
```
You will be asked to insert an N (Length of the group you want) and the permutation P you want to use as generator.

### Usage example
Input
```
Enter the LENGTH of the Group of Permutations. - e.g. N = 5
N = 5

Enter the GENERATOR you want to use to calculate the subgroup - e.g. P = 31254
1-> 3
2-> 1
3-> 2
4-> 5
5-> 4
```
Output
```
P^1 = (132)(45)
P^2 = (123)(4)(5)
P^3 = (1)(2)(3)(45)
P^4 = (132)(4)(5)
P^5 = (123)(45)
P^6 = (1)(2)(3)(4)(5)
```

## Authors
* Matias Ezequiel Sena

## Relevant links
For more information about permutation groups, you can visit the following websites:
* [Wikipedia - Permutation group](https://en.wikipedia.org/wiki/Permutation_group)
* [UGR - El grupo Simetrico.](https://www.ugr.es/~jurbano/aed/AED-Tema_2-Grupos.Grupo_simetrico.pdf)
* [Dpto. Construcciones - El grupo alternado](http://www.departamento.us.es/da/planantiguo/notas-ant/algebra/t11.pdf)

