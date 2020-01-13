# Ticket 10173 - Starting Two Apps at Once

Example repo for ticket 10173, press the `getData` button to request data from App B, if App B isn't running it will be launched with `fin.Application.startFromManifest` then the data will be sent back to App A via the [Channels API](https://cdn.openfin.co/docs/javascript/stable/InterApplicationBus.Channel.html).

### How to use this:

-   Clone this repository: `git clone https://github.com/connormccafferty/10173.git`
-   Install the dependencies: `cd 10173` & `npm install`
-   Start the live-server and launch the application: `npm start`
