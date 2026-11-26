Wholesale Stockist Tracker (sample)

A small, single-page dashboard that shows where every wholesale applicant stands in an approval process, and which ones are stuck waiting.

Live demo: https://emesza.github.io/wholesale-tracker-sample/

All shops, cities and numbers in this demo are fictional. It is a mock-up built to show the idea, not a real company's data.

The problem

Many small brands accept wholesale applications through a simple form, then handle each one by hand: review the application, approve it, send an agreement, wait for the signature, send a welcome email with a customer ID and catalog link, and finally wait for a first order. With more than a handful of shops in progress, it is easy to lose track of who is waiting on whom.

What this does
Key numbers at the top: shops in the pipeline, shops waiting too long, share that signed the agreement, first orders placed.
Pipeline view that shows how many shops reached each of the six stages.
Shop table you can filter by stage and sort by any column, with a "waiting too long" flag and a suggested next action for each shop.

The stages and alert thresholds are examples. In a real setup they would be tuned to how the team actually works.

How to use it

Open index.html in any modern browser. There is nothing to install and no server needed.

Tech

Plain HTML, CSS and JavaScript in one file. No dependencies. Works in light and dark mode and on mobile.

Adapting it to real data

The demo reads from a small array in the page. A real version would load a CSV export from the application form or spreadsheet the team already uses (for example Google Forms or Sheets), clean it, and compute the same stages and flags automatically. If you have a similar process and want something like this, feel free to get in touch.

Author

Matheus Souza Gomes, Data Science and AI student. Contact: itsemezing@outlook.com
