# Riddler-Can-You-Tell-When-The-Snow-Started

The details of the codeset and plots are included in the attached Adobe Acrobat reader (.pdf) file in this repository. 
You need to download the same to view the contents. There are referrals to other contents in BLUE colour also to follow.


    From Patrick Mayor comes a question about something we’re doing these
    days to keep ourselves and others safe: social distancing.

    You’re walking along the middle of a wide sidewalk when you see
    someone walking toward you from the other direction, also down the
    middle of the sidewalk, 12 feet away. Being responsible citizens, you
    pass each other while maintaining a distance of at least 6 feet at all
    times. By the time you reach each other’s original positions, you
    should be back in the middle of the sidewalk again.

    You should assume that the other person follows the same path you do,
    but flipped around (since they’re walking in the opposite direction).
    For example, you could both walk 3 feet to the left, 12 feet forward
    and finally 3 feet back to the right, walking a total of 18 feet
    before swapping positions.

    Being lazy (I mean, efficient), you’d like to know the shortest
    distance you and the other person could walk so that you can switch
    positions, all while staying at least 6 feet apart at all times. What
    is this distance?

Plan

I am basically going to simulate the process with very small time steps
and track the location of each person. These points can then be used to
measure the distance traveled by each person.
