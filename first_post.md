# An introduction to cryptography

## What is cryptography?

Cryptography is the study of methods of sending messages in an unrecognisable / disguised form such that only the 
intended recipient can read the message. Those who practice cryptography are known as crytpographer(s).

Below are some key terms that you will see used throughout these posts:

* Plaintext: The message that we wish to send
* Ciphertext: The disguised message
* Letter / Character: Any symbol that is used whilst writing the message.
* Alphabet: The collection of characters.
* Enciphering or Encryption: The process of converting plaintext to ciphertext.
* Deciphering: The reverse process of enciphering.
* Message units: Plaintext and ciphertext are broken up into message units.
* Cryptanalysis: Practice of revealing information hidden by cryptography using analytical and mathematical techniques,
without the consent of the cryptographer.

## Long Division

Long division is used frequently in cryptography and a large number of concepts within are based on this simple piece
of maths.

Let **a** and **b** be integers with a ≥ 0 and b > 0.

To do long division of **a** by **b** means to find integers q and r. Q being the quotient and r being the remainder. 
Thus it can be said that a = bq+r or a = (b*q) + r.

For example:

    14 = 3 * 4 + 2
    0 = 3 * 0 + 0
    15 = 3 * 5
    
    Note: 14 = 3 * 5 - 1 is not long division, no minus symbols are allowed.
    
If you wished to do long division on your ordinary pocket calculator like the ones that you may use in an exam you 
calculate this as follows:

    a / b = q.t
    
    q.t - q = 0.t 
    
    0.t x b = r
    
So let's see an example of this in action

    353278 / 8945 = ?
    
    a / b = 39.4944662 --> q.t
    
    q.t - q = 0.t = 0.4944662
    
    0.t x b = 0.4944662 * 8945 = 4424
    
    So that we can say:
    
    353278 / 8945 = 39 r 4423.
    
That concludes this introduction to cryptography.
    
    

