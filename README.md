# Go API client for worker

The ultimate, language agnostic, container based task processing framework.

## Overview
This API client was generated by the [swagger-codegen](https://github.com/swagger-api/swagger-codegen) project.  By using the [swagger-spec](https://github.com/swagger-api/swagger-spec) from a remote server, you can easily generate an API client.

- API version: 0.5.0
- Package version: 0.5.0
- Build date: 2016-08-24T15:56:20.549Z
- Build package: class io.swagger.codegen.languages.GoClientCodegen

## Installation
Put the package under your project folder and add the following in import:
```
    "./worker"
```

## Documentation for API Endpoints

All URIs are relative to *https://localhost:8080/v1*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*GroupsApi* | [**GroupsGet**](docs/GroupsApi.md#groupsget) | **Get** /groups | Get all group names.
*GroupsApi* | [**GroupsNameGet**](docs/GroupsApi.md#groupsnameget) | **Get** /groups/{name} | Get information for a group.
*GroupsApi* | [**GroupsNamePut**](docs/GroupsApi.md#groupsnameput) | **Put** /groups/{name} | Create/update a task group.
*GroupsApi* | [**GroupsPost**](docs/GroupsApi.md#groupspost) | **Post** /groups | Post new group
*RunnerApi* | [**GroupsNameTasksIdErrorPost**](docs/RunnerApi.md#groupsnametasksiderrorpost) | **Post** /groups/{name}/tasks/{id}/error | Mark task as failed.
*RunnerApi* | [**GroupsNameTasksIdStartPost**](docs/RunnerApi.md#groupsnametasksidstartpost) | **Post** /groups/{name}/tasks/{id}/start | Mark task as started, ie: status &#x3D; &#39;running&#39;
*RunnerApi* | [**GroupsNameTasksIdSuccessPost**](docs/RunnerApi.md#groupsnametasksidsuccesspost) | **Post** /groups/{name}/tasks/{id}/success | Mark task as succeeded.
*TasksApi* | [**GroupsNameTasksGet**](docs/TasksApi.md#groupsnametasksget) | **Get** /groups/{name}/tasks | Get task list by group name.
*TasksApi* | [**GroupsNameTasksIdCancelPost**](docs/TasksApi.md#groupsnametasksidcancelpost) | **Post** /groups/{name}/tasks/{id}/cancel | Cancel a task.
*TasksApi* | [**GroupsNameTasksIdDelete**](docs/TasksApi.md#groupsnametasksiddelete) | **Delete** /groups/{name}/tasks/{id} | Delete the task.
*TasksApi* | [**GroupsNameTasksIdErrorPost**](docs/TasksApi.md#groupsnametasksiderrorpost) | **Post** /groups/{name}/tasks/{id}/error | Mark task as failed.
*TasksApi* | [**GroupsNameTasksIdGet**](docs/TasksApi.md#groupsnametasksidget) | **Get** /groups/{name}/tasks/{id} | Gets task by id
*TasksApi* | [**GroupsNameTasksIdLogGet**](docs/TasksApi.md#groupsnametasksidlogget) | **Get** /groups/{name}/tasks/{id}/log | Get the log of a completed task.
*TasksApi* | [**GroupsNameTasksIdLogPost**](docs/TasksApi.md#groupsnametasksidlogpost) | **Post** /groups/{name}/tasks/{id}/log | Send in a log for storage.
*TasksApi* | [**GroupsNameTasksIdRetryPost**](docs/TasksApi.md#groupsnametasksidretrypost) | **Post** /groups/{name}/tasks/{id}/retry | Retry a task.
*TasksApi* | [**GroupsNameTasksIdStartPost**](docs/TasksApi.md#groupsnametasksidstartpost) | **Post** /groups/{name}/tasks/{id}/start | Mark task as started, ie: status &#x3D; &#39;running&#39;
*TasksApi* | [**GroupsNameTasksIdSuccessPost**](docs/TasksApi.md#groupsnametasksidsuccesspost) | **Post** /groups/{name}/tasks/{id}/success | Mark task as succeeded.
*TasksApi* | [**GroupsNameTasksIdTouchPost**](docs/TasksApi.md#groupsnametasksidtouchpost) | **Post** /groups/{name}/tasks/{id}/touch | Extend task timeout.
*TasksApi* | [**GroupsNameTasksPost**](docs/TasksApi.md#groupsnametaskspost) | **Post** /groups/{name}/tasks | Enqueue task
*TasksApi* | [**TasksGet**](docs/TasksApi.md#tasksget) | **Get** /tasks | Get next task.


## Documentation For Models

 - [Complete](docs/Complete.md)
 - [ErrorBody](docs/ErrorBody.md)
 - [Group](docs/Group.md)
 - [GroupWrapper](docs/GroupWrapper.md)
 - [GroupsWrapper](docs/GroupsWrapper.md)
 - [IdStatus](docs/IdStatus.md)
 - [ModelError](docs/ModelError.md)
 - [NewTask](docs/NewTask.md)
 - [NewTasksWrapper](docs/NewTasksWrapper.md)
 - [Start](docs/Start.md)
 - [Task](docs/Task.md)
 - [TaskWrapper](docs/TaskWrapper.md)
 - [TasksWrapper](docs/TasksWrapper.md)


## Documentation For Authorization

 All endpoints do not require authorization.


## Author



