This is an agent based each Bacteria vs. Phages evolutionary model. The Bacteria
have a little Neural Network that influences their decision making. The Phages
can inject their RNA into the Bacteria and take-over the mechanisms in the cell,
including the decision making of the neural network. The phages move from 
diffusion (random-walks) or through the transport of a Bacteria.
The Neural Network evolves via a genetic algorithm.

There are many parameters to play with, which, will be optimized soon!

Also, please switch between the array and class (modular) approach by going into the "build.zig" file and changing the target from "main.zig" to "mainarray.zig" or vice-versa.

-------------------------------
IMPLEMENTED
-------------------------------
- Real time population display.
- Saving of neural networks.

-------------------------------
COMING SOON 
-------------------------------
- Better visualization of the agents.
- Display of Neural Nets
- Optimized code for faster runtime.
- CUDA integration?
- Loading of neural networks.


------------------------------
FUNCTIONAL THINGS
------------------------------
-----------------------
How to use!
-----------------------
Please download Zig! It is a great language after all!

If you have a debian distribution, install Zig via the following command:

$ sudo snap install zig

If you do not have the snap package manager, you can install it via:

$ sudo apt-get update

$ sudo apt-get install snapd

And then of course running the command to install zig.

$ sudo snap install zig


If you have a MacOS, you can install Zig via Brew with the following command:

$ brew install zig

Otherwise, you have to do a manual installation of Zig (see https://github.com/ziglang/zig).


In order to run and build the script, please ensure you have zig installed, and run the following command in your zig environment / directory.

$ zig build run -Doptimize=ReleaseFast 

![Model](https://github.com/mengsig/PreyNPredators/blob/main/picture.png?raw=true)

Please enjoy, and share!

By: Marcus Engsig & Mikkel Petersen.
