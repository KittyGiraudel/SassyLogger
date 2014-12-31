SassyLogger
===========

Read [API documentation](http://hugogiraudel.com/SassyLogger).

The idea is to provide some kind of friendly API to log stuff in Sass,
including a way to log different type of messages (warnings, errors...).
This is obviously mainly aimed at framework and library developers.

Current implementation provides:

- 5 levels of logging ("DEBUG" "INFO" "WARN" "ERROR" "FATAL");
- a minimum level at which the logger starts printing;
- an history of all logs, that can be printed as CSS;
- a friendly API with easy-to-use functions;
- a helper to learn more about different levels of logging.

Find a proof of concept on [SassMeister](http://sassmeister.com/gist/9353f7e875a01502313e). Although note that SassMeister doesn't show `@warn` but this code would print content in the console in a regular environment.
 
Feel free to do whatever you want with this.
