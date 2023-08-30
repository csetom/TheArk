---
tags: template
---
\define thisTitle() [[$(currentTiddler)$]] 

{{||H1}}
{{||SDESC}}
### Content

<$button>
<$action-sendmessage $message="tm-new-tiddler"  tags=<<thisTitle>> sdesc=""/>
Új {{!!title}}
</$button>
<ul><$list filter="[all[current]tagging[]]">
<li><$link><<currentTiddler>></$link> - {{!!sdesc}}</li>
</$list>
</ul>


