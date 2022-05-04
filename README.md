# Click Farmer

The click farming business has really taken off recently.

The original click farming engineers started this project to count the number of
clicks around the world. However, they left to start another business.

They created a design document that describes how the system works, but they never
got around to finishing. We're not quite sure whether everything is correct either.

They say the system they left for you consists of a core database service they
wrote. In addition, they wrote a webserver. They expect to run many webservers
against one database concurrently, to handle the clickfarming load.

In the database folder you'll find the RPC server implementation that handles
database requests.

In the webserver folder you'll find the HTTP handlers and code which talks to
the database using protobuf + grpc defined in the pb folder.

In the docs folder you'll find the design document that the click farming
engineers wrote.

The goal is to get the product working to farm upvotes from around the world.
