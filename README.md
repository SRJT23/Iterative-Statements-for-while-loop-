# Iterative-Statements-for-while-loop-
#Basic idea of programming (Programming SRJT23 way) 


def pyramid(n):
   for i in range(0, n):
      for j in range (0, i+1):
         print ('*', end='')
      print ('\r')

n=10
pyramid(n)
