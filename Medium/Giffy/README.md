# Giffy

* **Category:** Medium
* **Mode:** Online, transitions to offline(?)
* **Authors:**
   * Shambhavi Paygude

* **Points:** TBD

## Specifications

* **Entry point:** Player is provided with a GIF.

* **Reward:** TBD (Usually a clue to another question)

## Description

"Can you decode a hidden message and find a secret flag in this GIF that might be something more than just a GIF?"

## Solution

1. The player is presented with a GIF that appears to be a fragmented QR code.
2. The goal is to reassemble the pieces of the QR code to form a complete QR code.
3. Once the player successfully reconstructs the QR code, they scan it using a QR code scanner.
4. The QR code leads to a Google Drive link.
5. The Google Drive link opens to a folder containing various GIFs and JPEG meme images.
6. Among the images, there is one that displays the text: "Can I recall a password when I know it has 'aWZz' in the middle?"
7. This particular image holds a hidden folder within it which has multiple text files that are base64 encrypted.
8.  Player needs to decrypt the one that contains 'aWZz'. Decrypting it gives "flag_gifsAreFun."
9. Player has to submit "gifsAreFun" as the answer.

## Hints:

 -  Hint 1 (Cost = TBD)
 -  Hint 2 (Cost = TBD)
