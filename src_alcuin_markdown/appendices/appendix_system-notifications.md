# System notifications {#reference_C06313BF166040BA9C8C4C15D553C8EF .reference}

|Code Type|Value|Description|
|---------|-----|-----------|
|A|65778|Error. A task has failed to be processed and attempts to complete processing have been halted.

|
|B|70945|Warning. A task has not been completed within the expected time frame. The system will contine to attemp to complete the task.

|
|G|10010|Confirmation. Confirmation that a task has been successfully completed. Code extensions are used to provide further information about the time taken to complete the task:

-   3-a. Task completed within a timeframe < 20m

-   3-b. Task completed within a timeframe < 40m
-   3-c. Task completed within a timeframe = 50m
-   3-d. Task completed within a timeframe \> 60m

-   3-e. Task completed within a timeframe \> 80m

|
|X|99999|Log. Supplemental message transaction log has been generated \(in response to a configuration setting\).

|

**Parent topic:**[Appendices](../appendices/appendix_top.html)

