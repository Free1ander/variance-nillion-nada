# variance-nillion-nada
This is one of example apps built using [nada by nillion](https://docs.nillion.com/)


## Steps to run app with test values
1. Clone or fork and clone this repo
2. Install nada

Get nilup
```
curl https://nilup.nilogy.xyz/install.sh | bash
```

install latest version of nillion sdk
```
nilup install latest
nilup use latest
nilup init
```

Check version
```
nillion -V

// Your output should be similar to the below
nilup 22c84830fff3c86beec27a8cb6353d45e7bfb8a4
```
3. Run app
```
nada run variance_integer_test_1
```
There are 4 ready tests in tests folder, but you can always the new one and run with it
