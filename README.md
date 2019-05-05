# logmaskarator sample

Sensitive information should be kept out of your log files.

This little springboot experimental project uses Apache Log4j 2 as the logging framework and was created to understand how to configure Log4j2 LogEventConverter plugin to mask sensitive information.

Current example allows to remove.
 * JWT tokens
 * Visa card Numbers
 * Visa 13 digit card numbers
 * American Express card numbers
 * MasterCard card numbers
 * DinersClub card numbers
 * Discovery card numbers
 * JCB 15 digit card numbers

