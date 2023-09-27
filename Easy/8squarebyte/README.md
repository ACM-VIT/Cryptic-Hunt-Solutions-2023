# (Question Name)

- **Category:** (Easy)
- **Mode:** (Offline)
- **Authors:**
  - Kaustav K. Patro
- **Points:** TBD

## Specifications

- **Entry point:** A static webpage which has an image
- **Reward:** TBD

## Description

What lies before you is more than just a link —it's a puzzle waiting to be unraveled.
https://8squarebytes-ch.netlify.app

## Solution

1. The rebus puzzle suggests that player must look for size of the "BASE". when the player opens the link and inspects the elements, he finds a link to a docX file. Player needs to determine the size of the "BASE" which is 64. This gives out the cipher, i.e base-64.
2. When player goes through inspect elements, he also finds a second hyperlink (which is hidden) in same webpage, it leads to another webpage.
3. The second webpage is seemingly blank but contains a string "VGhlIEx1bmdzIE9mIFRoZSBFYXJ0aA==".
4. The string is to be inserted in a base64 decoder (UTF-8 charset) which provides the location of the QR code. The string reads "The Lungs Of the earth" which suggests the Amazon kiosk near library.
5. Scan the QR code.

## Hints:

cost = 0
