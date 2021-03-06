---
title: "Module config"
title_tag: "Module config | Package @pulumi/azuread | Node.js SDK"
linktitle: "config"
meta_desc: "Explore members of the config module in the @pulumi/azuread package."
git_sha: "2552d877f9d16cc04b553141134ed06597b777f6"
block_external_search_index: true
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->

{{< resource-docs-alert "azuread" >}}






<h3>APIs</h3>
<ul class="api">
    <li><a href="#clientCertificatePassword"><span class="symbol api"></span>clientCertificatePassword</a></li>
    <li><a href="#clientCertificatePath"><span class="symbol api"></span>clientCertificatePath</a></li>
    <li><a href="#clientId"><span class="symbol api"></span>clientId</a></li>
    <li><a href="#clientSecret"><span class="symbol api"></span>clientSecret</a></li>
    <li><a href="#disableTerraformPartnerId"><span class="symbol api"></span>disableTerraformPartnerId</a></li>
    <li><a href="#environment"><span class="symbol api"></span>environment</a></li>
    <li><a href="#metadataHost"><span class="symbol api"></span>metadataHost</a></li>
    <li><a href="#msiEndpoint"><span class="symbol api"></span>msiEndpoint</a></li>
    <li><a href="#partnerId"><span class="symbol api"></span>partnerId</a></li>
    <li><a href="#tenantId"><span class="symbol api"></span>tenantId</a></li>
    <li><a href="#useMsi"><span class="symbol api"></span>useMsi</a></li>
</ul>




<h2 id="apis">APIs</h2>
<h3 class="pdoc-module-header" id="clientCertificatePassword" data-link-title="clientCertificatePassword">
    <a href="https://github.com/pulumi/pulumi-azuread/blob/2552d877f9d16cc04b553141134ed06597b777f6/sdk/nodejs/config/vars.ts#L9">
        let <strong>clientCertificatePassword</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> clientCertificatePassword: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;clientCertificatePassword&#34;) || (utilities.getEnv(&#34;ARM_CLIENT_CERTIFICATE_PASSWORD&#34;) || &#34;&#34;)</span>;</code></pre>
<h3 class="pdoc-module-header" id="clientCertificatePath" data-link-title="clientCertificatePath">
    <a href="https://github.com/pulumi/pulumi-azuread/blob/2552d877f9d16cc04b553141134ed06597b777f6/sdk/nodejs/config/vars.ts#L14">
        let <strong>clientCertificatePath</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> clientCertificatePath: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;clientCertificatePath&#34;) || (utilities.getEnv(&#34;ARM_CLIENT_CERTIFICATE_PATH&#34;) || &#34;&#34;)</span>;</code></pre>

The path to the Client Certificate associated with the Service Principal for use when authenticating as a Service
Principal using a Client Certificate.

<h3 class="pdoc-module-header" id="clientId" data-link-title="clientId">
    <a href="https://github.com/pulumi/pulumi-azuread/blob/2552d877f9d16cc04b553141134ed06597b777f6/sdk/nodejs/config/vars.ts#L18">
        let <strong>clientId</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> clientId: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;clientId&#34;) || (utilities.getEnv(&#34;ARM_CLIENT_ID&#34;) || &#34;&#34;)</span>;</code></pre>

The Client ID which should be used for service principal authentication.

<h3 class="pdoc-module-header" id="clientSecret" data-link-title="clientSecret">
    <a href="https://github.com/pulumi/pulumi-azuread/blob/2552d877f9d16cc04b553141134ed06597b777f6/sdk/nodejs/config/vars.ts#L23">
        let <strong>clientSecret</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> clientSecret: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;clientSecret&#34;) || (utilities.getEnv(&#34;ARM_CLIENT_SECRET&#34;) || &#34;&#34;)</span>;</code></pre>

The password to decrypt the Client Certificate. For use when authenticating as a Service Principal using a Client
Certificate

<h3 class="pdoc-module-header" id="disableTerraformPartnerId" data-link-title="disableTerraformPartnerId">
    <a href="https://github.com/pulumi/pulumi-azuread/blob/2552d877f9d16cc04b553141134ed06597b777f6/sdk/nodejs/config/vars.ts#L27">
        let <strong>disableTerraformPartnerId</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> disableTerraformPartnerId: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.getObject&lt;boolean&gt;(&#34;disableTerraformPartnerId&#34;)</span>;</code></pre>

Disable the Terraform Partner ID which is used if a custom `partner_id` isn't specified.

<h3 class="pdoc-module-header" id="environment" data-link-title="environment">
    <a href="https://github.com/pulumi/pulumi-azuread/blob/2552d877f9d16cc04b553141134ed06597b777f6/sdk/nodejs/config/vars.ts#L32">
        let <strong>environment</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> environment: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;environment&#34;) || (utilities.getEnv(&#34;ARM_ENVIRONMENT&#34;) || &#34;public&#34;)</span>;</code></pre>

The Cloud Environment which should be used. Possible values are `public`, `usgovernment`, `german`, and `china`.
Defaults to `public`.

<h3 class="pdoc-module-header" id="metadataHost" data-link-title="metadataHost">
    <a href="https://github.com/pulumi/pulumi-azuread/blob/2552d877f9d16cc04b553141134ed06597b777f6/sdk/nodejs/config/vars.ts#L36">
        let <strong>metadataHost</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> metadataHost: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;metadataHost&#34;)</span>;</code></pre>

The Hostname which should be used for the Azure Metadata Service.

<h3 class="pdoc-module-header" id="msiEndpoint" data-link-title="msiEndpoint">
    <a href="https://github.com/pulumi/pulumi-azuread/blob/2552d877f9d16cc04b553141134ed06597b777f6/sdk/nodejs/config/vars.ts#L41">
        let <strong>msiEndpoint</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> msiEndpoint: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;msiEndpoint&#34;) || (utilities.getEnv(&#34;ARM_MSI_ENDPOINT&#34;) || &#34;&#34;)</span>;</code></pre>

The path to a custom endpoint for Managed Service Identity - in most circumstances this should be detected
automatically.

<h3 class="pdoc-module-header" id="partnerId" data-link-title="partnerId">
    <a href="https://github.com/pulumi/pulumi-azuread/blob/2552d877f9d16cc04b553141134ed06597b777f6/sdk/nodejs/config/vars.ts#L45">
        let <strong>partnerId</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> partnerId: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;partnerId&#34;)</span>;</code></pre>

A GUID/UUID that is registered with Microsoft to facilitate partner resource usage attribution.

<h3 class="pdoc-module-header" id="tenantId" data-link-title="tenantId">
    <a href="https://github.com/pulumi/pulumi-azuread/blob/2552d877f9d16cc04b553141134ed06597b777f6/sdk/nodejs/config/vars.ts#L49">
        let <strong>tenantId</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> tenantId: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;tenantId&#34;) || (utilities.getEnv(&#34;ARM_TENANT_ID&#34;) || &#34;&#34;)</span>;</code></pre>

The Tenant ID which should be used. Works with all authentication methods except MSI.

<h3 class="pdoc-module-header" id="useMsi" data-link-title="useMsi">
    <a href="https://github.com/pulumi/pulumi-azuread/blob/2552d877f9d16cc04b553141134ed06597b777f6/sdk/nodejs/config/vars.ts#L53">
        let <strong>useMsi</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> useMsi: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.getObject&lt;boolean&gt;(&#34;useMsi&#34;) || (&lt;any&gt;utilities.getEnvBoolean(&#34;ARM_USE_MSI&#34;) || false)</span>;</code></pre>

Allow Managed Service Identity to be used for Authentication.

