polyglot-message-system
=======================

Target
______

Creating a message system for different programming languages (PHP, Javascript, VBScript, Erlang, Java, ...) for collecting all kind of messages (notification, messages, debug information, loggings, alerts, errors, warnings, etc).
The messages should be send so a common mq-server, which distributes these messages to different output channels (like screen, file, notification, database).
Reeintegration of these messages in the original codebase (like done with phpdebugbar).
Monitoring-tool for the messages with filter.
