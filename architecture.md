
---

### architecture.md`

```markdown
# System Architecture

## Architecture Overview

MemoryDesk AI follows a memory-enabled conversational AI architecture.

The major components are:

```text
+----------------------+
|       User           |
+----------+-----------+
           |
           v
+----------------------+
|    Web Interface     |
+----------+-----------+
           |
           v
+----------------------+
|     AI Agent / LLM   |
+----------+-----------+
           |
           v
+----------------------+
|   Memory Processing  |
+----------+-----------+
           |
      +----+----+
      |         |
      v         v
+-----------+ +-----------+
|  Retain   | |  Recall   |
|  Memory   | |  Memory   |
+-----+-----+ +-----+-----+
      |             |
      v             |
+-------------------------+
|   Persistent Memory     |
|        Layer            |
+------------+------------+
             |
             v
+-------------------------+
| Context-Aware Response  |
+------------+------------+
             |
             v
+-------------------------+
|          User           |
+-------------------------+
