=saros-via-http

A server + client for communicating between a Saros proxy embedded within an Eclipse instance, and a non-Eclipse IDE wishing to participate in a Saros session.

=Why do I want this?

You probably don't. It's a testbed/proof-of-concept for allowing IntelliJ to participate within a Saros session. It only supportss opening files (barely). Saros already uses a protocol for supporting multi-client text collaboration, called Jupiter. HTTP is not intended as a replacement.
