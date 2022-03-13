# gui-wrapper: Wrap that clunky department website into a structured openlab API
## Problem
Many computational life science tools are scattered around the web and take their input using poorly designed GUIs. Often these GUIs also do not support the processing of jobs containing multiple requests.

## Solution
Within this repo, we build tools that wrap these services and expose them with a unified API using serverless workers. 

### How to get involved
1. create a new issue for a webservice you know that you would like to see available in a clean, systematic way. Some examples for useful APIs that are buried behind a GUI include [swissADME](http://www.swissadme.ch/index.php) and [naturalantibody](https://research.naturalantibody.com/). 
2. contribute to the development of a serverless worker that can receive systematic requests via the openlab API and forward them to these bespoke webservices
3. contribute to the development of tests that check the uptime and faithfulness of the API

## Technology
* cloudflare workers

## Team 
open to all!

## Tokens 
stipends for open source contributors are available




