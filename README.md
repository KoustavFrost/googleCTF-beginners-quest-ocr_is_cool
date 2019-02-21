# googleCTF-beginners-quest-ocr_is_cool

The name of the problem is OCR IS COOL and the description goes like this way:
> Caesar once said, don't stab me… but taking a screenshot of an image sure feels like being stabbed. You connected to a VNC server on the Foobanizer 9000, it was view only. This screenshot is all that was present but it's gibberish. Can you recover the original text?

The problem also came with an attachment. It is a zip file which contents a image file of png format named OCR_is_cool.png

#### How to approach the problem?
- The picture is a screenshot of an email but everything seems to be encrypted in this image.
- The name of the file and the challenge is also a big hint. 
- Trying Googling the term OCR.
- According to Wikipedia, OCR goes like this way : Optical character recognition or optical character reader, often abbreviated as OCR, is the mechanical or electronic conversion of images of typed, handwritten or printed text into machine-encoded text, whether from a scanned document, a photo of a document, a scene-photo (for example the text on signs and billboards in a landscape photo) or from subtitle text superimposed on an image (for example from a television broadcast).
- So baically we need a tool which can conver the image into text then we can proceed on with the decryption of the text.
- There are a lot of online tools available which can do OCR convertion. 
- After the conversion, try searching for a string which kinda looks a typical flag. Ex:- CTF{...}
- Now we need to decode it to find the original flag.
- Search for an online ROT decryption tool to convert it to the flag.

#### The answer is:
> CTF{caesarcipherisasubstitutioncipher}

#### Note:
- Try cropping the image before the OCR conertion. My result file was all messed up. Try using multiple OCR tool.
- ROT needs some studying or experience.

#### Future Plans:
- [ ] Make the write-up a bit more understandable.
- [ ] Planning to make an YouTube video on this CTF.