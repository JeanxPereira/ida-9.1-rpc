# ida-rpc for IDA 9.0

<!-- <p align="center"><img src ="https://i.imgur.com/tBrw7Sp.png" /></p> -->

<div style="
display:flex;
flex-direction:column;
position:relative;
border-radius:8px; 
overflow:hidden; 
width:300px;
height:300px;
background-color:#28282d;
box-shadow: 0 0 20px 2px opacity(#000000,.3);
margin: 40px auto;
">
  <div style="
  height:60px; 
  background-image:url(https://github.com/JeanxPereira/ida-9.1-rpc/res/IDA-Header.png);
  background-size: cover;
  display:flex;
  vertical-align:baseline;"></div>
  <div style="
  width:90px;
  height:90px;
  border-radius:100%; 
  position:absolute; 
  top:16px; 
  left:16px;
  border:6px solid #28282d;">
    <div style="
    position:relative;">
      <img src ="https://github.com/jeanxpereira.png" style="
      border-radius:100%;
      width:90px;"/>
      <div style="
      position:absolute;
      bottom:3px; right:3px; 
      width:18px; height:18px; 
      border-radius:100%;  
      background-color:#2aa45f;
      border: 3px solid #28282d;"></div>
    </div>
  </div>
  <div style="
  padding:64px 16px 16px;
  color: white;">
    jeanxpereira
  </div>
  <div style="
  color: hsl(215 calc(1*8.824%) 73.333% /1);">
    <div style="
    padding:16px; 
    font-size:12px; line-height: 1.3333333333333333;
    font-weight: 700;">
      <p style="margin-bottom:8px;">PLAYING A GAME</p>
      <div style="
      align-items:flex-start; 
      display:flex;
      color: hsl(210 calc(1*9.091%) 87.059% /1);">
      <img src ="res/IDA-Teams.png" style="width:60px"/>
      <div>
      <p style="    
      display: block;
      font-size: 14px;
      line-height: 16px;
      margin-bottom:2px;">IDA Pro 9.1</p>
      <p style="    
      display: block;
      font-size: 14px;
      line-height: 16px;
      margin-bottom:2px;
      font-weight:lighter;">Darkspore_local.exe</p>
      <p style="    
      display: block;
      font-size: 14px;
      line-height: 16px;
      margin-bottom:2px;
      font-weight:lighter;">Reversing NounData (0xF65029)</p>
      <div style="display:flex; gap:6px; align-items:center;">
      <svg aria-hidden="true" role="img" xmlns="http://www.w3.org/2000/svg" width="12" height="12" fill="none" viewBox="0 0 24 24"><path fill="#73bf83" fill-rule="evenodd" d="M20.97 4.06c0 .18.08.35.24.43.55.28.9.82 1.04 1.42.3 1.24.75 3.7.75 7.09v4.91a3.09 3.09 0 0 1-5.85 1.38l-1.76-3.51a1.09 1.09 0 0 0-1.23-.55c-.57.13-1.36.27-2.16.27s-1.6-.14-2.16-.27c-.49-.11-1 .1-1.23.55l-1.76 3.51A3.09 3.09 0 0 1 1 17.91V13c0-3.38.46-5.85.75-7.1.15-.6.49-1.13 1.04-1.4a.47.47 0 0 0 .24-.44c0-.7.48-1.32 1.2-1.47l2.93-.62c.5-.1 1 .06 1.36.4.35.34.78.71 1.28.68a42.4 42.4 0 0 1 4.4 0c.5.03.93-.34 1.28-.69.35-.33.86-.5 1.36-.39l2.94.62c.7.15 1.19.78 1.19 1.47ZM20 7.5a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0ZM15.5 12a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3ZM5 7a1 1 0 0 1 2 0v1h1a1 1 0 0 1 0 2H7v1a1 1 0 1 1-2 0v-1H4a1 1 0 1 1 0-2h1V7Z" clip-rule="evenodd" class=""></path></svg>
      <p style="    
      display: block;
      color:#73bf83;
      font-size: 14px;
      line-height: 16px;
      margin-bottom:2px;
      font-weight:lighter;">2:49:23</p>
      </div>
      </div>
      </div>
    </div>
    <div></div>
  </div>
</div>



## About
ida-rpc was a quick test plugin to see what changed in the 7.0 sdk, ~~subsequently it only supports IDA 7.x as of now~~ updated to IDA 9.1, 
it allows for [discord rich presence](https://discordapp.com/rich-presence) to display information about the current IDA session

## Installation
To install ida-rpc simply copy **ida-rpc64.dll** from the [latest release](https://github.com/shikataganaii/ida-rpc-ida9/releases) to ```ida_install_location/plugins/``` ,
to change options within the plugin open the plugins menu and select IDA RPC ```Edit -> Plugins -> IDA RPC``` or use the default hotkey ```Ctrl-Alt-R```

## Building
To build this solution you'll need to get a copy of the [IDA 9.0 SDK](https://web.archive.org/web/20240810011401if_/https://out5.hex-rays.com/beta90_6ba923/idasdk90.zip), compile in 64bit Release64 and your done!
