---
title: "Nested Data Limitations"
date: 2018-10-23
parent: "Nested Data Functions"
---
Do not use Map, Array, and repeated scalar types in GROUP BY or ORDER BY clauses or in a comparison operator. Drill does not support comparisons between VARCHAR:REPEATED and VARCHAR:REPEATED.
