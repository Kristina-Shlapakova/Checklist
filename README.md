# Checklist for  [facebook](https://www.facebook.com/)
# [Log in](https://www.facebook.com/)
1.1 Check Log in with valid data (smoke test)

Expected result: log in to  account

1.2 Check Log in with empty fields(smoke test)

Expected result: Unable to log in

1.3 Check Log in with empty Login (smoke test)

Expected result: Unable to log in

1.4 Check Log in with empty Password (smoke test)

Expected result: Unable to log in

1.5 Check Log in with incorrect Login (critical pass)

Expected result: Unable to log in

1.6 Check Log in with incorrect Password (critical pass)

Expected result: Unable to log in

1.7 Сheck the email with spaces at the beginning and end (critical pass)

Expected result: log in to  account

1.8 Сheck the unregistered login or phone number (critical pass)

Expected result: Unable to log in

# [Forgot Password](https://ru-ru.facebook.com/login/identify/?ctx=recover&ars=facebook_login&from_login_screen=0)
2.1 Сheck the valid value

2.2 Сheck the unregistered login or phone number

# [Sign Up](https://www.facebook.com/r.php?locale=ru_RU&display=page)
3.1 Check all fields with valid data

3.2 Not fill  the required fields, click Sign Up

3.4 Check the phone number/email already registered users

3.5 Check the fields for the max/min number of symbols

3.6  The date of birth  select the current year

3.7 Enter first name in latin, last name in cyrillic




