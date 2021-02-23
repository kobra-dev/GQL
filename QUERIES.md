## Create Project

```
mutation {
  createProject(
    data: {
      user: "username"
      name: "project name"
      isPublic: true
      description: "description"
      projectJson: "project json!!"
    }
  ) {
    _id
  }
}

```

## Update Project

```
mutation {
  updateProject(
    id: "id"
    data: {
      user: "username"
      name: "pranav"
      isPublic: true
      description: "description"
      projectJson: "{projectjson}"
    }
  ) {
    _id
  }
}

```

## Delete Project

```
mutation {
  deleteProject(id: "id") {
    _id
  }
}

```

## Get Project by ID

```
query {
  findProjectByID(
    id:""
  ){
    name
    user
  }
}

```
