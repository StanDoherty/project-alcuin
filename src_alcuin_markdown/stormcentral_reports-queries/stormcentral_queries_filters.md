# StormCenter query filters {#r_mv_query_filters .reference}

|Query filter|Associated reports|Description|
|------------|------------------|-----------|
|**Access rule**|-   Access rule configuration

|Select the access rule to investigate.|
|**Acknowledged by**|-   Alarm report

|Users who acknowledged the alarm.|
|**Acknowledged on**|-   Alarm report

|Alarm acknowledgement time range.|
|**Action taken**|-   Hits

|User hit actions \(Monitor, Diagnose, Clear\).|
|**Acknowledgement type**|-   Alarm report

|Check one of the following acknowledgement type options: Alternate
:   Alarm was acknowledged by a user using the alternate mode.

Default
:   Alarm was acknowledged by a user, or auto-acknowledged by the system.

Forcibly
:   An administrator forced the alarm to be acknowledged.

|
|**Alarm priority**|-   Alarm report

|Alarm priority.|
|**Alarms**|-   Alarm report

|Select the types of alarms you want to investigate.|
|**Application**|-   Activity trails
-   Audit trails

|Which client application was used for the activity.|
|**Archiver**|-   Archiver events

|Select the Archivers to investigate.|
|**Clusters**|-   Cluster activities

|Select the clusters to investigate.|
|**Compare with**|-   Inventory report

|Compare entities with a source entity of the event.|
|**Creation time**|-   Incidents

|Incidents created/reported within the specified time range.|
|**Credential**|-   Credential management

|Specify whether or not the credential is assigned.|
|**Custom fields**|-   Most reports

|If custom fields are defined for the entity you are investigating, they can be included in this report.**NOTE:** You might not see the custom fields filter, depending on whether your user is configured to view that custom field.

|
|**Description**|-   Activity trails
-   Credential management

|Restrict the search to entries that contain this text string.|
|**Devices**|-   IO configuration

|Select the devices to investigate.|
|**Entities**|-   Audit trails

|Select the entities you want to investigate. You can filter the entities by name and by type.|
|**Health event**|-   Health history

|Name of the health event.|
|**Health severity**|-   Health history

|Severity level of the health event.|
|**Hit rules**|-   Hits
-   Reads

|Select the hit rules to include in the report.|
|**Hit type**|-   Hits

|Select the type of hits to include in the report.|
|**Impacted**|-   Activity trails

|The entities that were impacted by this activity.|
|**Incident time**|-   Incidents

|Incidents reported within the specified time range. The incident time corresponds to the event or alarm timestamp the incident refers to. If the incident does not refer to any event or alarm, then the incident time corresponds to the creation time.|
|**Initiator**|-   Activity trails

|User responsible for the activity.|
|**Investigated by**|-   Alarm report

|Which user put the alarm into the *under investigation* state.|
|**Investigated on**|-   Alarm report

|Specify a time range when the alarm was put into the *under investigation* state.|
|**Machine**|-   Health history

|Select a computer that was having health issues to investigate.|
|**Modified by**|-   Audit trails

|User responsible for the entity modification.|
|**Modification time**|-   Audit trails
-   Incidents

|*Audit trails* task
:   Entities modified within the specified time range.

*Incidents* task
:   Incidents modified within the specified time range.

|
|**Notes**|-   Incidents

|Enter text to find incidents with a description starting or containing the specified text.|
|**State**|-   Alarm report

|Current state of the alarm.Active
:   Alarm is not yet acknowledged. Selecting an active alarm shows the alarm acknowledge buttons in the report pane.

Acknowledged
:   Alarm was acknowledged by a user, or auto-acknowledged by the system.

Under investigation
:   Alarm with an acknowledgement condition that is still active was put under investigation.

Acknowledgement required
:   Alarm with an acknowledgement condition that was cleared is ready to be acknowledged.

|
|**Triggered on**|-   Alarm report

|Alarm trigger time range.|
|**Triggering event**|-   Alarm report

|Events used to trigger the alarm.|
|**Users**|-   Hits
-   Reads

|Select the user name.|

**Parent topic:**[StormCenter reports and queries](../stormcentral_reports-queries/stormcentral_reports_intro.html)

