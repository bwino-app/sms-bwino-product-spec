# Bwino SMS Prouct Specification Draft

Goals:

- Allow users to register using SMS
  - Documents: ID - used to check on ZRA site for real name and TPIN
- Allow users to borrow loans using SMS
- Allow users to add mobile wallets using SMS
- Allow users to add card using SMS\*

## Registration

Users initiate the registration process by sending different messages with a specified formats to the specified number.

1.  User registration

        Format: JOIN (space) FIRST NAME (space) LAST NAME (space) DD/MM/YYYY (space) NRC NUMBER (space) PIN
        User example: JOIN Brian Mutale 12/12/1989 952864/63/1 9852

2.  User address - house number

        ADDR PLOT/HOUSE_NUMBER
        User example: Plot 7645 Katondo Street

3.  User address - city

        CITY CITY_NAME
        User example: CITY Lusaka

4.  At this point, a thank you message can be sent to the user:

        Thank you for registering with us. We will send you a message when your account is activated. Good bye!

## Borrowing Loans

## Adding Mobile Wallets

## Adding Debit/Credit Cards
