I just came with the idea: what if I made a caesar cipher encrypter and decrypter? Can I do it in C? That's why I made this. I'm still a beginner in programming, so I'll listen to any suggestions to help make my code better.

If you want to try it out just download the source code, run "make" on the terminal and execute the file that corresponds to what you want to do (encrypt or decrypt) located in the "bin" folder, giving it a string to encrypt or decrypt, for example:

----------------------------------------
./bin/encrypt 'Hello! my name is Renan!'
----------------------------------------

The output is going to be the encrypted string in this case, but it works the same way for decrypting too. But to run it, you need to compile it first (using "make", as I said earlier).

When making, there's also "make clean" and "make install-home", but that's more for testing and to put the new compiled binaries in my "~/bin" folder, where i put my own programs, although you can use them too if you want.

