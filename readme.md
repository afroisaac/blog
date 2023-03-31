<div id="proj-spec-div" class="col-xs-offset-1 col-xs-10"> <h2 id="project-spec-headline" translate="" class="ng-scope">Project Specification</h2> <h1 id="project-name" ng-bind-html="localize(ctrl.rubric.project, 'name', markup=true)" class="ng-binding"><p>Personal Blog Website</p>
</h1> <div rubric-table="" rubric="ctrl.rubric" settings="ctrl.tableSettings" class="ng-isolate-scope"><!-- ngRepeat: section in rubric.sections --><div ng-repeat="section in rubric.sections" class="ng-scope"> <span class="rubric-section ng-binding" ng-bind-html="localize(section, 'name', markup=true)"><p>Structure</p>
</span> <table class="table table-bordered section-table"> <thead> <tr> <!-- ngIf: !rubric.hide_criteria --><th class="rubric-category criteria-column col-xs-3 ng-scope" ng-if="!rubric.hide_criteria"> <span translate="" class="ng-scope">Criteria</span> </th><!-- end ngIf: !rubric.hide_criteria --> <th class="rubric-category meets-specs-column" ng-class="settings.showReviewerTips ? col-xs-4 : (settings.showCompletedChecklist ? col-xs-6 : col-xs-7)"> <span translate="" class="ng-scope">Meets Specifications</span> </th> <!-- ngIf: settings.showReviewerTips --> <!-- ngIf: settings.showCompletedChecklist --> </tr> </thead> <tbody>  <!-- ngRepeat: rubricItem in section.rubric_items --><tr ng-repeat="rubricItem in section.rubric_items" class="ng-scope"> <!-- ngIf: !rubric.hide_criteria --><td class="rubric-item criteria col-xs-3 ng-binding ng-scope" ng-if="!rubric.hide_criteria" ng-bind-html="localize(rubricItem, 'criteria', markup=true)"><p>CSS Separate From HTML</p>
</td><!-- end ngIf: !rubric.hide_criteria --> <td class="rubric-item meets-spec ng-binding" ng-class="settings.showReviewerTips ? col-xs-4 : (settings.showCompletedChecklist ? col-xs-6 : col-xs-7)" ng-bind-html="localize(rubricItem, 'passed_description', markup=true)"><ol>
<li>Portfolio completely separates structure from design/style. </li>
<li>There are no attributes present in the body of the document. </li>
<li>There are no elements in the document.</li>
</ol>
</td> <!-- ngIf: settings.showReviewerTips --> <!-- ngIf: settings.showCompletedChecklist --> </tr><!-- end ngRepeat: rubricItem in section.rubric_items --><tr ng-repeat="rubricItem in section.rubric_items" class="ng-scope"> <!-- ngIf: !rubric.hide_criteria --><td class="rubric-item criteria col-xs-3 ng-binding ng-scope" ng-if="!rubric.hide_criteria" ng-bind-html="localize(rubricItem, 'criteria', markup=true)"><p>CSS Imports</p>
</td><!-- end ngIf: !rubric.hide_criteria --> <td class="rubric-item meets-spec ng-binding" ng-class="settings.showReviewerTips ? col-xs-4 : (settings.showCompletedChecklist ? col-xs-6 : col-xs-7)" ng-bind-html="localize(rubricItem, 'passed_description', markup=true)"><p>There should be at least 3 imported files in the main CSS file, but the student is welcome to break it down even further if that makes it easier for them.</p>
</td> <!-- ngIf: settings.showReviewerTips --> <!-- ngIf: settings.showCompletedChecklist --> </tr><!-- end ngRepeat: rubricItem in section.rubric_items --><tr ng-repeat="rubricItem in section.rubric_items" class="ng-scope"> <!-- ngIf: !rubric.hide_criteria --><td class="rubric-item criteria col-xs-3 ng-binding ng-scope" ng-if="!rubric.hide_criteria" ng-bind-html="localize(rubricItem, 'criteria', markup=true)"><p>Directories &amp; Files</p>
</td><!-- end ngIf: !rubric.hide_criteria --> <td class="rubric-item meets-spec ng-binding" ng-class="settings.showReviewerTips ? col-xs-4 : (settings.showCompletedChecklist ? col-xs-6 : col-xs-7)" ng-bind-html="localize(rubricItem, 'passed_description', markup=true)"><p>Files are organized with a directory structure that separates files based on page and functionality.</p>
</td> <!-- ngIf: settings.showReviewerTips --> <!-- ngIf: settings.showCompletedChecklist --> </tr><!-- end ngRepeat: rubricItem in section.rubric_items --><tr ng-repeat="rubricItem in section.rubric_items" class="ng-scope"> <!-- ngIf: !rubric.hide_criteria --><td class="rubric-item criteria col-xs-3 ng-binding ng-scope" ng-if="!rubric.hide_criteria" ng-bind-html="localize(rubricItem, 'criteria', markup=true)"><p>Links</p>
</td><!-- end ngIf: !rubric.hide_criteria --> <td class="rubric-item meets-spec ng-binding" ng-class="settings.showReviewerTips ? col-xs-4 : (settings.showCompletedChecklist ? col-xs-6 : col-xs-7)" ng-bind-html="localize(rubricItem, 'passed_description', markup=true)"><p>There is an intentional user flow on each page with appropriate links as needed.</p>
</td> <!-- ngIf: settings.showReviewerTips --> <!-- ngIf: settings.showCompletedChecklist --> </tr><!-- end ngRepeat: rubricItem in section.rubric_items --> </tbody> </table> </div><!-- end ngRepeat: section in rubric.sections --><div ng-repeat="section in rubric.sections" class="ng-scope"> <span class="rubric-section ng-binding" ng-bind-html="localize(section, 'name', markup=true)"><p>Design</p>
</span> <table class="table table-bordered section-table"> <thead> <tr> <!-- ngIf: !rubric.hide_criteria --><th class="rubric-category criteria-column col-xs-3 ng-scope" ng-if="!rubric.hide_criteria"> <span translate="" class="ng-scope">Criteria</span> </th><!-- end ngIf: !rubric.hide_criteria --> <th class="rubric-category meets-specs-column" ng-class="settings.showReviewerTips ? col-xs-4 : (settings.showCompletedChecklist ? col-xs-6 : col-xs-7)"> <span translate="" class="ng-scope">Meets Specifications</span> </th> <!-- ngIf: settings.showReviewerTips --> <!-- ngIf: settings.showCompletedChecklist --> </tr> </thead> <tbody>  <!-- ngRepeat: rubricItem in section.rubric_items --><tr ng-repeat="rubricItem in section.rubric_items" class="ng-scope"> <!-- ngIf: !rubric.hide_criteria --><td class="rubric-item criteria col-xs-3 ng-binding ng-scope" ng-if="!rubric.hide_criteria" ng-bind-html="localize(rubricItem, 'criteria', markup=true)"><p>Custom Design</p>
</td><!-- end ngIf: !rubric.hide_criteria --> <td class="rubric-item meets-spec ng-binding" ng-class="settings.showReviewerTips ? col-xs-4 : (settings.showCompletedChecklist ? col-xs-6 : col-xs-7)" ng-bind-html="localize(rubricItem, 'passed_description', markup=true)"><p>Custom images, layout, and styling.</p>
</td> <!-- ngIf: settings.showReviewerTips --> <!-- ngIf: settings.showCompletedChecklist --> </tr><!-- end ngRepeat: rubricItem in section.rubric_items --><tr ng-repeat="rubricItem in section.rubric_items" class="ng-scope"> <!-- ngIf: !rubric.hide_criteria --><td class="rubric-item criteria col-xs-3 ng-binding ng-scope" ng-if="!rubric.hide_criteria" ng-bind-html="localize(rubricItem, 'criteria', markup=true)"><p>Foundations/Building Blocks</p>
</td><!-- end ngIf: !rubric.hide_criteria --> <td class="rubric-item meets-spec ng-binding" ng-class="settings.showReviewerTips ? col-xs-4 : (settings.showCompletedChecklist ? col-xs-6 : col-xs-7)" ng-bind-html="localize(rubricItem, 'passed_description', markup=true)"><ul>
<li><strong>Typography</strong>: Custom design for typography with at least 3 unique properties for each typography selector<ol>
<li>Headers (h1 to h3 at minimum) <code>&lt;h1&gt;</code></li>
<li>Paragraph Text <code>&lt;p&gt;</code><br>a. Bold<br>b. Italic<br>c. Underlined</li>
<li>Links <code>&lt;a&gt;</code></li>
<li>Quotes</li>
</ol>
</li>
</ul>
<ul>
<li><strong>Colors</strong>: At least 3 colors are used.</li>
</ul>
</td> <!-- ngIf: settings.showReviewerTips --> <!-- ngIf: settings.showCompletedChecklist --> </tr><!-- end ngRepeat: rubricItem in section.rubric_items --><tr ng-repeat="rubricItem in section.rubric_items" class="ng-scope"> <!-- ngIf: !rubric.hide_criteria --><td class="rubric-item criteria col-xs-3 ng-binding ng-scope" ng-if="!rubric.hide_criteria" ng-bind-html="localize(rubricItem, 'criteria', markup=true)"><p>Components</p>
</td><!-- end ngIf: !rubric.hide_criteria --> <td class="rubric-item meets-spec ng-binding" ng-class="settings.showReviewerTips ? col-xs-4 : (settings.showCompletedChecklist ? col-xs-6 : col-xs-7)" ng-bind-html="localize(rubricItem, 'passed_description', markup=true)"><p>The following are used in the webpage:</p>
<ul>
<li>Image(s)</li>
<li>Image caption</li>
<li>Buttons</li>
<li>Card</li>
</ul>
</td> <!-- ngIf: settings.showReviewerTips --> <!-- ngIf: settings.showCompletedChecklist --> </tr><!-- end ngRepeat: rubricItem in section.rubric_items --><tr ng-repeat="rubricItem in section.rubric_items" class="ng-scope"> <!-- ngIf: !rubric.hide_criteria --><td class="rubric-item criteria col-xs-3 ng-binding ng-scope" ng-if="!rubric.hide_criteria" ng-bind-html="localize(rubricItem, 'criteria', markup=true)"><p>Patterns</p>
</td><!-- end ngIf: !rubric.hide_criteria --> <td class="rubric-item meets-spec ng-binding" ng-class="settings.showReviewerTips ? col-xs-4 : (settings.showCompletedChecklist ? col-xs-6 : col-xs-7)" ng-bind-html="localize(rubricItem, 'passed_description', markup=true)"><p>The general pattern of the webpage should be as follows:</p>
<ul>
<li><strong>Blog Homepage</strong><ul>
<li>Navbar</li>
<li>Blog Post Card<ul>
<li>Card</li>
<li>Image</li>
<li>Buttons</li>
</ul>
</li>
<li>Footer</li>
</ul>
</li>
<li><strong>Blog Post</strong><ul>
<li>Header</li>
<li>Author Info<ul>
<li>Name</li>
<li>Title</li>
<li>Current Company/School</li>
<li>Short Bio</li>
<li>Avatar</li>
</ul>
</li>
<li>Social Sharing<ul>
<li>Twitter</li>
<li>Facebook</li>
<li>LinkedIn</li>
</ul>
</li>
</ul>
</li>
</ul>
</td> <!-- ngIf: settings.showReviewerTips --> <!-- ngIf: settings.showCompletedChecklist --> </tr><!-- end ngRepeat: rubricItem in section.rubric_items --><tr ng-repeat="rubricItem in section.rubric_items" class="ng-scope"> <!-- ngIf: !rubric.hide_criteria --><td class="rubric-item criteria col-xs-3 ng-binding ng-scope" ng-if="!rubric.hide_criteria" ng-bind-html="localize(rubricItem, 'criteria', markup=true)"><p>Pages</p>
</td><!-- end ngIf: !rubric.hide_criteria --> <td class="rubric-item meets-spec ng-binding" ng-class="settings.showReviewerTips ? col-xs-4 : (settings.showCompletedChecklist ? col-xs-6 : col-xs-7)" ng-bind-html="localize(rubricItem, 'passed_description', markup=true)"><p>The following pages should be present:</p>
<ol>
<li>Blog Homepage</li>
<li>Blog Post</li>
</ol>
</td> <!-- ngIf: settings.showReviewerTips --> <!-- ngIf: settings.showCompletedChecklist --> </tr><!-- end ngRepeat: rubricItem in section.rubric_items --> </tbody> </table> </div><!-- end ngRepeat: section in rubric.sections --><div ng-repeat="section in rubric.sections" class="ng-scope"> <span class="rubric-section ng-binding" ng-bind-html="localize(section, 'name', markup=true)"><p>Layout</p>
</span> <table class="table table-bordered section-table"> <thead> <tr> <!-- ngIf: !rubric.hide_criteria --><th class="rubric-category criteria-column col-xs-3 ng-scope" ng-if="!rubric.hide_criteria"> <span translate="" class="ng-scope">Criteria</span> </th><!-- end ngIf: !rubric.hide_criteria --> <th class="rubric-category meets-specs-column" ng-class="settings.showReviewerTips ? col-xs-4 : (settings.showCompletedChecklist ? col-xs-6 : col-xs-7)"> <span translate="" class="ng-scope">Meets Specifications</span> </th> <!-- ngIf: settings.showReviewerTips --> <!-- ngIf: settings.showCompletedChecklist --> </tr> </thead> <tbody>  <!-- ngRepeat: rubricItem in section.rubric_items --><tr ng-repeat="rubricItem in section.rubric_items" class="ng-scope"> <!-- ngIf: !rubric.hide_criteria --><td class="rubric-item criteria col-xs-3 ng-binding ng-scope" ng-if="!rubric.hide_criteria" ng-bind-html="localize(rubricItem, 'criteria', markup=true)"><p>Flexbox Based Layout</p>
</td><!-- end ngIf: !rubric.hide_criteria --> <td class="rubric-item meets-spec ng-binding" ng-class="settings.showReviewerTips ? col-xs-4 : (settings.showCompletedChecklist ? col-xs-6 : col-xs-7)" ng-bind-html="localize(rubricItem, 'passed_description', markup=true)"><p>Uses Flexbox at least twice throughout the project to create a component or pattern</p>
</td> <!-- ngIf: settings.showReviewerTips --> <!-- ngIf: settings.showCompletedChecklist --> </tr><!-- end ngRepeat: rubricItem in section.rubric_items --><tr ng-repeat="rubricItem in section.rubric_items" class="ng-scope"> <!-- ngIf: !rubric.hide_criteria --><td class="rubric-item criteria col-xs-3 ng-binding ng-scope" ng-if="!rubric.hide_criteria" ng-bind-html="localize(rubricItem, 'criteria', markup=true)"><p>Grid Based Layout</p>
</td><!-- end ngIf: !rubric.hide_criteria --> <td class="rubric-item meets-spec ng-binding" ng-class="settings.showReviewerTips ? col-xs-4 : (settings.showCompletedChecklist ? col-xs-6 : col-xs-7)" ng-bind-html="localize(rubricItem, 'passed_description', markup=true)"><p>Uses CSS Grid at least twice throughout the project to create the layout for pages</p>
</td> <!-- ngIf: settings.showReviewerTips --> <!-- ngIf: settings.showCompletedChecklist --> </tr><!-- end ngRepeat: rubricItem in section.rubric_items --> </tbody> </table> </div><!-- end ngRepeat: section in rubric.sections --><div ng-repeat="section in rubric.sections" class="ng-scope"> <span class="rubric-section ng-binding" ng-bind-html="localize(section, 'name', markup=true)"><p>Responsiveness</p>
</span> <table class="table table-bordered section-table"> <thead> <tr> <!-- ngIf: !rubric.hide_criteria --><th class="rubric-category criteria-column col-xs-3 ng-scope" ng-if="!rubric.hide_criteria"> <span translate="" class="ng-scope">Criteria</span> </th><!-- end ngIf: !rubric.hide_criteria --> <th class="rubric-category meets-specs-column" ng-class="settings.showReviewerTips ? col-xs-4 : (settings.showCompletedChecklist ? col-xs-6 : col-xs-7)"> <span translate="" class="ng-scope">Meets Specifications</span> </th> <!-- ngIf: settings.showReviewerTips --> <!-- ngIf: settings.showCompletedChecklist --> </tr> </thead> <tbody>  <!-- ngRepeat: rubricItem in section.rubric_items --><tr ng-repeat="rubricItem in section.rubric_items" class="ng-scope"> <!-- ngIf: !rubric.hide_criteria --><td class="rubric-item criteria col-xs-3 ng-binding ng-scope" ng-if="!rubric.hide_criteria" ng-bind-html="localize(rubricItem, 'criteria', markup=true)"><p>Multi-Device Web Design</p>
</td><!-- end ngIf: !rubric.hide_criteria --> <td class="rubric-item meets-spec ng-binding" ng-class="settings.showReviewerTips ? col-xs-4 : (settings.showCompletedChecklist ? col-xs-6 : col-xs-7)" ng-bind-html="localize(rubricItem, 'passed_description', markup=true)"><p>Pages are mobile-friendly and display correctly on all display sizes (mobile, tablet, desktop).</p>
<p>Note: You can <a href="https://developers.google.com/web/tools/chrome-devtools/device-mode/" target="_blank">simulate Mobile Devices with Device Mode in Chrome DevTools</a>.</p>
</td> <!-- ngIf: settings.showReviewerTips --> <!-- ngIf: settings.showCompletedChecklist --> </tr><!-- end ngRepeat: rubricItem in section.rubric_items --> </tbody> </table> </div><!-- end ngRepeat: section in rubric.sections --><div ng-repeat="section in rubric.sections" class="ng-scope"> <span class="rubric-section ng-binding" ng-bind-html="localize(section, 'name', markup=true)"><p>Quality</p>
</span> <table class="table table-bordered section-table"> <thead> <tr> <!-- ngIf: !rubric.hide_criteria --><th class="rubric-category criteria-column col-xs-3 ng-scope" ng-if="!rubric.hide_criteria"> <span translate="" class="ng-scope">Criteria</span> </th><!-- end ngIf: !rubric.hide_criteria --> <th class="rubric-category meets-specs-column" ng-class="settings.showReviewerTips ? col-xs-4 : (settings.showCompletedChecklist ? col-xs-6 : col-xs-7)"> <span translate="" class="ng-scope">Meets Specifications</span> </th> <!-- ngIf: settings.showReviewerTips --> <!-- ngIf: settings.showCompletedChecklist --> </tr> </thead> <tbody>  <!-- ngRepeat: rubricItem in section.rubric_items --><tr ng-repeat="rubricItem in section.rubric_items" class="ng-scope"> <!-- ngIf: !rubric.hide_criteria --><td class="rubric-item criteria col-xs-3 ng-binding ng-scope" ng-if="!rubric.hide_criteria" ng-bind-html="localize(rubricItem, 'criteria', markup=true)"><p>Valid HTML</p>
</td><!-- end ngIf: !rubric.hide_criteria --> <td class="rubric-item meets-spec ng-binding" ng-class="settings.showReviewerTips ? col-xs-4 : (settings.showCompletedChecklist ? col-xs-6 : col-xs-7)" ng-bind-html="localize(rubricItem, 'passed_description', markup=true)"><ul>
<li>HTML5 semantic tags such as <code>&lt;header&gt;</code>, <code>&lt;footer&gt;</code>, <code>&lt;article&gt;</code>, <code>&lt;section&gt;</code> , etc. are used to add meaning to the code.</li>
<li>No div or section selectors are without a CSS class or id.</li>
</ul>
</td> <!-- ngIf: settings.showReviewerTips --> <!-- ngIf: settings.showCompletedChecklist --> </tr><!-- end ngRepeat: rubricItem in section.rubric_items --><tr ng-repeat="rubricItem in section.rubric_items" class="ng-scope"> <!-- ngIf: !rubric.hide_criteria --><td class="rubric-item criteria col-xs-3 ng-binding ng-scope" ng-if="!rubric.hide_criteria" ng-bind-html="localize(rubricItem, 'criteria', markup=true)"><p>HTML Formatting Rules</p>
</td><!-- end ngIf: !rubric.hide_criteria --> <td class="rubric-item meets-spec ng-binding" ng-class="settings.showReviewerTips ? col-xs-4 : (settings.showCompletedChecklist ? col-xs-6 : col-xs-7)" ng-bind-html="localize(rubricItem, 'passed_description', markup=true)"><ul>
<li>All code is lowercase</li>
<li>The code does not have trailing white spaces.</li>
<li>Indentation is consistent (either all tabs or all 2 spaces or all 4 spaces etc).</li>
<li>Code uses a new line for every block, list or table element and indent every such child element (it is acceptable to put all elements in one line).</li>
<li>When quoting attribute values, code uses consistent quotation marks (single vs. double).</li>
</ul>
</td> <!-- ngIf: settings.showReviewerTips --> <!-- ngIf: settings.showCompletedChecklist --> </tr><!-- end ngRepeat: rubricItem in section.rubric_items --><tr ng-repeat="rubricItem in section.rubric_items" class="ng-scope"> <!-- ngIf: !rubric.hide_criteria --><td class="rubric-item criteria col-xs-3 ng-binding ng-scope" ng-if="!rubric.hide_criteria" ng-bind-html="localize(rubricItem, 'criteria', markup=true)"><p>HTML Style Rules</p>
</td><!-- end ngIf: !rubric.hide_criteria --> <td class="rubric-item meets-spec ng-binding" ng-class="settings.showReviewerTips ? col-xs-4 : (settings.showCompletedChecklist ? col-xs-6 : col-xs-7)" ng-bind-html="localize(rubricItem, 'passed_description', markup=true)"><ul>
<li>HTML documents HTML5 <code>&lt;!doctype html&gt;</code></li>
<li>Code omits type attributes for style sheets and scripts.</li>
<li>[Optional] Code does not use entity references unless necessary e.g. characters with special meaning (like <code>&lt;</code> and <code>&amp;</code>) as well as control or “invisible” characters (like no-break spaces).</li>
</ul>
</td> <!-- ngIf: settings.showReviewerTips --> <!-- ngIf: settings.showCompletedChecklist --> </tr><!-- end ngRepeat: rubricItem in section.rubric_items --><tr ng-repeat="rubricItem in section.rubric_items" class="ng-scope"> <!-- ngIf: !rubric.hide_criteria --><td class="rubric-item criteria col-xs-3 ng-binding ng-scope" ng-if="!rubric.hide_criteria" ng-bind-html="localize(rubricItem, 'criteria', markup=true)"><p>CSS Formatting Rules</p>
</td><!-- end ngIf: !rubric.hide_criteria --> <td class="rubric-item meets-spec ng-binding" ng-class="settings.showReviewerTips ? col-xs-4 : (settings.showCompletedChecklist ? col-xs-6 : col-xs-7)" ng-bind-html="localize(rubricItem, 'passed_description', markup=true)"><ul>
<li>The code does not have trailing white spaces.</li>
<li>Indentation is consistent (either all tabs or all 2 spaces or all 4 spaces etc).</li>
<li>Code indents all content, that is rules within rules as well as declarations to reflect hierarchy and improve understanding.</li>
<li>The code uses a semicolon after every declaration for consistency and extensibility reasons.</li>
<li>Code always uses a space after a property name's colon, but no space between property and colon, for consistency reasons.</li>
<li>Code always uses a single space between the last selector and the opening brace that begins the declaration block. Code always start a new line for each selector and declaration.</li>
<li>Code always put a blank line (two line breaks) between rules.</li>
<li>Code uses consistent quotation marks for attribute selectors or property values (single vs. double).</li>
</ul>
</td> <!-- ngIf: settings.showReviewerTips --> <!-- ngIf: settings.showCompletedChecklist --> </tr><!-- end ngRepeat: rubricItem in section.rubric_items --><tr ng-repeat="rubricItem in section.rubric_items" class="ng-scope"> <!-- ngIf: !rubric.hide_criteria --><td class="rubric-item criteria col-xs-3 ng-binding ng-scope" ng-if="!rubric.hide_criteria" ng-bind-html="localize(rubricItem, 'criteria', markup=true)"><p>CSS Style Rules</p>
</td><!-- end ngIf: !rubric.hide_criteria --> <td class="rubric-item meets-spec ng-binding" ng-class="settings.showReviewerTips ? col-xs-4 : (settings.showCompletedChecklist ? col-xs-6 : col-xs-7)" ng-bind-html="localize(rubricItem, 'passed_description', markup=true)"><ul>
<li>The code uses meaningful or generic ID and class names that are as short as possible, but as long as necessary.</li>
<li>The code does not use element names in conjunction with IDs or classes.</li>
<li>The code uses shorthand properties where possible.</li>
<li>[Optional] Code omits unit specification after 0 values. </li>
<li>[Optional] Code includes leading 0s in decimal values for readability.</li>
<li>[Optional] Code uses 3-character hexadecimal notation where possible.</li>
<li>[Optional] Code separates words in ID and class names by a hyphen.</li>
</ul>
</td> <!-- ngIf: settings.showReviewerTips --> <!-- ngIf: settings.showCompletedChecklist --> </tr><!-- end ngRepeat: rubricItem in section.rubric_items --> </tbody> </table> </div><!-- end ngRepeat: section in rubric.sections --> </div> <!-- ngIf: ctrl.rubric.stand_out --><div id="stand-out" ng-if="ctrl.rubric.stand_out" class="col-xs-offset-1 col-xs-10 ng-scope"> <h2 id="stand-out-headline" class="text-center ng-scope" translate="">Suggestions to Make Your Project Stand Out!</h2> <div id="stand-out-text" ng-bind-html="localize(ctrl.rubric, 'stand_out', markup=true)" class="ng-binding"><ul>
<li><strong>Custom Text:</strong> You are welcome to use Lorem ipsum or other placeholder text in your blog and blog posts, but putting in real, custom text can make your project look even more impressive!</li>
<li><strong>Pattern - Related Articles:</strong> Add 2 to 3 fake blog post references after the blog post ends (i.e. to older blog posts)</li>
<li><strong>Pattern - Subscribe Form:</strong> Instead of a fake subscribe link on the blog, there is an actual form area with name and email input fields and a subscribe button.</li>
<li><strong>Project URL:</strong> Project is fully deployed on GitHub Pages, Netlify or another hosting provider that is free of charge.</li>
<li><strong>Design System:</strong> Consider implementing a <a href="https://www.forumone.com/ideas/what-is-design-system/" target="_blank">design system</a> for your webpage.</li>
<li><strong>Accessibility:</strong> <ul>
<li>Discernable text</li>
<li>Sufficient color contrast</li>
<li>ARIA attributes</li>
<li>Less than 5 violations found through the <a href="https://www.deque.com/axe/" target="_blank">Axe</a> (Chrome extension) test on the web page.</li>
</ul>
</li>
</ul>
</div> </div><!-- end ngIf: ctrl.rubric.stand_out --> </div>