# Theme
JANGAN DIJUAL BELAKAN YE BWANG !!!
BUTUH LICENSE/PW CHAT TELE GUA
>> t.me/fadhost <<

Comand Run Install Thema

bash <(curl https://raw.githubusercontent.com/gitfdil1248/thema/main/install.sh)



case 'cvpsubuntu': {
if (!isOwner ) return onlyOwn()
let teksnya = `Create Vps Do Os Ubuntu `
let sections = [{
title: '# UBUNTU 20.04',
highlight_label: 'Ubuntu 20.04',
rows: [{
title: 'VPS 1 GB 1 CORE',
description: `1GB 1C  Os Ubuntu 20 Region Sg`, 
id: '.cvps root,sgp1,s-1vcpu-1gb,ubuntu-20-04-x64'
},
{
title: 'VPS 2 GB 1 CORE',
description: `2GB 1C  Os Ubuntu 20 Region Sg`, 
id: '.cvps root,sgp1,s-1vcpu-2gb,ubuntu-20-04-x64'
},
{
title: 'VPS 4 GB 2 CORE',
description: `4GB 2C  Os Ubuntu 20 Region Sg`, 
id: '.cvps root,sgp1,s-2vcpu-4gb,ubuntu-20-04-x64'
},
{
title: 'VPS 8 GB 4 CORE',
description: `8GB 4C  Os Ubuntu 20 Region Sg`, 
id: '.cvps root,sgp1,s-4vcpu-8gb,ubuntu-20-04-x64'
},
{
title: 'VPS 16 GB 4 CORE',
description: `16GB 4C  Os Ubuntu 20 Region Nyc3`, 
id: '.cvps root,nyc3,s-4vcpu-16gb,ubuntu-20-04-x64'
}]
},
{
title: '# UBUNTU 22.04', 
highlight_label: 'System Information',
rows: [{
title: 'VPS 1 GB 1 CORE',
description: `1GB 1C  Os Ubuntu 22 Region Sg`, 
id: '.cvps root,sgp1,s-1vcpu-1gb,ubuntu-22-04-x64'
},
{
title: 'VPS 2 GB 1 CORE',
description: `2GB 1C  Os Ubuntu 22 Region Sg`, 
id: '.cvps root,sgp1,s-1vcpu-2gb,ubuntu-22-04-x64'
},
{
title: 'VPS 4 GB 2 CORE',
description: `4GB 2C  Os Ubuntu 22 Region Sg`, 
id: '.cvps root,sgp1,s-2vcpu-4gb,ubuntu-22-04-x64'
},
{
title: 'VPS 8 GB 4 CORE',
description: `8GB 4C  Os Ubuntu 22 Region Sg`, 
id: '.cvps root,sgp1,s-4vcpu-8gb,ubuntu-22-04-x64'
},
{
title: 'VPS 16 GB 4 CORE',
description: `16GB 4C  Os Ubuntu 22 Region Nyc3`, 
id: '.cvps root,nyc3,s-4vcpu-16gb,ubuntu-22-04-x64'
}]
},
{
title: '# UBUNTU 22.04', 
highlight_label: 'System Information',
rows: [{
title: 'VPS 1 GB 1 CORE',
description: `1GB 1C  Os Ubuntu 24 Region Sg`, 
id: '.cvps root,sgp1,s-1vcpu-1gb,ubuntu-24-04-x64'
},
{
title: 'VPS 2 GB 1 CORE',
description: `2GB 1C  Os Ubuntu 24 Region Sg`, 
id: '.cvps root,sgp1,s-1vcpu-2gb,ubuntu-24-04-x64'
},
{
title: 'VPS 4 GB 2 CORE',
description: `4GB 2C  Os Ubuntu 24 Region Sg`, 
id: '.cvps root,sgp1,s-2vcpu-4gb,ubuntu-24-04-x64'
},
{
title: 'VPS 8 GB 4 CORE',
description: `8GB 4C  Os Ubuntu 24 Region Sg`, 
id: '.cvps root,sgp1,s-4vcpu-8gb,ubuntu-24-04-x64'
},
{
title: 'VPS 16 GB 4 CORE',
description: `16GB 4C  Os Ubuntu 24 Region Nyc3`, 
id: '.cvps root,nyc3,s-4vcpu-16gb,ubuntu-24-04-x64'
}]
     }]
let listMessage = {
    title: 'List Vps Ubuntu', 
    sections
};

let msgii = generateWAMessageFromContent(m.chat, { viewOnceMessage: { message: { 
"messageContextInfo": { 
"deviceListMetadata": {}, 
"deviceListMetadataVersion": 2
}, 
interactiveMessage: proto.Message.InteractiveMessage.create({
contextInfo: { 
mentionedJid: [m.sender], 
externalAdReply: {
showAdAttribution: true }
}, body: proto.Message.InteractiveMessage.Body.create({ 
text: teksnya
}), 
footer: proto.Message.InteractiveMessage.Footer.create({ 
text: global.foother
}), 
header: proto.Message.InteractiveMessage.Header.create({ 
hasMediaAttachment: true, ...(await prepareWAMessageMedia({ image: await fs.readFileSync("./fadhostoffc/owner.jpg")}, { upload: fadhostoffc.waUploadToServer })) 
}), 
nativeFlowMessage: proto.Message.InteractiveMessage.NativeFlowMessage.create({ 
buttons: [{
"name": "single_select",
"buttonParamsJson": JSON.stringify(listMessage) 
},
 {
 "name": "cta_url",
 "buttonParamsJson": "{\"display_text\":\"Owner\",\"url\":\"https://wa.me/6289530583676\",\"merchant_url\":\"https://wa.me/6289530583676\"}"
}]
}) 
})} 
}}, {userJid: m.sender, quoted: m}) 
await fadhostoffc.relayMessage(msgii.key.remoteJid, msgii.message, { 
messageId: msgii.key.id 
})
}
break