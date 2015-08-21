### [Learn how to install!](https://github.com/chrisburgin95/pigarage/wiki/Instalation)
## What is this?
PIGARAGE is a dynamic multi user application for controlling your garage door
remotely from anywhere in the world. Its a little more complication but in
return will provide you with a larger feature base.

![Pi Garage Home](http://i.imgur.com/D7vS2HI.png)


## Key Features
#### Multiple Users
One of the key features of PIGARAGE is the ability to have multiple users with
a varying level of control. Below are the different types of users available:
    - Admin User: Add, Remove and Edit users.
    - Normal User: Toggle the garage door.
    - Temporary User: Toggle the garage door, this account expires on a set day.

The concept behind multiple users can be explained in this simple example.
    Your leaving on vacation and billy is watching your house, in the stone
    age you would leave billy a house key. But now you can just give him
    temporary access to open your garage door. If he looses his phone he can
    simply jump on the nearest computer and your cat continues to live. When
    you finally return from your trip billys account automatically expires on
    the date you set.

![Multiple User](http://i.imgur.com/rjRuYSy.png)

This also provides a great set of tools for future expansion of pigarage. Which
include a log to show admin users when the door has been opened and closed. So
you know if billy is actually feeding your cat(s).

#### Secure Login
Pi Garage is centered around the Idea that opening and closing your garage should be a secure operation that only approved parties can operate. Due to this the login system is very important, much time has gone into securing this system and doing countless tests to make sure this system is secured against to the outside world.

But who wants to login every single time they have to open their garage. No one does, because of this each login session will be stored until either this software is restarted or the end user logs out.

![Pigarage Login](http://i.imgur.com/7wxUytC.png)

#### Error Checking
A lot of simple projected created for the raspberry pi are thrown together and
easy to break. This is not the case with PIGARAGE. While I can not guarantee
that there will be no errors I can assure that there has been quite extensive
testing and bug fixing before this beta release. If you find an error please
let me know and I will fix it asap, please also feel free to submit pull
requests with any optimization or bug fixes.


## Future Features
#### Log
The next logical step in a user based system is to track when users open
and close the garage door. This can be great for parents or if you are
away on vacation with a house sitter(billy).



#### Webcam
This is going to need to be implemented on a user by user basis. I will
add the ability for PIGARAGE to show a webcam photo in the area below the
home button. Each time the home page is loaded PIGARAGE will look for a
a shell file to execute and take a photo that PIGARAGE will load. This is
where its left to the user, I will provide a shell script with support for
common web cam types.

The webcam will be used to show whether the garage door is open or closed,
as you noticed the application says "Toggle Door". I wanted to keep this
simple and avoid purchasing extra equipment to provide an actual status of
the door. I believe it is more important to be able to see the door and the
enviorment around.

Note: If the user has no script written the application will look as currently
presented with no webcam photo.



## Code Notes
My code is not perfect and is in need or organization, this is one of the areas
I will be strongly focusing on before moving forward with more features. My
goals include making sure im not writing code twice and providing a bug free
user experiance.

## Known Bugs
- Users page has more grey area above the login than below.
