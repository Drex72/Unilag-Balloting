## What it is?
A script to automate the process of Balloting for Unilag Hostels.

## 😕 How it works?
There are two scripts, one Handles balloting for a single person by taking their credentials and asking them for their hostel of choice and login into their accounts and extracts Fullname, Access Token, and also verifies JWT Token. If everything is correct and is in place, it executes the API endpoint which is responsible for balloting.
The second Handles Bulk Balloting where User credentials are stored in a csv and then passed into the system


## 🤖 Run:-
```
$ git clone https://github.com/Drex72/Unilag-Balloting
$ cd Unilag-Balloting
$ chmod +x Parallel-Balloting.sh
$ ./Parallel-Balloting.sh
```

## 📝 Note:-
Currently, I have redacted the password from the file for obvious reason. So it won't work as of now. Alternatively, you can create your own accounts and start using it on the script. Keep in mind that you can vote only one time with an account for the specific week's nomination.


## Caution:-
I don't know if this thing is legal or not. I've read the Terms & Conditions of unilag.edu.ng and I didn't find anything which could potentially indicate this script as illegal to use.