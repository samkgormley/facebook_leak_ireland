# Facebook Leak (Ireland)

## Social Media Post
[Tableau Interactive Dashboard](https://public.tableau.com/profile/sam.gormley#!/vizhome/facebook_leak_ireland/FacebookLeakIreland)

Over the last few days, many of you will have read about a Facebook leak containing the personal information of more than 500 million user accounts.  The leaked data had been circulating on private forums for a fee since at least 2019, but it was made publicly accessible over the weekend.

More than 1.4 million Irish users were affected by the leak and I’ve aggregated the data to create this dashboard.  It illustrates the demographic trends contained within the dataset.
 
You can check whether your phone number was included in the leak using Troy Hunt’s ‘Have I Been Pwned’ website: https://haveibeenpwned.com. You will need to enter your number using its international format (e.g. 35387000000).

In the past 24 hours, Facebook has stated that it will not be notifying affected users of this leak. Its reasons include that it “was not confident it had full visibility on which users would need to be notified”, “that users could not fix the issue” and “that the data was publicly available”.

This leak does not contain any password information, but mobile phone numbers for all of the ~1.4 million Irish users are available. If your phone number is included you should be particularly vigilant of any calls or texts from unknown numbers that you receive.

**Sources:**
* [Wired](https://www.wired.com/story/facebook-data-leak-500-million-users-phone-numbers/)
* [Reuters](https://www.reuters.com/article/us-facebook-data-leak-idUSKBN2BU2ZY)
* [Irish Times](https://www.irishtimes.com/business/technology/have-you-been-hit-by-facebook-s-data-breach-here-s-how-to-find-out-1.4530187)

## Methodology
This project primarily uses pandas for wrangling and feature extraction.
The pycountries library proved useful to match up the quite messy location data with actual countries.
Tableau was used to build the actual visualisations.

I have decided not to include the dataset with the repository so as not to perpetuate the sharing of personally identifiable information, however the dataset is widely available online if you wish to replicate my methodology.
