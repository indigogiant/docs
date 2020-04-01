
---
title: "OutputEventHub"
block_external_search_index: true
---

Manages a Stream Analytics Output to an EventHub.

> This content is derived from https://github.com/terraform-providers/terraform-provider-azurerm/blob/master/website/docs/r/stream_analytics_output_eventhub.html.markdown.



## Create a OutputEventHub Resource

{{< chooser language "javascript,typescript,python,go,csharp" / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">new </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/azure/streamanalytics/#OutputEventHub">OutputEventHub</a></span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">args</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/azure/streamanalytics/#OutputEventHubArgs">OutputEventHubArgs</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">pulumi.CustomResourceOptions</a></span><span class="p">);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span><span class="nf">OutputEventHub</span><span class="p">(resource_name, opts=None, </span>eventhub_name=None<span class="p">, </span>name=None<span class="p">, </span>resource_group_name=None<span class="p">, </span>serialization=None<span class="p">, </span>servicebus_namespace=None<span class="p">, </span>shared_access_policy_key=None<span class="p">, </span>shared_access_policy_name=None<span class="p">, </span>stream_analytics_job_name=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>NewOutputEventHub<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">pulumi.Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">args</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/streamanalytics?tab=doc#OutputEventHubArgs">OutputEventHubArgs</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">pulumi.ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/streamanalytics?tab=doc#OutputEventHub">OutputEventHub</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Azure/Pulumi.Azure.Streamanalytics.OutputEventHub.html">OutputEventHub</a></span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Azure/Pulumi.Azure.StreamAnalytics.Inputs.OutputEventHubArgs.html">OutputEventHubArgs</a></span> <span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">Pulumi.CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language nodejs %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language csharp %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

#### Resource Arguments




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Eventhub<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Event Hub.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the Stream Output. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Resource Group where the Stream Analytics Job exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Serialization</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#outputeventhubserialization">Pulumi.<wbr>Azure.<wbr>Stream<wbr>Analytics.<wbr>Inputs.<wbr>Output<wbr>Event<wbr>Hub<wbr>Serialization<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}A `serialization` block as defined below.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Servicebus<wbr>Namespace</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The namespace that is associated with the desired Event Hub, Service Bus Queue, Service Bus Topic, etc.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Shared<wbr>Access<wbr>Policy<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The shared access policy key for the specified shared access policy.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Shared<wbr>Access<wbr>Policy<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The shared access policy name for the Event Hub, Service Bus Queue, Service Bus Topic, etc.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Stream<wbr>Analytics<wbr>Job<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Stream Analytics Job. Changing this forces a new resource to be created.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Eventhub<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Event Hub.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The name of the Stream Output. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Resource Group where the Stream Analytics Job exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Serialization</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#outputeventhubserialization">Output<wbr>Event<wbr>Hub<wbr>Serialization</a></span>
    </dt>
    <dd>{{% md %}}A `serialization` block as defined below.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Servicebus<wbr>Namespace</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The namespace that is associated with the desired Event Hub, Service Bus Queue, Service Bus Topic, etc.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Shared<wbr>Access<wbr>Policy<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The shared access policy key for the specified shared access policy.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Shared<wbr>Access<wbr>Policy<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The shared access policy name for the Event Hub, Service Bus Queue, Service Bus Topic, etc.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Stream<wbr>Analytics<wbr>Job<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Stream Analytics Job. Changing this forces a new resource to be created.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>eventhub<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Event Hub.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the Stream Output. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Resource Group where the Stream Analytics Job exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>serialization</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#outputeventhubserialization">Output<wbr>Event<wbr>Hub<wbr>Serialization</a></span>
    </dt>
    <dd>{{% md %}}A `serialization` block as defined below.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>servicebus<wbr>Namespace</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The namespace that is associated with the desired Event Hub, Service Bus Queue, Service Bus Topic, etc.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>shared<wbr>Access<wbr>Policy<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The shared access policy key for the specified shared access policy.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>shared<wbr>Access<wbr>Policy<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The shared access policy name for the Event Hub, Service Bus Queue, Service Bus Topic, etc.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>stream<wbr>Analytics<wbr>Job<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Stream Analytics Job. Changing this forces a new resource to be created.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>eventhub_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the Event Hub.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the Stream Output. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>resource_<wbr>group_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the Resource Group where the Stream Analytics Job exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>serialization</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#outputeventhubserialization">Dict[Output<wbr>Event<wbr>Hub<wbr>Serialization]</a></span>
    </dt>
    <dd>{{% md %}}A `serialization` block as defined below.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>servicebus_<wbr>namespace</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The namespace that is associated with the desired Event Hub, Service Bus Queue, Service Bus Topic, etc.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>shared_<wbr>access_<wbr>policy_<wbr>key</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The shared access policy key for the specified shared access policy.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>shared_<wbr>access_<wbr>policy_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The shared access policy name for the Event Hub, Service Bus Queue, Service Bus Topic, etc.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>stream_<wbr>analytics_<wbr>job_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the Stream Analytics Job. Changing this forces a new resource to be created.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}







## OutputEventHub Output Properties

The following output properties are available:




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Eventhub<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Event Hub.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Stream Output. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Resource Group where the Stream Analytics Job exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Serialization</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#outputeventhubserialization">Pulumi.<wbr>Azure.<wbr>Stream<wbr>Analytics.<wbr>Outputs.<wbr>Output<wbr>Event<wbr>Hub<wbr>Serialization</a></span>
    </dt>
    <dd>{{% md %}}A `serialization` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Servicebus<wbr>Namespace</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The namespace that is associated with the desired Event Hub, Service Bus Queue, Service Bus Topic, etc.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Shared<wbr>Access<wbr>Policy<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The shared access policy key for the specified shared access policy.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Shared<wbr>Access<wbr>Policy<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The shared access policy name for the Event Hub, Service Bus Queue, Service Bus Topic, etc.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Stream<wbr>Analytics<wbr>Job<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Stream Analytics Job. Changing this forces a new resource to be created.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Eventhub<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Event Hub.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Stream Output. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Resource Group where the Stream Analytics Job exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Serialization</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#outputeventhubserialization">Output<wbr>Event<wbr>Hub<wbr>Serialization</a></span>
    </dt>
    <dd>{{% md %}}A `serialization` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Servicebus<wbr>Namespace</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The namespace that is associated with the desired Event Hub, Service Bus Queue, Service Bus Topic, etc.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Shared<wbr>Access<wbr>Policy<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The shared access policy key for the specified shared access policy.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Shared<wbr>Access<wbr>Policy<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The shared access policy name for the Event Hub, Service Bus Queue, Service Bus Topic, etc.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Stream<wbr>Analytics<wbr>Job<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Stream Analytics Job. Changing this forces a new resource to be created.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>eventhub<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Event Hub.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Stream Output. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Resource Group where the Stream Analytics Job exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>serialization</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#outputeventhubserialization">Output<wbr>Event<wbr>Hub<wbr>Serialization</a></span>
    </dt>
    <dd>{{% md %}}A `serialization` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>servicebus<wbr>Namespace</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The namespace that is associated with the desired Event Hub, Service Bus Queue, Service Bus Topic, etc.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>shared<wbr>Access<wbr>Policy<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The shared access policy key for the specified shared access policy.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>shared<wbr>Access<wbr>Policy<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The shared access policy name for the Event Hub, Service Bus Queue, Service Bus Topic, etc.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>stream<wbr>Analytics<wbr>Job<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the Stream Analytics Job. Changing this forces a new resource to be created.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>eventhub_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the Event Hub.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the Stream Output. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>resource_<wbr>group_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the Resource Group where the Stream Analytics Job exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>serialization</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#outputeventhubserialization">Dict[Output<wbr>Event<wbr>Hub<wbr>Serialization]</a></span>
    </dt>
    <dd>{{% md %}}A `serialization` block as defined below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>servicebus_<wbr>namespace</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The namespace that is associated with the desired Event Hub, Service Bus Queue, Service Bus Topic, etc.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>shared_<wbr>access_<wbr>policy_<wbr>key</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The shared access policy key for the specified shared access policy.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>shared_<wbr>access_<wbr>policy_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The shared access policy name for the Event Hub, Service Bus Queue, Service Bus Topic, etc.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>stream_<wbr>analytics_<wbr>job_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the Stream Analytics Job. Changing this forces a new resource to be created.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}








## Look up an Existing OutputEventHub Resource

Get an existing OutputEventHub resource's state with the given name, ID, and optional extra properties used to qualify the lookup.

{{< chooser language "javascript,typescript,python,go,csharp  " / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">public static </span><span class="nf">get</span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">id</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#ID">pulumi.Input&lt;pulumi.ID&gt;</a></span><span class="p">, </span><span class="nx">state</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/azure/streamanalytics/#OutputEventHubState">OutputEventHubState</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">pulumi.CustomResourceOptions</a></span><span class="p">): </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/azure/streamanalytics/#OutputEventHub">OutputEventHub</a></span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">static </span><span class="nf">get</span><span class="p">(resource_name, id, opts=None, </span>eventhub_name=None<span class="p">, </span>name=None<span class="p">, </span>resource_group_name=None<span class="p">, </span>serialization=None<span class="p">, </span>servicebus_namespace=None<span class="p">, </span>shared_access_policy_key=None<span class="p">, </span>shared_access_policy_name=None<span class="p">, </span>stream_analytics_job_name=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>GetOutputEventHub<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">pulumi.Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">id</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#IDInput">pulumi.IDInput</a></span><span class="p">, </span><span class="nx">state</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/streamanalytics?tab=doc#OutputEventHubState">OutputEventHubState</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">pulumi.ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/streamanalytics?tab=doc#OutputEventHub">OutputEventHub</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Azure/Pulumi.Azure.Streamanalytics.OutputEventHub.html">OutputEventHub</a></span><span class="nf"> Get</span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.Input.html">Pulumi.Input&lt;string&gt;</a></span> <span class="nx">id<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Azure/Pulumi.Azure.Streamanalytics.OutputEventHubState.html">OutputEventHubState</a></span>? <span class="nx">state<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">Pulumi.CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language nodejs %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>resource_name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Optional">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language csharp %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

The following state arguments are supported:



{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Eventhub<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the Event Hub.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the Stream Output. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the Resource Group where the Stream Analytics Job exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Serialization</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#outputeventhubserialization">Pulumi.<wbr>Azure.<wbr>Stream<wbr>Analytics.<wbr>Inputs.<wbr>Output<wbr>Event<wbr>Hub<wbr>Serialization<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A `serialization` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Servicebus<wbr>Namespace</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The namespace that is associated with the desired Event Hub, Service Bus Queue, Service Bus Topic, etc.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Shared<wbr>Access<wbr>Policy<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The shared access policy key for the specified shared access policy.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Shared<wbr>Access<wbr>Policy<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The shared access policy name for the Event Hub, Service Bus Queue, Service Bus Topic, etc.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Stream<wbr>Analytics<wbr>Job<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the Stream Analytics Job. Changing this forces a new resource to be created.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Eventhub<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The name of the Event Hub.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The name of the Stream Output. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The name of the Resource Group where the Stream Analytics Job exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Serialization</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#outputeventhubserialization">*Output<wbr>Event<wbr>Hub<wbr>Serialization</a></span>
    </dt>
    <dd>{{% md %}}A `serialization` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Servicebus<wbr>Namespace</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The namespace that is associated with the desired Event Hub, Service Bus Queue, Service Bus Topic, etc.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Shared<wbr>Access<wbr>Policy<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The shared access policy key for the specified shared access policy.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Shared<wbr>Access<wbr>Policy<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The shared access policy name for the Event Hub, Service Bus Queue, Service Bus Topic, etc.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Stream<wbr>Analytics<wbr>Job<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The name of the Stream Analytics Job. Changing this forces a new resource to be created.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>eventhub<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the Event Hub.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the Stream Output. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the Resource Group where the Stream Analytics Job exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>serialization</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#outputeventhubserialization">Output<wbr>Event<wbr>Hub<wbr>Serialization?</a></span>
    </dt>
    <dd>{{% md %}}A `serialization` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>servicebus<wbr>Namespace</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The namespace that is associated with the desired Event Hub, Service Bus Queue, Service Bus Topic, etc.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>shared<wbr>Access<wbr>Policy<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The shared access policy key for the specified shared access policy.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>shared<wbr>Access<wbr>Policy<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The shared access policy name for the Event Hub, Service Bus Queue, Service Bus Topic, etc.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>stream<wbr>Analytics<wbr>Job<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the Stream Analytics Job. Changing this forces a new resource to be created.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>eventhub_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the Event Hub.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the Stream Output. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>resource_<wbr>group_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the Resource Group where the Stream Analytics Job exists. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>serialization</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#outputeventhubserialization">Dict[Output<wbr>Event<wbr>Hub<wbr>Serialization]</a></span>
    </dt>
    <dd>{{% md %}}A `serialization` block as defined below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>servicebus_<wbr>namespace</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The namespace that is associated with the desired Event Hub, Service Bus Queue, Service Bus Topic, etc.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>shared_<wbr>access_<wbr>policy_<wbr>key</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The shared access policy key for the specified shared access policy.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>shared_<wbr>access_<wbr>policy_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The shared access policy name for the Event Hub, Service Bus Queue, Service Bus Topic, etc.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>stream_<wbr>analytics_<wbr>job_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the Stream Analytics Job. Changing this forces a new resource to be created.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}










## Supporting Types

<h4>Output<wbr>Event<wbr>Hub<wbr>Serialization</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#OutputEventHubSerialization">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#OutputEventHubSerialization">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/streamanalytics?tab=doc#OutputEventHubSerializationArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/streamanalytics?tab=doc#OutputEventHubSerializationOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Encoding</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The encoding of the incoming data in the case of input and the encoding of outgoing data in the case of output. It currently can only be set to `UTF8`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Field<wbr>Delimiter</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The delimiter that will be used to separate comma-separated value (CSV) records. Possible values are ` ` (space), `,` (comma), `   ` (tab), `|` (pipe) and `;`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Format</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Specifies the format of the JSON the output will be written in. Possible values are `Array` and `LineSeparated`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The serialization format used for outgoing data streams. Possible values are `Avro`, `Csv` and `Json`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Encoding</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The encoding of the incoming data in the case of input and the encoding of outgoing data in the case of output. It currently can only be set to `UTF8`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Field<wbr>Delimiter</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The delimiter that will be used to separate comma-separated value (CSV) records. Possible values are ` ` (space), `,` (comma), `   ` (tab), `|` (pipe) and `;`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Format</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Specifies the format of the JSON the output will be written in. Possible values are `Array` and `LineSeparated`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The serialization format used for outgoing data streams. Possible values are `Avro`, `Csv` and `Json`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>encoding</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The encoding of the incoming data in the case of input and the encoding of outgoing data in the case of output. It currently can only be set to `UTF8`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>field<wbr>Delimiter</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The delimiter that will be used to separate comma-separated value (CSV) records. Possible values are ` ` (space), `,` (comma), `   ` (tab), `|` (pipe) and `;`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>format</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Specifies the format of the JSON the output will be written in. Possible values are `Array` and `LineSeparated`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The serialization format used for outgoing data streams. Possible values are `Avro`, `Csv` and `Json`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>encoding</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The encoding of the incoming data in the case of input and the encoding of outgoing data in the case of output. It currently can only be set to `UTF8`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>field<wbr>Delimiter</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The delimiter that will be used to separate comma-separated value (CSV) records. Possible values are ` ` (space), `,` (comma), `   ` (tab), `|` (pipe) and `;`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>format</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Specifies the format of the JSON the output will be written in. Possible values are `Array` and `LineSeparated`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The serialization format used for outgoing data streams. Possible values are `Avro`, `Csv` and `Json`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}






