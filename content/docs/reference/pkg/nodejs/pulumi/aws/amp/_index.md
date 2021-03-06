---
title: "Module amp"
title_tag: "Module amp | Package @pulumi/aws | Node.js SDK"
linktitle: "amp"
meta_desc: "Explore members of the amp module in the @pulumi/aws package."
git_sha: "d072b346d2519850d0b24c72316f8d7487257ab0"
block_external_search_index: true
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->

{{< resource-docs-alert "aws" >}}




<h3>Resources</h3>
<ul class="api">
    <li><a href="#Workspace"><span class="symbol resource"></span>Workspace</a></li>
</ul>


<h3>Others</h3>
<ul class="api">
    <li><a href="#WorkspaceArgs"><span class="symbol api"></span>WorkspaceArgs</a></li>
    <li><a href="#WorkspaceState"><span class="symbol api"></span>WorkspaceState</a></li>
</ul>


<h2 id="resources">Resources</h2>
<h3 class="pdoc-module-header" id="Workspace" data-link-title="Workspace">
    <a href="https://github.com/pulumi/pulumi-aws/blob/d072b346d2519850d0b24c72316f8d7487257ab0/sdk/nodejs/amp/workspace.ts#L16">
        Resource <strong>Workspace</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>class</span> <span class='nx'>Workspace</span> <span class='kr'>extends</span> <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResource'>CustomResource</a></code></pre>

#### Import

AMP Workspaces can be imported using the identifier, e.g.

```sh
 $ pulumi import aws:amp/workspace:Workspace demo ws-C6DCB907-F2D7-4D96-957B-66691F865D8B
```

<h4 class="pdoc-member-header" id="Workspace-constructor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/d072b346d2519850d0b24c72316f8d7487257ab0/sdk/nodejs/amp/workspace.ts#L55"> <b>constructor</b></a>
</h4>


<pre class="highlight"><code><span class='kd'></span><span class='kd'>new</span> Workspace(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, args?: <a href='#WorkspaceArgs'>WorkspaceArgs</a>, opts?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>)</code></pre>


Create a Workspace resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h4 class="pdoc-member-header" id="Workspace-get">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/d072b346d2519850d0b24c72316f8d7487257ab0/sdk/nodejs/amp/workspace.ts#L26">method <b>get</b></a>
</h4>


<pre class="highlight"><code><span class='kd'>public static </span>get(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, id: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ID'>pulumi.ID</a>&gt;, state?: <a href='#WorkspaceState'>WorkspaceState</a>, opts?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>): <a href='#Workspace'>Workspace</a></code></pre>


Get an existing Workspace resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h4 class="pdoc-member-header" id="Workspace-getProvider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/d072b346d2519850d0b24c72316f8d7487257ab0/sdk/nodejs/amp/workspace.ts#L16">method <b>getProvider</b></a>
</h4>


<pre class="highlight"><code><span class='kd'></span>getProvider(moduleMember: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>): <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ProviderResource'>ProviderResource</a> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span></code></pre>

<h4 class="pdoc-member-header" id="Workspace-isInstance">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/d072b346d2519850d0b24c72316f8d7487257ab0/sdk/nodejs/amp/workspace.ts#L37">method <b>isInstance</b></a>
</h4>


<pre class="highlight"><code><span class='kd'>public static </span>isInstance(obj: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): obj is Workspace</code></pre>


Returns true if the given object is an instance of Workspace.  This is designed to work even
when multiple copies of the Pulumi SDK have been loaded into the same process.

<h4 class="pdoc-member-header" id="Workspace-alias">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/d072b346d2519850d0b24c72316f8d7487257ab0/sdk/nodejs/amp/workspace.ts#L47">property <b>alias</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>alias: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span>&gt;;</code></pre>

The alias of the prometheus workspace. See more [in AWS Docs](https://docs.aws.amazon.com/prometheus/latest/userguide/AMP-onboard-create-workspace.html).

<h4 class="pdoc-member-header" id="Workspace-arn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/d072b346d2519850d0b24c72316f8d7487257ab0/sdk/nodejs/amp/workspace.ts#L51">property <b>arn</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>arn: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

Amazon Resource Name (ARN) of the workspace.

<h4 class="pdoc-member-header" id="Workspace-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/d072b346d2519850d0b24c72316f8d7487257ab0/sdk/nodejs/amp/workspace.ts#L16">property <b>id</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>id: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ID'>ID</a>&gt;;</code></pre>

id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h4 class="pdoc-member-header" id="Workspace-prometheusEndpoint">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/d072b346d2519850d0b24c72316f8d7487257ab0/sdk/nodejs/amp/workspace.ts#L55">property <b>prometheusEndpoint</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>prometheusEndpoint: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

Prometheus endpoint available for this workspace.

<h4 class="pdoc-member-header" id="Workspace-urn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/d072b346d2519850d0b24c72316f8d7487257ab0/sdk/nodejs/amp/workspace.ts#L16">property <b>urn</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>urn: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#URN'>URN</a>&gt;;</code></pre>

urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.



<h2 id="apis">Others</h2>
<h3 class="pdoc-module-header" id="WorkspaceArgs" data-link-title="WorkspaceArgs">
    <a href="https://github.com/pulumi/pulumi-aws/blob/d072b346d2519850d0b24c72316f8d7487257ab0/sdk/nodejs/amp/workspace.ts#L110">
        interface <strong>WorkspaceArgs</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>WorkspaceArgs</span></code></pre>

The set of arguments for constructing a Workspace resource.

<h4 class="pdoc-member-header" id="WorkspaceArgs-alias">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/d072b346d2519850d0b24c72316f8d7487257ab0/sdk/nodejs/amp/workspace.ts#L114">property <b>alias</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>alias?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The alias of the prometheus workspace. See more [in AWS Docs](https://docs.aws.amazon.com/prometheus/latest/userguide/AMP-onboard-create-workspace.html).

<h3 class="pdoc-module-header" id="WorkspaceState" data-link-title="WorkspaceState">
    <a href="https://github.com/pulumi/pulumi-aws/blob/d072b346d2519850d0b24c72316f8d7487257ab0/sdk/nodejs/amp/workspace.ts#L92">
        interface <strong>WorkspaceState</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>WorkspaceState</span></code></pre>

Input properties used for looking up and filtering Workspace resources.

<h4 class="pdoc-member-header" id="WorkspaceState-alias">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/d072b346d2519850d0b24c72316f8d7487257ab0/sdk/nodejs/amp/workspace.ts#L96">property <b>alias</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>alias?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The alias of the prometheus workspace. See more [in AWS Docs](https://docs.aws.amazon.com/prometheus/latest/userguide/AMP-onboard-create-workspace.html).

<h4 class="pdoc-member-header" id="WorkspaceState-arn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/d072b346d2519850d0b24c72316f8d7487257ab0/sdk/nodejs/amp/workspace.ts#L100">property <b>arn</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>arn?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

Amazon Resource Name (ARN) of the workspace.

<h4 class="pdoc-member-header" id="WorkspaceState-prometheusEndpoint">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/d072b346d2519850d0b24c72316f8d7487257ab0/sdk/nodejs/amp/workspace.ts#L104">property <b>prometheusEndpoint</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>prometheusEndpoint?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

Prometheus endpoint available for this workspace.

