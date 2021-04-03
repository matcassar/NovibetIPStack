# NovibetIPStack

C# Interview Project

OVERVIEW
During this period of recruitment, we are seeking enthusiastic and talented software engineers,
who will participate in the design and development of enterprise scale applications as part of a
skilled, supportive, and diverse team. The role of the software engineer is to build
high-quality software that complies with coding standards and technical design. This project,
as part of the recruitment procedure, will help us understand your skills, and figure out the
exact position you will fit better.

GOALS
This project is divided into three main sections of development, and each of them is targeting
different level of skills, experience and coding patterns.
1. Dynamic Link Library (DLL) (1h-3h)
In the first part, we are going to create a library project. In this library, we will
consume a third party (external) free API, which provides information about IP
addresses. This library will expose a couple of public classes, through which the rest of
the code will communicate with the library and therefore with the API.
2. WebApi (3h-6h)
In the second part, we are going to create a WebApi project. This project will use the
library we previously created, and expose some functionality to web. For example, it
may serve a request for details for a specific IP, use the library to get the necessary
information, and send them back to the client.
3. WebApi: Batch Request Job (4h-6h)
In the last part, we are going to add some extra functionality to WebApi. It needs to
support a batch operation for updating IP details. First, it must expose a method where
a post request can be made providing an array of items of IP details that should be

updated. The caller will get a GUID as response, with which they can call a second
method of the WebApi later to get information about the progress of the job. Posted
items will be put into a buffer, where they will be processed in batches of 10 items
at a time.
4. Create Unit Tests (1h)
Create a simple project to perform Unit tests on the application build.
