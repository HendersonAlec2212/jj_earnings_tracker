# jj_earnings_tracker

The purpose of this project was to create a database to track the earnings accrued while working in the 'gig' economy as a delivery driver. I thought it would be fun to see a day by day comparison of how much I would earn with this job in comparison to my previous job as a Kitchen Manager at Chipotle.

I started by constructing basic functions/methods to request user information about the work shift, check the information using ValueError as a condition to reset in the event of user error. Information is aggregated and the final data is sent to a MongoDB as a document inside an already specified Collection.

The second part of this project works by displaying databases available to the user, and requesting which Database and the Collection to load. Once loaded the information about the shift is graphed using MatPlot and displayed via Plot and Data Frame before being saved in their respective formats, PNG and JSON.

I like the concept of doing this to track the information over time to see just how much more profitable gig-style work is in comparison to a full-time job as a team leader in the Food Service Industry. Analyzing information is fun when you have a large dataset to poke around but having the chance to experience a dataset being made around events in my own life has a small charm to it.

![Plot Comparison](https://github.com/HendersonAlec2212/jj_earnings_tracker/blob/
main/visualizations/JJ_vs_Chipotle_Earnings.png)

![Earnings per Weekday](https://github.com/HendersonAlec2212/jj_earnings_tracker/blob/main/visualizations/avg_per_weekday.png)


Email: hendersonalec2212@gmail.com
LinkedIn: https://www.linkedin.com/in/alec-henderson-8011b521a/
