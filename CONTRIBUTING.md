<h1>XCom Files contribution guidelines and rules</h1>
<p>Every change proposed will be evaluated beforehand by the development team, if it is deemed sufficient, it will imediately be merged, if not, either changes will be requested and discussed and the merge will be put on hold or the changes will be dismissed fully and the pull request will be closed. After the changes are implemented it will be evaluated once again and the cycle will repeat up until it is either accepted or rejected entirely.</p>
<p>The current development team is composed of:</p>
<ul>
<li>Solarius Scorch (chief developer).</li>
</ul>
<p>For better maintenance, expandability and fixing all entries shall be modularized (be isolated into modules that fulfill all the roles it is expected to, nothing more, nothing less). Why? Because it allows for the developers not only to have more ease when doing changes to each module, since they don't need to go through unrelated entries to find where they need to work, but also because it becomes easier to pinpoint where mistakes were made, since the mistake can be filtered to either a single file/folder or a collection of files/folders.</p>
<p>The procedures are as follows:</p>
<ul>
<li>Every file/folder contained within a folder must be a part of what the parent folder stands for (i.e.: any content related to cults must be contained only within the cults folder).</li>
<li>If an asset is to be used in something that relates to another folder, then that asset must be moved up in the hierarchy and all entries that were dependant on the asset checked for eventual changes that may be necessary (i.e.: a tileset that was used by cults only, now is going to also be used in a MIB mission).</li>
<li>All archs/factions must contain a folder under the root folder (the one that contains the metadata file). Currently all the folders that stand for such are: Cults; Shogg; Dreamscape; Cyberweb; Aliens; MIB; Osiron; Syndicate; Children from Aether; M.A.G.M.A; Apocalypse; Undead; Strange Creatures; Hybrids; <i>missing entries</i></li>
<li>Topic and topics stand for ruleset topics (i.e.: research, manufacturing, ufopedia, etc.).</li>
<li>Only one entry is allowed for any topic in all files from all folders (i.e.: there can't be more than one STR_SHAMBLER entry under the research topic).</li>
<li>All topic files must be named after the topic they stand for (i.e.: a manufacturing topic file must be named manufacturing.rul).</li>
<li>At most there can be one topic per file.</li>
<li>At most there can be one file for each topic in a folder.</li>
<li>All folders that have topics files in it must have a Languages folder containing the association between an entry and their text form.</li>
<li>All Languages folders must at least have a language file from an English dialect (i.e.: American English, British English, Canadian English, South African English, etc.).</li>
</ul>