---
title: "Module config"
title_tag: "Module config | Package @pulumi/spotinst | Node.js SDK"
linktitle: "config"
meta_desc: "Explore members of the config module in the @pulumi/spotinst package."
git_sha: "8b0777509728d621477d945466a125853cc401d5"
block_external_search_index: true
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->

{{< resource-docs-alert "spotinst" >}}






<h3>APIs</h3>
<ul class="api">
    <li><a href="#account"><span class="symbol api"></span>account</a></li>
    <li><a href="#featureFlags"><span class="symbol api"></span>featureFlags</a></li>
    <li><a href="#token"><span class="symbol api"></span>token</a></li>
</ul>




<h2 id="apis">APIs</h2>
<h3 class="pdoc-module-header" id="account" data-link-title="account">
    <a href="https://github.com/pulumi/pulumi-spotinst/blob/8b0777509728d621477d945466a125853cc401d5/sdk/nodejs/config/vars.ts#L12">
        let <strong>account</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> account: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;account&#34;) || (utilities.getEnv(&#34;SPOTINST_ACCOUNT&#34;) || &#34;&#34;)</span>;</code></pre>

Spotinst Account ID

<h3 class="pdoc-module-header" id="featureFlags" data-link-title="featureFlags">
    <a href="https://github.com/pulumi/pulumi-spotinst/blob/8b0777509728d621477d945466a125853cc401d5/sdk/nodejs/config/vars.ts#L16">
        let <strong>featureFlags</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> featureFlags: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;featureFlags&#34;)</span>;</code></pre>

Spotinst SDK Feature Flags

<h3 class="pdoc-module-header" id="token" data-link-title="token">
    <a href="https://github.com/pulumi/pulumi-spotinst/blob/8b0777509728d621477d945466a125853cc401d5/sdk/nodejs/config/vars.ts#L20">
        let <strong>token</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> token: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;token&#34;) || (utilities.getEnv(&#34;SPOTINST_TOKEN&#34;) || &#34;&#34;)</span>;</code></pre>

Spotinst Personal API Access Token

