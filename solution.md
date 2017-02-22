Matthews-MacBook-Pro:command-line-mystery Matkins$ touch solution.md

Matthews-MacBook-Pro:command-line-mystery Matkins$ ls
cheatsheet.md	hint3		hint6		instructions	solution.md
hint1		hint4		hint7		mystery
hint2		hint5		hint8		readme.md

Matthews-MacBook-Pro:command-line-mystery Matkins$ cat instructions

Matthews-MacBook-Pro:command-line-mystery Matkins$ cd mystery

Matthews-MacBook-Pro:mystery Matkins$ ls
crimescene	memberships	streets
interviews	people		vehicles

Matthews-MacBook-Pro:mystery Matkins$ cat crimescene

Matthews-MacBook-Pro:mystery Matkins$ grep 'CLUE' crimescene

CLUE: Footage from an ATM security camera is blurry but shows that the perpetrator is a tall male, at least 6'.
CLUE: Found a wallet believed to belong to the killer: no ID, just loose change, and membership cards for AAA, Delta SkyMiles, the local library, and the Museum of Bash History. The cards are totally untraceable and have no name, for some reason.
CLUE: Questioned the barista at the local coffee shop. He said a woman left right before they heard the shots. The name on her latte was Annabel, she had blond spiky hair and a New Zealand accent.

Matthews-MacBook-Pro:mystery Matkins$ cd interviews

Matthews-MacBook-Pro:interviews Matkins$ ls

Matthews-MacBook-Pro:interviews Matkins$ grep 'Church' interview-*
interview-699607:Interviewed Ms. Church at 2:04 pm.  Witness stated that she did not see anyone she could identify as the shooter, that she ran away as soon as the shots were fired.

Matthews-MacBook-Pro:interviews Matkins$ cat interivew-699607
cat: interivew-699607: No such file or directory

Matthews-MacBook-Pro:interviews Matkins$ cat interview-699607
Interviewed Ms. Church at 2:04 pm.  Witness stated that she did not see anyone she could identify as the shooter, that she ran away as soon as the shots were fired.

However, she reports seeing the car that fled the scene.  Describes it as a blue Honda, with a license plate that starts with "L337" and ends with "9"

Matthews-MacBook-Pro:interviews Matkins$ cd .. 
Matthews-MacBook-Pro:mystery Matkins$ ls
crimescene	memberships	streets
interviews	people		vehicles

Matthews-MacBook-Pro:mystery Matkins$ cat vehicles

Matthews-MacBook-Pro:mystery Matkins$ grep 'L337' vehicles

License Plate L337ZR9 - Red
License Plate L337P89 - Teal
License Plate L337GX9 - Orange
License Plate L337QE9 - blue but female
License Plate L337GB9 - blue but not honda
License Plate L337OI9 - blue but jaguar
License Plate L337X19 - blue fiat
License Plate L337539 - blue '5'3"
License Plate L3373U9 - blue but female
License Plate L337369 - blue but female
License Plate L337DV9 - Joe?
License Plate L3375A9 - Jeremy?
License Plate L337WR9 - female

Matthews-MacBook-Pro:mystery Matkins$ cd memberships

Matthews-MacBook-Pro:memberships Matkins$ ls
AAA			Fitness_Galaxy		TCSU_Alumni_Association
AAdvantage		Museum_of_Bash_History	Terminal_City_Library
Costco			REI			United_MileagePlus
Delta_SkyMiles		Rotary_Club

Matthews-MacBook-Pro:memberships Matkins$ grep 'Jeremy' AAA
Jeremy Bowers
Matthews-MacBook-Pro:memberships Matkins$ grep 'Jeremy' Delta_SkyMiles 
Jeremy Bowers
Matthews-MacBook-Pro:memberships Matkins$ grep 'Jeremy' Museum_of_Bash_History 
Jeremy Bowers
Matthews-MacBook-Pro:memberships Matkins$ grep 'Jeremy' Terminal_City_Library 
Jeremy Bowers
Matthews-MacBook-Pro:memberships Matkins$ 




