# Stash Userscripts

## Performer Edit Panel, Dot Notation Weight, Height and Penis converter

Userscript to that attaches event listeners to the Weight, height and penis input fields to use dot notation to convert the non standard format to the standard format for each. I.e. Feet . Inches to cm for height. Pounds . Ounces to kg for weight and Inches . Inches to cm for penis lengh

The height and penis length event listeners listen for a regex match of up to two intigers then the decimal point alongside another intiger. That once matched will calculate and replace the input value.

The weight event listener, listens to a regex match of upto 4 intigers then the decimal point and upto two intigers after that. Upon entering one intiger it will match but the cacluation function is put on a set timeout allong for entry of an additional intiger.

## Note

For the calculation to work, it needs the decimal point and any intigers after that to match and calculate.

I.e. to enter 5ft for height. I would enter 5.0

## Usage

Usage, for example if I want to add 5ft 7inches to the height input field. I would just enter, 5.7 and the value of the input field should automatically convert to 170 cm, the closest round integer of the caluclation.

## Will eventually add to my forked repo of the Userscripts Bundle
