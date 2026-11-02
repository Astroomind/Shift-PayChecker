# This app solves the common problem of having issues with pay when payday comes around for your everyday worker.
# This application keeps track of your hourly rate, night premium, sleep-ins, mileage, Weekend premium, Bank holiday and short notice pay.

# Rules are:
# Pay is gross, before tax and National Insurance. The app doesn't do tax.
# A shift belongs to the day it starts. A Friday night shift that ends on Saturday morning is a Friday shift.
# The bank holiday multiplier applies to the base rate only. Premiums are then added on top, per hour.
# Sleep-ins are a flat amount. No premium or multiplier ever applies to them.
# Each shift's pay is rounded to the nearest penny, with halves rounding up. A week's total adds up those rounded amounts.
