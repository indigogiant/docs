
---
title: "GetPostgresInstance"
title_tag: "Function GetPostgresInstance | Module azuredata | Package Azure NextGen"
meta_desc: "Explore the GetPostgresInstance function of the azuredata module, including examples, input properties, output properties, and supporting types. "
---



<!-- WARNING: this file was generated by Pulumi Docs Generator. -->
<!-- Do not edit by hand unless you're certain you know what you are doing! -->




## Using GetPostgresInstance {#using}

{{< chooser language "typescript,python,go,csharp" / >}}


{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">function </span>getPostgresInstance<span class="p">(</span><span class="nx">args</span><span class="p">:</span> <span class="nx">GetPostgresInstanceArgs</span><span class="p">, </span><span class="nx">opts</span><span class="p">?:</span> <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#InvokeOptions">InvokeOptions</a></span><span class="p">): Promise&lt;<span class="nx">GetPostgresInstanceResult</span>></span></code></pre></div>
{{% /choosable %}}


{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span>get_postgres_instance(</span><span class="nx">postgres_instance_name</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">resource_group_name</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">opts</span><span class="p">:</span> <span class="nx"><a href="/docs/reference/pkg/python/pulumi/#pulumi.InvokeOptions">Optional[InvokeOptions]</a></span> = None<span class="p">) -&gt;</span> GetPostgresInstanceResult</code></pre></div>
{{% /choosable %}}


{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>LookupPostgresInstance<span class="p">(</span><span class="nx">ctx</span><span class="p"> *</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">args</span><span class="p"> *</span><span class="nx">LookupPostgresInstanceArgs</span><span class="p">, </span><span class="nx">opts</span><span class="p"> ...</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#InvokeOption">InvokeOption</a></span><span class="p">) (*<span class="nx">LookupPostgresInstanceResult</span>, error)</span></code></pre></div>

> Note: This function is named `LookupPostgresInstance` in the Go SDK.

{{% /choosable %}}


{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static class </span><span class="nx">GetPostgresInstance </span><span class="p">{</span><span class="k">
    public static </span>Task&lt;<span class="nx">GetPostgresInstanceResult</span>> <span class="p">InvokeAsync(</span><span class="nx">GetPostgresInstanceArgs</span><span class="p"> </span><span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.InvokeOptions.html">InvokeOptions</a></span><span class="p">? </span><span class="nx">opts = null<span class="p">)</span><span class="p">
}</span></code></pre></div>
{{% /choosable %}}



The following arguments are supported:


{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="postgresinstancename_csharp">
<a href="#postgresinstancename_csharp" style="color: inherit; text-decoration: inherit;">Postgres<wbr>Instance<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Name of Postgres Instance{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="resourcegroupname_csharp">
<a href="#resourcegroupname_csharp" style="color: inherit; text-decoration: inherit;">Resource<wbr>Group<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Azure resource group{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="postgresinstancename_go">
<a href="#postgresinstancename_go" style="color: inherit; text-decoration: inherit;">Postgres<wbr>Instance<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Name of Postgres Instance{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="resourcegroupname_go">
<a href="#resourcegroupname_go" style="color: inherit; text-decoration: inherit;">Resource<wbr>Group<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Azure resource group{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="postgresinstancename_nodejs">
<a href="#postgresinstancename_nodejs" style="color: inherit; text-decoration: inherit;">postgres<wbr>Instance<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Name of Postgres Instance{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="resourcegroupname_nodejs">
<a href="#resourcegroupname_nodejs" style="color: inherit; text-decoration: inherit;">resource<wbr>Group<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Azure resource group{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="postgres_instance_name_python">
<a href="#postgres_instance_name_python" style="color: inherit; text-decoration: inherit;">postgres_<wbr>instance_<wbr>name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Name of Postgres Instance{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="resource_group_name_python">
<a href="#resource_group_name_python" style="color: inherit; text-decoration: inherit;">resource_<wbr>group_<wbr>name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the Azure resource group{{% /md %}}</dd>
</dl>
{{% /choosable %}}




## GetPostgresInstance Result {#result}

The following output properties are available:



{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="id_csharp">
<a href="#id_csharp" style="color: inherit; text-decoration: inherit;">Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Fully qualified resource Id for the resource. Ex - /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="location_csharp">
<a href="#location_csharp" style="color: inherit; text-decoration: inherit;">Location</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The geo-location where the resource lives{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="name_csharp">
<a href="#name_csharp" style="color: inherit; text-decoration: inherit;">Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the resource{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="systemdata_csharp">
<a href="#systemdata_csharp" style="color: inherit; text-decoration: inherit;">System<wbr>Data</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#systemdataresponse">Pulumi.<wbr>Azure<wbr>Next<wbr>Gen.<wbr>Azure<wbr>Data.<wbr>Outputs.<wbr>System<wbr>Data<wbr>Response</a></span>
    </dt>
    <dd>{{% md %}}Read only system data{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="type_csharp">
<a href="#type_csharp" style="color: inherit; text-decoration: inherit;">Type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The type of the resource. Ex- Microsoft.Compute/virtualMachines or Microsoft.Storage/storageAccounts.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="admin_csharp">
<a href="#admin_csharp" style="color: inherit; text-decoration: inherit;">Admin</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The instance admin{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="datacontrollerid_csharp">
<a href="#datacontrollerid_csharp" style="color: inherit; text-decoration: inherit;">Data<wbr>Controller<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The data controller id{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="k8sraw_csharp">
<a href="#k8sraw_csharp" style="color: inherit; text-decoration: inherit;">K8s<wbr>Raw</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">object</span>
    </dt>
    <dd>{{% md %}}The raw kubernetes information{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="lastuploadeddate_csharp">
<a href="#lastuploadeddate_csharp" style="color: inherit; text-decoration: inherit;">Last<wbr>Uploaded<wbr>Date</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Last uploaded date from on premise cluster. Defaults to current date time{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="tags_csharp">
<a href="#tags_csharp" style="color: inherit; text-decoration: inherit;">Tags</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary&lt;string, string&gt;</span>
    </dt>
    <dd>{{% md %}}Resource tags.{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="id_go">
<a href="#id_go" style="color: inherit; text-decoration: inherit;">Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Fully qualified resource Id for the resource. Ex - /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="location_go">
<a href="#location_go" style="color: inherit; text-decoration: inherit;">Location</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The geo-location where the resource lives{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="name_go">
<a href="#name_go" style="color: inherit; text-decoration: inherit;">Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the resource{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="systemdata_go">
<a href="#systemdata_go" style="color: inherit; text-decoration: inherit;">System<wbr>Data</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#systemdataresponse">System<wbr>Data<wbr>Response</a></span>
    </dt>
    <dd>{{% md %}}Read only system data{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="type_go">
<a href="#type_go" style="color: inherit; text-decoration: inherit;">Type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The type of the resource. Ex- Microsoft.Compute/virtualMachines or Microsoft.Storage/storageAccounts.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="admin_go">
<a href="#admin_go" style="color: inherit; text-decoration: inherit;">Admin</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The instance admin{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="datacontrollerid_go">
<a href="#datacontrollerid_go" style="color: inherit; text-decoration: inherit;">Data<wbr>Controller<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The data controller id{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="k8sraw_go">
<a href="#k8sraw_go" style="color: inherit; text-decoration: inherit;">K8s<wbr>Raw</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">interface{}</span>
    </dt>
    <dd>{{% md %}}The raw kubernetes information{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="lastuploadeddate_go">
<a href="#lastuploadeddate_go" style="color: inherit; text-decoration: inherit;">Last<wbr>Uploaded<wbr>Date</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Last uploaded date from on premise cluster. Defaults to current date time{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="tags_go">
<a href="#tags_go" style="color: inherit; text-decoration: inherit;">Tags</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]string</span>
    </dt>
    <dd>{{% md %}}Resource tags.{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="id_nodejs">
<a href="#id_nodejs" style="color: inherit; text-decoration: inherit;">id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Fully qualified resource Id for the resource. Ex - /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="location_nodejs">
<a href="#location_nodejs" style="color: inherit; text-decoration: inherit;">location</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The geo-location where the resource lives{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="name_nodejs">
<a href="#name_nodejs" style="color: inherit; text-decoration: inherit;">name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the resource{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="systemdata_nodejs">
<a href="#systemdata_nodejs" style="color: inherit; text-decoration: inherit;">system<wbr>Data</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#systemdataresponse">System<wbr>Data<wbr>Response</a></span>
    </dt>
    <dd>{{% md %}}Read only system data{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="type_nodejs">
<a href="#type_nodejs" style="color: inherit; text-decoration: inherit;">type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The type of the resource. Ex- Microsoft.Compute/virtualMachines or Microsoft.Storage/storageAccounts.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="admin_nodejs">
<a href="#admin_nodejs" style="color: inherit; text-decoration: inherit;">admin</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The instance admin{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="datacontrollerid_nodejs">
<a href="#datacontrollerid_nodejs" style="color: inherit; text-decoration: inherit;">data<wbr>Controller<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The data controller id{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="k8sraw_nodejs">
<a href="#k8sraw_nodejs" style="color: inherit; text-decoration: inherit;">k8s<wbr>Raw</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">any</span>
    </dt>
    <dd>{{% md %}}The raw kubernetes information{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="lastuploadeddate_nodejs">
<a href="#lastuploadeddate_nodejs" style="color: inherit; text-decoration: inherit;">last<wbr>Uploaded<wbr>Date</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Last uploaded date from on premise cluster. Defaults to current date time{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="tags_nodejs">
<a href="#tags_nodejs" style="color: inherit; text-decoration: inherit;">tags</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: string}</span>
    </dt>
    <dd>{{% md %}}Resource tags.{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="id_python">
<a href="#id_python" style="color: inherit; text-decoration: inherit;">id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Fully qualified resource Id for the resource. Ex - /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="location_python">
<a href="#location_python" style="color: inherit; text-decoration: inherit;">location</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The geo-location where the resource lives{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="name_python">
<a href="#name_python" style="color: inherit; text-decoration: inherit;">name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the resource{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="system_data_python">
<a href="#system_data_python" style="color: inherit; text-decoration: inherit;">system_<wbr>data</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#systemdataresponse">System<wbr>Data<wbr>Response</a></span>
    </dt>
    <dd>{{% md %}}Read only system data{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="type_python">
<a href="#type_python" style="color: inherit; text-decoration: inherit;">type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The type of the resource. Ex- Microsoft.Compute/virtualMachines or Microsoft.Storage/storageAccounts.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="admin_python">
<a href="#admin_python" style="color: inherit; text-decoration: inherit;">admin</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The instance admin{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="data_controller_id_python">
<a href="#data_controller_id_python" style="color: inherit; text-decoration: inherit;">data_<wbr>controller_<wbr>id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The data controller id{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="k8s_raw_python">
<a href="#k8s_raw_python" style="color: inherit; text-decoration: inherit;">k8s_<wbr>raw</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">Any</span>
    </dt>
    <dd>{{% md %}}The raw kubernetes information{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="last_uploaded_date_python">
<a href="#last_uploaded_date_python" style="color: inherit; text-decoration: inherit;">last_<wbr>uploaded_<wbr>date</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Last uploaded date from on premise cluster. Defaults to current date time{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="tags_python">
<a href="#tags_python" style="color: inherit; text-decoration: inherit;">tags</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">Mapping[str, str]</span>
    </dt>
    <dd>{{% md %}}Resource tags.{{% /md %}}</dd>
</dl>
{{% /choosable %}}




## Supporting Types


<h4 id="systemdataresponse">System<wbr>Data<wbr>Response</h4>






{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span id="createdat_csharp">
<a href="#createdat_csharp" style="color: inherit; text-decoration: inherit;">Created<wbr>At</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The timestamp of resource creation (UTC){{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="createdby_csharp">
<a href="#createdby_csharp" style="color: inherit; text-decoration: inherit;">Created<wbr>By</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}An identifier for the identity that created the resource{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="createdbytype_csharp">
<a href="#createdbytype_csharp" style="color: inherit; text-decoration: inherit;">Created<wbr>By<wbr>Type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The type of identity that created the resource{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="lastmodifiedat_csharp">
<a href="#lastmodifiedat_csharp" style="color: inherit; text-decoration: inherit;">Last<wbr>Modified<wbr>At</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The timestamp of resource last modification (UTC){{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="lastmodifiedby_csharp">
<a href="#lastmodifiedby_csharp" style="color: inherit; text-decoration: inherit;">Last<wbr>Modified<wbr>By</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}An identifier for the identity that last modified the resource{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="lastmodifiedbytype_csharp">
<a href="#lastmodifiedbytype_csharp" style="color: inherit; text-decoration: inherit;">Last<wbr>Modified<wbr>By<wbr>Type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The type of identity that last modified the resource{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span id="createdat_go">
<a href="#createdat_go" style="color: inherit; text-decoration: inherit;">Created<wbr>At</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The timestamp of resource creation (UTC){{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="createdby_go">
<a href="#createdby_go" style="color: inherit; text-decoration: inherit;">Created<wbr>By</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}An identifier for the identity that created the resource{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="createdbytype_go">
<a href="#createdbytype_go" style="color: inherit; text-decoration: inherit;">Created<wbr>By<wbr>Type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The type of identity that created the resource{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="lastmodifiedat_go">
<a href="#lastmodifiedat_go" style="color: inherit; text-decoration: inherit;">Last<wbr>Modified<wbr>At</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The timestamp of resource last modification (UTC){{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="lastmodifiedby_go">
<a href="#lastmodifiedby_go" style="color: inherit; text-decoration: inherit;">Last<wbr>Modified<wbr>By</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}An identifier for the identity that last modified the resource{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="lastmodifiedbytype_go">
<a href="#lastmodifiedbytype_go" style="color: inherit; text-decoration: inherit;">Last<wbr>Modified<wbr>By<wbr>Type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The type of identity that last modified the resource{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span id="createdat_nodejs">
<a href="#createdat_nodejs" style="color: inherit; text-decoration: inherit;">created<wbr>At</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The timestamp of resource creation (UTC){{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="createdby_nodejs">
<a href="#createdby_nodejs" style="color: inherit; text-decoration: inherit;">created<wbr>By</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}An identifier for the identity that created the resource{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="createdbytype_nodejs">
<a href="#createdbytype_nodejs" style="color: inherit; text-decoration: inherit;">created<wbr>By<wbr>Type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The type of identity that created the resource{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="lastmodifiedat_nodejs">
<a href="#lastmodifiedat_nodejs" style="color: inherit; text-decoration: inherit;">last<wbr>Modified<wbr>At</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The timestamp of resource last modification (UTC){{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="lastmodifiedby_nodejs">
<a href="#lastmodifiedby_nodejs" style="color: inherit; text-decoration: inherit;">last<wbr>Modified<wbr>By</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}An identifier for the identity that last modified the resource{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="lastmodifiedbytype_nodejs">
<a href="#lastmodifiedbytype_nodejs" style="color: inherit; text-decoration: inherit;">last<wbr>Modified<wbr>By<wbr>Type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The type of identity that last modified the resource{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span id="created_at_python">
<a href="#created_at_python" style="color: inherit; text-decoration: inherit;">created_<wbr>at</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The timestamp of resource creation (UTC){{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="created_by_python">
<a href="#created_by_python" style="color: inherit; text-decoration: inherit;">created_<wbr>by</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}An identifier for the identity that created the resource{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="created_by_type_python">
<a href="#created_by_type_python" style="color: inherit; text-decoration: inherit;">created_<wbr>by_<wbr>type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The type of identity that created the resource{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="last_modified_at_python">
<a href="#last_modified_at_python" style="color: inherit; text-decoration: inherit;">last_<wbr>modified_<wbr>at</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The timestamp of resource last modification (UTC){{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="last_modified_by_python">
<a href="#last_modified_by_python" style="color: inherit; text-decoration: inherit;">last_<wbr>modified_<wbr>by</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}An identifier for the identity that last modified the resource{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="last_modified_by_type_python">
<a href="#last_modified_by_type_python" style="color: inherit; text-decoration: inherit;">last_<wbr>modified_<wbr>by_<wbr>type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The type of identity that last modified the resource{{% /md %}}</dd>
</dl>
{{% /choosable %}}





<h2 id="package-details">Package Details</h2>
<dl class="package-details">
	<dt>Repository</dt>
	<dd><a href="https://github.com/pulumi/pulumi-azure-nextgen">https://github.com/pulumi/pulumi-azure-nextgen</a></dd>
	<dt>License</dt>
	<dd>Apache-2.0</dd>
</dl>

