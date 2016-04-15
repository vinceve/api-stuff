# api-stuff

## Goal

The goal of this personal project is to create a toolchain to easily define api's and generate code for them. A second part will be that the api sends out meta information
to render UI components based on the information of the api. All of this should be repeatable.

## Steps

1. Define an API in a spec.
2. Write business logic decoupled from the API.
3. Run a tool to generate the code for the API. This will generate also a scheme that defines all the fields + required or not.
4. The clientside implements a tool that reads the scheme and creates some kind of formbuilder that you can use to generate html.