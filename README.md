# Google API & MCP Sandbox
This is an API sandbox for the Google API & MCP Sandbox, using an OpenAPI specification with examples, Microcks and Bruno as the sandbox interface, and this GitHub repository as the vehicle for delivering a localized sandbox.

## Capability-Driven
This sandbox is capability-driven, using an early [prototype of the Naftiko capability schema as the manifest](capability-google-sandbox.yml). The manifest provides the mapping to the OpenAPI source for the sandbox and guides the evolution of the sandbox, aligning with business outcomes—something we will keep iterating upon.

## OpenAPI
This sandbox uses OpenAPI as the definition, providing [a complete definition of all available paths for the Google API & MCP Sandbox. The OpenAPI for this sandnbox uses examples and Microcks extensions to mock the requests and responses for each API operation, something we will iterate and expand upon with richer examples as we move forward.

## Microcks
This sandbox uses Microcks to deliver the mock API. [You just install Microcks, with the Docker extension being the easiest](https://microcks.io/documentation/guides/installation/docker-desktop-extension/), [import the OpenAPI as a service](openapi/notion-openapi.yml), and you have a mocked API for all APIs, available via REST and MCP APIs--providing a multi-protocol sandbox.

## Bruno
This sandbox [uses Bruno as the client](https://www.usebruno.com/), leveraging Bruno Collections pre-generated from the OpenAPI and Bruno environments that uses the localhost and port of Microcks to work with the mocked API. You just have to install Microcks, then open the collection provided in this repository, select the available environment, and begin calling the Google API & MCP Sandbox via the sandbox.

## Summary
This is a summary of this sandbox, breaking down the available paths, operations, and other relevant detail regarding the scope of this sandbox, designed to support development and testing against the Google API & MCP Sandbox.

- Number of Paths: 140
- Number of Operations: 209
- Number of Read Operations: 74
- Number of Write Operations: 135
- Number of Schemas: 644
- Number of Responses: 0
- Number of Parameters: 48
- Number of Examples: 125
- Number of Request Bodies: 0
- Number of Headers: 0

## OpenAPIs
These are the OpenAPIs available for the Google API & MCP Sandbox, which are made available via this sandbox API, which can be imported into Microcks and deployed as a sandbox using their mock feature.

  - [Google Calendar Api](openapi/google-calendar-api-openapi.yml)
  - [Google Docs Api](openapi/google-docs-api-openapi.yml)
  - [Google Drive Activity Api](openapi/google-drive-activity-api-openapi.yml)
  - [Google Drive Api](openapi/google-drive-api-openapi.yml)
  - [Google Drive Labels Api](openapi/google-drive-labels-api-openapi.yml)
  - [Gemini Api](openapi/google-gemini-api-openapi.yml)
  - [Google Gmail Api](openapi/google-gmail-api-openapi.yml)
  - [Google Sheets Api](openapi/google-sheets-api-openapi.yml)

## Resources
These are the resources available via the Google API & MCP Sandbox, which are made available via this sandbox API, which are applied as tags to each operation in the OpenAPI.

  - About
  - Activity
  - Address
  - Addresses
  - Applications
  - Attachments
  - Audio Understanding
  - Auto
  - Batch
  - Batch Operations
  - Calendar Acl Rules
  - Calendar Acls
  - Calendar Events
  - Calendars
  - Cell Values
  - Changes
  - Channels
  - Colors
  - Comments
  - Content Generation
  - Create
  - Data Filters
  - Default
  - Delegates
  - Deletes
  - Developer Metadata
  - Disables
  - Document Understanding
  - Documents
  - Drafts
  - Drives
  - Enables
  - File Api
  - Files
  - Free Busy
  - Get
  - History
  - Image Generation
  - Import
  - Info
  - Insert
  - Labels
  - Language
  - Limits
  - Lists
  - Messages
  - Modify
  - Notifications
  - Obliterate
  - Patch
  - Permissions
  - Pop
  - Profile
  - Replies
  - Revisions
  - Send
  - Sets
  - Setting
  - Settings
  - Sheet Management
  - Speech Generation
  - Spreadsheet Management
  - Stop
  - Streaming
  - Team Drives
  - Threads
  - Trash
  - Update
  - User Calendars
  - User Settings
  - Users
  - Vacation
  - Verify
  - Video Understanding
  - Watch

## Operations
These are all of the available operations in this sandbox, providing a complete view of what you can do within this sandbox using the mocked Google API & MCP Sandbox.

  - Append Cell Values
  - Batch Clear Cell Values
  - Batch Clear Values By Data Filter
  - Batch Delete
  - Batch Get Cell Values
  - Batch Get Values By Data Filter
  - Batch Modify
  - Batch Update Cell Values
  - Batch Update Spreadsheet
  - Batch Update Values By Data Filter
  - Calendar
  - Clear Calendar
  - Clear Cell Values
  - Copy Sheet To Another Spreadsheet
  - Count Tokens
  - Create An Event
  - Create Cse Identites
  - Create Cse Keypairs
  - Create Delegates
  - Create Drafts
  - Create Filters
  - Create Forwarding Address
  - Create Labels
  - Create Labels
  - Create Name:delta
  - Create Name:disable
  - Create Name:enable
  - Create Name:publish
  - Create Name:updatelabelcopymode
  - Create Parent Permissions
  - Create Parent Permissions:batchdelete
  - Create Parent Permissions:batchupdate
  - Create Send As
  - Create Spreadsheet
  - Delete  Name
  - Delete Access Control Rule
  - Delete Cse Idenities
  - Delete Calendar
  - Delete Delegates
  - Delete Drafts
  - Delete Drives Driveid
  - Delete Event
  - Delete Files Fileid
  - Delete Files Fileid Comments Commentid
  - Delete Files Fileid Comments Commentid Replies Replyid
  - Delete Files Fileid Permissions Permissionid
  - Delete Files Fileid Revisions Revisionid
  - Delete Files Trash
  - Delete Filters
  - Delete Forwarding Addresses
  - Delete Labels
  - Delete Messages
  - Delete Send As
  - Delete Send As Smime Info
  - Delete Teamdrives Teamdriveid
  - Delete Threads
  - Disable Cse Keypairs
  - Enable Cse Keypairs
  - Get Cse Idenetites
  - Get Cse Keypairs
  - Get Imap
  - Generate Content
  - Generate Images
  - Generate Speech (text-to-speech)
  - Get About
  - Get Access Control Rule
  - Get Apps
  - Get Apps Appid
  - Get Attachments
  - Get Auto Forwarding Settings
  - Get Calendar
  - Get Calendar Colors
  - Get Calendar List
  - Get Calendar Settings
  - Get Cell Values
  - Get Changes
  - Get Changes Startpagetoken
  - Get Delegates
  - Get Developer Metadata
  - Get Documents
  - Get Drafts
  - Get Drives
  - Get Drives Driveid
  - Get Event
  - Get File Metadata
  - Get Files
  - Get Files Fileid
  - Get Files Fileid Comments
  - Get Files Fileid Comments Commentid
  - Get Files Fileid Comments Commentid Replies
  - Get Files Fileid Comments Commentid Replies Replyid
  - Get Files Fileid Export
  - Get Files Fileid Listlabels
  - Get Files Fileid Permissions
  - Get Files Fileid Permissions Permissionid
  - Get Files Fileid Revisions
  - Get Files Fileid Revisions Revisionid
  - Get Files Generateids
  - Get Filters
  - Get Forwarding Addresses
  - Get Labels
  - Get Language Settings
  - Get Messages
  - Get Pop Settings
  - Get Profile
  - Get Send As
  - Get Send As
  - Get Send As Smime Info
  - Get Spreadsheet
  - Get Spreadsheet By Data Filter
  - Get Teamdrives
  - Get Teamdrives Teamdriveid
  - Get Threads
  - Get Vacation Settings
  - Import Event
  - Import Messages
  - Insert Access Control Rule
  - Insert Calendar On List
  - Insert Event
  - Insert Messages
  - Insert Smime Info
  - List Cse Identites
  - List Cse Keypairs
  - List Calendar Settings
  - List Calendars
  - List Delegates
  - List Drafts
  - List Filters
  - List Forwarding Addresses
  - List History
  - List Labels
  - List Messages
  - List Smime Info
  - List Threads
  - Modify Messages
  - Modify Threads
  - Move Event
  - Obliterate Cse Keypairs
  - Patch Cse Identites
  - Patch  Parent Permissions
  - Patch Access Control Rule
  - Patch Calendar
  - Patch Calendar List
  - Patch Drives Driveid
  - Patch Event
  - Patch Files Fileid
  - Patch Files Fileid Comments Commentid
  - Patch Files Fileid Comments Commentid Replies Replyid
  - Patch Files Fileid Permissions Permissionid
  - Patch Files Fileid Revisions Revisionid
  - Patch Labels
  - Patch Send As
  - Patch Teamdrives Teamdriveid
  - Post  Activity:query
  - Post Changes Watch
  - Post Channels Stop
  - Post Documents
  - Post Documents Batch Update
  - Post Drives
  - Post Drives Driveid Hide
  - Post Drives Driveid Unhide
  - Post Files
  - Post Files Fileid Comments
  - Post Files Fileid Comments Commentid Replies
  - Post Files Fileid Copy
  - Post Files Fileid Modifylabels
  - Post Files Fileid Permissions
  - Post Files Fileid Watch
  - Post Teamdrives
  - Query Free Busy
  - Quick Add Event
  - Remove Calendar On List
  - Retrieve Labels
  - Retrieve Limits Label
  - Retrieve Name
  - Retrieve Parent Locks
  - Retrieve Parent Permissions
  - Return Access Control Rules
  - Return Events From Calendar
  - Search Developer Metadata
  - Send Drafts
  - Send Messages
  - Set Default S/mime Config
  - Stop Calendar Channel
  - Stop Notifications For User
  - Stream Generate Content
  - Trash Messsages
  - Trash Threads
  - Untrash Messages
  - Update Access Control Rule
  - Update Auto Forwarding
  - Update Calendar
  - Update Calendar List
  - Update Cell Values
  - Update Drafts
  - Update Event
  - Update Imap
  - Update Labels
  - Update Language Settings
  - Update Pop Settings
  - Update Send As Setting
  - Update Vacation Settings
  - Upload File (resumable)
  - Verify Send As
  - Watch Access Control Rules
  - Watch Calendar List
  - Watch Calendar Settings
  - Watch Events
  - Watch Users

## Backstage
We provide a Backstage software catalog entity for the Google API & MCP Sandbox, allowing this sandbox to be registered with any catalog, making it discoverable by team and across an organization--allowing anyone to fork and deploy locally within the enterprise.

  - [Google Calendar API](backstage/google-calendar-api-api-sandbox-backstage.yml)
  - [Google Docs API](backstage/google-docs-api-api-sandbox-backstage.yml)
  - [Google Drive Activity API](backstage/google-drive-activity-api-api-sandbox-backstage.yml)
  - [Google Drive API](backstage/google-drive-api-api-sandbox-backstage.yml)
  - [Google Drive Labels API](backstage/google-drive-labels-api-api-sandbox-backstage.yml)
  - [Gemini API](backstage/google-gemini-api-api-sandbox-backstage.yml)
  - [Google Gmail API](backstage/google-gmail-api-api-sandbox-backstage.yml)
  - [Google Sheets API](backstage/google-sheets-api-api-sandbox-backstage.yml)
## Support
Please provide any questions or feedback via GitHub issues, or just email kinlane@naftiko.io with feedback. The goal is to keep iterating upon this sandbox using existing OpenAPI, Microcks, and Bruno features, offering value out of the box via this forkable third-party Google API & MCP Sandbox.

