# CobbEventMap
Map of all Events in Cobb, it'll update continously as more events are updated/added.

Google Doc:[Start of SRS](https://docs.google.com/document/d/1Rgw3P0wztg_1fpQFE6azbV5ggrXr2gqih148aO_7AmQ/edit?usp=sharing)

Google Docs:[Start of SDS](https://docs.google.com/document/d/1lwd2MEzxqNC4RpjslsBRXzktGBvV2D-i4lqspM40Nbk/edit?usp=drivesdk)



API endpoint that'll help out:
https://www.cobbcounty.gov/api/search/events?page=0&search=&fromDate=&toDate=&department=&category=&age=&location=
--> Will help with collecting data for 30 days maybe more however it doesn't describe the exact location of the event

- Will need to store the data in a database so we don't run into a api rate limit using a daily scheduled job.
- Have our own API designed to send out database data
- So more stuff to think about
