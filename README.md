# Awesome Time [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome tools, techniques, and resources for understanding and working with time. Inspired by [awesome-go](https://github.com/avelino/awesome-go) and all the other [awesome lists](https://github.com/sindresorhus/awesome).

Please [contribute](./CONTRIBUTING.md) to the list!

## Table of Contents

- [Concepts](#concepts)
- [Provenance](#provenance)
- [Identity, State, and Values](#identity-state-and-values)
- [Databases](#databases)

### Concepts

General concepts about time or used when modeling time-based systems.

- [Immutability](https://en.wikipedia.org/wiki/Immutable_object) - A property of something which prevents it from being changed.
- [Perdurantism](https://en.wikipedia.org/wiki/Perdurantism) and [Endurantism](https://en.wikipedia.org/wiki/Endurantism) - Philosophical theories of persistence and identity.
- [Temporal logic](https://en.wikipedia.org/wiki/Temporal_logic) - Any system of rules and symbolism for representing, and reasoning about, propositions qualified in terms of time.

### Provenance

Resources that pertain to modeling, storing, or using [provenance](https://en.wikipedia.org/wiki/Provenance) data.

- [W3C PROV](http://www.w3.org/TR/prov-overview/) - Specification based on Semantic Web technologies for modeling provenance data including a data model, constraints, semantics.

### Identity, State, and Values

Resources that discuss the differences between identity, state, and values.

- [Persistent data structures and managed references](http://www.infoq.com/presentations/Value-Identity-State-Rich-Hickey) - A talk by Rich Hickey about identity, state, and values.
- [The database as a value](http://www.infoq.com/presentations/Datomic-Database-Value) - Rich Hickey talks about immutability, epochal time, and persistent data structures.

### Databases

Databases where time is a first class concept.

- [Badwolf](https://github.com/google/badwolf) - BadWolf is a temporal graph store loosely modeled after the concepts introduced by the Resource Description Framework (RDF).
- [Datomic](http://www.datomic.com) - Immutable database of facts with *time-travel* queries.
- [InfluxDB](https://influxdb.com) - Scalable datastore for metrics, events, and real-time analytics.
- [Prometheus](http://prometheus.io) - An open-source service monitoring system and time series database.
