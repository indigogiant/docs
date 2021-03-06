---
title: "Module types/input"
title_tag: "Module types/input | Package @pulumi/github | Node.js SDK"
linktitle: "input"
meta_desc: "Explore members of the input module in the @pulumi/github package."
git_sha: "e8f9b4d493759a8abb4db6981f20e9c741ce1d20"
block_external_search_index: true
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->

{{< resource-docs-alert "github" >}}






<h3>APIs</h3>
<ul class="api">
    <li><a href="#BranchProtectionRequiredPullRequestReview"><span class="symbol api"></span>BranchProtectionRequiredPullRequestReview</a></li>
    <li><a href="#BranchProtectionRequiredStatusCheck"><span class="symbol api"></span>BranchProtectionRequiredStatusCheck</a></li>
    <li><a href="#BranchProtectionV3RequiredPullRequestReviews"><span class="symbol api"></span>BranchProtectionV3RequiredPullRequestReviews</a></li>
    <li><a href="#BranchProtectionV3RequiredStatusChecks"><span class="symbol api"></span>BranchProtectionV3RequiredStatusChecks</a></li>
    <li><a href="#BranchProtectionV3Restrictions"><span class="symbol api"></span>BranchProtectionV3Restrictions</a></li>
    <li><a href="#OrganizationWebhookConfiguration"><span class="symbol api"></span>OrganizationWebhookConfiguration</a></li>
    <li><a href="#RepositoryPages"><span class="symbol api"></span>RepositoryPages</a></li>
    <li><a href="#RepositoryPagesSource"><span class="symbol api"></span>RepositoryPagesSource</a></li>
    <li><a href="#RepositoryTemplate"><span class="symbol api"></span>RepositoryTemplate</a></li>
    <li><a href="#RepositoryWebhookConfiguration"><span class="symbol api"></span>RepositoryWebhookConfiguration</a></li>
    <li><a href="#TeamSyncGroupMappingGroup"><span class="symbol api"></span>TeamSyncGroupMappingGroup</a></li>
</ul>




<h2 id="apis">APIs</h2>
<h3 class="pdoc-module-header" id="BranchProtectionRequiredPullRequestReview" data-link-title="BranchProtectionRequiredPullRequestReview">
    <a href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L7">
        interface <strong>BranchProtectionRequiredPullRequestReview</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>BranchProtectionRequiredPullRequestReview</span></code></pre>
<h4 class="pdoc-member-header" id="BranchProtectionRequiredPullRequestReview-dismissStaleReviews">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L8">property <b>dismissStaleReviews</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>dismissStaleReviews?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="BranchProtectionRequiredPullRequestReview-dismissalRestrictions">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L9">property <b>dismissalRestrictions</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>dismissalRestrictions?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;[]&gt;;</code></pre>
<h4 class="pdoc-member-header" id="BranchProtectionRequiredPullRequestReview-requireCodeOwnerReviews">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L10">property <b>requireCodeOwnerReviews</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>requireCodeOwnerReviews?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="BranchProtectionRequiredPullRequestReview-requiredApprovingReviewCount">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L11">property <b>requiredApprovingReviewCount</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>requiredApprovingReviewCount?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number'>number</a></span>&gt;;</code></pre>
<h3 class="pdoc-module-header" id="BranchProtectionRequiredStatusCheck" data-link-title="BranchProtectionRequiredStatusCheck">
    <a href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L14">
        interface <strong>BranchProtectionRequiredStatusCheck</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>BranchProtectionRequiredStatusCheck</span></code></pre>
<h4 class="pdoc-member-header" id="BranchProtectionRequiredStatusCheck-contexts">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L15">property <b>contexts</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>contexts?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;[]&gt;;</code></pre>
<h4 class="pdoc-member-header" id="BranchProtectionRequiredStatusCheck-strict">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L16">property <b>strict</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>strict?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span>&gt;;</code></pre>
<h3 class="pdoc-module-header" id="BranchProtectionV3RequiredPullRequestReviews" data-link-title="BranchProtectionV3RequiredPullRequestReviews">
    <a href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L19">
        interface <strong>BranchProtectionV3RequiredPullRequestReviews</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>BranchProtectionV3RequiredPullRequestReviews</span></code></pre>
<h4 class="pdoc-member-header" id="BranchProtectionV3RequiredPullRequestReviews-dismissStaleReviews">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L20">property <b>dismissStaleReviews</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>dismissStaleReviews?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="BranchProtectionV3RequiredPullRequestReviews-dismissalTeams">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L21">property <b>dismissalTeams</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>dismissalTeams?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;[]&gt;;</code></pre>
<h4 class="pdoc-member-header" id="BranchProtectionV3RequiredPullRequestReviews-dismissalUsers">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L22">property <b>dismissalUsers</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>dismissalUsers?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;[]&gt;;</code></pre>
<h4 class="pdoc-member-header" id="BranchProtectionV3RequiredPullRequestReviews-includeAdmins">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L26">property <b>includeAdmins</b></a>
</h4>

<div class="note note-deprecated">
<i class="fas fa-exclamation-triangle pr-2"></i><strong>DEPRECATED</strong>
Use enforce_admins instead
</div>
<pre class="highlight"><code><span class='kd'></span>includeAdmins?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="BranchProtectionV3RequiredPullRequestReviews-requireCodeOwnerReviews">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L27">property <b>requireCodeOwnerReviews</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>requireCodeOwnerReviews?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="BranchProtectionV3RequiredPullRequestReviews-requiredApprovingReviewCount">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L28">property <b>requiredApprovingReviewCount</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>requiredApprovingReviewCount?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number'>number</a></span>&gt;;</code></pre>
<h3 class="pdoc-module-header" id="BranchProtectionV3RequiredStatusChecks" data-link-title="BranchProtectionV3RequiredStatusChecks">
    <a href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L31">
        interface <strong>BranchProtectionV3RequiredStatusChecks</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>BranchProtectionV3RequiredStatusChecks</span></code></pre>
<h4 class="pdoc-member-header" id="BranchProtectionV3RequiredStatusChecks-contexts">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L32">property <b>contexts</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>contexts?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;[]&gt;;</code></pre>
<h4 class="pdoc-member-header" id="BranchProtectionV3RequiredStatusChecks-includeAdmins">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L36">property <b>includeAdmins</b></a>
</h4>

<div class="note note-deprecated">
<i class="fas fa-exclamation-triangle pr-2"></i><strong>DEPRECATED</strong>
Use enforce_admins instead
</div>
<pre class="highlight"><code><span class='kd'></span>includeAdmins?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="BranchProtectionV3RequiredStatusChecks-strict">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L37">property <b>strict</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>strict?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span>&gt;;</code></pre>
<h3 class="pdoc-module-header" id="BranchProtectionV3Restrictions" data-link-title="BranchProtectionV3Restrictions">
    <a href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L40">
        interface <strong>BranchProtectionV3Restrictions</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>BranchProtectionV3Restrictions</span></code></pre>
<h4 class="pdoc-member-header" id="BranchProtectionV3Restrictions-apps">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L41">property <b>apps</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>apps?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;[]&gt;;</code></pre>
<h4 class="pdoc-member-header" id="BranchProtectionV3Restrictions-teams">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L42">property <b>teams</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>teams?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;[]&gt;;</code></pre>
<h4 class="pdoc-member-header" id="BranchProtectionV3Restrictions-users">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L43">property <b>users</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>users?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;[]&gt;;</code></pre>
<h3 class="pdoc-module-header" id="OrganizationWebhookConfiguration" data-link-title="OrganizationWebhookConfiguration">
    <a href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L46">
        interface <strong>OrganizationWebhookConfiguration</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>OrganizationWebhookConfiguration</span></code></pre>
<h4 class="pdoc-member-header" id="OrganizationWebhookConfiguration-contentType">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L47">property <b>contentType</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>contentType?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="OrganizationWebhookConfiguration-insecureSsl">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L48">property <b>insecureSsl</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>insecureSsl?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="OrganizationWebhookConfiguration-secret">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L49">property <b>secret</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>secret?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="OrganizationWebhookConfiguration-url">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L53">property <b>url</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>url: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

URL of the webhook

<h3 class="pdoc-module-header" id="RepositoryPages" data-link-title="RepositoryPages">
    <a href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L56">
        interface <strong>RepositoryPages</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>RepositoryPages</span></code></pre>
<h4 class="pdoc-member-header" id="RepositoryPages-cname">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L60">property <b>cname</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>cname?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The custom domain for the repository. This can only be set after the repository has been created.

<h4 class="pdoc-member-header" id="RepositoryPages-custom404">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L64">property <b>custom404</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>custom404?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span>&gt;;</code></pre>

Whether the rendered Github Pages site has a custom 404 page.

<h4 class="pdoc-member-header" id="RepositoryPages-htmlUrl">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L68">property <b>htmlUrl</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>htmlUrl?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The absolute URL (including scheme) of the rendered Github Pages site e.g. `https://username.github.io`.

<h4 class="pdoc-member-header" id="RepositoryPages-source">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L72">property <b>source</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>source: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='#RepositoryPagesSource'>RepositoryPagesSource</a>&gt;;</code></pre>

The source branch and directory for the rendered Pages site. See Github Pages Source below for details.

<h4 class="pdoc-member-header" id="RepositoryPages-status">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L76">property <b>status</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>status?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The Github Pages site's build status e.g. `building` or `built`.

<h4 class="pdoc-member-header" id="RepositoryPages-url">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L77">property <b>url</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>url?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h3 class="pdoc-module-header" id="RepositoryPagesSource" data-link-title="RepositoryPagesSource">
    <a href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L80">
        interface <strong>RepositoryPagesSource</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>RepositoryPagesSource</span></code></pre>
<h4 class="pdoc-member-header" id="RepositoryPagesSource-branch">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L84">property <b>branch</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>branch: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The repository branch used to publish the site's source files. (i.e. `main` or `gh-pages`.

<h4 class="pdoc-member-header" id="RepositoryPagesSource-path">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L88">property <b>path</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>path?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The repository directory from which the site publishes (Default: `/`).

<h3 class="pdoc-module-header" id="RepositoryTemplate" data-link-title="RepositoryTemplate">
    <a href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L91">
        interface <strong>RepositoryTemplate</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>RepositoryTemplate</span></code></pre>
<h4 class="pdoc-member-header" id="RepositoryTemplate-owner">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L92">property <b>owner</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>owner: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="RepositoryTemplate-repository">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L93">property <b>repository</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>repository: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h3 class="pdoc-module-header" id="RepositoryWebhookConfiguration" data-link-title="RepositoryWebhookConfiguration">
    <a href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L96">
        interface <strong>RepositoryWebhookConfiguration</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>RepositoryWebhookConfiguration</span></code></pre>
<h4 class="pdoc-member-header" id="RepositoryWebhookConfiguration-contentType">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L97">property <b>contentType</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>contentType?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="RepositoryWebhookConfiguration-insecureSsl">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L98">property <b>insecureSsl</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>insecureSsl?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="RepositoryWebhookConfiguration-secret">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L99">property <b>secret</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>secret?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="RepositoryWebhookConfiguration-url">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L103">property <b>url</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>url: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

URL of the webhook.  This is a sensitive attribute because it may include basic auth credentials.

<h3 class="pdoc-module-header" id="TeamSyncGroupMappingGroup" data-link-title="TeamSyncGroupMappingGroup">
    <a href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L106">
        interface <strong>TeamSyncGroupMappingGroup</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>TeamSyncGroupMappingGroup</span></code></pre>
<h4 class="pdoc-member-header" id="TeamSyncGroupMappingGroup-groupDescription">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L110">property <b>groupDescription</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>groupDescription: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The description of the IdP group.

<h4 class="pdoc-member-header" id="TeamSyncGroupMappingGroup-groupId">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L114">property <b>groupId</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>groupId: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The ID of the IdP group.

<h4 class="pdoc-member-header" id="TeamSyncGroupMappingGroup-groupName">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-github/blob/e8f9b4d493759a8abb4db6981f20e9c741ce1d20/sdk/nodejs/types/input.ts#L118">property <b>groupName</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>groupName: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The name of the IdP group.

