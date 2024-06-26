# 默认账户密码

```
username：neo4j
password：neo4j
```

# Neo4j

**Neo4j** 是世界领先的图数据库。它是一个高性能图形存储，具有成熟且强大的数据库所需的所有功能，例如友好的查询语言和 ACID 事务。程序员使用灵活的节点和关系网络结构而不是静态表进行工作，但可以享受企业级数据库的所有好处。对于许多应用程序来说，与关系数据库相比，Neo4j 提供了数量级的性能优势。

## 核心功能

### 1. 图形数据模型

- **节点（Nodes）**：图数据库的基本单元，表示实体。
- **边（Relationships）**：连接节点的有向连接，表示实体间的关系。
- **属性（Properties）**：节点和边可以附带的键值对，用于描述节点和边的特性。

### 2. Cypher 查询语言

- **声明性查询语言**：类似 SQL，但专为图形数据库设计。
- **模式匹配**：基于图模式进行查询，简洁高效。
- **读写操作**：支持复杂查询、插入、更新和删除操作。

### 3. ACID 事务支持

- **原子性（Atomicity）**：确保所有操作都成功，或者在失败时回滚。
- **一致性（Consistency）**：数据库从一个一致状态转换到另一个一致状态。
- **隔离性（Isolation）**：并发事务互不干扰。
- **持久性（Durability）**：事务提交后，数据持久化保存。

### 4. 高性能和可扩展性

- **内存中图处理**：大部分操作在内存中完成，速度快。
- **水平扩展**：支持分片和复制，处理大规模数据。

### 5. 可视化工具

- **Neo4j Browser**：内置的交互式可视化工具，方便查询和结果展示。
- **Neo4j Bloom**：高级数据可视化和探索工具，适合商业用户。

### 6. 安全和访问控制

- **身份验证和授权**：基于角色的访问控制，确保数据安全。
- **SSL/TLS 加密**：保护数据传输安全。