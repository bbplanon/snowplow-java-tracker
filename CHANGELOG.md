Version 0.4.0 (2014-07-23)
--------------------------
Added support for in-memory batching (#6)
Added POST support (#7)
Added Python-style subject class (#22)
Created an async HTTP request solution (#37)
Replaced contracts with cofoja (#43)
Removed configurations HashMap (#45)
Added additional methods that don't require setting a context Map (#48)
Retrieves Snowplow version automatically pulled from Gradle (#13)
Added additional methods that don't require setting a timestamp (#49) 

Version 0.3.0 (2014-07-13)
--------------------------
Added ability for contexts to be HashMap, not just JSON string (#11)
Added SLF4J logging for key events (e.g. tracker initialization) (#15)
Added timestamp as option to each track method (#26)
Created unit tests for Payload class (#34)
Created unit tests for Utils class (#35)
Updated Jackson dependency to newer version (#38)
Removed the Contracts class and any use of it (#42)
Removed support for context passed in as String (#44)

Version 0.2.0 (2014-07-02)
--------------------------
Moved all 3 main()s into unit tests (#5)
Added Travis support to README (#9)
Replaced org.JSON code with Jackson 1.9.13 (#14)
Renamed PlowContractor (#19)
Camelcased all functions (#20)
Made sure null fields are left off from querystring (#21)
Removed Tracker base constructor (#23)
Added tests for track_ecommerce_transaction and _transaction_item (#25)
Made track_ecommerce_transaction_item private (#29)
Changed transaction_items to use a Class, not a Map (#31)
Removed event_name and event_vendor from trackUnstructEvent (#32)
Removed context_vendor from Tracker constructor (#36)
Created Constant class or equivalent (#33)

Version 0.1.0 (2014-06-19)
--------------------------
Initial release, huge thanks @GleasonK!