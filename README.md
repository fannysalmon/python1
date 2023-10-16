This tic tac toe has a variable size defined at the beginning, X and O have arbitrary values X=9999 and O=999. The user only have to enter xhere he wants to put is pawn.

Function getPlace(matrix, place) :
0 = (0,0) or 4 = (1,0)
Element 1D	Element2D
0	(0,0)
1	(0, 1)
2	(0, 2)
3	(1, 0)
4	(1, 1)
5	(1, 2)
6	(2, 0)
7	(2, 1)
8	(2, 2)


Function transpose(matrix) :
For example : 
matrix=[['X','O','X'],['X','X','O'],['X','O','O']]
print(transpose(matrix)
will print : [['X', 'X', 'X'], ['O', 'X', 'O'], ['X', 'O', 'O']]

Function sumOfDiagonals(element) :
matrix=[[0,0,999],[0,999,0],[999,0,0]]
print : (999, 2997)
matrix=[[999,0,0],[0,999,0],[0,0,999]]
print : (2997, 999)
matrix = matrix=[[999,0,999],[0,999,0],[999,0,999]]
print : (2997, 2997)
the 0 in the last don’t have any consequences in the sum.

Function verification(element) :
matrix=[[999,0,0],[0,999,0],[0,0,999]]
SIZE=3
X=9999
O=999
return : 999 (O)

matrix=[[9999,0,0],[0,999,0],[0,0,9999]]
SIZE=3
X=9999
O=999
return 9999 (X)

matrix=[[1,0,0],[0,1,0],[0,0,1]]
SIZE=3
X=9999
O=999
return : -1
