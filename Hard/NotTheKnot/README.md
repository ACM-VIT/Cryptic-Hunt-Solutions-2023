# NotTheKnot

* **Category:** Hard
* **Mode:** Online, transitions to offline(?)
* **Authors:**
  * Shambhavi Paygude, Yasha Pacholee

* **Points:** TBD

## Specifications

* **Entry point:** An image of topoisomerase enzyme is provided.

* **Reward:** TBD (Usually a clue to another question)

## Description

Prepare for an intriguing challenge as you delve into an image that unravels the mysteries of a biological marvel renowned for unique DNA transformations. Follow its natural habitat, and you'll encounter a pair of intricate visual enigmas. Unravel this twisted journey and get a glimpse into a fascinating connection within the abstract realm!

## Solution

1.  Players are provided with an image of the topoisomerase enzyme. (This enzyme is resposible for interconverting relaxed and supercoiled forms, linked and unlinked species, and knotted and unknotted DNA.)

2. A clue from the image will hint the player to find a place where it might be found(The metadata will have hidden text which says G15 ). It is a biological enzyme (chem/bio lab) which leads the player to smv (Computational Biology Lab G15). 

3. 2 QRs will be present at smv which on scanning gives the player 2 images. The images consist of one knot each (The Stevedore Knot and Figure-8 knot).

4. The metadata of one of the images will consist of an encrypted string ( in base64 : cmVpZGVtZWlzdGVy ) which on decrypting gives "Reidemeister" . Player has to use the Reidemeister Moves to untangle the knots and get two unknots. 

5. The metadata of the other image will give the centre for the unknot which can be used to make the equation of the unlink. ( base64 - Q2VudHJlKGEsYik=, decoded : Centre(a,b))

6. Unlink is a link that is equivalent  to two or more unknots. Hence, the obtained unknots define an unlink. Player has to identify the unlink and enter the unlink equation as answer __(x-a)^2+(y-b)^2=r^2__

## Hints:

 -  Hint 1 (Cost = TBD)
 -  Use the reidemeister moves and find the equation of the knot obtained after that. 

## Links

https://with.acmvit.in/ch23-phase-4-7-3XYl33Q55N5iO5N9Gk087DA6 (Computational Biology Lab G15)

https://with.acmvit.in/ch23-phase-4-7-99360FlNdK4A2KGX4zZ8A056 (Computational Biology Lab G15)

https://with.acmvit.in/ch23-phase-4-7-26Y5ah7nC0BR1qc1AB755HN2 (in the desc of ques)

