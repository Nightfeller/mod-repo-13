# E-commerce Back End

## Description

This is a back end for E-commerce transactions, allowing you to preform GET, POST, PUT, and DELETE requests on the JSON files.
## Installation

To start, use ``` Ctrl + Shift + ` ``` to open up the Integrated Terminal. If you can't find where the backtick symbol is on your keyboard, it's usually to the left of the *1* key and above the *Tab* key.

Inside the terminal, you should see that it is in Powershell. To change it to Git Bash, go to the plus icon and click on the arrow besides it. There click on the option, *Git Bash*, to change the terminal to the compatible CLI.

Next, type in the terminal `npm install` or `npm i` to install the correct packages and dependancies. If any problems come up, follow the terminal instructions and use `npm audit fix` and/or `npm audit fix --force` to solve the problem. The instructions might also tell you to use `npm fund`. However, that is not needed.

You will also need to split the terminal to run mySQL. In order to do that, use `Ctrl + Shift + 5` in a terminal instance to split it into two seperate terminal. After that, run the code `mysql -u <username> -p`.

### Note

You will need a mySQL user for this back end. If you don't already have one, go to [this link here](https://www.digitalocean.com/community/tutorials/how-to-create-a-new-user-and-grant-permissions-in-mysql) to create a new user.
## Usage

The first thing you should do is run the command `scource db\schema.sql` in the mysql terminal. Then, in the bash terminal, run `npm run seed` to "seed" in the information for usage.

To actually use the back end, see [this video here](https://drive.google.com/file/d/1j1CPDg3MYn4cTlUgMJfFNPQPs3KVt6xO/view) for a simple walkthrough.
## Credits

There are no one to give credits to.
## License

There is no license for this product.
