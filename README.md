<h1>uikit2Twig</h1>

<h2>Uikit Base Component Twig Macros</h2>
<h3>Alert</h3>
<p>This macro will generate markup based on the&nbsp;<a href="https://getuikit.com/v2/docs/alert.html" rel="nofollow">uikit alert</a>.</p>
<div data-hasbody="true" data-macro-name="code">
<div><strong>Alert Macro</strong></div>
<div>
<div>
<div>
<table border="0" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td>
<div title="Hint: double-click to select code">
<div><code>{{ uikit.alert(content, options) }}</code></div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
</div>
</div>
</div>
<p>The <strong>content&nbsp;</strong>parameter can contain plain text or markup. The <strong>options</strong> parameter requires an <code>array { name : value }.</code></p>
<div>
<table>
<thead>
<tr>
<th tabindex="0" data-column="0">
<div>Option Name</div>
</th>
<th tabindex="0" data-column="1">
<div>
<p>Option Value</p>
</div>
</th>
<th tabindex="0" colspan="1" data-column="2">
<div>Description</div>
</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="1">
<pre>color</pre>
</td>
<td colspan="1">
<pre>success</pre>
<pre>warning</pre>
<pre>danger</pre>
</td>
<td colspan="1">
<p>Change the color based on message type.<br />If no valid option is set, the alert will default to blue.</p>
</td>
</tr>
<tr>
<td colspan="1">
<pre>close</pre>
</td>
<td colspan="1">
<pre>button</pre>
<pre>a</pre>
</td>
<td colspan="1">Make the alert dismissable.
<p>If no option set alert can not be dismissed. If you want a dismissable alert you can set it as an HTML button or anchor tag.</p>
</td>
</tr>
<tr>
<td colspan="1">
<pre>size</pre>
</td>
<td colspan="1">
<pre>large</pre>
</td>
<td colspan="1">
<p>Get a bigger Alert for more complex content.</p>
<p>If no valid option set it defaults to the smaller size.</p>
</td>
</tr>
<tr>
<td colspan="1">
<pre>attributes</pre>
</td>
<td colspan="1">
<pre>array {}</pre>
<p><em>Any valid attribute for an HTML &lt;div&gt;</em></p>
<p><em>example:</em></p>
<pre>attributes : {class : 'a-class-name','data-attr' : 'some data'}</pre>
</td>
<td colspan="1">Customise with HTML attributes.</td>
</tr>
</tbody>
</table>
</div>
<h3>Animation</h3>
<p>Uikit provides a set of classes for adding animation. This macro allows you to inject these classes into templates while keeping them framework agnostic for any changes that might come down the road. See the <a href="https://getuikit.com/v2/docs/animation.html" rel="nofollow">uikit animation component </a>for details on how these classes work.</p>
<div data-hasbody="true" data-macro-name="code">
<div><strong>Animation Macro</strong></div>
<div>
<div>
<div>
<table border="0" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td>
<div title="Hint: double-click to select code">
<div><code>{{ uikit.animations(name) }}</code></div>
<div><code>&lt;!--Example--&gt;</code></div>
<div><code>&lt;</code><code>div</code> <code>class</code><code>=</code><code>'{{ uikit.animations('</code><code>fade') }}'&gt;content of div&lt;/</code><code>div</code><code>&gt;</code></div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
</div>
</div>
</div>
<div>
<table>
<thead>
<tr>
<th tabindex="0" data-column="0">
<div>Parameter</div>
</th>
<th tabindex="0" data-column="1">
<div>Description</div>
</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>fade</code></td>
<td>The element fades in.</td>
</tr>
<tr>
<td><code>scale-up</code></td>
<td>The element scales up.</td>
</tr>
<tr>
<td><code>scale-down</code></td>
<td>The element scales down.</td>
</tr>
<tr>
<td><code>slide-top</code></td>
<td>The element slides in from the top.</td>
</tr>
<tr>
<td><code>slide-bottom</code></td>
<td>The element slides in from the bottom.</td>
</tr>
<tr>
<td><code>slide-left</code></td>
<td>The element slides in from the left.</td>
</tr>
<tr>
<td><code>slide-right</code></td>
<td>The element slides in from the right.</td>
</tr>
<tr>
<td><code>shake</code></td>
<td>The element shakes.</td>
</tr>
<tr>
<td><code>scale</code></td>
<td>The element scales down without fading in.</td>
</tr>
</tbody>
</table>
</div>
<h3>Badge</h3>
<p>&nbsp;This macro will generate markup based on the <a href="https://getuikit.com/v2/docs/badge.html" rel="nofollow">uikit badge</a>.</p>
<div data-hasbody="true" data-macro-name="code">
<div><strong>Badge Macro</strong></div>
<div>
<div>
<div>
<table border="0" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td>
<div title="Hint: double-click to select code">
<div><code>{{ uikit.badge(content, options) }}</code></div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
</div>
</div>
</div>
<p>The&nbsp;<strong>content&nbsp;</strong>parameter can contain plain text or markup. The&nbsp;<strong>options</strong>&nbsp;parameter requires an&nbsp;<code>array { name : value }.</code></p>
<div>
<table>
<thead>
<tr>
<th tabindex="0" data-column="0">
<div>Option Name</div>
</th>
<th tabindex="0" data-column="1">
<div>
<p>Option Value</p>
</div>
</th>
<th tabindex="0" colspan="1" data-column="2">
<div>Description</div>
</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="1">
<pre>color</pre>
</td>
<td colspan="1">
<pre>success</pre>
<pre>warning</pre>
<pre>danger</pre>
</td>
<td colspan="1">
<p>Change the color based on message type.<br />If no valid option is set, the alert will default to blue.</p>
</td>
</tr>
<tr>
<td colspan="1">
<pre>notification</pre>
</td>
<td colspan="1">
<pre>boolean</pre>
</td>
<td colspan="1">Make the alert dismissable.
<p>If no option set, defaults to false.</p>
</td>
</tr>
<tr>
<td colspan="1">
<pre>attributes</pre>
</td>
<td colspan="1">
<pre>array {}</pre>
<p><em>Any valid attribute for an HTML &lt;div&gt;</em></p>
<p><em>example:</em></p>
<pre>attributes : {class : 'a-class-name','data-attr' : 'some data'}</pre>
</td>
<td colspan="1">Customise with HTML attributes.</td>
</tr>
</tbody>
</table>
</div>
<h3>Button</h3>
<p>&nbsp;This macro will generate markup based on the&nbsp;<a href="https://getuikit.com/v2/docs/button.html" rel="nofollow">uikit button</a>.</p>
<div data-hasbody="true" data-macro-name="code">
<div><strong>Badge Macro</strong></div>
<div>
<div>
<div>
<table border="0" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td>
<div title="Hint: double-click to select code">
<div><code>{{ uikit.button(action, options) }}</code></div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
</div>
</div>
</div>
<p>The original application I created this for required that all button language should follow the pattern of having an action and an optional subject. Example: 'Search' is a stand alone action. Or, for more clarity one might add a subject 'Our Database'. We add the distinction for styling purposes as well as consistency of actionable interface components. A link or a button's text should always be an action that reflects what will happen if the user interacts with it.</p>
<p>The&nbsp;<strong>action&nbsp;</strong>parameter can contain plain text or markup. It should contain the action of the link text. The&nbsp;<strong>options</strong>&nbsp;parameter requires an&nbsp;<code>array { name : value }.</code>&nbsp;</p>
<p>Feel free to edit out the subject option if you don't like or want it.</p>
<div>
<table>
<thead>
<tr>
<th tabindex="0" data-column="0">
<div>Option Name</div>
</th>
<th tabindex="0" data-column="1">
<div>
<p>Option Value</p>
</div>
</th>
<th tabindex="0" colspan="1" data-column="2">
<div>Description</div>
</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="1">
<pre>subject</pre>
</td>
<td colspan="1">plain text or markup</td>
<td colspan="1">All button language should follow the pattern of having an action and an optional subject. Example: 'Search' is a stand alone action. Or, for more clarity one might add a subject 'Our Database'. We add the distinction for styling purposes as well as consistency of actionable interface components. A link or a button's text should always be an action that reflects what will happen if the user interacts with it. Adding the subject, simply should add clarity and specificity to the action.</td>
</tr>
<tr>
<td colspan="1">
<pre>color</pre>
</td>
<td colspan="1">
<pre>primary</pre>
<p>success</p>
<pre>danger</pre>
<pre>link</pre>
</td>
<td colspan="1">
<p>Change the color based on message type.<br />If no valid option is set, the button will default to grey.</p>
<p>Link color value maintains the button html but styles to look like a link.</p>
</td>
</tr>
<tr>
<td colspan="1">
<pre>size</pre>
</td>
<td colspan="1">
<pre>mini</pre>
<pre>small</pre>
<pre>large</pre>
</td>
<td colspan="1">
<p>Get a smaller or larger button. <br />If no valid option is set, buttons will be the default size.</p>
</td>
</tr>
<tr>
<td colspan="1">
<pre>fullwidth</pre>
</td>
<td colspan="1">
<pre>boolean</pre>
</td>
<td colspan="1">Make the button 100% width of it's parent container.
<p>If no option set, defaults to false.</p>
</td>
</tr>
<tr>
<td colspan="1">
<pre>link</pre>
</td>
<td colspan="1">
<pre>boolean</pre>
</td>
<td colspan="1">
<p>HTML markup as anchor but style to look like a button, if set to true. Defaults to false.</p>
<p>IMPORTANT: If set to true, you will need to include an 'href' in options.attributes.</p>
</td>
</tr>
<tr>
<td colspan="1">
<pre>icon</pre>
</td>
<td colspan="1">
<pre>array {} </pre>
</td>
<td colspan="1">Add an icon to your button. Imports the uikit.icon macro.<br />See that macro for full details of available options.</td>
</tr>
<tr>
<td colspan="1">
<pre>disabled</pre>
</td>
<td colspan="1">
<pre>boolean</pre>
</td>
<td colspan="1">Disable the button. Defaults to false.</td>
</tr>
<tr>
<td colspan="1">
<pre>attributes</pre>
</td>
<td colspan="1">
<pre>array {}</pre>
<p><em>Any valid attribute for an HTML &lt;button&gt; or &lt;a&gt; (depending which you choose)</em></p>
<p><em>example:</em></p>
<pre>attributes : {class : 'a-class-name','data-attr' : 'some data'}</pre>
</td>
<td colspan="1">Customise with HTML attributes.</td>
</tr>
</tbody>
</table>
</div>
<h3>Description List (or Definition List)</h3>
<p>This macro will generate markup based on the&nbsp;<a href="https://getuikit.com/v2/docs/description-list.html" rel="nofollow">uikit description list</a>.</p>
<div data-hasbody="true" data-macro-name="code">
<div><strong>Description List Macro</strong></div>
<div>
<div>
<div>
<table border="0" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td>
<div title="Hint: double-click to select code">
<div><code>{{ uikit.descriptionList(data, options) }}</code></div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
</div>
</div>
</div>
<h4>Data Parameter</h4>
<p>The <strong>data</strong> parameter expects a multidimensional array. Each child array requires a <strong>term&nbsp;</strong>and a <strong>description.&nbsp;</strong>Both terms and descriptions can contain plain text or markup.</p>
<p><em>Example:</em></p>
<div>
<div data-hasbody="true" data-macro-name="code">
<div>
<div>
<div>
<table border="0" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td>
<div title="Hint: double-click to select code">
<div><code>{{ uikit.descriptionList(</code></div>
<div><code> </code><code>[</code></div>
<div><code> </code><code>{ term : 'some term' , description : 'some discription' }</code></div>
<div><code> </code><code>]</code></div>
<div><code>) }}</code></div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
</div>
</div>
</div>
<p>A single term can have a single or multiple descriptions (or definitions) therefore, <strong>description</strong>&nbsp;can also contain an array [ ].</p>
<p><em>Example:</em></p>
</div>
<div data-hasbody="true" data-macro-name="code">
<div>
<div>
<div>
<table border="0" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td>
<div title="Hint: double-click to select code">
<div><code>{{ uikit.descriptionList(</code></div>
<div><code> </code><code>[</code></div>
<div><code> </code><code>{ term : 'some term' , description : 'some description' },</code></div>
<div><code> </code><code>{ term : 'some term', description : ['some description', 'some other description', 'some other other description']}</code></div>
<div><code> </code><code>]</code></div>
<div><code>) }}</code></div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
</div>
</div>
</div>
<h4>Options</h4>
<p>The&nbsp;<strong>options</strong>&nbsp;parameter requires an&nbsp;<code>array { name : value }.</code></p>
<div>
<table>
<thead>
<tr>
<th tabindex="0" data-column="0">
<div>Option Name</div>
</th>
<th tabindex="0" data-column="1">
<div>
<p>Option Value</p>
</div>
</th>
<th tabindex="0" colspan="1" data-column="2">
<div>Description</div>
</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="1">
<pre>style</pre>
</td>
<td colspan="1">
<pre>horizontal</pre>
<pre>line</pre>
</td>
<td colspan="1">
<p>Display terms and descriptions side by side (horizontal) or term over description and separate the description list items with lines (line). <br />If no valid value set, will default to horizontal.</p>
</td>
</tr>
<tr>
<td colspan="1">
<pre>attributes</pre>
</td>
<td colspan="1">
<pre>array {}</pre>
<p><em>Any valid attribute for an HTML &lt;dl&gt;</em></p>
<p><em>example:</em></p>
<pre>attributes : {class : 'a-class-name','data-attr' : 'some data'}</pre>
</td>
<td colspan="1">Customise with HTML attributes.</td>
</tr>
</tbody>
</table>
</div>
<h3>Icon</h3>
<p>This macro will generate markup based on <a href="https://getuikit.com/v2/docs/icon.html" rel="nofollow">uikit icon library</a>.</p>
<div></div>
<div data-hasbody="true" data-macro-name="code">
<div><strong>Icon Macro</strong></div>
<div>
<div>
<div>
<table border="0" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td>
<div title="Hint: double-click to select code">
<div><code>{{ uikit.icon(icon, options) }}</code></div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
</div>
</div>
</div>
<p>The&nbsp;<strong>icon&nbsp;</strong>parameter needs an available icon class from <a href="https://getuikit.com/v2/docs/icon.html" rel="nofollow">uikit library</a>(Needs the full class since I have an addtional icon library. Feel free to edit that if you only want to use uikit's icons.). The&nbsp;<strong>options</strong>&nbsp;parameter requires an&nbsp;<code>array { name : value }.</code></p>
<div>
<table>
<thead>
<tr>
<th tabindex="0" data-column="0">
<div>
<div>Option Name</div>
</div>
</th>
<th tabindex="0" data-column="1">
<div>
<div>
<p>Option Value</p>
</div>
</div>
</th>
<th tabindex="0" colspan="1" data-column="2">
<div>
<div>Description</div>
</div>
</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="1">
<pre>link</pre>
</td>
<td colspan="1">
<pre>boolean</pre>
</td>
<td colspan="1">
<p>Defaults to false. If set, the HTML tag for the icon switches from &lt;span&gt; to &lt;a&gt;. A class will be applied to remove default link styling and applies hover styling.</p>
<p><em>(see 'hover' in uikit icon docs)</em></p>
<p>IMPORTANT: If set to true, you will need to include an 'href' in options.attributes.</p>
</td>
</tr>
<tr>
<td colspan="1">
<pre>button</pre>
</td>
<td colspan="1">
<pre>boolean</pre>
</td>
<td colspan="1">
<p>Defaults to false. If set, the HTML tag for the icon switches from &lt;span&gt; to &lt;a&gt;. A class will be applied to remove default link styling and applies button styling.</p>
<p><em>(see 'button' in uikit icon docs)</em></p>
<p>IMPORTANT: If set to true, you will need to include an 'href' in options.attributes.</p>
</td>
</tr>
<tr>
<td colspan="1">
<pre>justify</pre>
</td>
<td colspan="1">
<pre>boolean</pre>
</td>
<td colspan="1">
<p>To add a fixed width to the icon and center it, add the <code>.uk-icon-justify</code> class. This is useful when using different icons in a list.</p>
<p>Defaults to false.</p>
</td>
</tr>
<tr>
<td colspan="1">
<pre>spin</pre>
</td>
<td colspan="1">
<pre>boolean</pre>
</td>
<td colspan="1">If you need the icon to spin, set this to true. Defaults to false (because we are no fun).</td>
</tr>
<tr>
<td colspan="1">
<pre>size</pre>
</td>
<td colspan="1">
<pre>small</pre>
<pre>medium</pre>
<pre>large</pre>
</td>
<td colspan="1">
<p>Some prebaked sizing. Default inherits font size of the parent container or whatever CSS value you customize it with.</p>
</td>
</tr>
<tr>
<td colspan="1">
<pre>attributes</pre>
</td>
<td colspan="1">
<pre>array {}</pre>
<p><em>Any valid attribute for an HTML &lt;span&gt; or &lt;a&gt; <em>(depending which you choose)</em></em></p>
<p><em>example:</em></p>
<pre>attributes : {class : 'a-class-name','data-attr' : 'some data'}</pre>
</td>
<td colspan="1">Customise with HTML attributes.</td>
</tr>
</tbody>
</table>
</div>
<h3>Modal</h3>
<p>This macro will generate markup based on the&nbsp;<a href="https://getuikit.com/v2/docs/modal.html" rel="nofollow">uikit modal</a>. All modals need a trigger (link or button or js event) to open the hidden modal div. The first macro, <code>uikit.modalTrigger</code>, will generate a link or button. The behavior of the modal is also set on the trigger. The second macro, <code>uikit.modal</code>, will create the hidden div for the modal content. <strong>The target parameter of the trigger and the corresponding modal must match.</strong></p>
<div data-hasbody="true" data-macro-name="code">
<div><strong>Modal Macros</strong></div>
<div>
<div>
<div>
<table border="0" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td>
<div title="Hint: double-click to select code">
<div><code>{# Place trigger link or button wherever you need it. #}</code></div>
<div><code>{{ uikit.modalTrigger(action, target, options) }}</code></div>
<div><code>{# Add target model macro wherever it makes sense in the dom of the page. #}</code></div>
<div><code>{{ uikit.modal(content, target, options) }}</code></div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
</div>
</div>
</div>
<h4>Trigger Options</h4>
<div>
<table>
<thead>
<tr>
<th tabindex="0" data-column="0">
<div>Option Name</div>
</th>
<th tabindex="0" data-column="1">
<div>Option Value</div>
</th>
<th tabindex="0" data-column="2">
<div>Description</div>
</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="1">
<pre>bgcloseDisable</pre>
</td>
<td colspan="1">
<pre>boolean</pre>
</td>
<td colspan="1">
<p>Set this option to disable the user's ability to click the background div of the modal overlay to close the modal. User must click the close 'x' in this scenario.</p>
<p>Defaults to false.</p>
</td>
</tr>
<tr>
<td colspan="1">
<pre>keepOpenModal</pre>
</td>
<td colspan="1">
<pre>boolean</pre>
</td>
<td colspan="1">
<p>Disable the automatic closing of a currently open model.</p>
<p>Defaults to false.</p>
</td>
</tr>
<tr>
<td colspan="1">
<pre>center</pre>
</td>
<td colspan="1">
<pre>boolean</pre>
</td>
<td colspan="1">
<p>Vertically center the modal.</p>
<p>Defaults to false.</p>
</td>
</tr>
<tr>
<td colspan="1">
<pre>button</pre>
</td>
<td colspan="1">
<pre>boolean or array {}</pre>
<p><em>See options array from button macro.</em></p>
</td>
<td colspan="1">Sets triggle to HTML button. If set to true, or present triggle will be button. You can add any button options as well in the form of an array which can pass the same options from the <a href="https://confluence.sentryds.com/pages/viewpage.action?pageId=104269962#Sentrikit(NOTRELEASED-WORKINPROGRESS)-buttonMacro">uikit.button macro</a>'s options.</td>
</tr>
<tr>
<td colspan="1">
<pre>link</pre>
</td>
<td colspan="1">
<pre>array {}</pre>
<p><em>Use array if you need to set a<em>ny valid attribute for an HTML &lt;a&gt;</em>. IMPORTANT: href will be set by 'target' so don't add another here. Example:</em></p>
<pre>link : { attributes : { class : 'js-modal-confirm' }</pre>
</td>
<td colspan="1">Triggle defaults to an &lt;a&gt; but if you would like to set additional HTML attributes you can do so with this array.</td>
</tr>
</tbody>
</table>
</div>
<h4>Target Options</h4>
<div>
<table>
<thead>
<tr>
<th tabindex="0" data-column="0">
<div>Option Name</div>
</th>
<th tabindex="0" data-column="1">
<div>Option Value</div>
</th>
<th tabindex="0" data-column="2">
<div>Description</div>
</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="1">
<pre>class</pre>
</td>
<td colspan="1">
<p>HTML class</p>
</td>
<td colspan="1">
<p>Add additional classes to the modal container.</p>
</td>
</tr>
<tr>
<td colspan="1">
<pre>lightbox</pre>
</td>
<td colspan="1">
<pre>boolean</pre>
</td>
<td colspan="1">Create a lightbox-like modal dialog.</td>
</tr>
<tr>
<td colspan="1">
<pre>blank</pre>
</td>
<td colspan="1">
<pre>boolean</pre>
</td>
<td colspan="1">Reset all styling, like padding and margin.</td>
</tr>
<tr>
<td colspan="1">
<pre>large</pre>
</td>
<td colspan="1">
<pre>boolean</pre>
</td>
<td colspan="1">Apply the site's container width to the modal dialog.</td>
</tr>
<tr>
<td colspan="1">
<pre>header</pre>
</td>
<td colspan="1">
<p>plain text or HTML</p>
</td>
<td colspan="1">Add content to an optional header area (has it's own div and class)<br />(Depending on what you need, you might also just add a heading in the content.)&nbsp;</td>
</tr>
<tr>
<td colspan="1">
<pre>footer</pre>
</td>
<td colspan="1">
<p>plain text or HTML</p>
</td>
<td colspan="1">
<p>Add content to an optional footer area (has it's own div and class)</p>
<p>&nbsp;Note: If you are using a form and you'd like the buttons in the prebaked you'll either need to set the form start and end outside the modal target macro, or place your whole form inside of the content and forgo the prebaked footer.</p>
</td>
</tr>
<tr>
<td colspan="1">
<pre>caption</pre>
</td>
<td colspan="1">
<p>plain text or HTML</p>
</td>
<td colspan="1">Create a caption that will be placed outside the modal.</td>
</tr>
</tbody>
</table>
</div>

<h3>More documentation to follow. :)</h3>
