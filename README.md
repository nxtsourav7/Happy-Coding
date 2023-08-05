# Happy-Coding
A Competitive Programming setup using VSCode for C++ users in Ubuntu with Debugging support.


## **Features**
1) VSCode ready to use out of the box .
1) Run `./templete.sh` in Ubuntu to reset the `Scratch` Folder.
1) All `.cpp` files automatically take input from `input.txt` and output to `output.txt` in the same folder.

## **Prerequisites**

1) Follow Steps 1-2 from [Official VSCode Linux Prerequisites](https://code.visualstudio.com/docs/cpp/config-linux#_prerequisites)
1) Make sure g++ is installed
    * Install
        ```bash
        sudo apt-get update
        sudo apt-get install build-essential
        ```
    * Check Installation
        ```bash
        g++ --version
        gdb --version
        ```

You are good to go!

## Installation
1) Download this repository.
    ```bash
    git clone https://github.com/nxtsourav7Happy-Coding.git
    ```

1) Open VSCode in `Happy-Coding` Folder.
    ```bash
    cd Happy-Coding
    code .
    ```

1) Open a Integrated Terminal by clicking on `Terminal -> New Terminal` or press `` Ctrl+ Shift + ` ``
1) You can always create a `Scratch` Folder from terminal by

    * Make the script executable (Only needed once)

        ```bash
        chmod +x templete.sh
        ```
    * Execute the script

        ```bash
        ./templete.sh
        ```
    Note: To reset the `Scratch` Folder at any time, you may run this command again.

## Usage
1) You should write your code in the `Scratch` Folder.
1) Press `F5` or click Right top cornner `Play` batton to run any `.cpp` file. The file will automatically take input from `input.txt` and write output to `output.txt`

Happy Coding!
