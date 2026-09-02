# CobbEventMap
Map of all Events in Cobb, it'll update continously as more events are updated/added.


API endpoint that'll help out:
https://www.cobbcounty.gov/api/search/events?page=0&search=&fromDate=&toDate=&department=&category=&age=&location=
--> Will help with collecting data for 30 days maybe more however it doesn't describe the exact location of the event

- Will need to store the data in a database so we don't run into a api rate limit using a daily scheduled job.
- Have our own API designed to send out database data
- So more stuff to think about
