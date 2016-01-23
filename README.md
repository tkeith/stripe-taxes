This script will help you calculate your revenue & deductions for your Stripe account.

Instructions:

- Log into your Stripe account
- From the left side-bar, choose "balance"
- Click "view balance history"
- Click "filters", select only "date", choose "is between"
- For the start date, enter "1/1/(tax year)", and for the end date enter "12/31/(tax year)" (for example, 1/1/15 and 12/31/15 for the 2015 tax year)
- Click "export", and a .csv file should be downloaded
- Run "./process-balance-history (csv file path)"
