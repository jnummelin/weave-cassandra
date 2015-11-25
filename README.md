# Weave Cassandra

This container is an extension of the official Docker [Cassandra](https://hub.docker.com/_/cassandra/) image which adds support for running in Weave networked containers.
Specifically, this container allows setting the `CASSANDRA_LISTEN_ADDRESS` and `CASSANDRA_BROADCAST_ADDRESS` environment variables to a value of `weave`.
Setting this value cause the container to discover the container's overlay IP address using the weave interface.

** NOTE **
Only the 3.0 and 2.2 "branches" are updated
