# retry
My own, simpler implementation of the retry tool. Lets you repeat a command until it succeeds.

# Installing
```sh
git clone https://github.com/HassanIQ777/retry.git
cd retry
```

# Running
```sh
chmod +x retry
./retry
```

# Usage
To use the program you just call it before whatever you want to repeat until success.

For example:

```sh
retry git clone https://github.com/HassanIQ777/retry.git
```

# Why?
This program can be very useful when you're trying to downoload a large file that might get interrupted like the github cloning process, but you want to make sure it automatically finishes the cloning ever if it gets interrupted for whatever reason.