# Projetos-Pessoais

# Vetorização:
w = np.array([1,2.5,-3.3]
b = 4 
x = np.array([10,20,30])
f = np.dot(w,x)+b

# Sem vetorizaçao:
f = 0
for j in range(n):
  f = f + w[j] * x[j]
f = f + b

#vector slicing operations

a = np.arange(10)
print(f"a         = {a}")

#access 5 consecutive elements (start:stop:step)
c = a[2:7:1];     print("a[2:7:1] = ", c)

# access 3 elements separated by two 
c = a[2:7:2];     print("a[2:7:2] = ", c)

# access all elements index 3 and above
c = a[3:];        print("a[3:]    = ", c)

# access all elements below index 3
c = a[:3];        print("a[:3]    = ", c)

# Operações envolvendo todo o vetor:

a = np.array([1,2,3,4])
print(f"a             : {a}")
# negate elements of a
b = -a 
print(f"b = -a        : {b}")

# sum all elements of a, returns a scalar
# vetores devem ser do mesmo tamanho para realizarem operacoes 
b = np.sum(a) 
print(f"b = np.sum(a) : {b}")

a = np.array([ 1, 2, 3, 4])
b = np.array([-1,-2, 3, 4])
print(f"Binary operators work element wise: {a + b}")

# np.dot faz o somarproduto entre dois vetores

a = np.array([1, 2, 3, 4])
b = np.array([-1, 4, 3, 2])
c = np.dot(a, b)



# access all elements
c = a[:];         print("a[:]     = ", c)
