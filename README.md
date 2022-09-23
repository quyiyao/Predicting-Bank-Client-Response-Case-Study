# Predicting-Bank-Client-Response-Case-Study

# Problem statement:
Data: marketing campaigns data of a Portuguese banking institution. <br />
The marketing campaigns were based on phone calls. <br />
Often, more than one contact to the same client was required, in order to assess if the product (bank term deposit) would be ('yes') or not ('no')
subscribed by the client.<br />

The goal is to predict if the client will subscribe to a term product (variable Y).<br />

# Input variables:

# data that is specific to each client:
1 - age (numeric)<br />
2 - job : type of job (categorical)<br />
3 - marital : marital status (categorical)<br />
4 - education (categorical)<br />
5 - default: has credit in default? (categorical)<br />
6 - housing: has housing loan? (categorical)<br />
7 - loan: has personal loan? (categorical)<br />

# related with the last contact of the current campaign:
8 - contact: contact communication type (categorical: 'cellular','telephone')<br />
9 - month: last contact month of year (categorical)<br />
10 - day_of_week: last contact day of the week (categorical)<br />
11 - duration: last contact duration, in seconds (numeric). <br />
12 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)<br />
13 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)<br />
14 - previous: number of contacts performed before this campaign and for this client (numeric)<br />
15 - poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')<br />

# social and economic context attributes
16 - emp.var.rate: employment variation rate - quarterly indicator (numeric)<br />
17 - cons.price.idx: consumer price index - monthly indicator (numeric)<br />
18 - cons.conf.idx: consumer confidence index - monthly indicator (numeric)<br />
19 - euribor3m: euribor 3 month rate - daily indicator (numeric)<br />
20 - nr.employed: number of employees - quarterly indicator (numeric)<br />

# Output variable (desired target):
21 - y - has the client subscribed a term deposit? (binary: 'yes','no')<br />
