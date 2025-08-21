<｜begin▁of▁sentence｜># -*- coding: utf-8 -*-
"""
Created on Wed Sep 25 16:37:38 2019

@author: stitch
"""

#Escriba un programa que lea la velocidad del automovil y la velocidad 
#permitida. Si la velocidad es menor o igual que el limite, muestre "ok"
#pero si la velocidad es mayor que el limite, la multa es de 400 por cada 5km/h
#por arriba del limite.

velocidad=int(input('Ingrese la velocidad del automovil: '))
limite=int(input('Ingrese el limite de velocidad: '))

if velocidad<=limite:
    print('ok')
else:
    multa=((velocidad-limite)/5)*400
    print('La multa es de: ', multa)
    