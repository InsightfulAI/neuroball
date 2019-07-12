# Neuroball
Neuroball is a Swift Playground, meaning you will need [XCode](https://developer.apple.com/xcode/) or the [Swift Playgrounds](https://www.apple.com/au/swift/playgrounds/) iPad app to run it.

In Neuroball, you play against a hard-coded AI opponent in a Pong-like game. However, as you play, the game will record and store your movements, which can be used to train a neural network that imitates your playstyle. You can then play against this opponent. Unfortuantely, saving is not possible. However, you can play one of the four pre-trained networks, with the playing styles "Normal", "Aggressive", "Defensive", and "Idiot". Each style is distinctive with different difficulty levels. The "Aggressive" AI is considered the hardest while the "Idiot" AI is easy to beat - it will frequently miss the ball. I trained these AI by playing with different playstyles.

Neuroball uses its own implementation for the multi-layer perceptron models that are used to predict playstyles. Neuroball also contains its own linear algebra library which powers the neural nets; this is powered by the [Accelerate](https://developer.apple.com/documentation/accelerate) framework which provides access to libraries such as BLAS which is used to compute matrix operations quickly.

Neuroball was originally entered for WWDC Scholarships in 2019. Unfortunately, it was not accepted. Since then, Neuroball has been updated to support the iPad.
