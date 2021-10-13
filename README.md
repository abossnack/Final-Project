l = ""
n = 0.0
t = .07
while (l.upper() != "C"):
    l = input("Please enter the price of the item or enter 'C' to calculate: ")
    if (l.upper() != "C"):
        n += float(l)

print("Subtotal: $", round(n, 2))
st = t*n
print("Tax:      $", round(st, 2))
ft = st+n
print("Total:    $", round(ft, 2))
