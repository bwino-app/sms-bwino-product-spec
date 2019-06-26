# Bwino SMS Prouct Specification Draft

Goals:

- Allow users to register using SMS
  - Documents: ID - used to check on ZRA site for real name and TPIN
- Allow users to borrow loans using SMS
- Allow users to add mobile wallets using SMS
- Allow users to add card using SMS\*

## Registration

- Users initiate the registration process by sending a message with a specified format to the specified number

      When the user sends START to [Bwino Number]

      Response: Welcome to Bwino! If possible, read our Ts & Cs here: (link to Ts & Cs) To continue with registration, please reply with your: FORENAME SURNAME e.g. Brian Mutale

      User: Brian Mutale

      Response: Thank you, [FORENAME]! What is your date of birth: DD MM YYYY

      User: 12 12 1989

      Response: To secure your account, please enter a 4-digit PIN

      User: 6789

      Response: Hey [FORENAME], could you please tell us your NRC number? You do not need to include the slashes e.g. 123456789 instead of 123456/78/9

      User: 574587631

      Response: Where do you live, [FORENAME]? Only your house or plot number is required in this step.

      User: Plot 7645

      Response: Nice! Which road is your house located on?

      User: Katondo Street

      Response: Which city are you located in?

      User: Lusaka

      Response: Thank you for registering with us. We will send you a message when your account is activated. Good bye!

## Borrowing Loans

## Adding Mobile Wallets

## Adding Debit/Credit Cards
