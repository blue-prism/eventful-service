# eventful-service

This asset interacts with the web service exposed by Eventful at <http://api.eventful.com>

## Usage
The asset provides interaction with the following API endpoints

* **Events - Search**
  Search events based on keyword, location, name, etc.
* **Events - Get**
  Returns a single event based on Event ID.
* **Venues - Search**
  Search venues based on keyword, location, name, etc.
* **Venues - Get**
  Returns a single event based on Venue ID.
* **Performers - Search**
  Search performers based on keyword, location, name, etc.
* **Performers - Get**
  Returns a single performer based on Performer ID.
* **Users - Search**
  Search users based on keyword, location, name, etc.
* **Users - Get**
  Returns a single user based on User ID.
  
  
## Setup
To use this asset, download or clone this repository. Extract the *.bprelease file* and import it into your Blue Prism environment.

Following that, request an **application key** from <http://api.eventful.com>

An application key is a required parameter for all requests in this object.