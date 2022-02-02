# $arrayJoin
Returns all splitted elements in the array with an optional separator

#### Usage: `$arrayJoin[Seperator (optional)]

Return nothing if no elements in the array`
<br/>
<discord-messages>
	<discord-message :bot="false" role-color="#ffcc9a" author="Member">
		!!exec $textsplit[WIKI] /* splits every character */ {{ '\n' }} $arrayjoin[-]
	</discord-message>
	<discord-message :bot="true" role-color="#0099ff" author="Custom Command" avatar="https://media.discordapp.net/avatars/725721249652670555/781224f90c3b841ba5b40678e032f74a.webp">
		W-I-K-I
	</discord-message>
</discord-messages>

##### Function Difficultly: <Badge type="tip" text="Easy" vertical="middle" /> 
###### Tags: <Badge type="tip" text="array" vertical="middle" /> <Badge type="tip" text="join" vertical="middle" /> <Badge type="tip" text="textsplit" vertical="middle" /> <Badge type="tip" text="get" vertical="middle" />