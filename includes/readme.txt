>   netdb.h

It is modified to override the protection of addrinfo declaration.
The struct is now brought out of the #ifdef block
The struct inside the #ifdef declaration has been renamed to addrinfo__USE_XOPEN2K