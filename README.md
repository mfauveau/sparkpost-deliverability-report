# SparkPost Deliverability Report

Do you want to send yourself a daily report of your SparkPost's account deliverability performance? Look no further! No more waiting on your TAM weekly report or fiddling around with the SparkPost UI to extract stats.

## Screenshot

![Daily Deliverability Report](screenshot.png?raw=true "Daily Deliverability Report")

## Install

1. Check out a clone of this repo to a location of your choice, such as: `git clone https://github.com/mfauveau/sparkpost-deliverability-report.git ~/sparkpost-deliverability-report`
2. Run `cd ~/sparkpost-deliverability-report && npm install` to get the dependencies (requires Node.js to be installed on the machine)
3. Create a `config.js` file based on the example provided: `cp config.js.example config.js && nano config.js`
4. Test the daily `~/sparkpost-deliverability-report/deliverability-report -d` and weekly `~/sparkpost-deliverability-report/deliverability-report -w` reports.
5. Setup cronjobs for the reports you'd like to receive.

## Update

Simply `git pull master` and make sure your config.js is up to date.

## Acknowledgement

Thanks to SparkPost's Clea and Todd for helping to make sure the formulas were right.
