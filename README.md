# simple CLI application that print the numbers from 1 to 10 in random order to the terminal. 

    brew install coreutils && shuf -e {1..10}
> **brew** can be installed for Linux/Mac and any other non-ARM processor by https://brew.sh/. For ARM ones, if using Mac, **Rosetta 2** can be used; and if using Linux, the repository should be cloned.

My favorite is shell, but there in a script in go, that can be executed by:

    brew install go && go build random.go && ./random

> **brew** can be installed for Linux/Mac and any other non-ARM processor by https://brew.sh/.

> **Test** files should be added also.
