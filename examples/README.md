# librdkafka examples

This directory contains example applications utilizing librdkafka.
The examples are built by running `make` and they will be be linked
statically or dynamically to librdkafka in the parent `../src` directory.

Begin with the following examples:

 * [consumer.c](consumer.c) - a typical C high-level consumer application.
 * [producer.c](producer.c) - a typical C producer application.
 * [producer.cpp](producer.cpp) - a typical C++ producer application.
 * [idempotent_producer.c](idempotent_producer.c) - Idempotent producer.


For more complex uses, see:
 * [rdkafka_example.c](rdkafka_example.c) - simple consumer, producer, metadata listing, kitchen sink, etc.
 * [rdkafka_example.cpp](rdkafka_example.cpp) - simple consumer, producer, metadata listing in C++.
 * [rdkafka_complex_consumer_example.c](rdkafka_complex_consumer_example.c) - a more contrived high-level C consumer example.
 * [rdkafka_complex_consumer_example.cpp](rdkafka_complex_consumer_example.cpp) - a more contrived high-level C++ consumer example.
 * [rdkafka_consume_batch.cpp](rdkafka_consume_batch.cpp) - batching high-level C++ consumer example.
 * [rdkafka_performance.c](rdkafka_performance.c) - performance, benchmark, latency producer and consumer tool.
 * [kafkatest_verifiable_client.cpp](kafkatest_verifiable_client.cpp) - for use with the official Apache Kafka client system tests.
