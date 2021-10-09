First draft of a functional programming lab assignment

My general idea is creating a Bank class which just contains a list of Accounts (each account has a name and balance)
The Bank can:
    print out all accounts
    add money to all accounts
    report accounts with negative balances
    report accounts with balances above a certain threshold 
    report the average balance across all accounts

I'm thinking that we provide code that implements the public Bank functions calling std::for_each, std::transform, std::copy_if, and std::accumulate
and the students would have to implement the delegate functions/closures that are passed into those calls (aka all private static functions).
But I'm still thinking about how much should be provided vs how much should be implemented by students.    
    