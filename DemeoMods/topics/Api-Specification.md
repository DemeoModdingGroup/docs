# Api Specification


## Requests
<api-doc openapi-path="./../snippets/spec/openapi.yml" >
    <api-endpoint endpoint="/projects/projects.json" method="GET">
        <response type="200">
            <sample src="./../snippets/samples/projects.json" lang="JSON" />
        </response>
    </api-endpoint>
    <api-endpoint endpoint="/projects/{name}/project.json" method="GET">
        <response type="200">
            <sample src="./../snippets/samples/project.json" lang="JSON" />
        </response>
    </api-endpoint>
    <api-endpoint endpoint="/projects/{name}/versions.json" method="GET">
        <response type="200">
            <sample src="./../snippets/samples/project_versions.json" lang="JSON" />
        </response>
    </api-endpoint>
</api-doc>

## Schema
<api-schema openapi-path="./../snippets/spec/openapi.yml" name="project_object" />
<api-schema openapi-path="./../snippets/spec/openapi.yml" name="project_versions_object" />