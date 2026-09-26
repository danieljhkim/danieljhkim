### Daniel Kim

Backend and infrastructure engineer in San Jose. By day: distributed systems, search, and data infrastructure. After hours: tooling that lets AI coding agents do real work safely.

**Now building [constellation-works](https://github.com/constellation-works)**, a small set of
local-first tools for working with coding agents.

- **[orbit](https://github.com/constellation-works/orbit)**: a delivery layer for AI coding agents.
  An agent files work as a task; Orbit runs it in a sandboxed worktree with file locks and review
  gates, and every run ends in a pull request with an audit log. Works with Claude Code, Codex,
  Cursor, Copilot and others.
  `brew install constellation-works/tap/orbit`
- **[pulsar](https://github.com/constellation-works/pulsar)**: an MCP server that lets agents post
  to X as a human-authorized account without ever holding the credentials.
- Work in progress: [nebula](https://github.com/constellation-works/nebula) (idea lineage graph),
  [orbit-graph](https://github.com/constellation-works/orbit-graph) (code graph indexing),
  [orbit-research](https://github.com/constellation-works/orbit-research) (reproducible research
  workflows).

**Systems projects**

| | |
|---|---|
| [dsearch](https://github.com/danieljhkim/dsearch) | Distributed search engine: BM25, vector, and hybrid ranking over sharded Lucene indices |
| [kvDB](https://github.com/danieljhkim/kvDB) | Distributed key-value store in Java with shard routing, replication, and a control plane |
| [local-data-platform](https://github.com/danieljhkim/local-data-platform) | Local HDFS/YARN + Hive + Spark dev environment with profile-based config overlays |
| [monodev](https://github.com/danieljhkim/monodev) | Reusable dev overlays (agent instructions, scripts, editor config) without polluting git |

**Background:** distributed systems and fault tolerance · search infrastructure (Lucene,
embeddings, ranking) · Java and Go backend services · data platforms (Spark, Airflow, Hive,
Hadoop, GCP, AWS).

[danieljhk.com](https://danieljhk.com)
