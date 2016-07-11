Changelog
=========

2.0.1 (2016-07-11)
------------------

 * [!]: fixed return from "DB->query()" and "Prepare->execute()"
        -> e.g. if an update-query updated zero rows, then we return "0" instead of "true" now


2.0.0 (2016-07-11)
------------------

INFO: There was no breaking API changes, so you can easily upgrade from 1.x.

 * [!]: use "MYSQLI_OPT_INT_AND_FLOAT_NATIVE" + fallback
 * [!]: fixed return statements from "DB"-Class e.g. from "query()", "execSQL()"
 * [!]: don't use "UTF8::html_entity_decode()" by default
 * [+]: added "Prepare->bind_param_debug()" for debugging and logging prepare statements