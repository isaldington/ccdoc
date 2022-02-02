# $arrayInclude
Checks if a value exists in the splitted array by `$textSplit`. If included, `true`, if no, `false`

#### Usage: `$arrayInclude[value]`
<br/>
<discord-messages>
	<discord-message :bot="false" role-color="#ffcc9a" author="Member">
		!!exec $textsplit[Mika Wiki Mido; ] {{ '\n' }} Is it Rake included? $arrayInclude[Rake]
	</discord-message>
	<discord-message :bot="true" role-color="#0099ff" author="Custom Command" avatar="https://media.discordapp.net/avatars/725721249652670555/781224f90c3b841ba5b40678e032f74a.webp">
		Is it Rake included? false
	</discord-message>
</discord-messages>

##### Function Difficultly: <Badge type="tip" text="Easy" vertical="middle" /> 
###### Tags: <Badge type="tip" text="array" vertical="middle" /> <Badge type="tip" text="include" vertical="middle" /> <Badge type="tip" text="textsplit" vertical="middle" /><Badge type="tip" text="check" vertical="middle" />