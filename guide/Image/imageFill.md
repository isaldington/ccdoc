# $imageFill

Fill image with specific color name

## Usage

```bash
$imageFill[color;x;y;width;height;opacity]
```

### Colors:
Accept Color Hex or Common Color Names like gray, black

### Example 1:
<discord-messages>
          <discord-message :bot="false" role-color="#ffcc9a" author="Member">
        !!exec $imageCreate[300;300]<br>$imageFill[gray]<br>$image[$imageOutput]<br><br>
          </discord-message>
          <discord-message :bot="true" role-color="#0099ff" author="Custom Command" avatar="https://media.discordapp.net/avatars/725721249652670555/781224f90c3b841ba5b40678e032f74a.webp">
            <discord-embed slot="embeds" image="https://i.imgur.com/NwKtUYB.png">
            </discord-embed>
          </discord-message>
</discord-messages>

### Example 2:
<discord-messages>
          <discord-message :bot="false" role-color="#ffcc9a" author="Member">
        !!exec $imageCreate[300;300]<br>$imageFill[gray]<br>$imageFill[red;100;100;50;50]<br>$image[$imageOutput]<br><br>
          </discord-message>
          <discord-message :bot="true" role-color="#0099ff" author="Custom Command" avatar="https://media.discordapp.net/avatars/725721249652670555/781224f90c3b841ba5b40678e032f74a.webp">
            <discord-embed slot="embeds" image="https://i.imgur.com/QeSr9tZ.png">
            </discord-embed>
        </discord-message>
</discord-messages>