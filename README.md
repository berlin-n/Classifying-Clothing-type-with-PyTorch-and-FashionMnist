# Classifying-Clothing-type-with-PyTorch-and-FashionMnist

---

## Motivation:

I'm sort of a big fashion person, and I had this idea of being able to recommend styling fits based on clothing within an individual's possession.
For instance, maybe you 18 pairs of jeans of different styles, and 18 more tops, you might think you know the best fit combination, but what if
PyTorch knows more, because you can't argue with Maths, haha. I'm sure there's a lot more that needs to be understood about how the the data is represented in tensors, and how it affects the whole idea, thus my embarkment on this with FashionMNIST, which I didn't know was a thing, till I decided to do some Googling.

---
## ...
The notebook has comments, so I will not be going in depth.
First, I just realised, that in a real world scenario, images of clothes will be a lot more than 28 x 28 pixels, and for the use case in my head, they will need to have colors.
The data FashionMNIST provides won't be ideal for what I want to do-- might end up taking pictures of my own clothes-- that doesn't stop this though.

Also, since I've never used FashionMNIST, I learn't something about the data, which made sense. it's Tensors we're working with, not CSVs, at least not directly.
I checked the files after downloading the data, saw a bunch of files not familiar to me --I'm used to simple train.csv, test.csv.
Apparently, I use code to setup the training and testing data, and that's not all. I don't know if it's the same way for the other datasets in the "datasets" library,
but it comes as tuples of tensors, with each tuple having 2 values, X and Y, basically --image pixels and the category it belongs to.

