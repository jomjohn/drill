---
title: "Reserved Keywords"
date: 2015-12-28 21:37:20 UTC
parent: "SQL Reference"
---
When you use a reserved keyword in a Drill query, enclose the word in
backticks. For example, if you issue the following query to Drill,  
you must include backticks around the word TABLES because TABLES is a reserved
keyword:

``SELECT * FROM INFORMATION_SCHEMA.`TABLES`;``

The following table provides the Drill reserved keywords that require back
ticks:

<table ><tbody><tr><td valign="top" ><h1 id="ReservedKeywords-A">A</h1><p>ABS<br />ALL<br />ALLOCATE<br />ALLOW<br />ALTER<br />AND<br />ANY<br />ARE<br />ARRAY<br />AS<br />ASENSITIVE<br />ASYMMETRIC<br />AT<br />ATOMIC<br />AUTHORIZATION<br />AVG</p><h1 id="ReservedKeywords-B">B</h1><p>BEGIN<br />BETWEEN<br />BIGINT<br />BINARY<br />BIT<br />BLOB<br />BOOLEAN<br />BOTH<br />BY</p><h1 id="ReservedKeywords-C">C</h1><p>CALL<br />CALLED<br />CARDINALITY<br />CASCADED<br />CASE<br />CAST<br />CEIL<br />CEILING<br />CHAR<br />CHARACTER<br />CHARACTER_LENGTH<br />CHAR_LENGTH<br />CHECK<br />CLOB<br />CLOSE<br />COALESCE<br />COLLATE<br />COLLECT<br />COLUMN<br />COMMIT<br />CONDITION<br />CONNECT<br />CONSTRAINT<br />CONVERT<br />CORR<br />CORRESPONDING<br />COUNT<br />COVAR_POP<br />COVAR_SAMP<br />CREATE<br />CROSS<br />CUBE<br />CUME_DIST<br />CURRENT<br />CURRENT_CATALOG<br />CURRENT_DATE<br />CURRENT_DEFAULT_TRANSFORM_GROUP<br />CURRENT_PATH<br />CURRENT_ROLE<br />CURRENT_SCHEMA<br />CURRENT_TIME<br />CURRENT_TIMESTAMP<br />CURRENT_TRANSFORM_GROUP_FOR_TYPE<br />CURRENT_USER<br />CURSOR<br />CYCLE</p></td><td valign="top" ><h1 id="ReservedKeywords-D">D</h1><p>DATABASES<br />DATE<br />DAY<br />DEALLOCATE<br />DEC<br />DECIMAL<br />DECLARE<br />DEFAULT<br />DEFAULT_KW<br />DELETE<br />DENSE_RANK<br />DEREF<br />DESCRIBE<br />DETERMINISTIC<br />DISALLOW<br />DISCONNECT<br />DISTINCT<br />DOUBLE<br />DROP<br />DYNAMIC</p><h1 id="ReservedKeywords-E">E</h1><p>EACH<br />ELEMENT<br />ELSE<br />END<br />END_EXEC<br />ESCAPE<br />EVERY<br />EXCEPT<br />EXEC<br />EXECUTE<br />EXISTS<br />EXP<br />EXPLAIN<br />EXTERNAL<br />EXTRACT</p><h1 id="ReservedKeywords-F">F</h1><p>FALSE<br />FETCH<br />FILES<br />FILTER<br />FIRST_VALUE<br />FLOAT<br />FLOOR<br />FOR<br />FOREIGN<br />FREE<br />FROM<br />FULL<br />FUNCTION<br />FUSION</p><h1 id="ReservedKeywords-G">G</h1><p>GET<br />GLOBAL<br />GRANT<br />GROUP<br />GROUPING</p><h1 id="ReservedKeywords-H">H</h1><p>HAVING<br />HOLD<br />HOUR</p></td><td valign="top" ><h1 id="ReservedKeywords-I">I</h1><p>IDENTITY<br />IMPORT<br />IN<br />INDICATOR<br />INNER<br />INOUT<br />INSENSITIVE<br />INSERT<br />INT<br />INTEGER<br />INTERSECT<br />INTERSECTION<br />INTERVAL<br />INTO<br />IS</p><h1 id="ReservedKeywords-J">J</h1><p>JOIN</p><h1 id="ReservedKeywords-L">L</h1><p>LANGUAGE<br />LARGE<br />LAST_VALUE<br />LATERAL<br />LEADING<br />LEFT<br />LIKE<br />LIMIT<br />LN<br />LOCAL<br />LOCALTIME<br />LOCALTIMESTAMP<br />LOWER</p><h1 id="ReservedKeywords-M">M</h1><p>MATCH<br />MAX<br />MEMBER<br />MERGE<br />METHOD<br />MIN<br />MINUTE<br />MOD<br />MODIFIES<br />MODULE<br />MONTH<br />MULTISET</p><h1 id="ReservedKeywords-N">N</h1><p>NATIONAL<br />NATURAL<br />NCHAR<br />NCLOB<br />NEW<br />NO<br />NONE<br />NORMALIZE<br />NOT<br />NULL<br />NULLIF<br />NUMERIC</p><h1 id="ReservedKeywords-O">O</h1><p>OCTET_LENGTH<br />OF<br />OFFSET<br />OLD<br />ON<br />ONLY<br />OPEN<br />OR<br />ORDER<br />OUT<br />OUTER<br />OVER<br />OVERLAPS<br />OVERLAY</p></td><td valign="top" colspan="1" ><h1 id="ReservedKeywords-P">P</h1><p>PARAMETER<br />PARTITION<br />PERCENTILE_CONT<br />PERCENTILE_DISC<br />PERCENT_RANK<br />POSITION<br />POWER<br />PRECISION<br />PREPARE<br />PRIMARY<br />PROCEDURE</p><h1 id="ReservedKeywords-R">R</h1><p>RANGE<br />RANK<br />READS<br />REAL<br />RECURSIVE<br />REF<br />REFERENCES<br />REFERENCING<br />REGR_AVGX<br />REGR_AVGY<br />REGR_COUNT<br />REGR_INTERCEPT<br />REGR_R2<br />REGR_SLOPE<br />REGR_SXX<br />REGR_SXY<br />RELEASE<br />REPLACE<br />RESULT<br />RETURN<br />RETURNS<br />REVOKE<br />RIGHT<br />ROLLBACK<br />ROLLUP<br />ROW<br />ROWS<br />ROW_NUMBER</p><h1 id="ReservedKeywords-S">S</h1><p>SAVEPOINT<br />SCHEMAS<br />SCOPE<br />SCROLL<br />SEARCH<br />SECOND<br />SELECT<br />SENSITIVE<br />SESSION_USER<br />SET<br />SHOW<br />SIMILAR<br />SMALLINT<br />SOME<br />SPECIFIC<br />SPECIFICTYPE<br />SQL<br />SQLEXCEPTION<br />SQLSTATE<br />SQLWARNING<br />SQRT<br />START<br />STATIC<br />STDDEV_POP<br />STDDEV_SAMP<br />SUBMULTISET<br />SUBSTRING<br />SUM<br />SYMMETRIC<br />SYSTEM<br />SYSTEM_USER</p></td><td valign="top" colspan="1" ><h1 id="ReservedKeywords-T">T</h1><p>TABLE<br />TABLES<br />TABLESAMPLE<br />THEN<br />TIME<br />TIMESTAMP<br />TIMEZONE_HOUR<br />TIMEZONE_MINUTE<br />TINYINT<br />TO<br />TRAILING<br />TRANSLATE<br />TRANSLATION<br />TREAT<br />TRIGGER<br />TRIM<br />TRUE</p><h1 id="ReservedKeywords-U">U</h1><p>UESCAPE<br />UNION<br />UNIQUE<br />UNKNOWN<br />UNNEST<br />UPDATE<br />UPPER<br />USE<br />USER<br />USING</p><h1 id="ReservedKeywords-V">V</h1><p>VALUE<br />VALUES<br />VARBINARY<br />VARCHAR<br />VARYING<br />VAR_POP<br />VAR_SAMP</p><h1 id="ReservedKeywords-W">W</h1><p>WHEN<br />WHENEVER<br />WHERE<br />WIDTH_BUCKET<br />WINDOW<br />WITH<br />WITHIN<br />WITHOUT</p><h1 id="ReservedKeywords-Y">Y</h1><p>YEAR</p></td></tr></tbody></table></div>
