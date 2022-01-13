# jj_earnings_tracker


The purpose of this project was to create a database to track the eranings accrued while working in the 'gig' economy as a delivery driver. I thought it would be fun to see a day by day comparison of how much I would earn with this job in comparison to my previous job as a Kitchen Manager at Chipotle.

I started by production basic functions to request user information about the work shift, check the information using ValueError as a condition to reset in the event of user error. Information is aggregated and the final data is sent to a MongoDB as a document inside an already specified Collection.

The second part of this project works by displaying databases available to the user, and requesting which is to be loaded. The user selects the Database and the Collection to load. Once loaded the information about the shift is graphed using MatPlot and displayed viaa Plot and Data Frame before being saved in their respective formats, PNG and JSON.

I like the concept of doing this to track the information over time to see just how much more profitable gig-style work is in comparison to a full-time job as a team leader. The income so far has been consistently higher than at Chipotle and with much less to worry about, allowing me more energy to focus on projects like this.

![Plot Comparison](https://github.com/HendersonAlec2212/jj_earnings_tracker/blob/main/JJ_vs_Chipotle_Earnings.png)