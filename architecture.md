+---------------------------+
|         Frontend         |
| (React.js, Tailwind, Vite)|
+------------+--------------+
             |
             v
+------------+-------------+
|        FastAPI API       |
| (Python, SQLAlchemy)     |
+------------+-------------+
             |
     +-------+--------+
     |                |
     v                v
+---------+    +-------------+
|PostgreSQL|    |   Neo4J    |
|  (Main   |    | (Graph DB  |
| Storage) |    | for fraud  |
|          |    | detection) |
+---------+    +-------------+
             |
             v
      +-------------+
      | Smart       |
      | Contracts   |
      | (Hardhat,   |
      | Solidity)   |
      +-------------+

