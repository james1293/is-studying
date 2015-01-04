is-studying
===========


##Priorities:
1. DONE! Basic web interface.
  1. Absolutely basic: Just names of people studying. Not even subjects. (They can add subjects if they want)
  2. So must have way to say "Add me" (include name) and "Remove me".
    3. Going to assume each person will only remove themselves.
    4. Need to tell user if didn't remove (i.e. spelled wrong)
    



----------------------

Below:THE BIGGER PLAN
===============

Is studying happening in the tutor room?


User goes to site, say
tinyurl.com/is-anyone-studying-something-like-this

And sees...

--------------

#Is Anyone Studying?

Subject|Number of people studying now
-------|------------
PHYS 1111 | 2
PHYS 3000|1
Unspecified| 2

Password: __________

--------------

Logging in will allow web users to see names of people studying, if the people have chosen to have their name visible.

Sidenote: I think the server can be a galileo (or Rasp Pi) sitting at my house, because the GRU network is NOT worth dealing with (Trying to get server permissions, etc. -- I know I'm not saying this right, but .... just avoid the GRU network for anything that's not just client-type behavior.) 


...And now,

#The Interface in the Room

If we wanted to go SUPER SIMPLE, we could have just buttons for the class. So basically don't record that "name" is studying, just "subject" is being studied.
This avoids having a full keyboard, and makes it very easy to use.
(Doing a quick count in my head, there are 15 total physics and chemistry classes offered every semester.)

There would also be a single switch, which would let the user "Add" or "Subtract" from the total.

So you have

1 OR 2 LINE SCREEN: SHOWS THE MOST RECENT COMMAND THAT WAS EXECUTED (like Added 1 person to studying Phys 1111)

SWITCH (Choices are Add or Subtract)

BUTTON FOR EACH CLASS (about 15 buttons)


##More interface ideas (but I really do like the idea mentioned just before this)

1) Keyboard to type name
2) Screen to show name
3) OR... just a touch screen...
3) Optionally, the same list that is shown on the web interface (But people can always just, you know, ask around: "Who's studying PHYS 1111?")


#Future Directions
1) On the Web interface: Way to say "I will be there at [time]"
2) Log in with Facebook??
