# What's new in the SkyPoint platform

We're excited to announce our newest updates and releases! This article summarizes public preview features, general availability enhancements, and feature updates. To see the long-term feature plans see the bottom of this page.

> [!TIP]
> To submit feature requests and product suggestions, email us at support@skypointcloud.com or use Github issues.

# December 2021 Updates

The updates in December 2021 include new features and bug fixes.

## Sprint 212 Release

### Resolved Issues:

#### SkyPoint Dataflow:
1. Created date in Dataflows has been fixed to reflect the created date time instead of showing current date time.

#### SkyPoint Predict:
1. "Preview" text has been removed from Prediction Models.

#### SkyPoint Activate:
1. "Preview" text has been removed from Audience.

#### Settings and Administration:
1. Pipeline failures when running scheduler has been fixed.
2. Issue while disabling the scheduler has been fixed.

### Feature Updates

#### SkyPoint Profile:

- **UI changes for Relationships** - UI for Relationships has been modified using Fluent UI.

#### Settings and Administration:

- **Scheduler Save and Edit Option** - Save is enabled when setting the scheduler for the first time. Once saved, the option to Edit is available.

# November 2021 Updates

The updates in November 2021 include new features and bug fixes.

## Sprint 212A Release

### Resolved Issues:

#### SkyPoint Dataflow:
1. UI issue for Tapin2 connector logo has been fixed.
2. Salesforce Marketing Cloud: User can now download only the required activities. Previously, all activities in the list were downloaded irrespective of the selection.
3. Floating header issue in entities has been fixed.

#### SkyPoint Empower:
1. Data settings tab is now working fine under Privacy Center. The error "Something went wrong" has been fixed.

#### SkyPoint Activate:
1. Decimal type attributes can now be added when creating business metrics.

#### SkyPoint Profile:
1. Navigation issues while transitioning different states during configuring enrichments has been fixed.
2. New Connection in Enrichment can now be saved. "Save" was shown disabled even after successful validation of the connection.
3. Activity Stream in Dashboard now displays activies in reverse chronological order.

## Sprint 211 Release

### Resolved Issues:
1. Pagination has been removed and breadcrumbs have been added on UI in **Dataflow** when adding new connectors.
2. UI issues in entities section have been fixed.
  - Total record count under entities is now visible. 
  - Filter option for Actions has been removed.

### Feature Updates

#### SkyPoint Profile:

- **Big query enrichment possible with only key validation** - Big query enrichment connection can be verified using Key file, project id and email id. There is no requirement to add Json file for validation.

- **UI changes for enrichment** - UI for enrichment has been modified using Fluent UI.

- **UI changes for entities** - UI for entities, attribute and data has been modified using Fluent UI.

#### SkyPoint Dataflow:

- **Tapin2 connector** - Tapin2 connector support has been added in Dataflow section.

- **Label inactive integrations** - Any datasource integrations which are not yet enabled show "Coming Soon" on hover.

#### SkyPoint Predict:

- **SkyPoint Predict**: UI for Prediction has been modified using Fluent UI.

- **UI changes for Custom Models** - UI for custom models has been modified using Fluent UI.

## Sprint 210 Release

### Resolved Issues:
1. UI issue related to incorrect header label for "Actions" under Insights > My Predictions has been fixed.

### Feature Updates
**Customer 360**:

- **Backup functionality for Instances** - Create and Restore Backup feature has been added for Instances. 

- **Associations renamed to Relationships**- UI change for renaming associations to Relationships has been implemented.

# October 2021 Updates 

The updates in October 2021 include new features, performance upgrades, and bug fixes.

## Sprint 210 mid-sprint Release

### Resolved Issues:
1. Skypoint Documentation link on the platform redirects to Overview page now. Previously user could only see Index page.
2. UI issues for Big Query enrichment have been fixed. The count of records enriched and the enriched data values are correctly visible under Entities.
3. UI issues for SFTP enrichment have been fixed. The count of records enriched and the enriched data values are correctly visible under Entities.

### Feature Updates: 

**Customer 360**:

- **UI changes for Timelines** - Timelines section view has been modified using Fluent UI.

- **UI changes for Dashboard widgets** - Widgets on the Dashboard have been  modified using Fluent UI.

- **View Instance Details** - Details for the Instances have been added- Refresh cadence, Organization ID , Security group and Type are available for every Instance. User can further edit to add more fields in Instance details.

- **Reset Functionality for Instances** - Reset functionality has been added under Instances. Three options are available for reset: **CDP data, Datavault data and Privacy center data**. Under CDP, further there are 3 options: 'Reset everything', 'Keep all dataflows', 'Keep all dataflows, settings for stitch and profile entity'.


## Sprint 209 Full Release 

### Resolved Issues:
1.Data, Insights and Actions get selected together on UI, only one should be shown as selected
2.Platform Level : Configured Audiences Not showing Up In Audience Page : Error 500
3.Unwanted text if0/00 is displayed on menu bar in place of sidebar collapse option

### Feature Updates: 

**Customer 360**:

- **Persist unique ID from previous run for Full refresh when running ML match**: The feature provisions that the same unique ID's are used in case of full refresh for ML match.

- **Enrichment for customer profiles using SFTP**: Enrich the profiles with data from SFTP now. The funtionality needs connection details, path to the SFTP file, user profile which needs to be enriched and attribute mapping between the user profile and the SFTP file. Save the enrichment created and hit Run. Currently, only csv file format is supported for SFTP enrichment.

- **UI changes for Dashboard** - UI for dashboard has been modified using fluent UI. Changes can be seen in the side bar, the headers, the cards section and the activity stream. Changes for the Graph section are in progress.

- **UI changes for Settings** - Settings section view has been modified using Fluent UI.

- **Cleanse your data by eliminating redundant records**: New feature has been added to remove the duplicate rows before mapping process. 

- **Export on schedule**: Three types of schedulers have been enabled for export. On every system refresh, every day and every week. Different time zones and timing can also be selected.

- **Create a new Instance from existing one**: Copy from existing instance funtionality takes care of copying the configurations for dataflow, enrichment, entity, timelines, metrics, audience, association, stitch and export.

- **Instance management history option**: History has been enabled for Instances.

- **FHIR Connector Support**: Support to import data from FHIR has been enabled in Dataflow. 
