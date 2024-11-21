# ggplot_adventcalendaR
25-day advent calendaR providing an introduction to ggplot2!

Here it is! A 25-day ggplot advent calendaR, a follow-up to the <a href="https://kiirstio.wixsite.com/kowen/post/the-25-days-of-christmas-an-r-advent-calendar" >R advent calendaR </a> that teaches the very basics in R.

I know there are so so so many topics I did not cover in this calendaR. I wanted to give you a basic intro to ggplot so I've tried to do so by covering a lot of material using a few examples per day to show the power, versatility, and structure of ggplot2. You may notice that I didn't cover anything related to maps or spatial R. My next goal is a spatial R calendaR (:

I feel the need to note that I'm not an expert and in fact I learned a lot of this stuff while creating the calendaR (one of the reasons I wanted to do it in the first place!). I also created this calendaR on a tight timeline (2 days before December 1st), so there are bound to be mistakes. Please let me know if you find anything that needs to be fixed or flagged.

For this advent calendaR, I decided to do things a little differently. For one, I deposited everything to GitHub. This is much more efficient! I also used R Notebook files for each day. I believe this means you will need to use R Studio. I recently started using R Notebooks and I really like them, especially for something like this where I want to include a lot of notes along with the code. You can still run the code line by line in the chunks, but you can also click the play button on the right-hand side to run the whole chunk at once (this will come in handy on Day 25!).

Please let me know what you think! You can connect with me on BlueSky <a href="https://twitter.com/KiirstiO](https://bsky.app/profile/kiirsti.bsky.social" >@kiirsti.bsky.social </a>, X/Twitter <a href="https://twitter.com/KiirstiO" >@kiirstio </a> or Mastodon <a href="https://ecoevo.social/@kiirsti" >@kiirsti@ecoevo.social </a> - I like reading your comments!

Okay, enjoy and happy holidays!

P.S. I borrowed a lot of information and ideas from this source, so I want to highlight it again here: https://ggplot2-book.org/

<br>
*** TO GET STARTED ***

Click on the green button that says "CODE" and select "Download zip". This will download all the files for you to get started! I'd like to give people a chance to do this as an advent calendaR with minimal temptation to "cheat". After Christmas, I will post the full R Notebook file that I used to create this which has all 25 days in one file.

*** HAVING ISSUES?***

On Day 25, if you get an error about "Trees.X" does not exist, change read.csv() to read_csv(). This should fix the error. Read.csv() is automatically loaded in base R using package "Utils". Read_csv() is from package "readr" which is part of the tidyverse. Read_csv() loads the data in as a tibble (a tidy dataframe). I have already changed this in the Day 25 file, so if you are just downloading the files now, you can ignore this message :)
