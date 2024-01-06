weight=input('weight: ')
unit=input('(L)bs or (K)g: ')
if unit==str('k'):
    print(f"you are {int(weight)/.45}pounds")
elif unit==str('l'):
    print(f"you are {int(weight)*.45}kg")
else:
    print('wrong alphabate')
