# Hourly billing overview

You are billed on an hourly basis for each instance you launch on Amezmo. Although you will always see monthly
pricing on the Amezmo page, you are always billed hourly "behind the scenes." This feature has several advantages:

## Organized invoices
Always pay for your services on the first of every month, never in the middle of the month, or sparsely
throughout the month.

## Pay for what you use
If you only use an instance, for example, to test out a new PHP application, then you don’t have to pay
for a full month of service if you only require the instance for a few days.

## Hourly billing use case

If you terminate an instance, you will only pay for the total number of hours the instance was active during the
month. Let's go through an example. Alice launches an instance on January 6th, 2021. She then
imports a fresh application to test a new client project.

Unfortunately, her client informs her on January 9th, 2021 that they need to cancel the project. In turn,
Alice terminates the application on Amezmo and bills the client.
The total bill for Alice's usage on Amezmo for this client project would be for only 3 days, not a full month.

To calculate the total price, take the instance type and divide it by 744.
744 is the optimistic number of hours in a full month during a calendar year.
Since there are only ever a maximum of 31 days per month (and often less than that), 744 hours is the maximum
number of hours you're billed for during any given month. But it’s less than this during the months of
February, April, June, July, September, October, and November.