# Unseen Dimension

* **Category:** (Hard)
* **Mode:** Online
* **Authors:**
  * Raghav Sampath
* **Points:** TBD

## Specifications

* **Entry point:** A Link or Button that downloads a Word Document on the player's device
* **Reward:** TBD (Usually a clue to another question)

## Description

"Venture into the enigmatic depths of the Hexagon, a time-honored haven for scientific wonders. Navigate through the document's intricate passages, deciphering cryptic clues that allude to veiled revelations. Untangle the mystery, and seize triumph amidst concealed dimensions."

## Solution

Participants will be presented with a PDF File. While it may seem like a harmless word document containing the description of a certain laboratory or classroom where they might find a suitable solution to the puzzle. Though they may try, there is no reward waiting for them in the room. The solution to this is within the paragraphs

This mode of text steganography converts the secret message to bits and converts the letters in the cover text to uppercase when the bit is 1 at the same index in the bitstring or leaves the letter in lowercase when the bit is 0 at that index. 

For example, the secret message starts is "se", which in ASCII is 0x73 and 0x65 and in binary form it is "01110011" and "01100101".  Then the binary sequence of each secret character is reversed, so we get the bitstream: "11 00 11 10  10 10 01 10".  The conversions for the 16 (non blank) cover-text letters then look like this: 

Lorem ipsum dolor sit amet         [original cover text] 
lorem ipsum dolor sit amet          [cover text in lowercase] 
LOreM IPsUm DolOR sit amet  [cover text adapted according to the bitstream] 
11 00 11 10 10 10 01 10       [bitstream used for adapting the case of the letters]

1. Identify the pattern and obtain the binary sequence of each paragraph
2. Decode the cover text to a binary sequence
3. Convert the binary sequence to ASCII. 
4. This will still be in a base64 format which the participant will need to convert to UTF-8 to obtain the final answer

The following are the secret messages in each of the paragraphs in order
Answer to the question is `BIOTECHNOLOGY`

`SW5jb3JyZWN0X0Fuc3dlcg==` - Incorrect_Answer
`V3JvbmdfQW5zd2Vy` - Wrong_Answer
`QklPVEVDSE5PTE9HWQ==` - BIOTECHNOLOGY
`SW5jb3JyZWN0X2FnYWlu` - Incorrect_Again

## Hints:

 - Capital Letters Binary Sequence (Consider using Zero Padding) & Change format.