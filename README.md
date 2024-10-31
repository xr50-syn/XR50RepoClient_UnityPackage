## XR5.0 Training Repo Standalone POC


## Description
A Unity package containing a simple client that interfaces with the XR50 Training Repo. It implements helper functions to interface with its WebAPI.

## Installation
Import the package into an existing Unity project.

## Usage
The XR50RepoClient.cs can be attached to Unity objects. The UserName and AppName must be set to existing user and App.
The help functions implement the GET, CREATE, & DELETE for the App_Management, User_Management, Training_Module_Management, and Resource_Management Interface. Note that CREATE & DELETE require the user to have admin privileges.
For the Asset_Management Interface, only the GET method is implemented. On top of that, the Download method allows the download of an Asset stored in Owncloud. Asset Creation can only happen externally outside of the XR environment.

The Resources/Samples Directory contains sample JSON files that will create a sample Application with 3 Training Modules.


## Authors and acknowledgment
Emmanouil Mavrogiorgis (emaurog@synelixis.com)

## License
This work is shared under the MIT License.


