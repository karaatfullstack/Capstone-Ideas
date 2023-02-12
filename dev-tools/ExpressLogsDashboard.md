## Express Logs Dashboard

#### Overview
You will be building an dashboard application to visualize an Express server. When the user starts their Express server, a separate server starts up on a different port, rendering a collection of realtime interactive visualizations. They can see how many requests are coming in over time, which routes are getting hit, how long it takes to respond, and how often errors occur.

#### MVP
Your users should be able to
* Apply the custom Express middleware to an existing Express application (e.g. `app.use(expressDashboard({dev: true, port: 7070}))`)
* Persist a record of requests / responses, so users can track historical trends between restarts
* See a chart of incoming requests over time
* Filter outgoing responses by status code
* Visualize the response time for each request

#### Stretch Goals
Users can
* See a map of where the requests are coming from (e.g. by IP address)
* Also visualize database performance (e.g. reads and writes to the DB over time)
* Also visualize front-end performance, and track bugs in the browser (e.g. errors thrown in a React component)

#### Examples and Inspiration
* [Loggly Dashboard](https://www.loggly.com/docs/dashboards/)
* [Sentry Client-Side Logging](https://sentry.io/)
