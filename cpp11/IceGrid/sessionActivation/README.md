This demo demonstrates the use of the session activation mode where
the server is activated on demand once it is allocated by the client
and deactivated when the client releases the server.

To run the demo, first start the IceGrid service:

      icegridnode --Ice.Config=config.grid

In a separate window:

     icegridadmin --Ice.Config=config.grid -e "application add application.xml"
     client

This will deploy the application described in the file
`application.xml` and start the client.

Messages will be displayed in the IceGrid service window.
