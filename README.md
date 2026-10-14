# Jigsaw Learning — Google searches

A one-page dashboard showing every search people typed into Google before landing on the Jigsaw Learning website, for the **last full calendar month**. It rolls forward by itself on the 1st of each month.

What it shows, in plain language:

- Visits from Google, times shown, number of different searches, average spot on Google
- Visits day by day
- The 10 searches that brought the most visits
- Name searches vs topic searches, and searches asked as questions
- Quick wins (searches sitting just below the top) and searches seen a lot but rarely clicked
- Pages people landed on, devices, top countries
- A searchable, sortable list of every search, with CSV download

## Where the numbers come from

Google Search Console, through the EDGE AI Visibility Tracker web app (`action=gscQueries`, in `Gsc.gs`).

## Opening it

Nothing private is stored in this repo. The connection details travel in the link's `#` part, which browsers never send to GitHub:

```
https://edge-marketing-and-des1gn.github.io/jigsaw-learning-search-queries/#feed=<tracker /exec URL>&t=<client token>&domain=<domain>&name=Jigsaw%20Learning
```

Add `#demo` to the address to see it with sample numbers.
