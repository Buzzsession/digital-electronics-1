# MORSE TRANSMITTER

### Team members

* Jan Pavlacka (responsible for coffee)
* Filip Voch   (responsible for xxx)
* Josef Macek  (responsible for xxx)
* Daniel Smyd  (responsible for xxx)

### Table of contents

* [Project objectives](#objectives)
* [Hardware description](#hardware)
* [VHDL modules description and simulations](#modules)
* [TOP module description and simulations](#top)
* [Video](#video)
* [References](#references)

<a name="objectives"></a>

## Project objectives

Implementace kódu na desku Nexys-A7-50T schopného přeložit čísla a písmena do morseovy abecedy

<a name="hardware"></a>

## Hardware description

Používáme desku Nexys-A7-50T a využíváme tyto její komponenty:
Clock100MHz
7 přepínačů SW
modrou a červenou RGB LED
tlačítko BTNC

<a name="modules"></a>

## VHDL modules description and simulations

clock_enable - zpomalení hodinového signálu
cnt_up_down - čítač, který pracuje v režimu čítání směrem dolů  
morse_t - přiřazení 20bit signálu data, který znázorňuje dané číslo nebo písmeno v morseově abecedě ke konkrétnímu číslu nebo písmenu a následné přiřazení tohoto signálu na výstupní 1bit proměnou morse_o

<a name="top"></a>

## TOP module description and simulations

![figure](images/Top-project.jpeg)

<a name="video"></a>

## Video

Write your text here

<a name="references"></a>

## References

1. Write your text here.
