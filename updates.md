---
layout: page
title: Updates
sidebar_link: true
id: updates
notoc: true
---

Here is the versioned list of all the new features and changes. [tagtog Cloud](https://www.tagtog.net) runs always on the latest version. If you are running **tagtog On-Premises**, make sure to [update to the latest version](on_premises_README.html) to make the most of your experience.

Have feedback? :heart: Report bugs and/or suggest improvements on our [:point_right:GitHub issues page:point_left:](https://github.com/tagtog/tagtog-doc/issues).

Moreover, follow the latest updates on our [Twitter: @tagtog_net 🐦](https://twitter.com/tagtog_net) !

---

## 3.2019-W01.2 🎇
<ul class="updates">
  <li class="new"><span markdown="1">Configuration fix</span></li>
</ul>

---

## 3.2019-W01.0 🎆

<ul class="updates">
  <li class="new"><span markdown="1">Removed an internal process. This saves ~1GB of memory on-premises :-)</span></li>
  <li class="new"><span markdown="1">Slightly faster API thanks to less internal DB connections</span></li>
  <li class="fix"><span markdown="1">Avoid double redirection upon login (first to "/", then to the user's page). This allows for custom-based authentications via reverse proxies (On-Premises)</span></li>
  <li class="new"><span markdown="1">Created API for project settings. As a first step, you can export your settings using the endpoint: `/-api/settings/v1/export?owner=???&project=???`</span></li>
  <li class="doc"><span markdown="1">Renamed On-Premises admin page for: [SysAdmin On-Premises](on-premises-sysadmin.html)</span></li>
  <li class="new"><span markdown="1">Empowered On-Premises system admins to [allow or disallow visitors to create accounts](on-premises-sysadmin.html#do-not-allow-visitors-to-create-accounts)</span></li>
  <li class="new"><span markdown="1">New security-concerning action for On-Premises sysadmins to [revoke all existing auth tokens](on-premises-sysadmin.html#user-management)</span></li>
  <li class="doc"><span markdown="1">On-Premises: abort the start if the `vm.max_map_count` value is too low. [See the requirements](on_premises_README.html#requirements).</span></li>
  <li class="fix"><span markdown="1">Fixed bug On-Premises SysAdmin page wherein some users could not be deleted</span></li>
</ul>

---

## 3.2018-W52.0 👑
_2018-12-26_

<ul class="updates">
  <li class="new"><span markdown="1">Clean front-page for **On-premises** version. Information regarding Plans has been removed.</span></li>
  <li class="new"><span markdown="1">Increased the capacity of our Cloud servers even more</span></li>
</ul>

---

## 3.2018-W51.3 🎄
_2018-12-22_

<ul class="updates">
  <li class="new"><span markdown="1">**CSV** (and **TSV**) file parsing!!! 📊 [Check out the documentation](CsvFileParsing)</span></li>
  <li class="new"><span markdown="1">Entity types are now sorted alphabetically in the <a title="tagtog - Annotation menu" href="webeditor.html#annotation-menu">annotation menu</a>. If you have a big list of entities this menu is now scrollable! :barber:</span></li>
  <li class="fix"><span markdown="1">Issue fixed On-Premises that could cause on some environments to wrongly report document upload errors</span></li>  
  <li class="doc"><span markdown="1">Add examples to upload pre-annotated documents using the API. [Documentation](API.html#import-annotated-documents-post "tagtog - Upload pre-annotated files")</span></li>
  <li class="new"><span markdown="1">Increased the capacity of our Cloud servers to provide you with a faster and more robust service 🥰</span></li>
  <li class="fix"><span markdown="1">Fixed small error in the ML component that could cause training exceptions on empty sentences in the data</span></li>
  <li class="fix"><span markdown="1">Fixed a bug in the [EntitiesTsv format](EntitiesTsv "Entities TSV format"), in which documents without entity annotations did not output any text</span></li>
  <li class="new"><span markdown="1">New output format: [EntitiesOnlyClassesTsv format](EntitiesOnlyClassesTsv "EntitiesOnlyClassesTsv format") 🎅</span></li>

</ul>

---

## 3.2018-W49.3 🙆‍♂️
_2018-12-11_

<ul class="updates">
  <li class="fix"><span markdown="1">Fix small bug that affected showing relationships of connected entities being in different parts</span></li>
</ul>

---

## 3.2018-W49.2 ✌️
_2018-12-07_

<ul class="updates">
  <li class="new"><span markdown="1">Improve DB connectivity</span></li>
</ul>

---

## 3.2018-W49.1 🗣
_2018-12-05_

<ul class="updates">
  <li class="new"><span markdown="1">Pre-annotate your documents with doc labels (classification) upon file upload! (Hint: check the "Advanced" menu on the [+ Content] submit form button)</span>. <a title="tagtog - Upload files with predefined document labels" href="documentpool.html#upload-files-with-predefined-document-labels">Documentation</a></li>
  <li class="new"><span markdown="1">Upload pre-annotated documents directly from the GUI by uploading the text file and the annotations file together</span>. <a title="tagtog - Upload pre-annotated files" href="documentpool.html#upload-pre-annotated-documents">Documentation</a></li>
</ul>

---

## 3.2018-W49.0 🍃
_2018-12-03_

<ul class="updates">
  <li class="new"><span markdown="1">Milestone 1 - Major overhaul in architecture, for scalability => tagtog becomes even faster!</span></li>
</ul>

---

## 3.2018-W48.0 👊
_2018-11-26_

<ul class="updates">
  <li class="new"><span markdown="1">Speed enhancements</span></li>
</ul>

---


## 3.2018-W46.5 🕵️‍♀️
_2018-11-19_

<ul class="updates">
  <li class="doc"><span markdown="1">Improve [tagtog.net](http://tagtog.net "The Text Annotation Tool")'s discoverability in search engines</span></li>
</ul>

---

## 3.2018-W46.4-PAYMENT_GATEWAY ⛩
_2018-11-15_

<ul class="updates">
  <li class="new"><span markdown="1">[Native PDF 📃 ! Annotate actual PDFs; then use them to train your ML models as easily as if they were plain texts! 😲](http://tagtog.net#pdf-annotation)</span></li>
  <li class="new"><span markdown="1">[Use the new automated payment gateway to manage your subscriptions!](http://tagtog.net/-pricing)</span></li>
  <li class="fix"><span markdown="1">Stability improvements</span></li>
  <li class="doc"><span markdown="1">Add documentation: [upload annotated documents via API](API.html#import-annotated-documents-post "tagtog - upload annotated documents")</span></li>
  <li class="doc"><span markdown="1">Add documentation: [search by document label](search-queries.html#search-by-document-label "tagtog - search by document label")</span></li>
  <li class="doc">Extend admin section in project settings: <a title="tagtog - admin section" href="/projects.html#admin">admin section</a></li>
  <li class="doc"><a title="tagtog - PDF annotation tool" href="pdf-annotation-tool.html">PDF annotation tool</a></li>
  <li class="doc"><a title="tagtog - Admin page for on-premises instances" href="on-premises-sysadmin.html">Admin page for on-premises instances</a></li>
</ul>

---

## 3.2018-W41.0 👣
_2018-10-12_

<ul class="updates">
  <li class="new"><span markdown="1">Minor improvements</span></li>
</ul>

---

## 3.2018-W40.10 💹
_2018-10-06_

<ul class="updates">
  <li class="fix"><span markdown="1">More fixes on the NativePDF viewer</span></li>
  <li class="fix"><span markdown="1">Small fixes OnPremises</span></li>
</ul>

---

## 3.2018-W40.9 💋
_2018-10-05_

<ul class="updates">
  <li class="new"><span markdown="1">Increment max. number of entities OnPremises ML, from 50 to 500</span></li>
  <li class="fix"><span markdown="1">Strengthen the stability of the system OnPremises upon possible parsing errors</span></li>
</ul>

---

## 3.2018-W40.5 🔥
_2018-10-05_

<ul class="updates">
  <li class="fix"><span markdown="1">Re-Fixed **NativePDF** view; documents did not open on the Cloud</span></li>
</ul>

---

## 3.2018-W40.3 👩‍
_2018-10-05_

<ul class="updates">
  <li class="fix"><span markdown="1">Several fixes and improvements</span></li>
</ul>

---

## 3.2018-W40.2 👩‍🚒
_2018-10-03_

<ul class="updates">
  <li class="fix"><span markdown="1">Fixed **NativePDF** view; documents did not open</span></li>
  <li class="fix"><span markdown="1">Fixed wrong uploads when given filenames included white spaces</span></li>
  <li class="fix"><span markdown="1">Long text lines without spaces are word breaking to fit the annotation editor.</span></li>
</ul>

---

## 3.2018-W40.1 📎
_2018-10-02_

<ul class="updates">
  <li class="new"><span markdown="1">Increased maximum number of entities for Cloud-Large plans, from 25 to 50</span></li>
  <li class="fix"><span markdown="1">The same annotators (project members) can now be added to different projects, as was expected</span></li>
</ul>

---

## 3.2018-W40.0 📎
_2018-10-02_

<ul class="updates">
  <li class="new"><span markdown="1">Support for source code files! Whether you are a `python`, `java`, `js`, or [any other programming language freak](/ioformats.html#files), now you are able to annotate preformatted text :-)</span></li>
  <li class="new"><span markdown="1">Copy and share **[permalinks](/webeditor.html#permalinks "tagtog docs - Permalinks")**</span></li>
  <li class="doc">Update documentation about document folders: <a title="tagtog - folders" href="/documentpool.html#folders">Folders</a></li>
  <li class="fix">The popup dialog to import documents is being closed when clicked outside</li>
</ul>

---

## 3.2018-W38.4 🤩
_2018-09-21_

<ul class="updates">
  <li class="new">Allowed <i>supercurators</i> (member role) to confirm the master annotations</li>
  <li class="new">Allowed uploading multiple documents without text. The tagtogIDs are randomized</li>
  <li class="new">Increased on-premises the maximum document upload size, from 50MB to 250MB</li>
  <li class="fix">Improved the error reporting and resilience on document uploading</li>
</ul>

---

## 3.2018-W38.2 🦍
_2018-09-20_

<ul class="updates">
  <li class="new">Supported PDFs that contain only images (no text)</li>
  <li class="fix">Fixed not being able to open documents following a search</li>
</ul>

---

## 3.2018-W38.1 🐵
_2018-09-18_

<ul class="updates">
  <li class="fix">Bug fixes</li>
</ul>

---

## 3.2018-W38.0 🍃
_2018-09-17_

<ul class="updates">
  <li class="new">Importing of project settings now works for project folders too 👌</li>
  <li class="new">Some improvements here and there</li>
</ul>

---

## 3.2018-W37.2 📂
_2018-09-14_

<ul class="updates">
  <li class="new">Removal of projects folders too :)</li>
  <li class="fix">Several fixes wrt. to project folders</li>
  <li class="new">Now you can use any unicode letter character in annotation names ❤️, <i>Sí señor! 谢谢！natürlich! बहुत बढ़िया! 素晴らしい！</i></li>
</ul>

---

## 3.2018-W37.0 🗂
_2018-09-13_

<ul class="updates">
  <li class="new">Definition of project folders!</li>
  <li class="new">New layout, which fits the screen better</li>
</ul>

---

## 3.2018-W36.6 🔥
_2018-09-07_

<ul class="updates">
  <li class="new">Exporting & Importing of project settings. Now you can curate your entity types, document labels, etc. in one project, export that information into a JSON settings file, and then use this file on a new project to start with the same annotation types. No more manual labor! :)</li>
  <li class="del">The project deletion action has been moved to the corresponding project's settings (instead of on the projects list)</li>
  <li class="fix">Fixed bug that allowed annotations across paragraphs, but didn't indicate them visually, thus creating confusion to users.</li>
</ul>

---

## 3.2018-W34.4 🤔
_2018-08-23_

<ul class="updates">
  <li class="fix">Fixed bug that could impede the communication between docker containers on-premises when using an http proxy</li>
</ul>

---

## 3.2018-W34.2 🐳
_2018-08-22_

<ul class="updates">
  <li class="fix">Fixed bug that could impede the communication between docker containers on-premises</li>
</ul>

---

## 3.2018-W34.0 ✈️
_2018-08-21_

<ul class="updates">
  <li class="fix">Fixed bug that could break document parsing on some on-premises installations</li>
</ul>

---

## 3.2018-W31.4 ☀️
_2018-08-12_

<ul class="updates">
  <li class="fix">Fixed small bug that impeded opening documents if there was a documents navigation error</li>
</ul>

---

## 3.2018-W31.3 🎂
_2018-08-09_

<ul class="updates">
  <li class="fix">Fixed bug that created issues with annotations when the character <code><</code> was in the imported text. Thank you for spotting this ❤️!</li>
  <li class="fix">Fixed bug that made not possible to open documents on IE.</li>
</ul>

---

## 3.2018-W31.2 🏝
_2018-08-07_

<ul class="updates">
  <li class="fix">Fixed bug that could cause to delete dictionary normalizations</li>
  <li class="new">Much simplified color selection while defining new entities! New entities now get a semi-randomized distinct color 🌈</li>
  <li class="doc">Improved error reporting on internal server errors</li>
  <li class="new del"><span class="new">The <a title="tagtog - webhooks" href="/projects.html#webhooks">webhook</a> output <code>tagtogID</code>'s payload was changed from a simple string (<code>text/plain</code>) containing a <i>tagtogID</i>, to a simple JSON object(<code>application/json</code>) containing the distinctive three:</span></li>
  <div markdown="1">
  ```json
  {
    "owner": "...",
    "project": "...",
    "tagtogID": "..."
  }
  ```
  </div>
</ul>

---

## 3.2018-W31.1 ⛱
_2018-08-05_

<ul class="updates">
  <li class="new">Deletable Settings: entities, dictionaries, and relationships! Thank you all for your feedback on this one ❤️</li>
  <li class="new">Admin panel On-Premises to manage the system's users</li>
  <li class="new">New output format! <a href="/EntitiesTsv">EntitiesTsv</a>, closely resembling Stanford NER tsv format🎉</li>
  <li class="fix">Fixed parsing of PubMed documents (that moved to a new data scheme format as of 2018-06-01)</li>
</ul>

---

## 3.2018-W30.1 📑🤖
_2018-07-26_

<ul class="updates">
  <li class="new">On-Premises ML version is officially out!</li>
  <li class="new">Now you can choose whether <a title="tagtog - pre-annotations" href="/webeditor.html#pre-annotations">pre-annotations</a> (i.e. the automatic annotations that are created while manually annotating) are <strong>case sensitive or not</strong></li>
  <li class="doc">Improved reporting of parsing errors in API uploads</li>
  <li class="new"><a href="/machine-learning.html">Machine Learning</a> is now deactivated by default for new projects -- <a title="Settings - Machine Learning" href="/projects.html#machine-learning">You can activate it in Settings</a></li>
  <li class="fix">Correct URLs for Project Settings sections</li>
  <li class="doc">Limited the amount of entity types, depending on the plan: cloud start (3), cloud medium (10), cloud large (25), on-premises annotator (25), on-premises annotator+ML (50)</li>
  <li class="doc">Add documentation links to Settings</li>
  <li class="doc">Extend documentation about <a title="tagtog - Webhooks" href="/projects.html#webhooks">Webhooks</a></li>
  <li class="doc">Add <a href="/ioformats.html#annotation-input-formats" title="tagtog - input output formats - input annotations">input format</a> to better understand how to import annotated documents</li>
</ul>

---

## 3.2018-W29.0 🇫🇷
_2018-07-18_

<ul class="updates">
  <li class="new">The maximum upload size on the cloud, was augmented from 2MB up to 5MB 📈</li>
  <li class="fix">Some improvements in the management of on-premises licenses</li>
  <li class="doc">Simplified pricing information</li>
</ul>

---

## 3.2018-W28.3 🇧🇪
_2018-07-13_

<ul class="updates">
  <li class="new"><a title="Annotation types" href="/webeditor.html#annotation-types">Relations</a> are now supported between entities from different paragraphs or sections 🔛!</li>
  <li class="fix">The uploading of documents has been fixed so that special characters such as "#" are accepted in the filenames</li>
  <li class="fix">Fixed memory leak that happened when annotating with dictionaries with some specially-charactered files, often PDFs</li>
  <li class="fix">Fixed bug that caused not using re-confirmed documents for ML training</li>
  <li class="new">Support for on-premises license updates</li>
</ul>

---

## 3.2018-W28.2 🕵️‍♀️
_2018-07-10_

<ul class="updates">
  <li class="fix">Fixed the problem that users could not edit <a title="Annotation types" href="/webeditor.html#annotation-types">Entity Labels</a></li>
  <li class="new">The modal menu to set <a title="Annotation types" href="/webeditor.html#annotation-types">Entity Labels</a> is now scrollable and supports a long list of labels</li>
</ul>

---

## 3.2018-W28.0 🥅

<ul class="updates">
  <li class="new">Support for <b>proxies on-premises</b> 🕵️‍♀️</li>
  <li class="fix">Fixed an interface bug affecting <b>Internet Explorer</b>, that blocked importing new documents</li>
</ul>

---

## 3.2018-W26.0 ⚽️

### Webhooks

<ul class="updates">
  <li class="new">You can now choose the new <code>tagtogID</code> (pseudo-)format in your <b>webhooks</b> to POST the updated document's id</li>
  <li class="new">You can now delete webhooks 😉</li>
  <li class="fix"><b>Webhooks</b> are now also triggered on new document uploads that have <i>no annotations</i></li>
  <li class="del">The formats <code>docJSON</code> and <code>PubAnnotation</code> were removed from the possible <b>webhooks</b>' payload. We might review this decision.</li>
</ul>

### More!

<ul class="updates">
  <li class="new">API call to get a JSON map of the annotations legend, <i>anntasks ids → names</i>. For a sample call, check your project's <kbd>Downloads</kbd> page.</li>
  <li class="fix">Fixed a bug that prevented the training of ML models for entities that had associated dictionaries (specifically created through the interface).</li>
  <li class="doc">This new page of release notes was created 🤩</li>
</ul>
